## Selected work

**[eals-pyspark](https://github.com/laikhuramkorouhanba/als-pyspark)**  
A PySpark implementation of element-wise Alternating Least Squares, following He et al. [(SIGIR 2016)](https://www.comp.nus.edu.sg/~kanmy/papers/sigir16.pdf). It learns recommendations from implicit signals such as clicks and purchases rather than star ratings, and weights unobserved interactions by item popularity instead of treating them all as equally negative. The formulation avoids the matrix inversions that make conventional ALS expensive, which is where most of the speedup comes from. Evaluated on 730,000 Yelp reviews under both a static protocol and a simulated stream. Built with [Bhavesh Chauhan](https://github.com/bhaveshchauhan2407).

**[document-extraction-rag](https://github.com/laikhuramkorouhanba/document-extraction-rag)**  
A retrieval system for security analysts working through CISA's Known Exploited Vulnerabilities catalogue, with a second path for querying PDFs the analyst uploads themselves. The two sources are retrieved differently on purpose: the vulnerability catalogue is structured and its records use consistent terminology, so sparse retrieval over TF-IDF works well and stays interpretable, while uploaded PDFs are unpredictable enough to need chunking and dense embeddings in a Chroma vector store. Generation runs on Llama 3.2 1B, small enough to keep the whole thing cheap to serve. Built during an exchange at the National Taipei University of Technology.

**[qrt-long-or-short](https://github.com/laikhuramkorouhanba/qrt-long-or-short)**  
A directional classifier for QRT's Long or Short challenge, predicting whether an anonymised asset allocation returns positive or negative the next day from twenty days of returns, signed volume and turnover. The real problem turned out to be the gap between validation and leaderboard: feature sets that pushed cross-validation past 0.53 fell back to roughly 0.50 on held-out data, so the work became a matter of stripping out anything whose SHAP importance moved around across folds, even where it looked good in validation. Cross-validation was grouped by timestamp so that same-day observations never landed on both sides of a split. The final CatBoost model scored 0.5303 in cross-validation and 0.5203 on the public leaderboard. Team project at École Polytechnique.

## Tools

Python for nearly everything. Spark when the data stops fitting on one machine, PyTorch and scikit-learn for modelling, and the usual surrounding pieces: SQL, Docker, Git, FastAPI.

## Elsewhere

[Portfolio](https://laikhuramkorouhanba.github.io/_/) · [LinkedIn](https://www.linkedin.com/in/korouhanbakhuman/) · [Email](mailto:laikhuram.korouhanba-khuman@polytechnique.edu)

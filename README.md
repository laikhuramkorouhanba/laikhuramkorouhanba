Dual master's student in Data Science and AI for Business at École Polytechnique and HEC Paris. Currently interning on the strategy team at Legrand, covering the data centre business.

Most of what I build sits close to the point where a model meets an actual decision. That has meant distributed recommendation systems, retrieval pipelines over documents that were never meant to be machine readable, and a fair amount of the unglamorous work of getting inconsistent data into a state where someone can trust it.

## Selected work

**[eals-pyspark](https://github.com/laikhuramkorouhanba/eals-pyspark)**  
A PySpark implementation of element-wise Alternating Least Squares, following He et al. (SIGIR 2016). It learns recommendations from implicit signals such as clicks and purchases rather than star ratings, and weights unobserved interactions by item popularity instead of treating them all as equally negative. The formulation avoids the matrix inversions that make conventional ALS expensive, which is where most of the speedup comes from. Evaluated on 730,000 Yelp reviews under both a static protocol and a simulated stream. Built with [Bhavesh Chauhan](https://github.com/bhaveshchauhan2407).

**[document-extraction-rag](https://github.com/laikhuramkorouhanba/document-extraction-rag)**  
[FILL: one sentence on what it extracts and from what kind of document. Then one sentence on a design decision you actually had to think about, such as the chunking strategy or how you dealt with retrieval quality. Then a result, such as accuracy on a test set or how much manual reading it removed.]

**[qrt-churn-prediction](https://github.com/laikhuramkorouhanba/qrt-churn-prediction)**  
[FILL: the problem in one sentence. Then the thing you did that was not obvious, such as a feature you engineered or a validation scheme that mattered. Then a number you can state precisely: leaderboard rank, AUC, whatever you have.]

## Tools

Python for nearly everything. Spark when the data stops fitting on one machine, PyTorch and scikit-learn for modelling, and the usual surrounding pieces: SQL, Docker, Git, FastAPI.

## Elsewhere

[Portfolio](https://laikhuramkorouhanba.github.io/_/) · [LinkedIn](FILL) · [Email](mailto:FILL)

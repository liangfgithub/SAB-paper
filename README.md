# A Scalable Algorithm for Bayesian Variable Selection (SAB) with Application to miRNA-mRNA Regulation in Cancer

**Authors:** Jin Wang, Feng Liang, Yuan Ji and Yitan Zhu


This paper is a chapter in the book _High Dimensional Data Science_, edited by [Ansu Chatterjee](https://snigchat.github.io/) and published by Springer. The appendix available here contains supplementary material that is not included in the book.

## Links
- [Appendix](appendix.pdf)

## Abstract

We propose a new computational framework for Bayesian variable selection. The key idea is to approximate the posterior distribution through an optimization procedure. Our algorithm, SAB, combines the classical EM algorithm with variational Bayes (VB). A key feature of SAB is its scalability, making it particularly efficient for high-dimensional settings with large p and small n. We show that SAB achieves both frequentist and Bayesian asymptotic consistency, despite being based on an approximation procedure. Numerically, we evaluate its performance in finite-sample settings as the number of variables ranges from small to large. To address a critical biological problem, we apply SAB to a state-of-the-art cancer genomics data set to investigate the complex regulatory relationships between miRNAs and mRNAs in cancer.

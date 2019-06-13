# Summary

In their 1985 paper, Harville and Fenech presented a method for constructing an exact confidence interval for the ratio of two variance components in a linear mixed model. To illustrate their results, the authors used data on the weights at birth of 62 single-birth male lambs. These lambs come from five population lines (two control lines and three selection lines). Each lamb was the offspring of one of 23 rams (male sheep), and each lamb had a different mother. The age of the mother is one of three categories: 1-2 years (category 1), 2-3 years (category 2), or 3+ years (category 3).

In this project, I build a linear mixed effects model with birth weight as the response and the above variables as predictors. Sire is included as a random effect in the model due to the fact that the sires used in the study can be thought of as a sample from a larger population. Maximum likelihood and restricted maximum likelihood techniques are used to fit the model, and asymptotic covariance matrices are calculated.

Please see the PDF document for a written report of the analysis. R code used for the project are included in-line.

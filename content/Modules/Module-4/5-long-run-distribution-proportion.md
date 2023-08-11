---
title: "The Long Run Distribution of a Proportion"
---

For a large sample size, the probability distribution of the possible values of an average is approximately a normal distribution, regardless of the probability distribution of the original individual measurements. In this video, we investigate whether something similar is true when we’re interested in a proportion.

Stream the video without the embedded quiz questions by clicking on the video link below. Closed captions are available.

{{< youtube CBdX-_bmt4g >}}

[Notes on the video: The Long Run Distribution of a Proportion](../6-3-The-Long-Run-Distribution-of-a-Proportion.pdf)

### A point to consider for this video:

The Central Limit Theorem is usually stated in terms of averages. Why does it also hold for proportions? A proportion is the count of the number of successes in **n trials divided by *n*. If the outcome of each trial is thought of as an observation of a Bernoulli random variable which is 1 if the outcome of the trial is a success and 0 otherwise, then the sum of the outcomes of the n Bernoulli random variables is the number of successes, and the average of the *n* Bernoulli random variables is the proportion of successes.

A natural question to ask is: *How many trials are needed so that the Normal distribution is a good approximation for the probability distribution of an estimator of a proportion?*  For averages, it is difficult to give a general answer because of the wide variety of probability distributions that the individual observations could possibly have.  However, it is possible to give a guideline for proportions.  Counts of the number of successes in a fixed number of trials are known to have Binomial distributions. Binomial distributions are symmetric when *p=0.5* and are more skewed the closer *p* is to 0 or 1; so smaller sample sizes are needed when *p* is close to 0.5 than when p is close to 0 or 1.  Here is a guideline for a sufficient sample size, n, for the Central Limit Theorem to apply when estimating a proportion:  The distribution of an estimator of a proportion will be well approximated by a Normal distribution if *np ≥ 10* and *n(1-p) ≥ 10*.
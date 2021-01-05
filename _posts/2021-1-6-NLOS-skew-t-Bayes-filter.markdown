---
layout: post
title:  "A NLOS-robust TOA positioning filter based on a skew-t measurement noise model"
date:   2021-1-6 07:25:35
categories: CS
tags: UWB indoor-positioning skew-t Bayes-filter
excerpt: This paper proposed a Bayes filter based on a NLOS error model named skew-t distribution. There are some common knowledge about the skew-t and Bayes filter. Maybe they can be used to filter noise in SHM.
mathjax: true
---

# Reference

> Nurminen, H., Ardeshiri, T., Piché, R. and Gustafsson, F., 2015, October. A NLOS-robust TOA positioning filter based on a skew-t measurement noise model. In 2015 International Conference on Indoor Positioning and Indoor Navigation (IPIN) (pp. 1-7). IEEE.

[https://doi.org/10.1109/IPIN.2015.7346786](https://doi.org/10.1109/IPIN.2015.7346786)


# Abstract
> A skew-t variational Bayes filter (STVBF) is applied to indoor positioning with time-of-arrival (TOA) based distance measurements and pedestrian dead reckoning (PDR). The proposed filter accommodates large positive outliers caused by occasional non-line-of-sight (NLOS) conditions by using a skew-t model of measurement errors. Real-data tests using the fusion of inertial sensors based PDR and ultra-wideband based TOA ranging show that the STVBF clearly outperforms the extended Kalman filter (EKF) in positioning accuracy with the computational complexity about three times that of the EKF.

# Comments
1. The **univariate skew t-distribution** is parametrized by its location parameter µ ∈ R, spread parameter σ ∈ R+, shape parameter density function (PDF) δ ∈ R and degrees of fr, and has a PDF, which can be found in the paper.
2. The proposed filter assumes that the measurement noise
follows the skew t-distribution, and approximates the posterior distribution using a **variational Bayes (VB)** approximation.
3. The real-time experiment was intersting, espeically for the RMSE and the assessment indicator.


# Questions
1. This paper was published on IPIN in 2015. Maybe the date is old and that's why it can be published without some new insights for now.

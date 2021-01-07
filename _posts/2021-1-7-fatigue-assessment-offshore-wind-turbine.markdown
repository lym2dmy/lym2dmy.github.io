---
layout: post
title:  "Long-term fatigue damage assessment for a floating offshore wind turbine under realistic environmental conditions"
date:   2021-1-7 07:41:23
categories: CE
tags: wind-turbine fatigue assessment ANN
excerpt: I think the paper is good to combine the fatigue assessment and the ANN method. The paper spent many sections to discuss the fatigue assessment of OWT is important and the common methods. And then, described and analyzed the dataset. At last, developed ANN and kriging models and analyzed the results, sensitivity, and long-term fatigue assessment.
mathjax: true
---

# Reference

> Li, X. and Zhang, W. (2020) ‘Long-term fatigue damage assessment for a floating offshore wind turbine under realistic environmental conditions’, Renewable Energy, 159, pp.570–584. doi: 10.1016/j.renene.2020.06.043.

[https://doi.org/10.1016/j.renene.2020.06.043](https://doi.org/10.1016/j.renene.2020.06.043)

Received 11 June 2019, Received in revised form 28 February 2020, Accepted 8 June 2020, Available online 13 June 2020

# Abstract
> Offshore wind energy has gained widespread attention and experienced a rapid development due to the significantly increasing demand for renewable energy over the past few years. Currently, the development of offshore floating wind turbines attracts lots of attention to harvest more energy from a sustained higher speed of offshore wind away from the coastline. With stronger cyclic wind and wave loadings, the floating wind turbine could possibly experience severe fatigue damages at certain critical locations, which might lead to a catastrophic failure. Evaluating accumulated fatigue damage for a floating wind turbine during its entire lifetime, therefore, becomes essential and urgent. As demonstrated in the codes, specifications, or design practices, fatigue assessments require massive computational costs and pose challenges to numerical simulations since lots of dynamic analyses under different environmental scenarios need to be performed. To reduce the calculation cost for this time-consuming process while maintaining high accuracy, a probabilistic long-term fatigue damage assessment approach is proposed in the present study by implementing a C-vine copula model and a surrogate model. The C-vine copula model provides a multivariate dependency description for the on-site wind and wave-related environmental parameters. Two surrogate models, including the Kriging model and the artificial neural network (ANN), are implemented to efficiently predict the short-term fatigue damages at critical locations of the floating wind turbine. The proposed long-term fatigue damage assessment framework is accurate and suitable for evaluating structural long-term fatigue damages accumulated in a real environment especially when effects from more environmental parameters are to be considered. Based on surrogate models, sensitivity analyses are carried out to investigate the relative significance of each environmental parameter on short-term fatigue damages. In addition, uncertainties from short-term fatigue damages are also incorporated into the probabilistic fatigue evaluation framework to assess the accumulated long-term fatigue damages for a spar type floating wind turbine.

# Comments
1. With stronger cyclic wind and wave loadings, the floating wind turbine could possibly experience severe fatigue damages at certain critical locations, which might lead to a catastrophic failure. This sentence is good.
2. Here the authors introduced the **fatigue assessment**. As demonstrated in the codes, specifications, or design practices, fatigue assessments require massive computational costs and pose turbine during its entire lifetime, therefore, becomes essential and urgent. As demonstrated in the codes, specifications, or design practices, fatigue assessments require massive computational costs and pose challenges to numerical simulations since lots of dynamic analyses under different environmental sce-narios need to be performed.
3. **Here is an open source dataset**. The hindcast environmental data from the USACE Wave Information Study [31] at a site off the south coast of Alaska (56?N, 154?W, station ID: 81003) is implemented for determining the wind and wave loads on the floating wind turbine in the present study. **This data set provides hourly wind and wave information for a duration of32 years.** Six most critical parameters that could affect the wind and wave loads are considered in the present study including wind direction (WNDDIR), mean wind speed at 10 m above the sea level (WNDSPD), significant wave height (HMO), peak spectral wave period (TP), mean wave direction (WAVD), and directional spread at the mean wave direction (SPRD). 
4. In the present study, the feedforward ANN is implemented to estimate the relationship between the environmental parameters and the short-term equivalent fatigue stress at different locations on the floating wind turbine. The


# Questions
1. No questions. I think the paper is good to combine the fatigue assessment and the ANN method. The paper spent many sections to discuss the fatigue assessment of OWT is important and the common methods. And then, described and analyzed the dataset. At last, developed ANN and kriging models and analyzed the results, sensitivity, and long-term fatigue assessment.
2. Maybe the review time is as long as one year.

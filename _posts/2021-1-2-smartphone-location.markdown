---
layout: post
title:  "Enhancing indoor smartphone location acquisition using floor plans"
date:   2021-1-2 21:13:59
categories: CS
tags: indoor-positioning
excerpt: .
mathjax: true
---

# Reference

> Rajagopal, N., Lazik, P., Pereira, N., Chayapathy, S., Sinopoli, B. and Rowe, A., 2018, April. Enhancing indoor smartphone location acquisition using floor plans. In 2018 17th ACM/IEEE International Conference on Information Processing in Sensor Networks (IPSN) (pp. 278-289). IEEE.

[https://doi.org/10.1109/IPSN.2018.00056](https://doi.org/10.1109/IPSN.2018.00056)


# Abstract
> Indoor localization systems typically determine a position using either ranging measurements, inertial sensors, environmental-specific signatures or some combination of all of these methods. Given a floor plan, inertial and signature-based systems can converge on accurate locations by slowly pruning away inconsistent states as a user walks through the space. In contrast, range-based systems are capable of instantly acquiring locations, but they rely on densely deployed beacons and suffer from inaccurate range measurements given non-line-of-sight (NLOS) signals. In order to get the best of both worlds, we present an approach that systematically exploits the geometry information derived from building floor plans to directly improve location acquisition in range-based systems. Our solving approach can disambiguate multiple feasible locations taking into account a mix of LOS and NLOS hypotheses to accurately localize with significantly fewer beacons. 

> We demonstrate our geometry-aware solving approach using a new ultrasonic beacon platform that is able to perform direct time-of-flight ranges on commodity smartphones. The platform uses Bluetooth Low Energy (BLE) for time synchronization and ultrasound for measuring propagation distance. We evaluate our system's accuracy with multiple deployments in a university campus and show that our approach shifts the 80% accuracy point from 4-8m to 1m as compared to solvers that do not use the floor plan information. We are able to detect and remove NLOS signals with 91.5% accuracy.

# Comments
1. 


# Questions
1. Map-based positioning method has been developed by other researchers. What is the difference between this paper and others? What is the most novelty of this paper? Maybe I do not understand this paper. The authors claimed that the problem they solved is estimating location using a single set of range measurements from beacons without having the user to walk. I think the problem is similar with others, despite of particle filter.
2. 

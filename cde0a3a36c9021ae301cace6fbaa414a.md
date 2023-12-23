---
title: Test of Proportions
author: Lorenzo Drumond
date: 2023-11-14T13:49:32
last: 2023-12-23T02:22:19
zk_id: cde0a3a36c9021ae301cace6fbaa414a
tags: #week2 #theory #experiment #test #statistics #designing_running_and_analyzing_experiments #proportions #design #coursera #rlang
---


# Test of Proportions
A test of proportion is looking at proportions of responses.

example: two versions of website A/B; 60 partecipants (stakeholders), haven't seen website before. After 20 mins of free exploration, they give preference on A or B.

We want to analyse the user preference. Get the statistical significance in what website is preferred based on the proportion of people voting for it.

This is called a one-sample proportion test, because we only have one sample (one variable) of proportions.

We want to know if the difference in proportion we see is any statistically different from chance.

Pearson chi-square test: one sample test of proportions; it will test if the different in proportions is significant (when p-value is less than threshold)

Each stat test has a statistics associated with it. That statistics is related to the value of the distribution the statistics is calculated over. For pearson chi-square test, it's the chi-square distribution.

What does it mean to get a significant result? p-value is below 0.05, traditionally taken to be threshold below which result is stat. sig.

Degree of freedom is a parameter that depends on the test. This parameter needs to be reported.

# References
- https://www.coursera.org/learn/designexperiments
- [[report-the-result-of-a-test]]

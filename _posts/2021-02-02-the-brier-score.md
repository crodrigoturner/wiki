---
id: 10074
title: 'The Brier score'
date: '2021-02-02T11:55:15+00:00'
author: crodrigoturner
excerpt: 'The Brier score is a proper score function that measures the accuracy of probabilistic predictions.'
layout: post
guid: 'https://www.carlosrodrigo.com/?p=10074'
permalink: /the-brier-score/
---

The Brier score is a proper score function that measures the accuracy of probabilistic predictions. It is applicable to tasks in which predictions must assign probabilities to a set of mutually exclusive discrete outcomes. The set of possible outcomes can be either binary or categorical in nature, and the probabilities assigned to this set of outcomes must sum to one (where each individual probability is in the range of 0 to 1). It was proposed by Glenn W. Brier in 1950. The Brier score can be thought of as either a measure of the «calibration» of a set of probabilistic predictions, or as a «cost function». More precisely, across all items i ∈ 1… N {\\displaystyle i\\in {1…N}}in a set N predictions, the Brier score measures the mean squared difference between:The predicted probability assigned to the possible outcomes for item iThe actual outcome o i {\\displaystyle o\_{i}}Therefore, the lower the Brier score is for a set of predictions, the better the predictions are calibrated  
[https://en.wikipedia.org/wiki/Brier\_score](https://en.wikipedia.org/wiki/Brier_score)
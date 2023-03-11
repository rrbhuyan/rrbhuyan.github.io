---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Structured Dynamic Pricing: Optimal Regret in a Global Shrinkage Model
-

 ## *Under Submission, ICML 2023*

**Rashmi Ranjan Bhuyan, Adel Javanmard, Sungchul Kim, Gourab Mukherjee, Ryan A. Rossi, Tong Yu, Handong Zhao**

We consider dynamic pricing strategies in a streamed longitudinal data set-up where the objective is to maximize, over time, the cumulative profit. Since consumers sharing similar characteristics act in similar ways, we consider a global shrinkage structure assuming that the consumers’ preferences can be well approximated by an SAR model. We propose a pricing policy based on penalized SGD and analyze the regret of the policy against a clairvoyant policy. Our regret analysis results demonstrates asymptotic optimality of the proposed policy and the importance of shrinkage in the aforementioned setup.

An MCEM algorithm for consistent estimation in Network-linked high-dimensional multinomial Probit 
-

## *In Preparation*

**Rashmi Ranjan Bhuyan, Trambak Banerjee, Bhaswar Bhattacharya, Gourab Mukherjee**

The multinomial probit model (MNP) is widely used for analyzing unordered categorical data and we regularly encounter cross-sectional datasets with categorical responses and high-dimensional covariates. In absence of repeated observations from the respondents, we use additional network structure to pool information across similar units to provide significantly better inference. However, estimating the effects of sparse high-dimensional covariates in the presence of network linkages is challenging. We develop a novel Monte Carlo EM algorithm for consistent variable selection in this high-dimensional MNP setup. We demonstrate the application of the proposed method in spatial autocorrelation network structured MNP models.

A Dynamic Bayesian Mixture Model for Fine-grained Promotion Mix Analysis of Digital Coupons
-

## *In Preparation*

**Rashmi Ranjan Bhuyan, Wreetabrata Kar, Gourab Mukherjee**

We develop a novel dynamic mixture model for analyzing the effects of varied marketing components in a digital promotion campaign that uses online coupons. We segment customers based on their purchase history and provides fine-grained estimates of the heterogeneous effects that promotion mix variables have on the different consumer segments. The proposed model not only captures long- term heterogeneous segments in the customer pools but also tracks short term changes in customer engagement of recent coupons through dynamic indices. We conduct Bayesian estimation of the model parameters by using a novel Gibbs algorithm using Polya-Gamma distributions based data augmentation strategy in handling Binomial likelihoods. Finally, through a path-algorithm we provide an integrated framework for providing fine-grained analysis of the promotion component effects at various levels of heterogeneity.

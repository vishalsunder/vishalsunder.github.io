---
title: "RNNSurv: A Deep Learning Approach to Recurrent Event Survival Analysis with Competing Risks"
collection: publications
permalink: /publications/pakdd-paper
venue: "PAKDD"
date: 2019-04-14
citation: 'Garima Gupata, <b>Vishal Sunder</b>, Ranjitha Prasad, Gautam Shroff. <i>The 23rd Pacific-Asia Conference on Knowledge Discovery and Data Mining.</i> <b>PAKDD 2019</b>.'
---  

## Abstract
Survival analysis refers to a gamut of statistical techniques developed to infer the survival time from time-to-event data. In particular, we are interested in recurrent event survival analysis in the presence of one or more competing risks in each recurrent time-step, in order to obtain the probabilistic relationship between the input covariates and the distribution of event times. Since traditional survival analysis techniques suffer from drawbacks due to strong parametric model constraints and constant hazard based assumptions, we propose a modern deep learning based flexible probabilistic framework for cause-specific recurrent survival analysis. In single-risk scenarios, we propose an LSTM-based model where the time-steps represent the recurrent events for each participant whose covariates may be static or time-varying. To cater to multi-risk scenarios, we build on the single-risk LSTM model and introduce a cumulative incidence curve approach to handle the multiple competing risks using a joint distribution over the event times and each of the competing risks over multiple time-steps and term the proposed novel architecture as RNNSurv. We use the concordance index per risk and the maximum absolute error in every time-step as the metrics of performance. We demonstrate a superior predictive performance of the proposed approach (single and multiple risk scenarios) as compared to traditional model-based approaches, and deep learning based approaches for synthetic and state-of-the-art public datasets.

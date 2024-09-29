---
title: "TCNFormer: Temporal Convolutional Network Former for Short-Term Wind Speed Forecasting"
collection: publications
permalink: /publication/paper6
excerpt: 'This study proposes the Temporal Convolutional Network Former (TCNFormer) for short-term (12-hour) wind speed forecasting.'
date: 2024-8-27
venue: 'Submitted to AAAI 2025'
paperurl: 'https://arxiv.org/pdf/2408.15737'
---

Global environmental challenges and rising energy demands have led to extensive exploration of wind energy technologies. Accurate wind speed forecasting (WSF) is crucial for optimizing wind energy capture and ensuring system stability. However, predicting wind speed remains challenging due to its inherent randomness, fluctuation, and unpredictability. This study proposes the Temporal Convolutional Network Former (TCNFormer) for short-term (12-hour) wind speed forecasting. The TCNFormer integrates the Temporal Convolutional Network (TCN) and transformer encoder to capture the spatio-temporal features of wind speed. The transformer encoder consists of two distinct attention mechanisms: causal temporal multi-head self-attention (CT-MSA) and temporal external attention (TEA). CT-MSA ensures that the output of a step derives only from previous steps, i.e., causality. Locality is also introduced to improve efficiency. TEA explores potential relationships between different sample sequences in wind speed data. This study utilizes wind speed data from the NASA Prediction of Worldwide Energy Resources (NASA POWER) of Patenga Sea Beach, Chittagong, Bangladesh (latitude 22.2352{\deg} N, longitude 91.7914{\deg} E) over a year (six seasons). The findings indicate that the TCNFormer outperforms state-of-the-art models in prediction accuracy. The proposed TCNFormer presents a promising method for spatio-temporal WSF and may achieve desirable performance in real-world applications of wind power systems.
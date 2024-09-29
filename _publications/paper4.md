---
title: "EAViT: External Attention Vision Transformer for Audio Classification"
collection: publications
permalink: /publication/paper4
excerpt: 'This paper presents the External Attention Vision Transformer (EAViT) model, a novel approach designed to enhance audio classification accuracy.'
date: 2024-08-23
venue: 'Asia-Pacific Signal and Information Processing Association Annual Summit and Conference (APSIPA)'
paperurl: 'https://arxiv.org/pdf/2408.13201'
---

This paper presents the External Attention Vision Transformer (EAViT) model, a novel approach designed to enhance audio classification accuracy. As digital audio resources proliferate, the demand for precise and efficient audio classification systems has intensified, driven by the need for improved recommendation systems and user personalization in various applications, including music streaming platforms and environmental sound recognition. Accurate audio classification is crucial for organizing vast audio libraries into coherent categories, enabling users to find and interact with their preferred audio content more effectively. In this study, we utilize the GTZAN dataset, which comprises 1,000 music excerpts spanning ten diverse genres. Each 30-second audio clip is segmented into 3-second excerpts to enhance dataset robustness and mitigate overfitting risks, allowing for more granular feature analysis. The EAViT model integrates multi-head external attention (MEA) mechanisms into the Vision Transformer (ViT) framework, effectively capturing long-range dependencies and potential correlations between samples. This external attention (EA) mechanism employs learnable memory units that enhance the network's capacity to process complex audio features efficiently. The study demonstrates that EAViT achieves a remarkable overall accuracy of 93.99%, surpassing state-of-the-art models.
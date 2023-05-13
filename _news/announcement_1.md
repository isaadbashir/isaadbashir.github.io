---
layout: post
title: MedIA Paper Accepted
date: 2023-05-29 07:59:00-0400
inline: false
related_posts: false
---

Title:  Consistency Regularisation in Varying Contexts and Feature Perturbations for Semi-Supervised Semantic Segmentation of Histology Images

Abstract: Semantic segmentation of various tissue and nuclei types in histology images is fundamental to many downstream tasks in the area of computational pathology (CPath). In recent years, Deep Learning (DL) methods have been shown to perform well on segmentation tasks but DL methods generally require a large amount of pixel-wise annotated data. Pixel-wise annotation sometimes requires expert's knowledge and time which is laborious and costly to obtain. In this paper, we present a consistency based semi-supervised learning (SSL) approach that can help mitigate this challenge by exploiting a large amount of unlabelled data for model training thus alleviating the need for a large annotated dataset. However, SSL models might also be susceptible to changing context and features perturbations exhibiting poor generalisation due to the limited training data. We propose an SSL method that learns robust features from both labelled and unlabelled images by enforcing consistency against varying contexts and feature perturbations. The proposed method incorporates context-aware consistency by contrasting pairs of overlapping images in a pixel-wise manner from changing contexts resulting in robust and context invariant features. We show that cross-consistency training makes the encoder features invariant to different perturbations and improves the prediction confidence. Finally, entropy minimisation is employed to further boost the confidence of the final prediction maps from unlabelled data. We conduct an extensive set of experiments on two publicly available large datasets (BCSS and MoNuSeg) and show superior performance compared to the state-of-the-art methods.

Code: https://github.com/isaadbashir/crcfp

URL: https://arxiv.org/abs/2301.13141
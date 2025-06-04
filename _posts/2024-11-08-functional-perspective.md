---
layout: post
title: Neural Network Compression - The Functional Perspective (+ Extensions)
date: 2024-11-08 12:00:00
description: Presented by Israel Mason-Williams
tags: published-paper
categories: talks
related_publications: true
---

**[Israel Mason-Williams](https://openreview.net/profile?id=~Israel_Mason-Williams1)** will be presenting and discussing the paper Neural Network Compression: The Functional Perspective (+ Extensions) {% cite mason-williams2024neural %} {% cite mason-williams2024knowledge %}.

**_Abstract_**

Compression techniques, such as Knowledge distillation, Pruning, and Quantization reduce the computational costs of model inference and enable on-edge machine learning. The efficacy of compression methods is often evaluated through the proxy of accuracy and loss to understand similarity of the compressed model. This study aims to explore the functional divergence between compressed and uncompressed models. The results indicate that Quantization and Pruning create models that are functionally similar to the original model. In contrast, Knowledge distillation creates models that do not functionally approximate their teacher models. The compressed model resembles the dissimilarity of function observed in independently trained models. Therefore, it is verified, via a functional understanding, that Knowledge distillation is not a compression method. Thus, leading to the definition of Knowledge distillation as a training regulariser given that no knowledge is distilled from a teacher to a student.

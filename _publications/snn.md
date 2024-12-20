---
title: "Are Conventional SNNs Really Efficient? A Perspective from Network Quantization"
collection: publications
category: conferences
permalink: /publication/snn
date: 2024-06-16
venue: 'Conference on Computer Vision and Pattern Recognition'
paperurl: 'https://raw.githubusercontent.com/FloyedShen/FloyedShen.github.io/master/files/snn.pdf'
citation: 'Shen, G., Zhao, D., Li, T., Li, J., & Zeng, Y. (2024). Are Conventional SNNs Really Efficient? A Perspective from Network Quantization. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 27538–27547). (highlight)'
---

Spiking Neural Networks (SNNs) have been widely praised for their high energy efficiency and immense potential. However, comprehensive research that critically contrasts and correlates SNNs with quantized Artificial Neural Networks (ANNs) remains scant, often leading to skewed comparisons lacking fairness towards ANNs. This paper introduces a unified perspective, illustrating that the time steps in SNNs and quantized bit-widths of activation values present analogous representations. Building on this, we present a more pragmatic and rational approach to estimating the energy consumption of SNNs. Diverging from the conventional Synaptic Operations (SynOps), we champion the ”Bit Budget” concept. This notion permits an intricate discourse on strategically allocating computational and storage resources between weights, activation values, and temporal steps under stringent hardware constraints. Guided by the Bit Budget paradigm, we discern that pivoting efforts towards spike patterns and weight quantization, rather than temporal attributes, elicits profound implications for model performance. Utilizing the Bit Budget for holistic design consideration of SNNs elevates model performance across diverse data types, encompassing static imagery and neuromorphic datasets. Our revelations bridge the theoretical chasm between SNNs and quantized ANNs and illuminate a pragmatic trajectory for future endeavors in energy-efficient neural computations.
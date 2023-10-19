---
title: "In-Sensor & Neuromorphic Computing Are all You Need for Energy Efficient Computer Vision"
collection: publications
permalink: /publications/2023ICASSP_In-sensor+neuromorphic
excerpt: ''
date: 2023-05-12
venue: 'IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)'
year: '2023'
authors: 'Gourav Datta, Zeyu Liu, Md Abdullah-Al Kaiser, Souvik Kundu, Joe Mathai, Zihan Yin, Ajey P Jacob, Akhilesh R Jaiswal, Peter A Beerel'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10094902&casa_token=GWNukJ5dlT8AAAAA:EPotgP2ZIAK6Kr4Hv2SkQTzyKz2-u8SeJljvCRN1nzCsWsthKLx3mKQGUveXyYR4EKTiUq-sEA&tag=1'

---

Due to the high activation sparsity and use of accumulates (AC) instead of expensive multiply-and-accumulates (MAC), neuromorphic spiking neural networks (SNNs) have
emerged as a promising low-power alternative to traditional DNNs for several computer vision (CV) applications. However, most existing SNNs require multiple time steps for
acceptable inference accuracy, hindering real-time deployment and increasing spiking activity and, consequently, energy consumption. Recent works proposed direct encoding
that directly feeds the analog pixel values in the first layer of the SNN in order to significantly reduce the number of time steps. Although the overhead for the first layer MACs with direct encoding is negligible for deep SNNs and the CV processing is efficient using SNNs, the data transfer between the image sensors and the downstream processing costs significant bandwidth and may dominate the total energy. To mitigate this concern, we propose an in-sensor computing hardware-software co-design framework for SNNs targeting image recognition tasks. Our approach reduces the bandwidth between sensing and processing by 12−96× and the resulting total energy by 2.32× compared to traditional CV processing, with a 3.8% reduction in accuracy on ImageNet.

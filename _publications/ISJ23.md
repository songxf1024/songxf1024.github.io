---
title: "Image Matching and Localization Based on Fusion of Handcrafted and Deep Features"
collection: publications
permalink: /publications/ISJ23
date: 2009-10-01
venue: 'IEEE Sensors Journal'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10225672'
codeurl: 'https://github.com/songxf1024/DeFusion'
citation: 'X. Song, Y. Zou, Z. Shi and Y. Yang, "Image Matching and Localization Based on Fusion of Handcrafted and Deep Features," in IEEE Sensors Journal, vol. 23, no. 19, pp. 22967-22983, 1 Oct.1, 2023.'
---

<div style="gap: 10px; display: flex; flex-direction: column; align-items: center;">
    <img src="/images/publications/ISJ23/System Architecture.png" alt="Image 1" style="width: 800px; height: auto; border-radius: 5px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 10px;">
    <img src="/images/publications/ISJ23/Decision Level Fusion.png" alt="Image 2" style="width: 800px; height: auto; border-radius: 5px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 10px;">
</div>

With the popularity of vision sensors and the advancement of image processing technology, machine vision tasks based on image matching have received widespread attention. Matching methods based on handcrafted features have strong interpretability, but they are susceptible to noise in complex environments. In addition, deep learning has shown potential in improving matching performance, but at the cost of large amounts of specific samples and computing resources. In recent years, there have been efforts to explore how to combine handcrafted features and deep features to enhance the performance, but most of them only consider their sequential relationship. To address these challenges, we propose a novel image matching scheme with a fine-grained decision-level fusion (DLF) method that fully considers the judgments of handcrafted features and deep features for potential correspondence points, effectively combining handcrafted and deep features in a novel way. We also train generic features on public datasets to handle unseen scenes. We use RootSIFT as prior knowledge to guide the extraction of deep features, significantly reducing computational overhead. In addition, we carefully design preprocessing steps by incorporating device attitude information. We conduct image matching experiments on public datasets and our own captured dataset. Compared to the existing methods, as illustrated in our experimental results, the proposed scheme achieves an overall 2.5–6× more correct matches with improved robustness. Finally, we design a target localization algorithm incorporating an unmanned aerial vehicle (UAV) to achieve accurate and efficient localization using the proposed matching scheme and weighted least squares (WLS) estimation algorithm, demonstrating the versatility of the proposed image matching scheme.


---
title: "DyLaClass: Dynamic Labeling Based Classification for Optimal Sparse Matrix Format Selection in Accelerating SpMV"
collection: publications
permalink: /publications/DyLaClass
date: Dec. 2024
venue: 'IEEE Transactions on Parallel and Distributed Systems'
paperurl: 'https://www.computer.org/csdl/journal/td/2024/12/10738209/21rphBevhMk'
citation: 'Zheng Shi, Yi Zou, Xianfeng Song, Shupeng Li, Fangming Liu, and Quan Xue, “DyLaClass: Dynamic Labeling Based Classification for Optimal Sparse Matrix Format Selection in Accelerating SpMV”, to appear in IEEE Transactions on Parallel and Distributed Systems, 2024.'
---

<div style="gap: 10px; display: flex; flex-direction: column; align-items: center;">
    <img src="/images/publications/TPDS24DyLaClass/storage_format.jpg" alt="Image 1" style="width: 800px; height: auto; border-radius: 5px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 10px;">
</div>

Sparse matrix-vector multiplication (SpMV) is crucial in many scientific and engineering applications, particularly concerning the effectiveness of different sparse matrix storage formats for various architectures, no single format excels across all hardware. Previous research has focused on trying different algorithms to build predictors for the best format, yet it overlooked how to address the issue of the best format changing in the same hardware environment and how to reduce prediction overhead rather than merely considering the overhead in building predictors. This paper proposes a novel classification algorithm for optimizing sparse matrix storage formats, DyLaClass, based on dynamic labeling and flexible feature selection. Particularly, we introduce mixed labels and features with strong correlations, allowing us to achieve ultra-high prediction accuracy with minimal feature inputs, significantly reducing feature extraction overhead. For the first time, we propose the concept of the most suitable storage format rather than the best storage format, which can stably predict changes in the best format for the same matrix across multiple SpMV executions. We further demonstrate the proposed method on the University of Florida’s public sparse matrix collection dataset. Experimental results show that compared to existing work, our method achieves up to 91% classification accuracy. Using two different hardware platforms for verification, the proposed method outperforms existing methods by 1.26 to 1.43 times. Most importantly, the stability of the proposed prediction model is 25.5% higher than previous methods, greatly increasing the feasibility of the model in practical field applications.

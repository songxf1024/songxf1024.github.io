---
title: "GIMS: Image Matching System Based on Adaptive Graph Construction and Graph Neural Network"
collection: publications
permalink: /publications/GIMS
date: 2025-8-23
venue: 'Neural Networks'
paperurl: 'https://arxiv.org/abs/2412.18221'
codeurl: 'https://github.com/songxf1024/GIMS'
citation: 'Song X, Zou Y, Shi Z and Liu Z. GIMS: Image Matching System Based on Adaptive Graph Construction and Graph Neural Network[J]. Neural Networks, 2025.'
---

<div style="gap: 10px; display: flex; flex-direction: column; align-items: center;">
    <img src="/images/publications/NN25GIMS/overall_architecture.png" alt="Image 1" style="width: 800px; height: auto; border-radius: 5px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-bottom: 10px;">
</div>

Feature-based image matching has extensive applications in computer vision. Keypoints detected in images can be naturally represented as graph structures, and Graph Neural Networks (GNNs) have been shown to outperform traditional deep learning techniques. Consequently, the paradigm of image matching via GNNs has gained significant prominence in recent academic research. In this paper, we first introduce an innovative adaptive graph construction method that utilizes a filtering mechanism based on distance and dynamic threshold similarity. This method dynamically adjusts the criteria for incorporating new vertices based on the characteristics of existing vertices, allowing for the construction of more precise and robust graph structures while avoiding redundancy. We further combine the vertex processing capabilities of GNNs with the global awareness capabilities of Transformers to enhance the model's representation of spatial and feature information within graph structures. This hybrid model provides a deeper understanding of the interrelationships between vertices and their contributions to the matching process. Additionally, we employ the Sinkhorn algorithm to iteratively solve for optimal matching results. Finally, we validate our system using extensive image datasets and conduct comprehensive comparative experiments. Experimental results demonstrate that our system achieves an average improvement of 3.8x-40.3x in overall matching performance. Additionally, the number of vertices and edges significantly impacts training efficiency and memory usage; therefore, we employ multi-GPU technology to accelerate the training process. 

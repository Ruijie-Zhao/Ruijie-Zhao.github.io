---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Ruijie Zhao, a third-year student majoring in Computer Science and Technology from [Ningbo University](https://www.nbu.edu.cn/). My research interest includes computer vision, machine learning, multi-model and gaze estimation.


Publications
---

### Gaze-Swin: Enhancing Gaze Estimation with a Hybrid CNN-Transformer Network and Dropkey Mechanism
  <details>
  <summary markdown="span"><strong>Abstract</strong></summary>
    
  Gaze estimation, which seeks to reveal where a person is looking, provides a crucial clue for understanding human intentions and behaviors. Recently, Visual Transformer has achieved promising results in gaze estimation. However, dividing facial images into patches compromises the integrity of the image structure, which limits the inference performance. To tackle this challenge, we present Gaze-Swin, an end-to-end gaze estimation model formed with a dual-branch CNN-Transformer architecture. In Gaze-Swin, we adopt the Swin Transformer as the backbone network due to its effectiveness in handling long-range dependencies and extracting global features. Additionally, we incorporate a convolutional neural network as an auxiliary branch to capture local facial features and intricate texture details. To further enhance robustness and address overfitting issues in gaze estimation, we replace the original self-attention in the Transformer branch with Dropkey Assisted Attention (DA-Attention). In particular, this DA-Attention treats keys in the Transformer block as Dropout units and employs a decay Dropout rate schedule to preserve crucial gaze representations in deeper layers. Comprehensive experiments on three benchmark datasets demonstrate the superior performance of our method in comparison to the state of the art.
  
  </details>

- **Paper URL**: [Read the full paper](https://www.mdpi.com/2079-9292/13/2/328)

- **Citation**: Zhao R, Wang Y, Luo S, et al. Gaze-Swin: Enhancing Gaze Estimation with a Hybrid CNN-Transformer Network and Dropkey Mechanism[J]. Electronics, 2024, 13(2): 328.

### Improving Domain Generalization on Gaze Estimation via Branch-out Auxiliary Regularization
  <details>
  <summary markdown="span"><strong>Abstract</strong></summary>
    
  Despite remarkable advancements, mainstream gaze estimation techniques, particularly appearance-based methods, often suffer from performance degradation in uncontrolled environments due to variations in illumination and individual facial attributes. Existing domain adaptation strategies, limited by their need for target domain samples, may fall short in real-world applications. This letter introduces Branch-out Auxiliary Regularization (BAR), an innovative method designed to boost gaze estimation's generalization capabilities without requiring direct access to target domain data. Specifically, BAR integrates two auxiliary consistency regularization branches: one that uses augmented samples to counteract environmental variations, and another that aligns gaze directions with positive source domain samples to encourage the learning of consistent gaze features. These auxiliary pathways strengthen the core network and are integrated in a smooth, plug-and-play manner, facilitating easy adaptation to various other models. Comprehensive experimental evaluations on four cross-dataset tasks demonstrate the superiority of our approach.

  </details>
  
- **Paper URL**: [Read the full paper](https://arxiv.org/abs/2405.01439)

- **Citation**: Zhao R, Tang P, Luo S. Improving Domain Generalization on Gaze Estimation via Branch-out Auxiliary Regularization[J]. arXiv preprint arXiv:2405.01439, 2024.

Competition
---
- The 48th ACM-ICPC Asia Nanjing Regional Contest **Silver Medal**
- The 9th CCPC Qinhuangdao Regional Contest **Silver Medal**
- The 48th ACM-ICPC Asia Jinan Regional Contest **Bronze Medal**
- The 47th ACM-ICPC Asia Shenyang Regional Contest **Bronze Medal**
- The 47th ACM-ICPC Asia Jinan Regional Contest **Bronze Medal**
- 2024 Mathematical Contest In Modeling Certificate of achievement **Honorable Mention**

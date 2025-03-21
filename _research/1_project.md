---
layout: page
title: Knowledge Distillation Without Cross-Entropy
importance: 1
description: Research on eliminating logit-based loss in knowledge distillation via intelligent layer selection, enhancing training efficiency and model accuracy for computer vision.
img: assets/img/kd_image.png
category: AI and Machine Learning
---

---
Research conducted at The University of Colorado, Boulder  
Research Supervisor: Professor Danna Gurari and PhD Nick Cooper\
Conference Submission: NeurIPS 2025  


---

## **📜 Research Paper & Resources**
- **NeurIPS 2025 Submission**: *Towards Knowledge Distillation Without Cross-Entropy* (Under Review)
- **Research Institution**: University of Colorado, Boulder  
- **Focus Area**: **Knowledge Distillation**, **Intermediate Layer Learning**, **Logit-Free Training**
- **Code Repository**: *(Coming Soon!)*
- **Project Page & Resources**: *(Coming Soon!)*

---

## **🛠 Tech Stack & Tools**
- **Machine Learning & CV**: PyTorch, TorchVision, Vision Transformers (ViTs), VGG, ResNet  
- **Optimization**: Adam, One-cycle LR, PCA, SVD  
- **Datasets**: CIFAR-10, CIFAR-100, Tiny ImageNet  
- **Evaluation Metrics**: Accuracy, ARI, Training Efficiency (% Epochs Reduced)

---

## **📖 Research Overview**

This research introduces a novel **knowledge distillation method that eliminates the need for logit-based losses** (cross-entropy) when training student models. Traditional approaches use logits as the primary supervisory signal, but they often conflict with **intermediate layer knowledge**.

To solve this, our method:
- Proposes a **novel Knowledge Quality (KQ) metric** to select optimal teacher layers  
- Trains student backbones using only **intermediate feature loss** and **removes CE losses.** 
- Achieves improved performance across CNNs and ViTs on **image classification tasks**

---

## **📊 Major Contributions**

### **1. Logit-Free Knowledge Distillation**
- First method to train student backbones **without any logit-based loss (CE)**  
- Demonstrates significant gains in **training stability and generalization**

### **2. Knowledge Quality Metric for Layer Selection**
- Achieves superior performance when selecting teacher layers using this metric

### **3. Significant Accuracy & Efficiency Gains**
- Boosted **top-1 accuracy up to 15%** over baselines  
- Reduced training time by **up to 80%** across datasets and model pairs  

### **4. Robust Evaluation Across Architectures**
- Validated approach on **VGG, ResNet, MobileNet, ViTs**  
- Proved effectiveness across small and large-scale image datasets

---

## **🚀 Future Work & Applications**

- Extend KQ metric to **multi-teacher/multi-task settings**  
- Explore applicability to **language models and multimodal learning**  
- Develop **lightweight mobile-compatible student models** for real-time inference  

---

*For collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/saileshdwivedy/) or [Email](mailto:sailesh.dwivedy@colorado.edu).*

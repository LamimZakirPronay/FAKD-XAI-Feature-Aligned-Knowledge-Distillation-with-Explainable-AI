
FAKD-XAI: Feature-Aligned Knowledge Distillation with Explainable AI for Efficient Brain Tumor Classification

Abstract
Feature-Aligned Knowledge Distillation with XAI (FAKD-XAI)
Accurate and efficient classification of brain tumors by magnetic resonance imaging (MRI) scans is essential for clinical follow-up and treatment planning. However, in deep learning models, computational costs are often a significant barrier to practical application. This paper presents Feature-Aligned Knowledge Distillation with XAI (FAKD-XAI), a novel framework that classifies and rationally interprets brain tumors in an efficient manner. FAKD-XAI combines logit-level Knowledge Distillation with an adaptive intermediate feature-level distillation from ResNet-50 (Teacher Model) to a lightweight MobileNetV3-Large (Student Model) to facilitate learning between complex and simple models. Our alignment module featuring a 1×1 convolution layer was able to overcome the architectural divergences of the student model and enabled the efficient use of stratified feature transfer at different levels of the hierarchy. FAKD-XAI integrates Local Interpretable Model-agnostic Explanations (LIME), which enhances the understanding of the workings behind model predictions, promoting trust from clinicians. FAKD-XAI achieved an accuracy of 99.47% on the Brain Tumor MRI dataset while remaining computationally efficient for practical, clinical deployment. The use of Explainable AI (XAI) confirms that the model focuses on pertinent tumor areas, suggesting FAKD-XAI’s usefulness as a reliable diagnostic aid.

Dataset: Brain Tumor MRI Dataset from Kaggle

FAKD-XAI Framework

![68747470733a2f2f7777772e676f6f676c65617069732e636f6d2f646f776e6c6f61642f73746f726167652f76312f622f6b6167676c652d666f72756d2d6d6573736167652d6174746163686d656e74732f6f2f696e626f7825324631393138363138342532463433343836](https://github.com/user-attachments/assets/68d6da95-6076-478d-a575-2e86958b6823)

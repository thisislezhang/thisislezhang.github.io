---
layout: page
permalink: /research/
title: Projects I am working on
tags: [research]
modified: 3-10-2024
comments: false
---

Le's research is focusing on computational modelling, pattern recognition, and machine learning for biomedical imaging and data analysis. His research aims to add understanding and capability in biomedicine by drawing on ideas from medical imaging, computer vision, data science, and machine learning. Much of his work focusses on Cardiac Magnetic Resonance Image Analysis, Multi-Modality Neuroimage Analysis, and Retinal Fundus Image Analysis. His research has been published in top conferences and journals in the fields of machine learning and medical image analysis, including NeurIPS, MICCAI, Medical Image Analysis and Patten Recognition, and nominated for the MICCAI Young Scientist Award in 2019.

### Generative AI for Medical Imaging

Generative AI for medical imaging involves the use of artificial intelligence techniques, particularly generative models, to assist in various tasks within the field of medical imaging. These models can generate realistic images from scratch or modify existing images to improve their quality or highlight specific features. Key techniques include Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), and more recently, Transformers and Stable Diffusion. These techniques hold promise in enhancing medical imaging workflows by generating synthetic data for training deep learning models, improving image quality, aiding in disease diagnosis, and even facilitating personalized treatment plans. However, challenges such as the need for large and diverse datasets, ensuring the clinical relevance and safety of generated images, and interpretability of AI-generated results remain areas of active research and development. Despite these challenges, generative AI continues to show significant potential in revolutionizing medical imaging by providing tools to assist clinicians in more accurate and efficient diagnoses and treatments.
<br />
<br />
<img align="middle" width="800" src="{{ site.url }}/images/GenAI.gif" alt="...">
<br />
<br />
 
### Learning to Segment from Limited Labeled Data

Recent years have seen increasing use of supervised learning methods for segmentation tasks. However, the predictive performance of these algorithms depends on the quality of labels. This problem is particularly pertinent in the medical image domain, where both the annotation cost and inter-observer variability are high. In a typical label acquisition process, different human experts provide their estimates of the ``true'' segmentation labels under the influence of their own biases and competence levels. Treating these noisy labels blindly as the ground truth limits the performance that automatic segmentation algorithms can achieve. In this project, we present a method for jointly learning, from purely noisy observations alone, the reliability of individual annotators and the true segmentation label distributions, using two coupled CNNs. The separation of the two is achieved by encouraging the estimated annotators to be maximally unreliable while achieving high fidelity with the noisy training data.
<br />
<br />
<img align="middle" width="800" src="{{ site.url }}/images/NIPS.png" alt="...">
<br />
<br />


### Medical Image Quality Control

Accurate ventricular volume measurements depend on complete heart coverage in cardiac magnetic resonance (CMR) from where most immediate indicators of normal/abnormal cardiac function are available non-invasively. However, incomplete coverage, especially missing basal or apical slices in CMR sequences is insufficiently addressed in population imaging and current clinical research studies yet has important impact on volume calculation accuracy. In this project, we adapt the generative machine learning model to generate missing CMR slices, following manual, semi- or fully-automatic quality control (QC). We present a novel, robust method for image imputation based on a generative adversarial network to infer missing slices, conditioned on information in adjacent image slices.
<br />
<br />
<img align="middle" width="800" src="{{ site.url }}/images/IQA.jpg" alt="...">
<br />
<br />





---
layout: page
title: Outcome Prediction for Patients with Oropharyngeal Cancer
description: MSc Thesis —Contrastive Self-supervised Learning for Outcome Prediction of Patients with Oropharyngeal Cancer. <br> 

img: assets/img/oscc.png
importance: 4
category: Medical Image Analysis
---

<p style="font-size:22px"><b>Abstract</b></p>

---

With the emergence of new cancer subtypes and treatment options, there is a growing need for personalized treatment in patients with oropharyngeal squamous cell carcinoma (OPSCC). Developing robust outcome prediction models capable of identifying low and high-risk patients prior to treatment is a non-trivial task that may ultimately assist in stratifying patients for intensified or de-escalated treatment strategies, most suitable for them, without compromising their survival.

Deep learning methods have demonstrated remarkable potential for predicting prognostic outcomes in head and neck cancers. The standard approach entails fully-supervised learning on volumetric medical images. However, annotating 3D medical images is an immensely time-consuming and expensive process, and in some cases, it may be even infeasible due to stringent privacy regulations. Consequently, the availability of labeled data in this domain is often limited, rendering the training process extremely challenging.

Inspired by recent advances in self-supervised learning, this study delves into various <em>contrastive learning </em> frameworks for learning visual representations from medical images without relying on manual annotations. Throughout this endeavor, we also explore a diverse range of medical imaging modalities as input to determine the optimal configuration. Additionally, we conduct comparisons among different architectural choices, including <em>convolutional neural networks</em> and <em>vision transformers</em>. Furthermore, we investigate the extraction of features from multiple intermediate layers of these architectures to gain insights into the contribution of lower-level representations to the predictive performance of the models.

The ultimate goal is to improve long-term survival rates by accurately identifying potential high-risk patients prior to treatment based solely on their diagnostic imaging tests. To this end, two datasets sourced from the publicly accessible [TCIA (The Cancer Imaging Archive)](https://www.cancerimagingarchive.net/), namely the [Head-Neck-PET-CT](https://wiki.cancerimagingarchive.net/display/Public/Head-Neck-PET-CT) and [HNSCC](https://wiki.cancerimagingarchive.net/display/Public/HNSCC) collections, are employed for pre-training the models. Subsequently, the [OPC-Radiomics](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=33948764) dataset from the same repository is utilized for fine-tuning. Finally, we assess the generalization ability of our models on an independent external set of 400 OPSCC patients provided by the [University Medical Center Groningen, the Netherlands (UMCG)](https://umcgresearch.org/). <br> 

📈 <u><b>Our best model achieves a <b>15% increase</b> in accuracy compared to the state‑of‑the‑art methods.</b></u>



<br>

<p style="font-size:22px"><b>Research Questions</b></p>

---

We framed our investigation on contrastive representation learning for medical image analysis in
terms of the following research questions:

<ul>

<p> RQ1. &nbsp; &nbsp; <em> What is the optimal contrastive learning protocol? </em> </p>

<p> RQ2. &nbsp; &nbsp; <em> What is the optimal medical imaging modality? </em> </p>
<p> RQ3. &nbsp; &nbsp; <em> What is the optimal encoder for learning meaningful representations? </em> </p>
<p>RQ4. &nbsp; &nbsp; <em> Does multi-level feature extraction empower contrastive representation learning? </em> </p>
<p>RQ5. &nbsp; &nbsp; <em> Does ensemble learning boost performance over individual models? </em> </p>
</ul>


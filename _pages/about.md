---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I‘m a Ph.D. Candidate in the Department of Electrical and Computer Engineering at Florida International University (FIU), where I work as a Graduate Research&Teaching Assistant in Dr. Ou Bai’s Human Cyber-Physical Systems (HCPS) Laboratory. My research focuses on the intersection of Computer Vision, Deep Learning, Embedded Systems, and Multimodal Large Language Models (MLLMs), with an emphasis on real-time, resource-constrained, and wearable AI systems. I have published research in venues across multimedia, biometrics, computer vision, and natural language processing at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=k--3fM4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

Currently, I'm working on an AI-powered wearable multimodal multi-task real-time dynamic behavior analysis system, aiming to integrate perception, reasoning, and decision-making into embedded and edge AI platforms. Particularly interested in efficient multimodal LLM inference, model compression, and edge/embedded AI deployment, with the goal of enabling intelligent systems to operate reliably under strict latency, computation, and energy constraints. My research has been applied to a range of real-world cyber-physical systems, including wearable exoskeletons, multimodal emotion recognition, and human–AI interaction systems.

📫 Contact: pxiang@fiu.edu


# 🔥 News
- *2025.08*: &nbsp;🎉🎉 The [[**MTCAE-DFER Project**](https://github.com/Peihao-Xiang/MTCAE-DFER)] code has been uploaded to GitHub.
- *2025.07*: &nbsp;🎉🎉 The paper [**MTCAE-DFER**](https://arxiv.org/abs/2412.18988) has been accepted by the 9th IEEE International Joint Conference on Biometrics!
- *2025.06*: &nbsp;🎉🎉 The paper [**Label Ranker**](https://doi.org/10.1145/3731715.3733369) has been published on ACM DL.
- *2025.05*: &nbsp;🎉🎉 The [[**Label Ranker Project**](https://github.com/Peihao-Xiang/Label-Ranker)] code has been uploaded to GitHub.
- *2025.04*: &nbsp;🎉🎉 The paper [**Label Ranker**](https://www.preprints.org/manuscript/202503.0003) has been accepted by the 15th ACM International Conference on Multimedia Retrieval!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCB 2025</div><img src='Paper/Fusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MTCAE-DFER: Multi-Task Cascaded Autoencoder for Dynamic Facial Expression Recognition](https://arxiv.org/abs/2412.18988)

**Peihao Xiang**, Kaida Wu, Ou Bai

IEEE 9th International Joint Conference on Biometrics

8-11 September, 2025 \| Osaka, Japan

[[**IJCB 2025**](https://ijcb2025.ieee-biometrics.org/)][[**arXiv**](https://arxiv.org/abs/2412.18988)][[**Code**](https://github.com/Peihao-Xiang/MTCAE-DFER)]
- MTCAE-DFER learns robust spatiotemporal facial representations for dynamic expression recognition by cascading autoencoders under a multi-task learning framework that jointly optimizes reconstruction and classification.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICMR 2025</div><img src='Paper/OP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Label Ranker: Self-aware Preference for Classification Label Position in Visual Masked Self-supervised Pre-trained Model](https://doi.org/10.1145/3731715.3733369)

**Peihao Xiang**, Kaida Wu, Ou Bai

ACM 15th International Conference on Multimedia Retrieval

30 June - 3 July, 2025 \| Chicago, IL, USA

[[**ICMR 2025**](https://www.icmr-2025.org/)][[**Paper**](https://doi.org/10.1145/3731715.3733369)][[**Preprints**](https://www.preprints.org/manuscript/202503.0003)][[**Code**](https://github.com/Peihao-Xiang/Label-Ranker)][[**Video**](https://drive.google.com/file/d/1MhP51vQf-NjJPpR_13V6N2MW46kTq67b/view?usp=drive_link)]
- Label Ranker introduces a self-aware label positioning mechanism for visual masked self-supervised pre-trained models (e.g., MAE-style architectures). It observes that the position at which a classification label (or token) is injected into the model significantly affects downstream performance, yet is usually treated as a fixed or arbitrary design choice.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICPRS 2024</div><img src='Paper/MultiMAE-DER_V2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MultiMAE-DER: Multimodal Masked Autoencoder for Dynamic Emotion Recognition](https://doi.org/10.1109/ICPRS62101.2024.10677820)

**Peihao Xiang**, Chaohao Lin, Kaida Wu, Ou Bai

IEEE 14th International Conference on Pattern Recognition Systems

15-18 July, 2024 \| University of Westminster, London, UK

[[**ICPRS 2024**](http://s836450039.websitehome.co.uk/icprs24/index.html#intro)][[**Paper**](https://doi.org/10.1109/ICPRS62101.2024.10677820)][[**arXiv**](https://arxiv.org/abs/2404.18327)][[**Code**](https://github.com/Peihao-Xiang/MultiMAE-DER)][[**Video**](https://www.youtube.com/watch?v=HqaTGxtQaEo)]
- MultiMAE-DER proposes a multimodal masked autoencoder framework for dynamic emotion recognition (DER) that learns robust temporal–emotional representations by jointly modeling multiple modalities (e.g., visual, audio, and physiological signals). 
</div>
</div>

## Conference Papers

- [**ICML2026**](https://icml.cc/)\|[Entropy Reveals Block Importance in Masked Self-Supervised Vision Transformers](https://arxiv.org/abs/2602.03918)
  
  **Peihao Xiang**, Kaida Wu, Ou Bai
  
  Forty-Third International Conference on Machine Learning
  
  6-11 July, 2026 \| Seoul, South Korea

  [[**arXiv**](https://arxiv.org/abs/2602.03918)]
  
- [**AIRC2026**](https://www.airc.org/)\|[Load Estimation for Industrial Load-lifting Exoskeletons Using Insole Pressure Sensors and Machine Learning](https://arxiv.org/abs/2503.07527)

  Kaida Wu, **Peihao Xiang**, Chaohao Lin and Ou Bai

  IEEE 7th International Conference on Artificial Intelligence, Robotics, and Control

  8-10 April, 2026 \| Georgia Southern University, Savannah, GA, USA

  [[**arXiv**](https://arxiv.org/abs/2503.07527)]
  
- [**IJCB2025**](https://ijcb2025.ieee-biometrics.org/)\|[MTCAE-DFER: Multi-Task Cascaded Autoencoder for Dynamic Facial Expression Recognition](https://arxiv.org/abs/2412.18988)

  **Peihao Xiang**, Kaida Wu, Ou Bai

  IEEE 9th International Joint Conference on Biometrics

  8-11 September, 2025 \| Osaka, Japan

  [[**arXiv**](https://arxiv.org/abs/2412.18988)][[**Code**](https://github.com/Peihao-Xiang/MTCAE-DFER)]
  
- [**IJCNLP-AACL2025**](https://2025.aaclnet.org/)\|[CLL-RetICL: Contrastive Linguistic Label Retrieval-based In-Context Learning for Text Classification via Large Language Models](https://aclanthology.org/2025.findings-ijcnlp.97/)

  Chaohao Lin, Kaida Wu, **Peihao Xiang**, Yanzhao Wu, Ou Bai

  ACL 14th International Joint Conference on Natural Language Processing & the 4th Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics

  20-24 December, 2025 \| Mumbai, India

  [[**Paper**](https://aclanthology.org/2025.findings-ijcnlp.97/)][[**Code**](https://github.com/Toby28/CLLRetICL)]
  
- [**ICMR2025**](https://www.icmr-2025.org/)\|[Label Ranker: Self-aware Preference for Classification Label Position in Visual Masked Self-supervised Pre-trained Model](https://doi.org/10.1145/3731715.3733369)

  **Peihao Xiang**, Kaida Wu, Ou Bai

  ACM 15th International Conference on Multimedia Retrieval

  30 June - 3 July, 2025 \| Chicago, IL, USA

  [[**Paper**](https://doi.org/10.1145/3731715.3733369)][[**Preprints**](https://www.preprints.org/manuscript/202503.0003)][[**Code**](https://github.com/Peihao-Xiang/Label-Ranker)]
  
- [**AIAC2025**](https://2025.icaiac.org/)\|[Human Intention Detection for Upper-Limb Assistive Exoskeletons Using a Motor’s Built-in Current Sensor](https://doi.org/10.1109/AIAC68175.2025.11332347)

  Kaida Wu, **Peihao Xiang**, Chaohao Lin, Daniel Picado, Lixuan Chen, Ou Bai
  
  IEEE 3rd International Conference on Artificial Intelligence and Automation Control
  
  15-17 October, 2025 \| Paris, France

  [[**Paper**](https://doi.org/10.1109/AIAC68175.2025.11332347)]
  
- [**ASRU2025**](https://2025.ieeeasru.org/)\|[Emotional Styles Hide in Deep Speaker Embeddings: Disentangle Deep Speaker Embeddings for Speaker Clustering](https://arxiv.org/abs/2509.23358)

  Chaohao Lin, Xu Zheng, Kaida Wu, **Peihao Xiang**, Ou Bai
  
  IEEE 2025 Automatic Speech Recognition and Understanding Workshop
  
  6-10 December, 2025 \| Honolulu, Hawaii, USA

  [[**arXiv**](https://arxiv.org/abs/2509.23358)][[**Code**](https://github.com/Toby28/DDSESC)]
  
- [**ICPRS2024**](http://s836450039.websitehome.co.uk/icprs24/index.html#intro)\|[MultiMAE-DER: Multimodal Masked Autoencoder for Dynamic Emotion Recognition](https://doi.org/10.1109/ICPRS62101.2024.10677820)

  **Peihao Xiang**, Chaohao Lin, Kaida Wu, Ou Bai

  IEEE 14th International Conference on Pattern Recognition Systems

  15-18 July, 2024 \| University of Westminster, London, UK

  [[**Paper**](https://doi.org/10.1109/ICPRS62101.2024.10677820)][[**arXiv**](https://arxiv.org/abs/2404.18327)][[**Code**](https://github.com/Peihao-Xiang/MultiMAE-DER)]
  
- [**ICARCE2023**](https://www.icarce.com/)\|[Assessment of a Modular Upper-Limb Exoskeleton with Powered Assistance](https://doi.org/10.1109/ICARCE59252.2024.10492561)

  Kaida Wu, **Peihao Xiang**, Rodrigo Ramon, Aparna Aravelli, Leonel Lagos, Ou Bai

  IEEE 2nd International Conference on Automation, Robotics and Computer Engineering

  14-16 December, 2023 \| Wuhan, China

  [[**Paper**](https://doi.org/10.1109/ICARCE59252.2024.10492561)]

## Patents
- [Interaction Method, Device, Apparatus, Medium and Program Product](https://patents.google.com/patent/CN116107417A/en?q=(%E7%9B%B8)&inventor=%E4%BD%A9%E8%B1%AA&oq=%E7%9B%B8%E4%BD%A9%E8%B1%AA&page=1)

  Yuan Wang, **Peihao Xiang**, Lei Huang

  Publication date: 2023/5/12

  Patent number: CN 116107417 A

  Application number: 202111327835 .4

- [Visual and Tactile Feedback System](https://patents.google.com/patent/CN116088671A/en?q=(%E7%9B%B8)&inventor=%E4%BD%A9%E8%B1%AA&oq=%E7%9B%B8%E4%BD%A9%E8%B1%AA&page=1)

  Yuan Wang, **Peihao Xiang**, Lei Huang

  Publication date: 2023/5/9

  Patent number: CN 116088671 A

  Application number: 202111312751 .3

- [Visual-Tactile Feedback System](https://patents.google.com/patent/CN216052966U/en?q=(%E7%9B%B8)&inventor=%E4%BD%A9%E8%B1%AA&oq=%E7%9B%B8%E4%BD%A9%E8%B1%AA)

  Yuan Wang, **Peihao Xiang**, Lei Huang

  Publication date: 2022/3/15

  Patent Number: CN 216052966 U

  Application number: 202122723460 .5

- [Industrial Synchronous Pulse Fiber Optic Transceiver Server](https://patents.google.com/patent/CN214507078U/en?q=(%E7%9B%B8)&inventor=%E4%BD%A9%E8%B1%AA&oq=%E7%9B%B8%E4%BD%A9%E8%B1%AA&page=1)

  Yalei Yin, **Peihao Xiang**, Haipeng Liang

  Publication date: 2021/10/26

  Patent Number: CN 214507078 U

  Application number: 202120572811 .4

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

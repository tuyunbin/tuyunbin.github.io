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

I am a postdoctoral fellow from the University of Chinese Academy of Sciences (UCAS). My research interests include vision-and-language and multimedia content analysis. You can find my [CV](/assets/yunbin_cv.pdf) here.


I received my doctoral degree from UCAS in 2025, advised by [Prof. Li Su](https://people.ucas.ac.cn/~suli) and [Prof. Liang Li](https://vipl.ict.ac.cn/people/lliang/) (ICT, CAS). I received my master's degree from Kunming University of Science and Technology in 2022, advised by [Prof. Zhengtao Yu](https://xzy.kmust.edu.cn/info/1159/1311.htm). I received my bachelor's degree from Hangzhou Dianzi University in 2018, advised by [Prof. Chenggang Yan](https://auto.hdu.edu.cn/2019/0621/c3803a96028/page.htm). I was lucky to have opportunities to collaborate with [Assoc. Prof. Xishan Zhang](https://people.ucas.edu.cn/~zhangxishan)  (ICT, CAS) and [Prof. Xingzheng Wang](https://cmce.szu.edu.cn/info/1428/5099.htm)  (Shenzhen University).  **Feel free to reach out to me if you have an interest in the relevant topics.**



# 🔥 News
- 2025.11: A paper is accepted by IEEE TMM. Congrats to Zhuo Tao!
- 2025.09: A paper is accepted by IEEE TVCG. Congrats to Minghao Liu!
- 2025.09: A paper is accepted by NeurIPS 2025. Congrats to Junxi Chen!
- 2025.05: A paper is accepted by ACL 2025 Findings (long paper). Congrats to Yi Li!
- 2025.04: I will be serving as an Area Chair for ACM MM 2025.
- 2025.04: I will be serving as an Area Chair for EMNLP 2025.
- 2025.02: I will be serving as an Area Chair for ACL 2025.
- 2025.01: Selected for the Inaugural Doctoral Student Program under the Young Elite Scientists Sponsorship Program by CAST. （入选首届中国科协青年人才托举工程博士生专项计划，托举学会：中国计算机学会）
- 2024.12: Two papers are accepted by AAAI 2025. Congrats to Shijie Li!
- 2024.07: A paper is accepted by ECCV 2024.
- 2024.07: A paper is accepted by ACM MM 2024. Congrats to Shijie Li!
- 2024.07: A paper is accepted by IEEE TMM. Congrats to Yiting Liu!
- 2024.07: A paper is accepted by ECAI 2024. Congrats to Shijie Li!
- 2024.05: A paper is accepted by ACL 2024 main conference (long paper).
<!-- 2024.04: A paper is accepted by ACM TOMM. Congrats to [Shengbin Yue](https://yueshengbin.github.io/)! -->
<!-- 2024.01: A paper is accepted by IEEE TPAMI. &nbsp;🎉🎉🎉 -->

# 📝 Publications 

Selected publications are listed below, focusing on three primary research tasks: hierarchical retrieval and step-captioning, image difference captioning, and video captioning. The full list is available on <a href='https://scholar.google.com/citations?user=T-T1X0QAAAAJ&hl=en'><img src="https://img.shields.io/badge/Google%20Scholar-orange"></a>.

## 📚 Hierarchical Retrieval and Step-captioning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/QUAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Query-centric Audio-Visual Cognition Network for Moment Retrieval, Segmentation and Step-Captioning](https://ojs.aaai.org/index.php/AAAI/article/view/32803/34958) [[Code](https://github.com/tuyunbin/QUAG)]  

**Yunbin Tu**, Liang Li, Li Su, Qingming Huang

- QUAG addresses moment retrieval, moment segmentation, and step captioning in a unified framework.
- QUAG learns a query-centric audio-visual representation based on  the shallow-to-deep principle.
</div>
</div>



## 🖼️ Image Difference Captioning (Change Captioning)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/DIRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distractors-Immune Representation Learning with Cross-modal Contrastive Regularization for Change Captioning](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05989.pdf) [[Code](https://github.com/tuyunbin/DIRL)]  [[Supp.](https://arxiv.org/pdf/2407.11683)]

**Yunbin Tu**, Liang Li, Li Su, Chenggang Yan, Qingming Huang

<!-- <strong><span class='show_paper_citations' data='T-T1X0QAAAAJ:_kc_bZDykSQC'></span></strong> -->

<!-- [**Project**](https://github.com/ycmin95/VAC_CSLR) <strong><span class='show_paper_citations' data='qc2906sAAAAJ:u_35RYKgDlwC'></span></strong> -->
- DIRL attains a pair of stable image representations by correlating the corresponding their channels and decorrelating different ones.
- CCR regularizes the cross-modal alignment by maximizing the contrastive alignment between the attended difference features and generated words.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/CARD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Context-aware Difference Distilling for Multi-change Captioning](https://aclanthology.org/2024.acl-long.430.pdf) [[Code](https://github.com/tuyunbin/CARD)]  

**Yunbin Tu**, Liang Li, Li Su, Zheng-Jun Zha, Chenggang Yan, Qingming Huang

- CARD addresses multi-change captioning with an unknown number of changes.
- CARD decouples common/difference context features to guide the learning of features of all genuine changes for generating corresponding sentences. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/SMART.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SMART: Syntax-calibrated Multi-Aspect Relation Transformer for Change Captioning](https://ieeexplore.ieee.org/abstract/document/10433795) [[Code](https://github.com/tuyunbin/SMART)]  | *Extension work of SRDRL (ACL Findings 2021)*

**Yunbin Tu**, Liang Li, Li Su, Zheng-Jun Zha, Qingming Huang

- SMART uses a multi-aspect relation learning network to learn effective change features for caption generation.
- SMART uses a POS-based visual switch to dynamically use visual information during different word generation.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/SCORER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-supervised Cross-view Representation Reconstruction for Change Captioning](https://openaccess.thecvf.com/content/ICCV2023/papers/Tu_Self-supervised_Cross-view_Representation_Reconstruction_for_Change_Captioning_ICCV_2023_paper.pdf) [[Code](https://github.com/tuyunbin/SCORER)]  [[Supp.]( https://openaccess.thecvf.com/content/ICCV2023/supplemental/Tu_Self-supervised_Cross-view_Representation_ICCV_2023_supplemental.pdf)]

**Yunbin Tu**, Liang Li, Li Su, Zheng-Jun Zha, Chenggang Yan, Qingming Huang

- SCORER learns two view-invariant image representations by by maximizing cross-view contrastive alignment of two similar images.
- CBR reversely models a "hallucination" representation with the caption and "before" image, and matchs it with the real "after" image.
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2023</div><img src='images/VARD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Viewpoint-Adaptive Representation Disentanglement Network for Change Captioning](https://ieeexplore.ieee.org/document/10108947) [[Code](https://github.com/tuyunbin/VARD)]  

**Yunbin Tu**, Liang Li, Li Su, Junping Du, Ke Lu, Qingming Huang

- VARD helps the model  adapt to viewpoint changes via mining the intrinsic properties of two images and modeling their position information.
- VARD uses an unchanged representation disentanglement to distinguish the unchanged features from changed features.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2023</div><img src='images/NCT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Neighborhood Contrastive Transformer for Change Captioning](https://ieeexplore.ieee.org/document/10086696) [[Code](https://github.com/tuyunbin/NCT)]  

**Yunbin Tu**, Liang Li, Li Su, Ke Lu, Qingming Huang

- NCT learns the contrast features between two images via a  neighboring feature aggregating and a common feature distilling.  
- Explicit dependencies between words is used to help the decoder to better understand complex syntax structure during training.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2021</div><img src='images/R3NET.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[R<sup>3</sup>Net: Relation-embedded Representation Reconstruction Network for Change Captioning](https://aclanthology.org/2021.emnlp-main.735.pdf) [[Code](https://github.com/tuyunbin/r3net)] [[Video](https://aclanthology.org/2021.emnlp-main.735.mp4)]

**Yunbin Tu**, Liang Li, Chenggang Yan, Shengxiang Gao, Zhengtao Yu

- R<sup>3</sup>Net learns relations within each image and between two images to reconstruct unchanged and changed features. 
- R<sup>3</sup>Net uses syntactic skeleton predictor  to enhance  semantic interaction between change localization and caption generation. 
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Findings 2021</div><img src='images/SRDRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantic Relation-aware Difference Representation Learning for Change Captioning](https://aclanthology.org/2021.findings-acl.6.pdf) [[Code](https://github.com/tuyunbin/SRDRL)] [[Video](https://aclanthology.org/2021.findings-acl.6.mp4)]

**Yunbin Tu**, Tingting Yao, Liang Li, Jiedong Lou, Shengxiang Gao, Zhengtao Yu, Chenggang Yan

- SRDRL models self-semantic relation to explore the underlying changes, and measures cross-semantic relation  to localize the real change. 
- SRDRL relys on the POS of words, and uses an attention-based visual switch to dynamically use visual information for caption generation.
  
</div>
</div>

## 🎞️ Video Captioning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR 2023</div><img src='images/HMG+HTG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Relation-aware Attention for Video Captioning via Graph Learning](https://www.sciencedirect.com/science/article/abs/pii/S0031320322006835) 

**Yunbin Tu**, Chang Zhou, Junjun Guo, Huafeng Li, Shengxiang Gao, Zhengtao Yu

- HTG aims to enhance the inter-relation of attention by reversely modeling the relation of each word with respect to every attended visual feature.
- HMG aims to enhance the intra-relation of attention by capturing the relations among all of the attended visual features.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2022</div><img src='images/I2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[I<sup>2</sup>Transformer: Intra- and Inter-relation Embedding Transformer for TV Show Captioning](https://ieeexplore.ieee.org/document/9738841) [[Code](https://github.com/tuyunbin/I2Transformer)]  

**Yunbin Tu**, Li Su, Shengxiang Gao, Chenggang Yan, Zheng-Jun Zha, Zhengtao Yu, Qingming Huang

- TV show captioning aims to generate a linguistic sentence based on the video and its associated subtitle. 
- I<sup>2</sup>Transformer uses an intra-relation embedding to capture intra-relation in each modality and an inter-relation embedding to produce the omni-representation of all modalities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PR 2021</div><img src='images/TTA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing the alignment between target words and corresponding frames for video captioning](https://www.sciencedirect.com/science/article/abs/pii/S0031320320305057) [[Code](https://github.com/tuyunbin/Enhancing-the-Alignment-between-Target-Words-and-Corresponding-Frames-for-Video-Captioning)]  

**Yunbin Tu**, Chang Zhou, Junjun Guo, Shengxiang Gao, Zhengtao Yu

- TTA uses pre-detected visual tags from the video to bridge the gap between vision and language.
- TTA exactly align the target words with corresponding frames guided by the visual tags.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2019</div><img src='images/STAT_TMM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[STAT: Spatial-Temporal Attention Mechanism for Video Captioning](https://ieeexplore.ieee.org/document/8744407) [[Code](https://github.com/tuyunbin/Video-Description-with-Spatial-Temporal-Attention)]  | *Extension work of STAT (ACM MM 2017)*

Chenggang Yan, **Yunbin Tu**, Xingzheng Wang, Yongbing Zhang, Xinhong Hao, Yongdong Zhang, Qionghai Dai

- STAT uses both object-level visual and label features to address the problem of detail missing.
- STAT successfully takes into account both the spatial and temporal structures in a video.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2017</div><img src='images/STAT_MM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Description with Spatial-Temporal Attention](https://dl.acm.org/doi/10.1145/3123266.3123354) [[Code](https://github.com/tuyunbin/Video-Description-with-Spatial-Temporal-Attention)]  

**Yunbin Tu**, Xishan Zhang, Bingtao Liu, Chenggang Yan

- STAT uses object-level local features to address the problem of detail missing.
- STAT selects relevant local features by spatial attention and then attend to important frames by temporal attention to recognize related semantics.
</div>
</div>

# 🏆 Honors and Awards
-  The Inaugural Doctoral Student Program under the Young Elite Scientists Sponsorship Program, China Association for Science and Technology, 2025. （首届中国科协青年人才托举工程博士生专项计划，托举学会：中国计算机学会）
-  CAS President Scholarship (Excellent Prize), 2025. (中国科学院院长优秀奖)
-  AAAI Student Scholarship, 2025.
-  National Scholarship for Doctoral Students, Ministry of Education of the People’s Republic of China, 2024.
-  Diversity and Inclusion Award, Annual Meeting of the Association for Computational Linguistics (ACL), 2024.
-  National Scholarship for Master's Students, Ministry of Education of the People’s Republic of China, 2021.
-  Student Travel Grant, ACM International Conference on Multimedia (ACM MM), 2017.

# 📖 Educations
- 2022 - 2025, Ph.D. in Computer Applied Technology, University of Chinese Academy of Sciences (UCAS), China.
- 2019 – 2022, M.S. in Pattern Recognition and Intelligent Systems, Kunming University of Science and Technology (KUST), China.
- 2014 – 2018, B.S. in Automation, Hangzhou Dianzi University (HDU), China.

# 👨‍🏫 Academic Services
- Area Chair of ACL 2025 / EMNLP 2025 / ACM MM 2025
- Journal Reviewer of  TPAMI / TIP / TMM / TCSVT / PR / CVIU  ...
- Conference Reviewer of ICCV / CVPR / ECCV / NeurIPS / AAAI / ICLR ...

<!-- # ⚙️ Misc
- A summary of papers on gesture and sign language recognition. [![](https://img.shields.io/github/stars/ycmin95/awesome-Gesture-Sign-Language-Recognition?style=social&label=Awesome-Gesture-Sign-Language-Recognition Stars)](https://github.com/ycmin95/awesome-Gesture-Sign-Language-Recognition)
- A simple tool to visualize the main keywords of accepted papers for the recent Computer Vision conferences [![](https://img.shields.io/github/stars/ycmin95/CVPaperStatistics?style=social&label=CVPaperStatistics Stars)](https://github.com/ycmin95/CVPaperStatistics)


 # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

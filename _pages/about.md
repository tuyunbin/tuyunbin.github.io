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

I am a final-year Ph.D. student from the School of Computer Science and Technology, University of Chinese Academy of Sciences (UCAS). My research interests include vision-and-language and multimedia content analysis. You can find my [CV](/assets/yunbin_cv.pdf) here.


I am very fortunate to be advised by [Prof. Li Su](https://people.ucas.ac.cn/~suli) and [Prof. Liang Li](https://vipl.ict.ac.cn/people/lliang/) (ICT, CAS). I received my master's degree from Kunming University of Science and Technology in 2022, advised by [Prof. Zhengtao Yu](https://xzy.kmust.edu.cn/info/1159/1311.htm). I received my bachelor's degree from Hangzhou Dianzi University in 2018, advised by [Prof. Chenggang Yan](https://auto.hdu.edu.cn/2019/0621/c3803a96028/page.htm). I was lucky to have opportunities to collaborate with [Assoc. Prof. Xishan Zhang](http://www.ict.cas.cn/sourcedb_ict_cas/cn/jssrck/202003/t20200310_5509322.html)  (ICT, CAS) and [Prof. Xingzheng Wang](https://cmce.szu.edu.cn/info/1429/3786.htm)  (Shenzhen University).  



# 🔥 News
- *2024.09*: &nbsp;🎉🎉 One paper on skeleton-aware sign language recognition was accepted by ACCV 2024. Congratulations to Yifan Yang and the team!
- *2024.06*: &nbsp;🎉🎉 One paper on vision-language pre-training in SLT was accepted by ECCV 2024. Congratulations to Peiqi Jiao and the team!
- *2023.12*: &nbsp;🎉🎉 Successfully defended my PhD dissertation. 
- *2023.10*: &nbsp;🎉🎉 One paper on keyframe selection in CSLR was accepted by Scientia Sinica Informationis 2023. 
- *2023.10*: Present the doctoral consortium "Alignment Constraints for Video-based Sign Language Understanding" at the workshop on Assistive Computer Vision and Robotics at ICCV23 [[pdf]](https://iplab.dmi.unict.it/acvr2023/program/Alignment_Constraints_for_Video_based_Sign_Language_Understanding.pdf) [[workshop]](https://iplab.dmi.unict.it/acvr2023/program)
- *2023.07*: &nbsp;🎉🎉 One paper on co-occurrence signals in CSLR was accepted by ICCV 2023. Congratulations to Peiqi Jiao and the team!
- *2022.07*: &nbsp;🎉🎉 One paper on sequential representation learning was accepted by ECCV 2022.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/radialCTC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Radial Embedding for Visual Sequence Learning](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/5670_ECCV_2022_paper.php)

**Yuecong Min**, Peiqi Jiao, Yanan Li, Xiaotao Wang, Lei Lei, Xiujuan Chai, Xilin Chen

<strong><span class='show_paper_citations' data='qc2906sAAAAJ:u_35RYKgDlwC'></span></strong>

<!-- [**Project**](https://github.com/ycmin95/VAC_CSLR) <strong><span class='show_paper_citations' data='qc2906sAAAAJ:u_35RYKgDlwC'></span></strong> -->
- RadialCTC constrains sequence features on a hypersphere while retaining the iterative alignment mechanism of CTC, which also provides a clear geometric interpretation for CTC
- RadialCTC controls the peaky behavior with a simple angular perturbation term
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/vac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visual Alignment Constraint for Continuous Sign Language Recognition](https://openaccess.thecvf.com/content/ICCV2021/html/Min_Visual_Alignment_Constraint_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html)

**Yuecong Min**, Aiming Hao, Xiujuan Chai, Xilin Chen

[![](https://img.shields.io/github/stars/ycmin95/VAC_CSLR?style=social&label=VAC Stars)](https://github.com/ycmin95/VAC_CSLR) [![](https://img.shields.io/github/forks/ycmin95/VAC_CSLR?style=social&label=Forks)](https://github.com/ycmin95/VAC_CSLR) \| <strong><span class='show_paper_citations' data='qc2906sAAAAJ:zA6iFVUQeVQC'></span></strong>
- VAC provides an efficient way to make CSLR models end-to-end trainable and is adopted as the baseline model by many recent works
- Two metrics to evaluate the contributions of the feature extractor and the alignment module
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/pointlstm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Efficient PointLSTM for Point Clouds Based Gesture Recognition](https://openaccess.thecvf.com/content_CVPR_2020/html/Min_An_Efficient_PointLSTM_for_Point_Clouds_Based_Gesture_Recognition_CVPR_2020_paper.html)

**Yuecong Min**, Yanxiao Zhang, Xiujuan Chai, Xilin Chen

[![](https://img.shields.io/github/stars/ycmin95/pointlstm-gesture-recognition-pytorch?style=social&label=PointLSTM Stars)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch) [![](https://img.shields.io/github/forks/ycmin95/pointlstm-gesture-recognition-pytorch?style=social&label=Forks)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch) \| <strong><span class='show_paper_citations' data='qc2906sAAAAJ:iH-uZ7U-co4C'></span></strong>
- PointLSTM can leverage long-term spatio-temporal relationships in irregular sequence data (e.g., point cloud) while preserving the spatial structure for irregular sequence recognition problem
- Evaluation results on 3D gesture recognition and action recognition show great potential for real-time applications
</div>
</div>

- S2Net: Skeleton-aware SlowFast Network for Efficient Sign Language Recognition. Yifan Yang, **Yuecong Min**, Xilin Chen, accepted by Asian Conference on Computer Visionn (ACCV), 2024.
- [Visual Alignment Pre-training for Sign Language Translation.](https://www.ecva.net/papers/eccv_2024/papers_ECCV/html/5894_ECCV_2024_paper.php) Peiqi Jiao, **Yuecong Min**, Xilin Chen, European Conference on Computer Vision (ECCV), 2024. 
- [Adaptive Keyframe Selection for Continuous Sign Language Recognition.](https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0467) **Yuecong Min**, Xilin Chen, SCIENTIA SINICA Informationis, 2023.        
- [CoSign: Exploring Co-occurrence Signals in Skeleton-based Continuous Sign Language Recognition.](https://openaccess.thecvf.com/content/ICCV2023/html/Jiao_CoSign_Exploring_Co-occurrence_Signals_in_Skeleton-based_Continuous_Sign_Language_Recognition_ICCV_2023_paper.html) Peiqi Jiao, **Yuecong Min**, Yanan Li, Xiaotao Wang, Lei Lei, Xilin Chen, International Conference on Computer Vision (ICCV), 2023.
- [Self-Mutual Distillation Learning for Continuous Sign Language Recognition.](https://openaccess.thecvf.com/content/ICCV2021/html/Hao_Self-Mutual_Distillation_Learning_for_Continuous_Sign_Language_Recognition_ICCV_2021_paper.html) Aiming Hao, **Yuecong Min**, and Xilin Chen, International Conference on Computer Vision (ICCV), 2021.
- [Teaching Chinese Sign Language with A Smartphone.](https://www.sciencedirect.com/science/article/pii/S2096579621000309) Yanxiao Zhang, **Yuecong Min**, Xilin Chen, Virtual Reality &amp; Intelligent Hardware, 2021.
- [FlickerNet: Adaptive 3D Gesture Recognition from Sparse Point Clouds.](https://bmvc2019.org/wp-content/uploads/papers/0326-paper.pdf) **Yuecong Min**, Xiujuan Chai, Lei Zhao, Xilin Chen, British Machine Vision Conference (BMVC), 2019.


# 🎖 Honors and Awards
- **China National Scholarship for Ph.D.**, ICT, CAS, 2022


# 📖 Educations
- 2017.09 - 2024.1, I was a Ph.D. student at Institute of Computing Technology, CAS, under the supervision of Prof. [Xilin Chen](https://scholar.google.com/citations?user=vVx2v20AAAAJ&hl=en&oi=ao).
- 2013.09 - 2017.07, I was a college student in Shandong University, Weihai.

# ✒️ Academic Services
- Invited journal reviewer for
IEEE TPAMI / IEEE TMM / IEEE TIP / PR ...
- Invited conference reviewer for
CVPR'22 /ACM MM'22 / ECCV'22 / CVPR'23 ...

# ⚙️ Misc
- A summary of papers on gesture and sign language recognition. [![](https://img.shields.io/github/stars/ycmin95/awesome-Gesture-Sign-Language-Recognition?style=social&label=Awesome-Gesture-Sign-Language-Recognition Stars)](https://github.com/ycmin95/awesome-Gesture-Sign-Language-Recognition)
- A simple tool to visualize the main keywords of accepted papers for the recent Computer Vision conferences [![](https://img.shields.io/github/stars/ycmin95/CVPaperStatistics?style=social&label=CVPaperStatistics Stars)](https://github.com/ycmin95/CVPaperStatistics)


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

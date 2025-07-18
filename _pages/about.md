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
I am currently a third-year Ph.D. student (2022–now) in the Department of Automation at the University of Science and Technology of China (USTC), supervised by <a href="https://scholar.google.com/citations?user=9sCGe-gAAAAJ&hl=en" target="_blank">Prof. Tianzhu Zhang</a>. I received my bachelor's degree in Computer Science and Technology from Central South University in 2022.

My research interests lie in semantic segmentation, few-shot learning, and AI-generated content (AIGC).

I have published some papers at the top international AI conferences. 
<!-- with <a href='https://scholar.google.com/citations?user=WelDcqkAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 LARM was accepted by ICCV 2025.
- *2025.05*: &nbsp;🎉🎉 <a href="https://icml.cc/virtual/2025/poster/46247" target="_blank">BLDA</a> was accepted by ICML 2025.
- *2025.03*: &nbsp;🎉🎉 <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Dual-Agent_Optimization_framework_for_Cross-Domain_Few-Shot_Segmentation_CVPR_2025_paper.pdf" target="_blank">DATO</a> was accepted by CVPR 2025.
- *2025.03*: &nbsp;🎉🎉 <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Unbiased_Video_Scene_Graph_Generation_via_Visual_and_Semantic_Dual_CVPR_2025_paper.pdf" target="_blank">VISA</a> was accepted by CVPR 2025.
- *2024.12*: &nbsp;🎉🎉  I got <strong>1<sup>st</sup></strong> place on WSI-level Glomeruli Detection in Kidney Pathology Image Segmentation Challenge (MICCAI 2024).
- *2024.07*: &nbsp;🎉🎉 <a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09199.pdf" target="_blank">DLE</a> was accepted by ECCV 2024.
- *2024.04*: &nbsp;🎉🎉 <a href="https://www.ijcai.org/proceedings/2024/0164.pdf" target="_blank">DENet</a> was accepted by IJCAI 2024.
- *2023.09*: &nbsp;🎉🎉 I got <strong>1<sup>st</sup></strong> place on Cell Detection from Cell-Tissue Interaction Challenge (MICCAI 2023)
- *2022.12*: &nbsp;🎉🎉 I got <strong>Meritorious Winner</strong> (Rank: 4/102) in the Weakly Supervised Cell Segmentation in Multi-modality High-Resolution Microscopy Images Challenge (NeurIPS 2022).



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/BLDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Balanced Learning for Domain Adaptive Semantic Segmentation](https://icml.cc/virtual/2025/poster/46247)
Wangkai Li, Rui Sun, Bohao Liao, **Zhaoyang Li**, Tianzhu Zhang.
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/DATO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dual-Agent Optimization framework for Cross-Domain Few-Shot Segmentation](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Dual-Agent_Optimization_framework_for_Cross-Domain_Few-Shot_Segmentation_CVPR_2025_paper.pdf)

**Zhaoyang Li**, Yuan Wang, Wangkai Li, Tianzhu Zhang, Xiang Liu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/VISA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unbiased Video Scene Graph Generation via Visual and Semantic Dual Debiasing](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_Unbiased_Video_Scene_Graph_Generation_via_Visual_and_Semantic_Dual_CVPR_2025_paper.pdf)

Yanjun Li, **Zhaoyang Li**, Honghui Chen, Lizhi Xu

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/DLE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Localization and expansion: A decoupled framework for point cloud few-shot semantic segmentation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09199.pdf)

**Zhaoyang Li**, Yuan Wang, Wangkai Li, Rui Sun, Tianzhu Zhang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/DEnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aggregation and purification: dual enhancement network for point cloud few-shot segmentation](https://www.ijcai.org/proceedings/2024/0164.pdf)

Guoxin Xiong, Yuan Wang, **Zhaoyang Li**, Wenfei Yang, Tianzhu Zhang, Xu Zhou, Shifeng Zhang, Yongdong Zhang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>


# 🎖 Honors and Awards
- First-class Scholarship, Graduate School of USTC
- First-class Scholarship, Undergraduate School of Central South University


# 📖 Educations
- *2022.09 - (now)*, Ph.D. student in the Department of Automation at the University of Science and Technology of China (USTC), Hefei.
- *2018.09 - 2022.06*, Undergraduate, Central South University, Changsha.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.06-now*, Bytedance <img src="/images/bytedance_logo.png" alt="Bytedance Logo" style="height: 1em; vertical-align: middle; margin-left: 4px;">, Shanghai.
- *2022.12-2024.06*, Institute of Artifical Intelligence, Hefei Comprehensive National Science Center <img src="/images/AI_lab.PNG" alt="AL Logo" style="height: 2em; vertical-align: middle; margin-left: 2px;">, Hefei.


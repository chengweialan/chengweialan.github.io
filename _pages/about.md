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

# 😊 About Me

I'm a fourth-year student at College of Engineering, Peking University. 

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 One paper submitted to CVPR 2025.
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr20252.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeSiRe-GS: 4D Street Gaussians for Static-Dynamic Decomposition
and Surface Reconstruction for Urban Driving Scenes](https://chatgpt.com/)

Chensheng Peng, **Chengwei Zhang**, Yixiao Wang, Yichen Ye

[**Project**](https://chatgpt.com/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

-We present DeSiRe-GS, a self-supervised gaussian splatting representation, enabling effective static-dynamic decomposition and high-fidelity surface reconstruction inchallenging driving scenarios. 
</div>
</div>


# 🎖 Honors and Awards
- *2022* Boeing Scholarship (Third Prize), College of Engineering, Peking University
- *2023* China Optics Valley Scholarship
- *2023* Merit Student of Peking University

# 📖 Educations
<img src="images/pku.png" alt="Peking University Logo" style="height: 2em; vertical-align: middle; margin-right: 8px;"> 
*2021.09 - 2025.07 (expected)*, B.S. in Robotics and Mechanics, College of Engineering, Peking University

# 💻 Research Experiences
<img src="images/pku.png" alt="Peking University Logo" style="height: 2em; vertical-align: middle; margin-right: 8px;"> 
*2023.05 - 2024.10*, Efficient Vision-guided Active SLAM Based On Terrain Information, advised by Prof.Chang Liu, College of Engineering, Peking University.

<img src="images/pku.png" alt="Peking University Logo" style="height: 2em; vertical-align: middle; margin-right: 8px;"> 
*2024.06 - Now*, Reinforcement Learning on Soft Robotics, advised by Prof.Ke Liu, College of Engineering, Peking University.

<img src="images/ucb.png" alt="Peking University Logo" style="height: 2em; vertical-align: middle; margin-right: 8px;"> 
*2024.07 - 2024.11*, 4D Street Gaussians for Static-Dynamic Decomposition and Surface Reconstruction for Urban Driving Scenes, advised by Prof.Masayoshi Tomizuka, School of Mechanical Engineering, UC Berkeley.

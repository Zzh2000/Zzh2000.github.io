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
# About Me
My name is Zihan Zhu (朱紫涵). I’m currently a [Direct Doctorate](https://inf.ethz.ch/doctorate/direct-doctorate-computer-science.html) student at ETH Zurich in Computer Science, supervised by Prof. Marc Pollefeys. I obtained my Bachelor degree at [Zhejiang University](https://www.zju.edu.cn/english/). My research interest lies in the intersection between computer vision and computer graphics. 

# 🔥 News
- *2023.03*: &nbsp;🎉🎉 Our paper NeRF On-the-go is accepted to CVPR 2024!
- *2023.03*: &nbsp;🎉🎉 NICER-SLAM received the <span style="color:#c20000;">Best Paper Honorable Mention Award</span> at 3DV 2024! 
- *2023.11*: &nbsp;🎉🎉 Our paper NICER-SLAM is accepted to 3DV 2024! 
- *2022.03*: &nbsp;🎉🎉 One paper conditionally accepted to SIGGRAPH 2022 (journal track)!
- *2022.03*: &nbsp;🎉🎉 I have been admitted to the Direct Doctorate programme in the ETH Zurich Department of Computer Science!
- *2022.03*: &nbsp;🎉🎉 Our paper NICE-SLAM is accepted to CVPR 2022! 

# 📖 Educations
- *2022.09 - present*, Direct Doctorate, Department of Computer Science, ETH Zurich, Zurich, Switzerland. 
- *2018.09 - 2022.06*, Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy, Hangzhou, China. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><img src='https://pengsongyou.github.io/media/teaser_otg3.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[NeRF On-the-go Exploiting Uncertainty for Distractor-free NeRFs in the Wild](https://rwn17.github.io/nerf-on-the-go/), [Weining Ren\*](https://github.com/rwn17),**Zihan Zhu\***, [Boyang Sun](https://inf.ethz.ch/people/people-atoz/person-detail.MjY0ODc2.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html), [Jiaqi Chen](https://inf.ethz.ch/people/people-atoz/person-detail.Mjc4NTY0.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Songyou Peng](https://pengsongyou.github.io)

( * equal contribution)

**CVPR, 2024** | [**Project**](https://rwn17.github.io/nerf-on-the-go/) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We enable robust novel view synthesis from casually captured in-the-wild images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/nicer_teaser.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[NICER-SLAM: Neural Implicit Scene Encoding for RGB SLAM](https://nicer-slam.github.io), **Zihan Zhu\***, [Songyou Peng\*](https://pengsongyou.github.io), [Viktor Larsson](https://vlarsson.github.io/), [Zhaopeng Cui](https://zhpcui.github.io/), [Martin R Oswald](http://people.inf.ethz.ch/moswald/), [Andreas Geiger](https://www.cvlibs.net/), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/)

( * equal contribution)

**3DV, 2024 (Oral, <span style="color:#c20000;">Best Paper Honorable Mention Award</span>)** | [**Project**](https://nicer-slam.github.io) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- **RGB-only** version of our [**NICE-SLAM**](http://pengsongyou.github.io/nice-slam), making it NICE**R**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='https://superxjm.github.io/source_files/Neural%20Indoor.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Scalable Neural Indoor Scene Rendering](https://xchaowu.github.io/papers/scalable-nisr/), [Xiuchao Wu\*](https://xchaowu.github.io/), [Jiamin Xu\*](https://superxjm.github.io/), **Zihan Zhu**, [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Qixing Huang](https://www.cs.utexas.edu/~huangqx/), [James Tompkin](https://jamestompkin.com/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)

( * equal contribution)

ACM Transactions on Graphics (TOG) 41, 4 (**SIGGRAPH 2022**) | [**Project**](https://xchaowu.github.io/papers/scalable-nisr/) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A scalable neural scene reconstruction and rendering method to support distributed training and interactive rendering of large indoor scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='https://pengsongyou.github.io/media/nice-slam/teaser.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[NICE-SLAM: Neural Implicit Scalable Encoding for SLAM](https://arxiv.org/pdf/2112.12130.pdf), **Zihan Zhu\***, [Songyou Peng\*](https://pengsongyou.github.io), [Viktor Larsson](https://vlarsson.github.io/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Zhaopeng Cui](https://zhpcui.github.io/), [Martin R Oswald](http://people.inf.ethz.ch/moswald/), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/)

( * equal contribution)

**CVPR, 2022** \| [**Project**](http://pengsongyou.github.io/nice-slam) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A neural implicit-based RGB-D SLAM that can be applied to large-scale scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/ibrsig21.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Scalable Image-based Indoor Scene Rendering with Reflections](https://yangzzzy.github.io/PDF/reflectiveIBR21.pdf), [Jiamin Xu](https://superxjm.github.io/), [Xiuchao Wu](https://xchaowu.github.io/), **Zihan Zhu**, [Qixing Huang](https://www.cs.utexas.edu/~huangqx/), [Yin Yang](https://yangzzzy.github.io/), [Hujun Bao](), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)

ACM Transactions on Graphics (TOG) 40, 4 (**SIGGRAPH 2021**) | [**Project**](https://dl.acm.org/doi/10.1145/3450626.3459849) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- An image-based rendering method that can be applied to large-scale indoor scenes with reflections.
</div>
</div>


<!-- 
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), Jiamin Xu, Xiuchao Wu, **Zihan Zhu**, Qixing Huang, Yin Yang, Hujun Bao, Weiwei Xu, **SIGGRAPH 2021** -->

<!-- 
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 💻 Academic Services
Conference Reviewer: CVPR, ICCV, ECCV, IROS, ICRA, SIGGRAPH, SIGGRAPH Asia, 3DV

Journal Reviewer: T-RO, RA-L, TVCG, TPAMI


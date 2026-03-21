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
- *2026.03*: &nbsp;🎉🎉 Our paper DROID-W is accepted to CVPR 2026!
- *2025.02*: &nbsp;🎉🎉 Our paper WildGS-SLAM is accepted to CVPR 2025!
- *2024.03*: &nbsp;🎉🎉 Our paper NeRF On-the-go is accepted to CVPR 2024!
- *2023.03*: &nbsp;🎉🎉 NICER-SLAM received the <span style="color:#c20000;">Best Paper Honorable Mention Award</span> at 3DV 2024! 
- *2023.11*: &nbsp;🎉🎉 Our paper NICER-SLAM is accepted to 3DV 2024! 
- *2022.03*: &nbsp;🎉🎉 One paper conditionally accepted to SIGGRAPH 2022 (journal track)!
- *2022.03*: &nbsp;🎉🎉 I have been admitted to the Direct Doctorate programme in the ETH Zurich Department of Computer Science!
- *2022.03*: &nbsp;🎉🎉 Our paper NICE-SLAM is accepted to CVPR 2022! 

# 📖 Educations
- *2022.09 - present*, Direct Doctorate, Department of Computer Science, ETH Zurich, Zurich, Switzerland. 
- *2018.09 - 2022.06*, Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy, Hangzhou, China. 

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div style="position:relative;" onmouseover="this.querySelector('img').style.display='none';this.querySelector('video').play();" onmouseout="this.querySelector('video').pause();this.querySelector('video').currentTime=0;this.querySelector('img').style.display='block';"><video width="100%" muted loop playsinline preload="auto"><source src='images/vigs_demo.mp4' type='video/mp4'></video><img src='images/vigs_poster.jpg' style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;" /></div></div>
<div class='paper-box-text' markdown="1">

[VIGS-SLAM: Visual Inertial Gaussian Splatting SLAM](https://vigs-slam.github.io/), **Zihan Zhu**, [Wei Zhang](https://www.ifp.uni-stuttgart.de/en/institute/team/Zhang-00004/), [Moyang Li](https://moyangli00.github.io/), [Norbert Haala](https://www.ifp.uni-stuttgart.de/institut/team/Haala-00001/), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Dániel Béla Baráth](https://cvg.ethz.ch/team/Dr-Daniel-Bela-Barath)

**arXiv, 2025** | [**Project**](https://vigs-slam.github.io/)
- Visual inertial Gaussian Splatting SLAM for robust and accurate localization and mapping.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div style="position:relative;" onmouseover="this.querySelector('img').style.display='none';this.querySelector('video').play();" onmouseout="this.querySelector('video').pause();this.querySelector('video').currentTime=0;this.querySelector('img').style.display='block';"><video width="100%" muted loop playsinline><source src='https://moyangli00.github.io/droid-w/static/videos/teaser.mp4' type='video/mp4'></video><img src='images/droidw_poster.jpg' style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;" /></div></div>
<div class='paper-box-text' markdown="1">

[DROID-W: DROID-SLAM in the Wild](https://moyangli00.github.io/droid-w/), [Moyang Li\*](https://moyangli00.github.io/), **Zihan Zhu\***, [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Dániel Béla Baráth](https://cvg.ethz.ch/team/Dr-Daniel-Bela-Barath)

( * equal contribution)

**CVPR, 2026** | [**Project**](https://moyangli00.github.io/droid-w/)
- Extending DROID-SLAM to handle in-the-wild scenes with dynamic objects and appearance changes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><video width="100%" muted loop playsinline onmouseover="this.play()" onmouseout="this.load();"><source src='https://wildgs-slam.github.io/resources/demo.mp4' type='video/mp4'></video></div>
<div class='paper-box-text' markdown="1">

[WildGS-SLAM: Monocular Gaussian Splatting SLAM in Dynamic Environments](https://wildgs-slam.github.io/), [Jianhao Zheng\*](https://jianhao-zheng.github.io/), **Zihan Zhu\***, [Valentin Bieri](https://www.linkedin.com/in/valentin-bieri-98426b207/), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Songyou Peng](https://pengsongyou.github.io), [Iro Armeni](https://ir0.github.io/)

( * equal contribution)

**CVPR, 2025** | [**Project**](https://wildgs-slam.github.io/)
- Monocular Gaussian Splatting SLAM that robustly handles dynamic environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><video width="100%" muted loop playsinline poster='https://pengsongyou.github.io/media/teaser_otg3.jpg' onmouseover="this.play()" onmouseout="this.load();"><source src='https://pengsongyou.github.io/media/teaser_otg_1.5x.mp4' type='video/mp4'></video></div>
<div class='paper-box-text' markdown="1">

[NeRF On-the-go Exploiting Uncertainty for Distractor-free NeRFs in the Wild](https://rwn17.github.io/nerf-on-the-go/), [Weining Ren\*](https://github.com/rwn17),**Zihan Zhu\***, [Boyang Sun](https://inf.ethz.ch/people/people-atoz/person-detail.MjY0ODc2.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html), [Jiaqi Chen](https://inf.ethz.ch/people/people-atoz/person-detail.Mjc4NTY0.TGlzdC8zMDQsLTIxNDE4MTU0NjA=.html), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Songyou Peng](https://pengsongyou.github.io)

( * equal contribution)

**CVPR, 2024** | [**Project**](https://rwn17.github.io/nerf-on-the-go/) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We enable robust novel view synthesis from casually captured in-the-wild images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><video width="100%" muted loop playsinline poster='https://pengsongyou.github.io/media/nicer_teaser.jpg' onmouseover="this.play()" onmouseout="this.load();"><source src='https://pengsongyou.github.io/media/nicer_teaser.mp4' type='video/mp4'></video></div>
<div class='paper-box-text' markdown="1">

[NICER-SLAM: Neural Implicit Scene Encoding for RGB SLAM](https://nicer-slam.github.io), **Zihan Zhu\***, [Songyou Peng\*](https://pengsongyou.github.io), [Viktor Larsson](https://vlarsson.github.io/), [Zhaopeng Cui](https://zhpcui.github.io/), [Martin R Oswald](http://people.inf.ethz.ch/moswald/), [Andreas Geiger](https://www.cvlibs.net/), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/)

( * equal contribution)

**3DV, 2024 (Oral, <span style="color:#c20000;">Best Paper Honorable Mention Award</span>)** | [**Project**](https://nicer-slam.github.io) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- **RGB-only** version of our [**NICE-SLAM**](http://pengsongyou.github.io/nice-slam), making it NICE**R**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><video width="100%" muted loop playsinline onloadedmetadata="this.currentTime=0.001;" onmouseover="this.play()" onmouseout="this.pause();this.currentTime=0.001;"><source src='https://xchaowu.github.io/papers/scalable-nisr/videos/salon.mp4' type='video/mp4'></video></div>
<div class='paper-box-text' markdown="1">

[Scalable Neural Indoor Scene Rendering](https://xchaowu.github.io/papers/scalable-nisr/), [Xiuchao Wu\*](https://xchaowu.github.io/), [Jiamin Xu\*](https://superxjm.github.io/), **Zihan Zhu**, [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Qixing Huang](https://www.cs.utexas.edu/~huangqx/), [James Tompkin](https://jamestompkin.com/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)

( * equal contribution)

ACM Transactions on Graphics (TOG) 41, 4 (**SIGGRAPH 2022**) | [**Project**](https://xchaowu.github.io/papers/scalable-nisr/) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A scalable neural scene reconstruction and rendering method to support distributed training and interactive rendering of large indoor scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><video width="100%" muted loop playsinline poster='https://pengsongyou.github.io/media/nice_teaser.jpg' onmouseover="this.play()" onmouseout="this.load();"><source src='https://pengsongyou.github.io/media/nice_teaser.mp4' type='video/mp4'></video></div>
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


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

I am currently a master student at Beijing Institute of Technology (BIT). I am reaserching under the supervision of P. Lizhi Wang. I received my bachelor's degree from BIT in 2023. My research interest includes Low-Level Computer Vision (Image Restoration), Generative models (Diffusion model) and Self-supervised methods. I'm also interested in Image Representations, Image Quality Assessment, AI for science and other interesting topics.




# 🔥 News
- *2024.05*: &nbsp;🎉🎉 Our paper DMID is accepted by TPAMI.
- *2025.02*: &nbsp;🎉🎉 Our paper Positive2Negative is accepted by CVPR.
- <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
<span id="busuanzi_container_site_pv">The total number of visits to this site：<span id="busuanzi_value_site_pv"></span></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/1-DMID.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stimulating the Diffusion Model for Image Denoising via Adaptive Embedding and Ensembling](https://arxiv.org/abs/2307.03992)

**Tong Li**, Hansen Feng, Lizhi Wang, Zhiwei Xiong, Hua Huang

[**Paper**](https://ieeexplore.ieee.org/document/10607932) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
| [**Code**](https://github.com/Li-Tong-621/DMID)
| [**Note**](https://zhuanlan.zhihu.com/p/1898420817429262557)
| [**Note**](https://zhuanlan.zhihu.com/p/639911080)
- We present a novel strategy called the Diffusion Model for Image Denoising (DMID) by understanding and rethinking the diffusion model from a denoising perspective.
- Our DMID strategy includes an adaptive embedding method that embeds the noisy image into a pre-trained unconditional diffusion model and an adaptive ensembling method that reduces distortion in the denoised image.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/2-P2N.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Positive2Negative: Breaking the Information-Lossy Barrier in Self-Supervised Single Image Denoising](https://arxiv.org/abs/2412.16460)

**Tong Li**, Lizhi Wang, Zhiyuan Xu, Lin Zhu, Wanxuan Lu, Hua Huang

[**Paper**](https://arxiv.org/abs/2412.16460) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
| [**Code**](https://github.com/Li-Tong-621/P2N)
- We propose a new self-supervised single image denoising paradigm, Positive2Negative, to break the information-lossy barrier.
- We propose a data construction method, which constructs multi-scale similar noisy images for training.
- We propose a denoising supervision method, which is theoretically guaranteed to learn robust denoising.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/3-PDE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[PDE: Gene Effect Inspired Parameter Dynamic Evolution for Low-light Image Enhancement](https://arxiv.org/abs/2505.09196)

**Tong Li**, Lizhi Wang, Hansen Feng, Lin Zhu, Hua Huang

[**Paper**](https://arxiv.org/abs/2505.09196) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
| [**Code**](https://github.com/Li-Tong-621/P2N)
- We identify and illustrate a counterintuitive phenomenon in existing models, which we refer to as the “gene effect”.
- We propose the PDE method to mitigate the gene effect, primarily relying on the POG technique.
- Experiments show our method mitigate the gene effect while improving the performance of LLIE.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/4-p2n-tpami.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Positive2Negative 期刊拓展](https://arxiv.org/abs/2412.16460)

**Tong Li**, Lizhi Wang, Zhiyuan Xu, Lin Zhu, Wanxuan Lu, Hua Huang

[**Paper**](https://arxiv.org/abs/2412.16460) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
| [**Code**](https://github.com/Li-Tong-621/P2N)
- We propose a new self-supervised single image denoising paradigm, Positive2Negative, to break the information-lossy barrier. +
- We propose a data construction method, which constructs multi-scale similar noisy images for training. +
- (Private) 
- We propose a denoising supervision method, which is theoretically guaranteed to learn robust denoising.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/4-p2n-tpami.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[YOND: Practical Blind Raw Image Denoising Free from Camera-Specific Data Dependency](https://arxiv.org/abs/2506.03645)

Hansen Feng, Lizhi Wang, Yiqi Huang, **Tong Li**, Lin Zhu, Hua Huang

[**Paper**](https://arxiv.org/abs/2412.16460) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
| [**Code**](https://github.com/Li-Tong-621/P2N)
- We introduce a novel blind raw image denoising method. With our method, an AWGN denoiser can generalize to various real raw data with a single training on synthetic datasets. We name our method YOND, as you need nothing else under our method, You Only Need a Denoiser.
- YOND consists of three key modules: the coarse-to-fine noise estimation (CNE), the expectation-matched variance-stabilizing transform (EM-VST), and the SNR-guided denoiser (SNR-Net).
- Extensive experiments across diverse camera datasets, along with flexible solutions for challenging cases, demonstrate the practicality of YOND.
</div>
</div>

# 🎖 Honors and Awards
- *2022.10* National Scholarship of China. 
- *2023.06* Outstanding Graduate Award of Beijing.
- *2023.06* Outstanding Graduation Thesis Award of Beijing. 
- *2024.10* National Scholarship of China. 


# 💻 Internships
- *2024.12 - 2025.05*, 美团, Research (Poster Generation - SD & FLUX)
- *2025.05 - *, 阿里妈妈, T-Star Lab Research (基模Base Model - Poster Generation - FLUX & HiDream)


# 📖 Educations
- *2023.09 - (now)*, Beijing Institute of Technology (BIT), Master. 
- *2019.09 - 2023.06*, Beijing Institute of Technology (BIT), Bechelor. 




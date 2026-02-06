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

I graduated with a bachelor's degree in Computer Science and Technology from Hohai University in June 2023.
Currently, I am pursuing a Ph.D. in Computer Science and Technology at Nankai University, under the guidance of Professor [Li, Tao](https://scholar.google.com/citations?user=FWamm4sAAAAJ&hl=zh-CN).

My primary research interests encompass diffusion models, image restoration and digital image processing. I have published top international AI conferences with total 
<a href="https://scholar.google.com/citations?user=IJiK74oAAAAJ">
  <img src="https://img.shields.io/endpoint?url=https://github.com/YukinoshitaLove/YukinoshitaLove.github.io/blob/google-scholar-stats/gs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>.

# 💡 Tech Transfer
VIVO X200 series: <a href="https://www.dxomark.com/putting-the-vivo-x200-pro-to-the-test-in-china/">High-fidelity generative diffusion models for telephoto image enhancement​</a>

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 ICLR 2026 Accepted. 
- *2024.09*: &nbsp;🎉🎉 NeurIPS 2024 Accepted. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 </div><img src='images/papers/livemoments.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
LiveMoments: Reselected Key Photo Restoration in Live Photos via Reference-guided Diffusion

Clara Xue, Zizheng Yan, <strong>Zhenning Shi</strong>, Yuhang Yu, Jingyu Zhuang, Qi Zhang, Jinwei Chen, Qingnan Fan

- The first to address the problem of reselected key photo restoration in Live Photos.
- LiveMoments significantly improves perceptual quality and fidelity over existing solutions, including the recent flagships from vivo and iPhone.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Arxiv </div><img src='images/papers/TriFlowSR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Ultra-High-Definition Reference-Based Landmark Image Super-Resolution with Generative Diffusion Prior](./pdfs/2508.10779v1.pdf)

<strong>Zhenning Shi</strong>, Zizheng Yan, Yuhang Yu, Clara Xue, Jingyu Zhuang, Qi Zhang, Jinwei Chen, Tao Li, Qingnan Fan
  
<a href="https://arxiv.org/abs/2508.10779" target="_blank">arXiv</a>
/
<a href="https://github.com/nkicsl/TriFlowSR" target="_blank">codes</a>

- The first to address ultra-high-definition (UHD) reference-based landmark image super-resolution under real-world degradations with a diffusion-based RefSR pipeline.
- Proposes TriFlowSR, a three-branch diffusion framework with Patch-Ref Attention to explicitly match LR and reference-HR features at the patch level, enabling better transfer of semantic and texture details and reducing artifacts.
- Introduces Landmark-4K, the first UHD RefSR dataset for landmarks (185 high-quality images, 49 categories; avg. resolution ~ $3295 \times 3295$.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> NeurIPS 2024 </div><img src='images/papers/Resfusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Resfusion: Denoising diffusion probabilistic models for image restoration based on prior residual noise](./pdfs/2311.14900v4.pdf)

<strong>Zhenning Shi</strong>, Haoshuai Zheng, Chen Xu, Changsheng Dong, Bin Pan, Xueshuo Xie, Along He, Tao Li, Huazhu Fu
  
<a href="https://arxiv.org/abs/2311.14900" target="_blank">arXiv</a>
/
<a href="https://github.com/nkicsl/Resfusion" target="_blank">codes</a>

- Start diffusion-based restoration process from noisy degraded images (not pure Gaussian noise) by injecting the residual term into the forward diffusion process, reducing unnecessary sampling.
- Proposes Resfusion, a general restoration framework that defines a weighted residual noise target (“resnoise”) and explicitly derives the quantitative relationship between the residual and noise terms, keeping the reverse process DDPM-consistent.
- Demonstrates competitive results with only five sampling steps, without requiring any physics-based priors.
</div>
</div>

# 📖 Educations
*2023 - now*: <strong>NKICS@NKU</strong>, *Nankai University*, China
- Nankai University, College of Computer Science, Ph.D.
- Supervisor: *Prof.* [Tao Li](https://scholar.google.com/citations?user=FWamm4sAAAAJ&hl=zh-CN)

*2019 - 2023*: <strong>AIM Group@HHU</strong>, *Hohai University*, China
- Hohai University, College of Computer Science, Bachelor
- Supervisor: *Prof.* [Fan Liu](https://scholar.google.com/citations?user=Sneof_QAAAAJ&hl=zh-CN)

# 💻 Internships
*2025.01 - 2025.08*: *[VIVO](https://www.vivo.com)*, China.
- Imaging Algorithm Center of VIVO, Assistant Algorithm Engineer
- Supervisor: *Dr.* [Qinnan Fan](https://scholar.google.com/citations?user=2cY2zwUAAAAJ&hl=en)
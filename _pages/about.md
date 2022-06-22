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

I work at X Lab as a research scientist now, leading the neuromorphic computing team and doing some fundamental neuromorphic computing-related research and engineering project. We are hiring researchers and engineers to work on neuromorphic computing, network binarization and quantization, object detection, SLAM, and path navigation. If interested, feel free to email me at yfguo@pku.edu.cn.

My research interest includes computer vision and computational mechanics. 
<!--
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2022.07*: &nbsp;🎉🎉 One first-authored paper for spiking neural network is accepted by CVPR 2022. 
- *2022.09*: &nbsp;🎉🎉 One co-first-authored paper for spiking neural network is accepted by NeurIPS 2021. 

# 📝 Selected Publications 

## 📹 Computer vision
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Yufei Guo\* **, Xinyi Tong\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Zhe Ma, Xuhui Huang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/recdis.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecDis-SNN: Rectifying Membrane Potential Distribution for Directly Training Spiking Neural Networks](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_RecDis-SNN_Rectifying_Membrane_Potential_Distribution_for_Directly_Training_Spiking_Neural_CVPR_2022_paper.pdf)

**Yufei Guo**\*, Xinyi Tong\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Zhe Ma, Xuhui Huang
  
- We present a new perspective to understand the difficulty of training SNNs by analyzing three undesired shifts of membrane potential distribution in forward propagation and the MPD-Loss to penalize the undesired shifts. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/differential.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Differentiable Spike: Rethinking Gradient-Descent for Training Spiking Neural Networks](https://proceedings.neurips.cc/paper/2021/file/c4ca4238a0b923820dcc509a6f75849b-Paper.pdf)

Yuhang Li\*, **Yufei Guo**\*, Shanghang Zhang, Shikuang Deng, Yongqing Hai, Shi Gu
  
- we propose a new family of Differentiable Spike (Dspike) functions that can adaptively evolve during training to find the optimal shape and smoothness for gradient estimation for spiking neural networks. 
</div>
</div>

## 🛠️ Computational mechanics

- [A CAE-oriented mesh hole-filling algorithm focusing on geometry and quality](https://www.emerald.com/insight/content/doi/10.1108/EC-07-2021-0411/full/html), Yongqing Hai, **Yufei Guo**\*, Mo Dong, **Engineering Computations 2022**, Corresponding Author.
- [A new mesh smoothing method based on a neural network](https://link.springer.com/article/10.1007/s00466-021-02097-z), **Yufei Guo**, Chuanrui Wang, Zhe Ma, Xuhui Huang, Kewu Sun, Rongli Zhao, **Computational Mechanics 2022**, First Author.
- [An Improved Advancing-front-Delaunay Method for Triangular Mesh Generation](https://link.springer.com/article/10.1007/s00466-021-02097-z), **Yufei Guo**, Xuhui Huang, Zhe Ma, Rongli Zhao, Kewu Sun, **Computer Graphics International Conference 2021**, First Author.
- [Adaptive surface mesh remeshing based on a sphere packing method and a node insertion/deletion method](https://www.sciencedirect.com/science/article/abs/pii/S0307904X21002353?via%3Dihub), **Yufei Guo**\*, Yongqing Hai\*, **Applied Mathematical Modelling 2021**, First Author.
- [Regular Position-Oriented Method for Mesh Smoothing](https://link.springer.com/article/10.1007/s10338-020-00201-z), Yongqing Hai, **Yufei Guo**\*, Siyuan Cheng, Yunpeng Hai, **Acta Mechanica Solida Sinica 2020**, Corresponding Author.
- [Direct modifications of tetrahedral meshes](https://www.emerald.com/insight/content/doi/10.1108/EC-12-2019-0573/full/html), **Yufei Guo**, Yongqing Hai, Jianfei Liu, **Engineering Computations 2020**, First Author.

# 🎖 Honors and Awards
- *2017.11* The second prize of Wechat applet application development competition 2017.
- *2016.10* The first prize of Huawei codecraft 2016.
- *2014.10* China National Scholarship.  

# 📖 Educations
- *2015.09 - 2020.07*, Docter, Peking University, Beijing. 
- *2011.09 - 2015.06*, Undergraduate, Beijing Institute of Technology, Beijing. 

# 💬 Invited Talks
- *2021.06*, 

# 💻 Internships
- *2019.05 - 2020.02*, [megvii](https://www.megvii.com/), China.
- *2014.06 - 2015.10*, [IBE](http://www.ibe.cn/), China.

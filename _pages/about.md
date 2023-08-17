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

I work at S Lab as a research scientist now, leading the advanced intelligent computing team and doing some fundamental intelligent computing-related research and engineering project. We are hiring researchers, engineers, and interns to work on neuromorphic computing, network compression, object detection, SLAM, path navigation and robtics. If interested, feel free to email me at yfguo@pku.edu.cn.

My research interest includes machine learning, computer vision, and computational mechanics. I have published more than 10 papers at the top international AI conferences and Mathematics & Mechanics journals.
<!--
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2023.07*: &nbsp;🎉 Two first-authored papers for spiking neural network are accepted by ICCV 2023.
- *2023.06*: &nbsp;🎉 One first-authored paper for reviewing spiking neural network is accepted by the Frontiers in Neuroscience journal.
- *2023.04*: &nbsp;🎉 One first-authored paper for spiking neural network is accepted by the Pattern Recognition journal.
- *2023.02*: &nbsp;🎉 Two papers are accepted by CVPR2023, including one corresponding-authored paper for 3D object detection.
- *2022.09*: &nbsp;🎉 One first-authored paper for spiking neural network is accepted by NeurIPS 2022.
- *2022.09*: &nbsp;🎉 I get the support by national natural science foundation of China 2022.
- *2022.07*: &nbsp;🎉 Two first-authored papers for spiking neural network are accepted by ECCV 2022.
- *2022.04*: &nbsp;🎉 One first-authored paper for spiking neural network is accepted by CVPR 2022. 
- *2021.09*: &nbsp;🎉 One first-authored paper about mesh smoothing based on neural network is accepted by Applied Mathematical Modelling Journal.
- *2021.09*: &nbsp;🎉 One co-first-authored paper for spiking neural network is accepted by NeurIPS 2021. 

# 📝 Publications 

## 📓 Review
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Frontiers in Neuroscience 2022</div><img src='images/review.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Direct Learning-Based Deep Spiking Neural Networks: A Review](https://arxiv.org/abs/2305.19725)

🖥️[**Project**](https://github.com/yfguo91/Awesome-Spiking-Neural-Networks) 📰[**Paper**](https://arxiv.org/abs/2305.19725)

**Yufei Guo**, Xuhui Huang, Zhe Ma

- In this paper, we present a comprehensive survey of these direct learning-based deep SNN works, mainly categorized into accuracy improvement methods, efficiency improvement methods, and temporal dynamics utilization methods.
</div>
</div>

## 🖥️ Machine learning
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/rmploss.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RMP-Loss: Regularizing Membrane Potential Distribution for Spiking Neural Networks](https://arxiv.org/pdf/2308.06787.pdf)

**Yufei Guo**\*, Xiaode Liu\*, Yuanpei Chen, Liwen Zhang, Weihang Peng, Yuhan Zhang, Xuhui Huang, Zhe Ma
  
- This paper aims to address the information loss problem caused by the 0/1 spike quantization of SNNs. We introduce RMP-Loss to adjust the membrane potential distribution which is directly related to quantization error to a range close to the spikes to reduce the quantization error. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/mpbn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Membrane Potential Batch Normalization for Spiking Neural Networks](https://arxiv.org/pdf/2308.08359.pdf) 

🖥️[**Code**](https://github.com/yfguo91/MPBN) 📰[**Paper**](https://arxiv.org/pdf/2308.08359.pdf)

**Yufei Guo**\*, Yuhan Zhang\*, Yuanpei Chen, Weihang Peng, Xiaode Liu, Liwen Zhang, Xuhui Huang, Zhe Ma
  
- In the paper, we advocated adding the MPBN before the firing function to regulate the disturbed data flow again. We also provided a training-inference-decoupled re-parameterization technique to fold the trained MPBN into the firing threshold to eliminate the extra time burden induced by MPBN in the inference time.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition 2023</div><img src='images/distill.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Joint A-SNN: Joint Training of Artificial and Spiking Neural Networks via Self-Distillation and Weight Factorization](https://linkinghub.elsevier.com/retrieve/pii/S0031320323003400) 

🖥️[**Code**](https://github.com/yfguo91/Joint-A-SNN) 📰[**Paper**](https://linkinghub.elsevier.com/retrieve/pii/S0031320323003400)

**Yufei Guo**\*, Weihang Peng\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Xuhui Huang, Zhe Ma
  
- In this paper, we have introduced the joint-training framework of ANN and SNN. Our framework consists of two core ingredients, the first is self-distillation from multiple branches, and the second is weight-factorized training assisted by the Singular Value Decomposition. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/imloss.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[IM-Loss: Information Maximization Loss for Spiking Neural Networks](https://openreview.net/pdf?id=Jw34v_84m2b) 

🖥️[**Code**](https://github.com/yfguo91/IM-Loss-Information-Maximization-Loss-for-Spiking-Neural-Networks) 📰[**Paper**](https://openreview.net/pdf?id=Jw34v_84m2b)

**Yufei Guo**\*, Yuanpei Chen\*, Liwen Zhang, Xiaode Liu, YingLei Wang, Xuhui Huang, Zhe Ma
  
- We design a novel loss, IM-Loss, which can directly maximize the information expressiveness of an SNN, and introduce the ESG method for training SNN in a more appropriate way by incorporating a dynamically changing coefficient into a differentiable asymptotic function.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/reloss.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reducing Information Loss for Spiking Neural Networks](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710036.pdf) 
  
🖥️[**Code**](https://github.com/yfguo91/Re-Loss) 📰[**Paper**](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710036.pdf)

**Yufei Guo**\*, Yuanpei Chen\*, Liwen Zhang, YingLei Wang, Xiaode Liu, Xinyi Tong, Yuanyuan Ou, Xuhui Huang, Zhe Ma
  
- This work aims at addressing the information loss problem caused by the ''Hard Reset'' mechanism of neurons and the 0/1 spike quantification. Then, the SRIF
model, which will drive the membrane potential to a dynamic reset potential, and the MPR that can adjust the membrane potential to a new value closer to quantification spikes than itself are proposed. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/real.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Real Spike: Learning Real-valued Spikes for Spiking Neural Networks](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720052.pdf)

🖥️[**Code**](https://github.com/yfguo91/Real-Spike) 📰[**Paper**](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136720052.pdf)
  
**Yufei Guo**\*, Liwen Zhang\*, Yuanpei Chen, Xinyi Tong, Xiaode Liu, YingLei Wang, Xuhui Huang, Zhe Ma
  
- We proposed Real Spike, which aims at enhancing the representation capacity for an SNN by learning real-valued spikes during training and transferring the
rich representation capacity into inference-time SNN by re-parameterizing the shared convolution kernel to different ones.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/recdis.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RecDis-SNN: Rectifying Membrane Potential Distribution for Directly Training Spiking Neural Networks](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_RecDis-SNN_Rectifying_Membrane_Potential_Distribution_for_Directly_Training_Spiking_Neural_CVPR_2022_paper.pdf)

**Yufei Guo**\*, Xinyi Tong\*, Yuanpei Chen, Liwen Zhang, Xiaode Liu, Zhe Ma, Xuhui Huang
  
- We present a new perspective to understand the difficulty of training SNNs by analyzing three undesired shifts of membrane potential distribution in forward propagation and the MPD-Loss to penalize the undesired shifts. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2021</div><img src='images/differential.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Differentiable Spike: Rethinking Gradient-Descent for Training Spiking Neural Networks](https://proceedings.neurips.cc/paper/2021/file/c4ca4238a0b923820dcc509a6f75849b-Paper.pdf)

Yuhang Li\*, **Yufei Guo**\*, Shanghang Zhang, Shikuang Deng, Yongqing Hai, Shi Gu
  
- We propose a new family of Differentiable Spike (Dspike) functions that can adaptively evolve during training to find the optimal shape and smoothness for gradient estimation for spiking neural networks. 
</div>
</div>

[PeakConv: Learning Peak Receptive Field for Radar Semantic Segmentation](), **CVPR 2023**
- Liwen Zhang, Xinyan Zhang, Youcheng Zhang, **Yufei Guo**, Yuanpei Chen, Xuhui Huang, Zhe Ma.


## 📹 Computer vision
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/gciou.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Dive into Gradients: Better Optimization for 3D Object Detection with Gradient-Corrected IoU Supervision](https://openaccess.thecvf.com/content/CVPR2023/papers/Ming_Deep_Dive_Into_Gradients_Better_Optimization_for_3D_Object_Detection_CVPR_2023_paper.pdf)

🖥️[**Code**](https://github.com/ming71/GCIoU-loss) 📰[**Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Ming_Deep_Dive_Into_Gradients_Better_Optimization_for_3D_Object_Detection_CVPR_2023_paper.pdf)

Qi Ming, Lingjuan Miao, Zhe Ma, Lin Zhao, Zhiqiang Zhou\*, Xuhui Huang, Yuanpei Chen, **Yufei Guo**\*
  
- In this paper, we demonstrate through experiments and mathematical proof that the gradients of 3D IoU loss w.r.t. angle error and the object scale change abnormally during training. Then, we propose a gradient-correction IoU loss for optimizing the gradient.
</div>
</div>

## 🛠️ Computational mechanics
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Computational Mechanics 2022</div><img src='images/smoothing.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A new mesh smoothing method based on a neural network](https://link.springer.com/article/10.1007/s00466-021-02097-z)

🖥️[**Code**](https://github.com/yfguo91/meshsmoothing) 📰[**Paper**](https://link.springer.com/article/10.1007/s00466-021-02097-z)
  
**Yufei Guo**, Chuanrui Wang, Zhe Ma, Xuhui Huang, Kewu Sun, Rongli Zhao
  
- We present a new smoothing method. The proposed method imitates the optimization-based smoothing based on a neural network, but it calculates the optimal position of a free node straightforwardly. Hence, the proposed method is more efficient than these optimization-based smoothing methods while being comparable in terms of mesh quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Applied Mathematical Modelling 2021</div><img src='images/balls.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive surface mesh remeshing based on a sphere packing method and a node insertion/deletion method](https://www.sciencedirect.com/science/article/abs/pii/S0307904X21002353?via%3Dihub) 

🖥️[**Code**](https://github.com/yfguo91/remesh) 📰[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0307904X21002353?via%3Dihub)
  
**Yufei Guo**\*, Yongqing Hai\*
  
- We present a triangular mesh remeshing method based on a sphere packing method and a node insertion/deletion method for surface meshes. The proposed method remeshes the surface mesh without projection of local areas, the intersection of fronts, Lloyd relaxation, and other complicated calculations, and the proposed method can generate a high-quality mesh without dependence on the quality of the original mesh, which make the method efficient and effective.
</div>
</div>

[B-rep construction, defeaturing, and meshing algorithms for discretized model](https://kns.cnki.net/kcms/detail/detail.aspx?filename=ZKZX202304015&dbname=cjfdtotal&dbcode=CJFD&v=MDYzMzRpUXJSY3pGckNVUjdtZll1WnJGeUhoVUwzS1B5YlJkckc0SE5MTXE0OUVZWVI2RGc4L3poWVU3enNPVDM=), **China Sciencepaper 2023**
- **Yufei Guo**, Kewu Sun, Rongli Zhao, Yinglei Wang, Yuanpei Chen, Zhibin Wang,  **First Author**.


[Enhanced optimal delaunay triangulation methods with connectivity regularization](http://www.amjcu.zju.edu.cn/amjcub/2020-2029/202203/453-469.pdf),  **Appl. Math. J. Chinese Univ. 2022**
- Yongqing Hai, **Yufei Guo**\*, Rongli Zhao, Kewu Sun, Feifei Shang, **Corresponding Author**.


[A CAE-oriented mesh hole-filling algorithm focusing on geometry and quality](https://www.emerald.com/insight/content/doi/10.1108/EC-07-2021-0411/full/html), **Engineering Computations 2022**
- Yongqing Hai, **Yufei Guo**\*, Mo Dong, **Corresponding Author**.


[Triangular Mesh Boolean Operation Method for Finite Element Analysis](https://www.china-simulation.com/CN/10.16182/j.issn1004731x.joss.20-0957), **Journal of System Simulation 2022**
- **Yufei Guo**, kang Zhao, Yongqing Hai, **First Author**.


[An Improved Advancing-front-Delaunay Method for Triangular Mesh Generation](https://link.springer.com/article/10.1007/s00466-021-02097-z), **Computer Graphics International Conference 2021**
- **Yufei Guo**, Xuhui Huang, Zhe Ma, Rongli Zhao, Kewu Sun, **First Author**.


[Regular Position-Oriented Method for Mesh Smoothing](https://link.springer.com/article/10.1007/s10338-020-00201-z), **Acta Mechanica Solida Sinica 2020**
- Yongqing Hai, **Yufei Guo**\*, Siyuan Cheng, Yunpeng Hai,  **Corresponding Author**.


[Direct modifications of tetrahedral meshes](https://www.emerald.com/insight/content/doi/10.1108/EC-12-2019-0573/full/html), **Engineering Computations 2020**
- **Yufei Guo**, Yongqing Hai, Jianfei Liu, **First Author**.


[Surface Adaptive Mesh Generation for STL Models Based on Ball-Packing Method](https://www.jcad.cn/jcadcms/show.action?code=publish_402880124b362464014b3c4d819803a1&newsid=3b5491011cd34af2bb3043a6ef810cec), **Journal of Computer-Aided Design and Computer Graphics 2018**
- **Yufei Guo**, Feifei Shang, Jianfei Liu, **First Author**.

# 💬 Invited Talks
- *2022.08*, I am invited to talk about Spiking Neural Networks at the conference on intelligence and aerospace.
- *2022.07*, I am invited to talk about Spiking Neural Networks at the conference on mathematics and aerospace.

# 🎖 Honors and Awards
- *2022.09* The National Natural Science Foundation of China 2022.

# 📖 Educations
- *2015.09 - 2020.07*, Doctor, Peking University, Beijing. 
- *2011.09 - 2015.06*, Undergraduate, Beijing Institute of Technology, Beijing. 

# 💻 Academic Services
- **Reviewer** of Conferences: AAAI, CVPR, ECCV, NeurIPS, etc.
- **Reviewer** of Journals: Computational Mechanics, Applied Mathematical Modelling, Engineering Computations, etc.

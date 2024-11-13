---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======

Hi! :wave: I am a fourth-year undergraduate in the Tang Ao-qing Honors Program in Computer Science at **Jilin University**. 

During my undergraduate studies, I have been fortunate to collaborate with Professor **[Wenbin Liu](https://ccst.jlu.edu.cn/info/1209/18150.htm)** and Professor **[Rui Ma](https://ruim-jlu.github.io/)** at **Jilin University**, focusing on spatiotemporal data mining and 3D vision, respectively. I also gained valuable experience as a visiting student under the supervision of Professor **[Zhaopeng Cui](https://zhpcui.github.io/)** at **Zhejiang University**, where I worked on 3D vision. Additionally, I completed two academic visits to the **University of Alberta**, where I focused on computer graphics, lasting one month and three months, respectively.

:key: My current research interest involves **computer graphics** and **3D vision**.

Publications
======

1. *GaussianPrediction: Dynamic 3D Gaussian Prediction for Motion Extrapolation and Free View Synthesis* <br/>
Boming Zhao, Yuan Li, **Ziyu Sun**, Lin Zeng, Yujun Shen, Rui Ma, Yinda Zhang, Hujun Bao, Zhaopeng Cui <br/>
*<a href="https://dl.acm.org/doi/abs/10.1145/3641519.3657417" target="_blank">Siggraph 2024</a>.*
[<a href="{{base.url}}/files/GaussianPrediction.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/GaussianPrediction.bib" target="_blank">BibTeX</a>] <details>
<img src="{{base.url}}/files/GSPrediction_task.png" alt="Converted PDF as Image" width="350">
<img src="{{base.url}}/files/GSPrediction_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
  This project marks my first exploration into **3D vision**, where I gained foundational research experience by collaborating with outstanding PhD students. In this work, we propose a **more compact 3D Gaussian Splatting (3DGS) representation** for dynamic scenes based on key points. We achieved an exciting task, which we call **future synthesis**: predicting the future movements of dynamic objects and generating renderings from arbitrary perspectives. My responsibilities included constructing the framework for the extrapolation network and assisting with the training of the reconstruction networks.</details>

2. *From Incomplete Coarse-Grained to Complete Fine-Grained: A Two-Stage Framework for Spatiotemporal Data Reconstruction* <br/>
**Ziyu Sun**, Haoyang Su, En Wang, Funing Yang, Yongjian Yang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2410.05323" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/DiffRecon.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/DiffRecon.bib" target="_blank">BibTeX</a>]<details>
<img src="{{base.url}}/files/DiffRecon_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/DiffRecon_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This work focuses on enhancing **spatial continuity** in data mining. Our key contribution is the introduction of a novel task called "**Spatiotemporal Data Reconstruction**," which leverages concepts from computer vision to infer a complete, fine-grained spatiotemporal map from incomplete, coarse-grained observations. We also propose a **two-stage diffusion model** that effectively captures spatiotemporal characteristics, leading to state-of-the-art performance.It is worth noting that this work is part of a series with *Toward Time-Continuous Data Inference in Sparse Urban CrowdSensing*, as both aim to achieve more precise (finer-grained in this work) modeling of real-world spatiotemporal data, with this work emphasizing the spatial perspective.</details>

4. *Toward Time-Continuous Data Inference in Sparse Urban CrowdSensing* <br/>
**Ziyu Sun**, Haoyang Su, Hanqi Sun, En Wang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2408.16027" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/time-dmf.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/time-dmf.bib" target="_blank">BibTeX</a>] <details>
<img src="{{base.url}}/files/time-dmf_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/time-dmf_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This work focuses on enhancing **temporal continuity** in data mining. Our key observation is that existing approaches often rely on "**time-discrete**" preprocessing steps before applying their algorithms, which can lead to inaccuracies. Most existing methods divide the timeline into discrete intervals and aggregate data within each unit, assuming data remains static within these intervals. In our research, we first adapt existing time-discrete solutions to a **fine-grained approach** by slicing the timeline into the smallest possible units for alignment with prior work. We then elevate this approach into a **time-continuous** model that accurately represents data along a continuous timeline. This work is part of a series with *From Incomplete Coarse-Grained to Complete Fine-Grained: A Two-Stage Framework for Spatiotemporal Data Reconstruction*, both aiming to achieve more precise modeling of real-world scenarios with a particular emphasis on temoral continuity in this study.<br/>This is my first academic work, and I face numerous challenges, from getting the model to function correctly to writing the paper independently. I am proud that I finished it finally. After multiple resubmissions, the paper is now in major revision. </details>


Projects
======

#### Computer graphics related

1. *Implementing a renderer from scratch* <br/>
Finished during my summer visit to the University of Alberta 
*[<a href="https://github.com/Zysun2002/Renderer-Alberta" target="_blank">Project Link</a>.]*<details>
<img src="{{base.url}}/files/pumpkin.gif" alt="Converted PDF as Image" width="200"><img src="{{base.url}}/files/balls.png" alt="Converted PDF as Image" width="356"><br/>
The renderer features two pipelines: one based on rasterization and the other on ray tracing. It also includes optimizations such as ambient occlusion mapping and shadow mapping. Writing codes to translate elegant mathematical concepts to visually appealing images always excites me.</details>

#### Others

1. *Compile2024-Simple-sysy-Compiler*
*[<a href="https://github.com/Zysun2002/Compile2024-Simple-sysy-Compiler" target="_blank">Project Link</a>.]*

2. *Distributed-Software-Development-between-JLU-and-UTAD*
*[<a href="https://github.com/Zysun2002/Distributed-Software-Development-2024" target="_blank">Project Link</a>.]*





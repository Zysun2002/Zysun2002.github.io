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

During my undergraduate studies, I have been fortunate to collaborate with Professor **Wenbin Liu** and Professor **Rui Ma** at **Jilin University**, focusing on spatiotemporal data mining and 3D vision, respectively. I also gained valuable experience as a visiting student under the supervision of Professor **Zhaopeng Cui** at **Zhejiang University**, where I worked on 3D vision. Additionally, I completed two academic visits to the **University of Alberta**, where I focused on computer graphics, lasting one month and three months, respectively.

My current research interest involves computer graphics and 3D vision.


Publications
======

1. *GaussianPrediction: Dynamic 3D Gaussian Prediction for Motion Extrapolation and Free View Synthesis* <br/>
Boming Zhao, Yuan Li, **Ziyu Sun**, Lin Zeng, Yujun Shen, Rui Ma, Yinda Zhang, Hujun Bao, Zhaopeng Cui <br/>
*<a href="https://dl.acm.org/doi/abs/10.1145/3641519.3657417" target="_blank">Siggraph 2024</a>.*
[<a href="{{base.url}}/files/GaussianPrediction.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/GaussianPrediction.bib" target="_blank">BibTeX</a>] <details>
<img src="{{base.url}}/files/GSPrediction_pipeline.png" alt="Converted PDF as Image" width="500"><br/>
  This project marks my first exploration into 3D vision, where I gained foundational research experience by collaborating with outstanding PhD students. In this work, we propose a more compact 3D Gaussian Splatting (3DGS) representation for dynamic scenes based on key points. We achieved an exciting task, which we call future synthesis: predicting the future movements of dynamic objects and generating renderings from arbitrary perspectives. My responsibilities included constructing the framework for the extrapolation network and assisting with the training of the reconstruction networks.</details>

2. *From Incomplete Coarse-Grained to Complete Fine-Grained: A Two-Stage Framework for Spatiotemporal Data Reconstruction* <br/>
**Ziyu Sun**, Haoyang Su, En Wang, Funing Yang, Yongjian Yang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2410.05323" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/DiffRecon.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/DiffRecon.bib" target="_blank">BibTeX</a>]<details>
<img src="{{base.url}}/files/DiffRecon_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/DiffRecon_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This work focuses on enhancing spatial continuity in data mining. Our key contribution is the introduction of a novel task called "Spatiotemporal Data Reconstruction," which leverages concepts from computer vision to infer a complete, fine-grained spatiotemporal map from incomplete, coarse-grained observations. We also propose a two-stage generative model that effectively captures spatiotemporal characteristics, leading to state-of-the-art performance. It is worth noting that this work is part of a series with *Toward Time-Continuous Data Inference in Sparse Urban CrowdSensing*, as both aim to achieve more precise (finer-grained in this work) modeling of real-world spatiotemporal data, with this work emphasizing the spatial perspective.</details>

3. *Toward Time-Continuous Data Inference in Sparse Urban CrowdSensing* <br/>
**Ziyu Sun**, Haoyang Su, Hanqi Sun, En Wang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2408.16027" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/time-dmf.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/time-dmf.bib" target="_blank">BibTeX</a>] <details>
<img src="{{base.url}}/files/time-dmf_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/time-dmf_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This work focuses on enhancing temporal continuity in data mining. Our key observation is that existing approaches typically employ a "time-discrete" preprocessing step before applying their algorithms, which can introduce inaccuracies. For example, nearly all existing methods slice the timeline into discrete time units and aggregate data within each unit, disregarding the precise arrival times of the data. In our research, we first propose a fine-grained adaptation for time-discrete solutions and then optimize it into a time-continuous version. Notably, this work is part of a series with *From Incomplete Coarse-Grained to Complete Fine-Grained: A Two-Stage Framework for Spatiotemporal Data Reconstruction*, both aiming to achieve more precise modeling of real-world scenarios from a temporal perspective, with a particular emphasis on continuity in this study.</details>

Projects
======

1. *Implementing a renderer from scratch*<br/> [<a href="https://github.com/Zysun2002/Renderer-Alberta" target="_blank">link</a>]<br/></details>
<img src="{{base.url}}/files/pumpkin.gif" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/balls.png" alt="Converted PDF as Image" width="350"><br/>
The renderer features two pipelines: one based on rasterization and the other on ray tracing. It also includes optimizations such as ambient occlusion mapping and shadow mapping. Writing codes to translate elegant mathematical concepts to visually appealing images always excites me.</details>










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

Hi! :wave: I am an incoming PhD-track student in computer science at UBC, working under the supervision of **[Alla Sheffer](https://www.cs.ubc.ca/~sheffa/students.html)**. I am excited to explore research topics in **computer graphics** and **geometry**. 

I graduated from the Tang Ao-Qing Honors Program at Jilin University, where I worked closely with Professors **[Wenbin Liu](https://ccst.jlu.edu.cn/info/1209/18150.htm)** and **[Rui Ma](https://ruim-jlu.github.io/)**. I was also fortunate to intern at Zhejiang University with **[Zhaopeng Cui](https://zhpcui.github.io/)**, as well as at the University of Alberta.


Publications
======

1. *GaussianPrediction: Dynamic 3D Gaussian Prediction for Motion Extrapolation and Free View Synthesis* <br/>
Boming Zhao, Yuan Li, **Ziyu Sun**, Lin Zeng, Yujun Shen, Rui Ma, Yinda Zhang, Hujun Bao, Zhaopeng Cui <br/>
*<a href="https://dl.acm.org/doi/abs/10.1145/3641519.3657417" target="_blank">Siggraph 2024</a>.*
[<a href="{{base.url}}/files/GaussianPrediction.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/GaussianPrediction.bib" target="_blank">BibTeX</a>] <details>
<img src="{{base.url}}/files/GSPrediction_task.png" alt="Converted PDF as Image" width="350">
<img src="{{base.url}}/files/GSPrediction_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
  In this work, we propose a **more compact 3D Gaussian Splatting (3DGS) representation** for dynamic scenes based on key points. With this representation, we achieved an exciting task, which we call **future synthesis**: predicting the future movements of dynamic objects and generating renderings from arbitrary perspectives.</details>

2. *From Incomplete Coarse-Grained to Complete Fine-Grained: A Two-Stage Framework for Spatiotemporal Data Reconstruction* <br/>
**Ziyu Sun**, Haoyang Su, En Wang, Funing Yang, Yongjian Yang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2410.05323" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/DiffRecon.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/DiffRecon.bib" target="_blank">BibTeX</a>]<details>
<img src="{{base.url}}/files/DiffRecon_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/DiffRecon_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This is the second work in our **"Fine-Grained Spatiotemporal Sensing"** series, where we focus on improving the spatial granularity of city data.Our key contribution is the introduction of a novel task called "**Spatiotemporal Data Reconstruction**," which leverages concepts from computer vision to infer a complete, fine-grained spatiotemporal map from incomplete, coarse-grained observations. We also propose a **two-stage diffusion model** that effectively captures spatiotemporal characteristics, leading to state-of-the-art performance.</details>

3. *Toward Time-Continuous Data Inference in Sparse Urban CrowdSensing* <br/>
**Ziyu Sun**, Haoyang Su, Hanqi Sun, En Wang, Wenbin Liu <br/>
*<a href="https://arxiv.org/abs/2408.16027" target="_blank">Preprint</a>.*
[<a href="{{base.url}}/files/time-dmf.pdf" target="_blank">PDF</a>] 
[<a href="{{base.url}}/files/time-dmf.bib" target="_blank">BibTeX</a>]<details>
<img src="{{base.url}}/files/time-dmf_task.png" alt="Converted PDF as Image" width="350"><img src="{{base.url}}/files/time-dmf_pipeline.png" alt="Converted PDF as Image" width="350"><br/>
This is the first work in our **"Fine-Grained Spatiotemporal Sensing"** series, where we focus on enhancing the temporal granularity of perceptual data, and even directly modeling continuous-time representations. Our key observation is that existing approaches often rely on "**time-discrete**" preprocessing steps before applying their algorithms, which can lead to inaccuracies. Most existing methods divide the timeline into discrete intervals and aggregate data within each unit, assuming data remains static within these intervals. In our research, we first adapt existing time-discrete solutions to a **fine-grained approach** by slicing the timeline into the smallest possible units for alignment with prior work. We then elevate this approach into a **time-continuous** model that accurately represents data along a continuous timeline.</details>


Projects
======

#### Rendering

1. *CUDA-Accelerated Rasterization and Ray-Tracing from Scratch* <br/>
Finished during my summer visit to the University of Alberta 
*[<a href="https://github.com/Zysun2002/Renderer-Alberta" target="_blank">Project Link</a>.]*<details>
<img src="{{base.url}}/files/pumpkin.gif" alt="Converted PDF as Image" width="200"><img src="{{base.url}}/files/balls.png" alt="Converted PDF as Image" width="400"><br/>
The renderer features two pipelines: one based on **rasterization** and the other on **ray tracing**. It also includes optimizations such as **ambient occlusion mapping** and **shadow mappin**g. I also achieved over **100x rendering speedup** through parallel computation using CUDA on ray tracing pipeline. Writing codes to translate elegant mathematical concepts to visually appealing images always excites me.</details>

#### Others

1. *Compile2024-Simple-sysy-Compiler*
*[<a href="https://github.com/Zysun2002/Compile2024-Simple-sysy-Compiler" target="_blank">Project Link</a>.]*

2. *Distributed-Software-Development-between-JLU-and-UTAD*
*[<a href="https://github.com/Zysun2002/Distributed-Software-Development-2024" target="_blank">Project Link</a>.]*

CV
======
My CV is attached [<a href="{{base.url}}/files/cv.pdf" target="_blank">here</a>].

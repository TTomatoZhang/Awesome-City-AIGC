# <p align='center'>`Advances in 3D City AIGC`</p>

An expanding review of papers, codes and datasets w.r.t 3D city generation.

## Table of Contents
- [3D city Generation](#table-city-gen) [(Detail)](#city-gen)
- [3D Road Generation](#table-road) [(Detail)](#road)
- [Road with Surface](#table-road-surface) [(Detail)](#surface)
- [Other 3D Generation](#other-3d-stylization)



**3D city Generation** <div id="table-city-gen"></div>

</summary>

|  Abbr.  |  Title   | Venue  | Paper  | Project  |Layout | 3D | Mesh|
|  ----  |  ----    | ----  |----   |----  |----  |----  |----  |
|InfiniCity |InfiniCity: Infinite-Scale City Synthesis|ICCV 2023|[[Paper](https://arxiv.org/abs/2408.01291)]| [[Project]([https://rese1f.github.io/CityGen/]|InfiniGAN|Octree + Voxel + Neural Rendering|None|
|CityGen |CityGen: Infinite and Controllable 3D City Layout Generation|preprint  |[[Paper](https://arxiv.org/abs/2408.01291)]| [[Project](https://rese1f.github.io/CityGen/)]|stablediffusion + LoRA (from local block to infinity)| Heightmap| None | 
|CityDreamer |CityDreamer: Compositional Generative Model of Unbounded 3D Cities| CVPR 2024 |[[Paper]([https://arxiv.org/abs/2408.01291](https://openaccess.thecvf.com/content/CVPR2024/papers/Xie_CityDreamer_Compositional_Generative_Model_of_Unbounded_3D_Cities_CVPR_2024_paper.pdf))]| [[Project](https://haozhexie.com/project/city-dreamer)]|MaskGIT|generative neural hash grid|None|
|SemCity |SemCity: Semantic Scene Generation with Triplane Diffusion| ECCV 2024 |[[Paper](https://arxiv.org/abs/2408.01291)]| [[Project](https://dong-huo.github.io/TexGen/)]|triplane+decoder|triplane+ diffusion|None|
|CityCraft |CityCraft: A Real Crafter for 3D City Generation| preprint|[[Paper]([https://arxiv.org/abs/2408.0129](https://arxiv.org/pdf/2406.04983)1)]| [[Project](https://github.com/djFatNerd/CityCraft)]|DiT with VAE from SDXL|Blender asset|Blender|
|Aerial Lifing|Aerial Lifting: Neural Urban Semantic and Building Instance Lifting
from Aerial Imagery|CVPR 2024|[Paper](https://arxiv.org/pdf/2403.11812)|[Project](https://github.com/zyqz97/Aerial_lifting)|M2F, SAM|NeRF|None|

<details open>
<summary>


** 2D Text to Remote Sensing Images ** <div id="table-city-gen"></div>

</summary>

|  Abbr.  |  Title   | Venue  | Paper  | Project  | Condition| Backbone|
|  ----  |  ----    | ----  |----   |----  |----  |----  | 
|Label Freedom|Stable Diffusion for Remote Sensing Image Generation|BigData 2023|[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10386381)|[Project]([https://github.com/xiaoyuan1996/Stable-Diffusion-for-Remote-Sensing-Image-Generation])|text|LoRA+StableDiffusion|
|Seg2Sat| Segmentation to aerial view using pre-trained diffuser models| None| None| [Project](https://github.com/RubenGres/Seg2Sat)|semantic segmentation map|StableDiffusion+Controlnet|
|DiffusionSat| DIFFUSIONSAT: A GENERATIVE FOUNDATION MODELFOR SATELLITE IMAGERY|ICLR 2024| [Papaer](https://openreview.net/pdf?id=I5webNFDgQ)|[Project](https://github.com/samar-khanna/DiffusionSat)| text, position, etc + image|CLIP+StableDiffusion|

<details open>
<summary>

## Road
Driving in the Occupancy World: Vision-Centric 4D Occupancy Forecasting and Planning via World Models for Autonomous Driving
OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving



## Road with Surface
OmniSDF: Scene Reconstruction using Omnidirectional Signed Distance Functions and Adaptive Binoctrees
Neural Rendering based Urban Scene Reconstruction for Autonomous Driving

## Other Related 3D Generation
  </summary>

   <summary>

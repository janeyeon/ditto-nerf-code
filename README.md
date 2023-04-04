# DITTO-NeRF: Diffusion-based Iterative Text To Omni-directional 3D Model

<!-- [![arXiv](https://img.shields.io/badge/arXiv-2211.16374-red)](https://arxiv.org/abs/2211.16374) [![project_page](https://img.shields.io/badge/-project%20page-blue)](https://janeyeon.github.io/ditto-nerf/) -->
 [![project_page](https://img.shields.io/badge/-project%20page-blue)](https://janeyeon.github.io/ditto-nerf/)


[//]: # ()
[//]: # ([![arXiv]&#40;https://img.shields.io/badge/paper-cvpr2022-cyan&#41;]&#40;https://openaccess.thecvf.com/content/CVPR2022/html/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.html&#41; [![arXiv]&#40;https://img.shields.io/badge/arXiv-2110.02711-red&#41;]&#40;https://arxiv.org/abs/2110.02711&#41;)

[//]: # ([![video]&#40;https://img.shields.io/badge/video-green&#41;]&#40;https://youtu.be/fpzkL_fBfOo; [![poster]&#40;https://img.shields.io/badge/poster-orange&#41;]&#40;https://drive.google.com/file/d/1QgRFIRba492dCZ6v7BcZB9zqyp91aTjL/view?usp=sharing&#41; )

<p align="center">

  <img src="assets/ditto-nerf-result.gif" />

</p> 

[comment]: <> (![]&#40;imgs/main1.png&#41;)

[comment]: <> (![]&#40;imgs/main2.png&#41;)

> **DITTO-NeRF: Diffusion-based Iterative Text To Omni-directional 3D Model**<br>
> [Hoigi Seo*](https://github.com/seohoiki3215), [Hayeon Kim*](https://github.com/janeyeon), [Gwanghyun Kim*](https://gwang-kim.github.io/), [Se Young Chun](https://icl.snu.ac.kr/pi) <br>
> 
> 
>**Abstract**: <br>
The increasing demand for high-quality 3D content creation has motivated the development of automated methods for creating 3D object models from a single image and/or from a text prompt. However, the reconstructed 3D objects using state-of-the-art image-to-3D methods still exhibit low correspondence to the given image and low multi-view consistency. Recent state-of-the-art text-to-3D methods are also limited, yielding 3D samples with low diversity per prompt with long synthesis time. To address these challenges, **we propose DITTO-NeRF, a novel pipeline to generate a high-quality 3D NeRF model from a text prompt or a single image**. Our DITTO-NeRF consists of constructing high-quality partial 3D object for limited in-boundary (IB) angles using the given or text-generated 2D image from the frontal view and then iteratively reconstructing the remaining 3D NeRF using inpainting latent diffusion model. We propose progressive 3D object reconstruction schemes in terms of scales (low to high resolution), angles (IB angles initially to outer-boundary (OB) later), and masks (object to background boundary) in our DITTO-NeRF so that high-quality information on IB can be propagated into OB. Our DITTO-NeRF outperforms state-of-the-art methods in terms of fidelity and diversity qualitatively and quantitatively with much faster training times than prior arts on image / text-to-3D such as DreamFusion, and NeuralLift-360. <br><br>
&#42; These authors contributed equally to this work

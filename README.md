# Remote Sensing Image Super-Resolution: Papers, Datasets & Benchmarks

A curated reference for deep-learning-based **remote sensing image super-resolution (RSISR)**: papers with code, datasets, benchmarks and evaluation notes.

> **Credits and scope.** The original list in *Survey* and *Papers & Codes* (entries **[1]-[109]**, 2017-2025) was compiled by **Sen Lei** and is reproduced here as a base, unchanged, with full credit to its author (see [Credits](#credits)). This repository extends it with entries **[110]+** (2024-2026 papers), a **Datasets** section, and **Evaluation notes**, compiled by [J. Estevez](https://github.com/EstevezCodando). Additions were checked against arXiv and the dataset pages on **2026-09-30**.

**Contents:** [Survey](#survey) | [Papers & Codes](#paperscodes) | [New papers 2025-2026](#new-papers-2025-2026) | [Methods at a glance](#methods-at-a-glance) | [Recommended starting points](#recommended-starting-points) | [Tools and libraries](#tools-and-libraries) | [Datasets](#datasets) | [Evaluation notes](#evaluation-notes) | [Credits](#credits)

## Survey

- 2025, Advancing Image Super-resolution Techniques in Remote Sensing: A Comprehensive Survey, [arXiv](https://arxiv.org/abs/2505.23248) [ISPRS](https://www.sciencedirect.com/science/article/pii/S0924271625004125)

- 2023, A review of GAN-based super-resolution reconstruction for optical remote sensing images, [Remote Sensing](https://www.mdpi.com/2072-4292/15/20/5062)

- 2022, A comprehensive review on deep learning based remote sensing image super-resolution methods, [Earth-Science Reviews](https://www.sciencedirect.com/science/article/pii/S0012825222001945)

- 2022, A review of image super-resolution approaches based on deep learning and applications in remote sensing, [Remote Sensing](https://www.mdpi.com/2072-4292/14/21/5423)

- 2021, Research on super-resolution reconstruction of remote sensing images: A comprehensive review, [Optical Engineering](https://www.spiedigitallibrary.org/journalIssue/Download?urlId=10.1117%2F1.OE.60.10.100901)

## Papers&Codes

| ID | Year  | Title                  | Model                  | Published                                                    | Code                                                         |
| -- | ----- |----------------------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [1]  |2017 |Super-Resolution for Remote Sensing Images via Local–Global Combined Network | LGCNet | [IEEE GRSL](https://ieeexplore.ieee.org/document/7937881) | - |
| [2]  |2017 |Video Satellite Imagery Super Resolution via Convolutional Neural Networks | - | [IEEE GRSL](https://ieeexplore.ieee.org/document/8101498/) | - | 
| [3]  |2018 |A New Deep Generative Network for Unsupervised Remote Sensing Single-Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/8400496) | - |
| [4]  |2018 | Deep Distillation Recursive Network for Remote Sensing Imagery Super-Resolution | DDRN | [RS](https://www.mdpi.com/2072-4292/10/11/1700) | - |
| [5]  |2018 | Aerial Image Super Resolution via Wavelet Multiscale Convolutional Neural Networks | WMCNN | [IEEE GRSL](https://ieeexplore.ieee.org/document/8316893) | - |
| [6]  |2020 | Coupled Adversarial Training for Remote Sensing Image Super-Resolution | CDGAN | [IEEE TGRS](https://ieeexplore.ieee.org/document/8946581) | - |
| [7]  |2020 | A Unified Network for Arbitrary Scale Super-Resolution of Video Satellite Images | ASSR | [IEEE TGRS](https://ieeexplore.ieee.org/document/8946581) | - |
| [8]  |2021 | Hybrid-Scale Self-Similarity Exploitation for Remote Sensing Image Super-Resolution | HSENet | [IEEE TGRS](https://ieeexplore.ieee.org/document/9400474) | [code](https://github.com/Shaosifan/HSENet)![GitHub stars](http://img.shields.io/github/stars/Shaosifan/HSENet.svg?logo=github&label=Stars) |
| [9]   |2021 | Deep-Learning-Based Super-Resolution of Video Satellite Imagery by the Coupling of Multiframe and Single-Frame Models | EGVSR | [IEEE TGRS](https://ieeexplore.ieee.org/document/9579427) | - |
| [10]  |2021 | RRSGAN: Reference-Based Super-Resolution for Remote Sensing Image | RRSGAN | [IEEE TGRS](https://ieeexplore.ieee.org/document/9328132) | [code](https://github.com/dongrunmin/RRSGAN)![GitHub stars](http://img.shields.io/github/stars/dongrunmin/RRSGAN.svg?logo=github&label=Stars) |
| [11]  |2021 | Collaborative Network for Super-Resolution and Semantic Segmentation of Remote Sensing Images | ColNet | [IEEE TGRS](https://ieeexplore.ieee.org/document/9506999) | - |
| [12]  |2021 | Satellite Video Super-Resolution via Multiscale Deformable Convolution Alignment and Temporal Grouping Projection | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9530280) | - |
| [13]  |2021 | Single-Image Super-Resolution for Remote Sensing Images Using a Deep Generative Adversarial Network With Local and Global Attention Mechanisms | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9479919) | - |
| [14]  |2021 | Target-Guided Feature Super-Resolution for Vehicle Detection in Remote Sensing Images | - | [IEEE GRSL](https://ieeexplore.ieee.org/document/9548683) | - |
| [15]  |2021 | Hierarchical Feature Aggregation and Self-Learning Network for Remote Sensing Image Continuous-Scale Super-Resolution | RSI-HFAS | [IEEE GRSL](https://ieeexplore.ieee.org/document/9585484) | [code](https://github.com/chongningni/RSI-HFAS)![GitHub stars](http://img.shields.io/github/stars/chongningni/RSI-HFAS.svg?logo=github&label=Stars) |
| [16]  |2021 | Remote Sensing Image Super-Resolution via Residual Aggregation and Split Attentional Fusion Network | RASAF | [IEEE JSTAR](https://ieeexplore.ieee.org/document/9541020) | - |
| [17]  |2021 | ESPC_NASUnet: An End-to-End Super-Resolution Semantic Segmentation Network for Mapping Buildings From Remote Sensing Images | ESPC-NASUnet | [IEEE JSTAR](https://ieeexplore.ieee.org/document/9429949) | - |
| [18]  |2022 | Transformer-based Multi-Stage Enhancement for Remote Sensing Image Super-Resolution | TransENet | [IEEE TGRS](https://ieeexplore.ieee.org/document/9654169) | [code](https://github.com/Shaosifan/TransENet)![GitHub stars](http://img.shields.io/github/stars/Shaosifan/TransENet.svg?logo=github&label=Stars) |
| [19]  |2022 | Real-world remote sensing image super-resolution via a practical degradation model and a kernel-aware network  | - | [ISPRS](https://www.sciencedirect.com/science/article/abs/pii/S0924271622001824) | - |
| [20]  |2022 | Large-factor Super-resolution of Remote Sensing Images with Spectra-guided Generative Adversarial Networks | SpecGAN | [IEEE TGRS](https://ieeexplore.ieee.org/document/9950553) | [code](https://github.com/YapengMeng/SpecGAN)![GitHub stars](http://img.shields.io/github/stars/YapengMeng/SpecGAN.svg?logo=github&label=Stars) |
| [21]  |2022 | FeNet: Feature Enhancement Network for Lightweight Remote-Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9759417) | [code](https://github.com/wangzheyuan-666/FeNet)![GitHub stars](http://img.shields.io/github/stars/wangzheyuan-666/FeNet.svg?logo=github&label=Stars) |
| [22]  |2022 | Multiattention Generative Adversarial Network for Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9787539) | - |
| [23]  |2022 | A Deep Multitask Convolutional Neural Network for Remote Sensing Image Super-Resolution and Colorization | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9721252) | - |
| [24]  |2022 | Dual Learning-Based Graph Neural Network for Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9861602) | - |
| [25]  |2022 | From Artifact Removal to Super-Resolution| - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9851467) | - |
| [26]  |2022 | Multilayer Degradation Representation-Guided Blind Super-Resolution for Remote Sensing Images | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9833534) | [code](https://github.com/lijierhhh/MDRGBSR)![GitHub stars](http://img.shields.io/github/stars/lijierhhh/MDRGBSR.svg?logo=github&label=Stars) |
| [27]  |2022 | Deep Joint Estimation Network for Satellite Video Super-Resolution With Multiple Degradations | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9745539) | - |
| [28]  |2022 | Contextual Transformation Network for Lightweight Remote-Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9632567) | [code](https://github.com/BITszwang/CTNet)![GitHub stars](http://img.shields.io/github/stars/BITszwang/CTNet.svg?logo=github&label=Stars) | 
| [29]  |2022 | Remote Sensing Image Super-Resolution via Dual-Resolution Network Based on Connected Attention Mechanism | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9530281) | - |
| [30]  |2022 | Multiframe Video Satellite Image Super-Resolution via Attention-Based Residual Learning | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/9442915) | - |
| [31]  |2022 | SWCGAN: Generative Adversarial Network Combining Swin Transformer and CNN for Remote Sensing Image Super-Resolution | SWCGAN | [IEEE JSTAR](https://ieeexplore.ieee.org/document/9829280) |
| [32]  |2023 | Lightweight Stepless Super-Resolution of Remote Sensing Images via Saliency-Aware Dynamic Routing Strategy | SalDRN | [IEEE TGRS](https://ieeexplore.ieee.org/document/10016645) | [code](https://github.com/hanlinwu/SalDRN)![GitHub stars](http://img.shields.io/github/stars/hanlinwu/SalDRN.svg?logo=github&label=Stars) |
| [33]  |2023 | A CNN-Based Sentinel-2 Image Super-Resolution Method Using Multiobjective Training | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/10026840) | - | 
| [34]  |2023 | Learning Dynamic Scale Awareness and Global Implicit Functions for Continuous-Scale Super-Resolution of Remote Sensing Images | SADN | [IEEE TGRS](https://ieeexplore.ieee.org/document/10026827) | [code](https://github.com/hanlinwu/SADN)![GitHub stars](http://img.shields.io/github/stars/hanlinwu/SADN.svg?logo=github&label=Stars) | 
| [35]  |2023 | Continuous Remote Sensing Image Super-Resolution Based on Context Interaction in Implicit Function Space | FunSR | [IEEE TGRS](https://ieeexplore.ieee.org/document/10114420) | [code](https://github.com/KyanChen/FunSR)![GitHub stars](http://img.shields.io/github/stars/KyanChen/FunSR.svg?logo=github&label=Stars) |
| [36]  |2023 | Hybrid Attention-Based U-Shaped Network for Remote Sensing Image Super-Resolution | HAUNet | [IEEE TGRS](https://github.com/likakakaka/HAUNet_RSISR) | [code](https://github.com/likakakaka/HAUNet_RSISR)![GitHub stars](http://img.shields.io/github/stars/likakakaka/HAUNet_RSISR.svg?logo=github&label=Stars) | 
| [37]  |2023 | Deep Blind Super-Resolution for Satellite Video | - | [IEEE TGRS](https://ieeexplore.ieee.org/document/10172076) | [code](https://github.com/XY-boy/Blind-Satellite-VSR)![GitHub stars](http://img.shields.io/github/stars/XY-boy/Blind-Satellite-VSR.svg?logo=github&label=Stars) | 
| [38]  |2023 | A Progressive Feature Enhancement Deep Network for Large-Scale Remote Sensing Image Superresolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10236467) | - |
| [39]  |2023 | Enhancing Remote Sensing Image Super-Resolution with Efficient Hybrid Conditional Diffusion Model | - | [RS](https://www.mdpi.com/2072-4292/15/13/3452) | - |
| [40]  |2023 | Hybrid-Scale Hierarchical Transformer for Remote Sensing Image Super-Resolution | - | [RS](https://www.mdpi.com/2072-4292/15/13/3442) | - |
| [41]  |2023 | Remote Sensing Image Super-Resolution With Residual Split Attention Mechanism | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/10158796) | - |
| [42]  |2023 | AEFormer: Zoom Camera Enables Remote Sensing Super-Resolution via Aligned and Enhanced Attention | AEFormer | [RS](https://www.mdpi.com/2072-4292/15/22/5409) | - |
| [43]  |2023 | From Degrade to Upgrade Learning a Self-Supervised Degradation-Guided Adaptive Network for Blind Remote Sensing Image Super-Resolution | DRSR | [Information Fusion](https://www.sciencedirect.com/science/article/pii/S1566253523001100) | [code](https://github.com/XY-boy/DRSR)![GitHub stars](http://img.shields.io/github/stars/XY-boy/DRSR.svg?logo=github&label=Stars) |
| [44]  |2023 | Zooming Out on Zooming In: Advancing Super-Resolution for Remote Sensing | - | [arXiv](https://arxiv.org/pdf/2311.18082) | [code](https://github.com/allenai/satlas-super-resolution)![GitHub stars](http://img.shields.io/github/stars/allenai/satlas-super-resolution.svg?logo=github&label=Stars) |
| [45]  |2023 | Multi-frame super-resolution of remote sensing images using attention-based GAN models | - | [Knowledge-Based Systems](https://www.sciencedirect.com/science/article/pii/S0950705123001375) | - |
| [46]  |2023 | Cross-sensor remote sensing imagery super-resolution via an edge-guided attention-based network | EGASR | [ISPRS](https://www.sciencedirect.com/science/article/pii/S0924271623001053) | [code](https://github.com/zhonghangqiu/EGASR)![GitHub stars](http://img.shields.io/github/stars/zhonghangqiu/EGASR.svg?logo=github&label=Stars) |
| [47]  |2023 | CLSR: Contrastive Learning for Semi-Supervised Remote Sensing Image Super-Resolution | CLSR | [IEEE GRSL](https://ieeexplore.ieee.org/document/10180093) | - |
| [48]  |2024 | Two-Stage Spatial-Frequency Joint Learning for Large-Factor Remote Sensing Image Super-Resolution | TSFNet | [IEEE TGRS](https://ieeexplore.ieee.org/document/10411925) | [code](https://github.com/likakakaka/TSFNet_RSISR)![GitHub stars](http://img.shields.io/github/stars/likakakaka/TSFNet_RSISR.svg?logo=github&label=Stars) |
| [49]  |2024 | TTST: A Top-k Token Selective Transformer for Remote Sensing Image Super-Resolution | TTST | [IEEE TIP](https://ieeexplore.ieee.org/document/10387229) | [code](https://github.com/XY-boy/TTST)![GitHub stars](http://img.shields.io/github/stars/XY-boy/TTST.svg?logo=github&label=Stars) |
| [50]  |2024 | Local-Global Context-Aware Generative Dual-Region Adversarial Networks for Remote Sensing Scene Image Super-Resolution | LGCGDAN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10403859) | - |
| [51]  |2024 | MSWAGAN: Multispectral Remote Sensing Image Super-Resolution Based on Multiscale Window Attention Transformer | MSWAGAN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10494508) | - |
| [52]  |2024 | CSwT-SR: Conv-Swin Transformer for Blind Remote Sensing Image Super-Resolution With Amplitude-Phase Learning and Structural Detail Alternating Learning | CSwT-SR | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10562345) | - | 
| [53]  |2024 | GCRDN: Global Context-Driven Residual Dense Network for Remote Sensing Image Superresolution | GCRDN | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/101154405) | [code](https://github.com/littlebeen/Remote-Sensing-Super-resolution-Model-Collection)![GitHub stars](http://img.shields.io/github/stars/littlebeen/Remote-Sensing-Super-resolution-Model-Collection.svg?logo=github&label=Stars) |
| [54]  |2024 | Multiscale Residual Dense Network for the Super-Resolution of Remote Sensing Images | MRDN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10453218) | - |
| [55]  |2024 | EDiffSR: An Efficient Diffusion Probabilistic Model for Remote Sensing Image Super-Resolution | EDiffSR | [IEEE TGRS](https://ieeexplore.ieee.org/document/10353979) | [code](https://github.com/XY-boy/EDiffSR)![GitHub stars](http://img.shields.io/github/stars/XY-boy/EDiffSR.svg?logo=github&label=Stars) |
| [56]  |2024 | Building Bridges across Spatial and Temporal Resolutions Reference-Based Super-Resolution via Change Priors and Conditional Diffusion Model | RefDiff |[CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_Building_Bridges_across_Spatial_and_Temporal_Resolutions_Reference-Based_Super-Resolution_via_CVPR_2024_paper.pdf) | [code](https://github.com/dongrunmin/RefDiff)![GitHub stars](http://img.shields.io/github/stars/dongrunmin/RefDiff.svg?logo=github&label=Stars) |
| [57]  |2024 | Non-Local Similarity-Based Attentive Graph Convolution Network for Remote Sensing Image Super-Resolution | NSGCN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10680068) | [code](https://github.com/WenjuanZhang-aircas/NSGCN)![GitHub stars](http://img.shields.io/github/stars/WenjuanZhang-aircas/NSGCN.svg?logo=github&label=Stars) |
| [58]  |2024 | Semantic Guided Large Scale Factor Remote Sensing Image Super-resolution with Generative Diffusion Prior | SGDM | [ISPRS](https://arxiv.org/abs/2405.07044) | [code](https://github.com/wwangcece/SGDM)![GitHub stars](http://img.shields.io/github/stars/wwangcece/SGDM.svg?logo=github&label=Stars) |
| [59]  |2024 | Scale-Aware Backprojection Transformer for Single Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10753509) | - |
| [60]  |2024 | Hyper-Laplacian Prior for Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10613839) | - |
| [61]  |2024 | Efficient Swin Transformer for Remote Sensing Image Super-Resolution | ESTNet | [IEEE TIP](https://ieeexplore.ieee.org/abstract/document/10746331) | [code](https://github.com/PuhongDuan/ESTNet)![GitHub stars](http://img.shields.io/github/stars/PuhongDuan/ESTNet.svg?logo=github&label=Stars) |
| [62]  |2024 | ACT-SR: Aggregation Connection Transformer for Remote Sensing Image Super-Resolution | ACT-SR | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/10767430) | [code](https://github.com/YingdongKang/ACT_SR)![GitHub stars](http://img.shields.io/github/stars/YingdongKang/ACT_SR.svg?logo=github&label=Stars) |
| [63]  |2024 | DRGAN: A Detail Recovery-Based Model for Optical Remote Sensing Images Super-Resolution | DRGAN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10781453) | - |
| [64]  |2024 | DTESR: Remote Sensing Imagery Super-Resolution With Dynamic Reference Textures Exploitation | DTESR | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/10793428) | - |
| [65]  |2024 | Toward Real-World Remote Sensing Image Super-Resolution: A New Benchmark and an Efficient Model | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10798467) | - |
| [66]  |2024 | Frequency-Assisted Mamba for Remote Sensing Image Super-Resolution | FMSR | [IEEE TMM](https://ieeexplore.ieee.org/abstract/document/10817590) | [code](https://github.com/XY-boy/FreMamba)![GitHub stars](http://img.shields.io/github/stars/XY-boy/FreMamba.svg?logo=github&label=Stars) |
| [67]  |2025 | Binary Lightweight Neural Networks for Arbitrary Scale Super-Resolution of Remote Sensing Images | BLiSR | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10841462) | - |
| [68]  |2025 | NeurOp-Diff:Continuous Remote Sensing Image Super-Resolution via Neural Operator Diffusion | NeurOp-Diff | [arXiv](https://arxiv.org/abs/2501.09054) | - |
| [69]  |2025 | Unsupervised Image Super-Resolution for High-Resolution Satellite Imagery via Omnidirectional Real-to-Synthetic Domain Translation | | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/10844307) | - |
| [70]  |2025 | Super-Resolution for Remote Sensing Imagery via the Coupling of a Variational Model and Deep Learning | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10879024) | - |
| [71]  |2025 | Semantic-aware Guidance for Blind Super-resolution of Remote Sensing Images | - | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/10855678) | - |
| [72]  |2025 | CSCT: Channel-Spatial Coherent Transformer for Remote Sensing Image Super-Resolution | CSCT | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10879083) | - |
| [73]  |2025 | Dual-Domain Optimization Model Based on Discrete Fourier Transform and Frequency-Domain Fusion for Remote Sensing Single-Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10879393) | [code](https://github.com/YB-Cheng/DDOM)![GitHub stars](http://img.shields.io/github/stars/YB-Cheng/DDOM.svg?logo=github&label=Stars) |
| [74]  |2025 | Heterogeneous Mixture of Experts for Remote Sensing Image Super-Resolution | - | [IEEE GRSL](https://arxiv.org/abs/2502.09654) | [code](https://github.com/Mr-Bamboo/MFG-HMoE)![GitHub stars](http://img.shields.io/github/stars/Mr-Bamboo/MFG-HMoE.svg?logo=github&label=Stars) |
| [75]  |2025 | SCAT: Shift Channel Attention Transformer for Remote Sensing Image Super-Resolution | SCAT | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/10886926) | - |
| [76]  |2025 | HyDA-Net: A Hybrid Dense Attention Network for Remote Sensing Multi-Image Super-Resolution | HyDA-Net | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/10909490) | - |
| [77]  |2025 | Rethinking Dual-Stream Super-Resolution for Enhancing Remote Sensing Object Detection | - | [ICASSP](https://ieeexplore.ieee.org/abstract/document/10888385) | - |
| [78]  |2025 | Single-Step Latent Consistency Model for Remote Sensing Image Super-Resolution | LCMSR | [arXiv](https://arxiv.org/abs/2503.19505) | - |
| [79]  |2025 | Frequency-Domain Super-Resolution With Reconstruction Using Compressed Representation (FDSR-RCR) Algorithm for Remote Sensing Satellite Images | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/10947128) | - |
| [80]  |2025 | Taming a diffusion model to revitalize remote sensing image super-resolution | - | [RS](https://www.mdpi.com/2072-4292/17/8/1348) | - |
| [81]  |2025 | Efficient High-Frequency Texture Recovery Diffusion Model for Remote Sensing Image Super-Resolution | IRR-DiffSR | [IEEE TIM](https://ieeexplore.ieee.org/abstract/document/10947187/) | [code](https://github.com/55Dupup/IRR-DiffSR)![GitHub stars](http://img.shields.io/github/stars/55Dupup/IRR-DiffSR.svg?logo=github&label=Stars) |
| [82]  |2025 | TTRD3: Texture Transfer Residual Denoising Dual Diffusion Model for Remote Sensing Image Super-Resolution | TTRD3 | [arXiv](https://arxiv.org/abs/2504.13026) | [code](https://github.com/LED-666/TTRD3)![GitHub stars](http://img.shields.io/github/stars/LED-666/TTRD3.svg?logo=github&label=Stars) |
| [83]  |2025 | Lightweight Edge-Guided Super-Resolution Network for Remote Sensing Images | EGSRN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11006733) | - |
| [84]  |2025 | SeG-SR: Integrating Semantic Knowledge into Remote Sensing Image Super-Resolution via Vision-Language Model | SeG-SR | [IEEE TGRS](https://ieeexplore.ieee.org/document/11175207) | [code](https://github.com/Mr-Bamboo/SeG-SR)![GitHub stars](http://img.shields.io/github/stars/Mr-Bamboo/SeG-SR.svg?logo=github&label=Stars) |
| [85]  |2025 | Dynamic State-Control Modeling for Generalized Remote Sensing Image Super-Resolution | - | [CVPRW](https://openaccess.thecvf.com/content/CVPR2025W/MORSE/html/Li_Dynamic_State-Control_Modeling_for_Generalized_Remote_Sensing_Image_Super-Resolution_CVPRW_2025_paper.html) | - |
| [86]  |2025 | A lightweight hybrid neural network for remote sensing image super-resolution reconstruction | - | [EAAI](https://www.sciencedirect.com/science/article/pii/S095219762501440X) | - |
| [87]  |2025 | Efficient Mamba-Attention Network for Remote Sensing Image Super-Resolution | EMAN | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11030723) | - |
| [88]  |2025 | Lightweight remote sensing super-resolution with multi-scale graph attention network | - | [PR](https://www.sciencedirect.com/science/article/pii/S0031320324009294) | [code](https://github.com/Yu-Wang-0801/MSGAN)![GitHub stars](http://img.shields.io/github/stars/Yu-Wang-0801/MSGAN.svg?logo=github&label=Stars) |
| [89]  |2025 | MFEM: Multiscale Frequency-Enhanced Mamba for Lightweight Remote Sensing Image Super-Resolution | MFEM | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/11075853) | - |
| [90]  |2025 | Rep-Mamba: Re-Parameterization in Vision Mamba for Lightweight Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11122524) | [code](https://github.com/meigeni0929/Rep-Mamba)![GitHub stars](http://img.shields.io/github/stars/meigeni0929/Rep-Mamba.svg?logo=github&label=Stars) |
| [91]  |2025 | Multi-level Priors-Guided Diffusion-based Remote Sensing Image Super-Resolution | - | [ISPRS](https://www.sciencedirect.com/science/article/pii/S0924271625002825) | [code](https://github.com/lijing28/DLMSR)![GitHub stars](http://img.shields.io/github/stars/lijing28/DLMSR.svg?logo=github&label=Stars) |
| [92]  |2025 | Progressive Structure Preservation and Detail Refinement for Remote Sensing Single-Image Super-Resolution | - | [IEEE TNNLS](https://ieeexplore.ieee.org/abstract/document/11127215 ) | - |
| [93]  |2025 | HAMD-RSISR: Hybrid Attention and Multidictionary for Remote Sensing Super-Resolution | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11130383) | - |
| [94]  |2025 | NSBRNet: Non-Local Spatio-Temporal Bidirectional Recurrent Network for Satellite Video Super-Resolution | - | [IEEE TCSVT](https://ieeexplore.ieee.org/abstract/document/11131285) | - |
| [95]  |2025 | DBTSR: A U-shaped adaptive sparse transformer for single remote sensing image super-resolution | - | [ESWA](https://www.sciencedirect.com/science/article/pii/S0957417425030404) | [code](https://github.com/TeresaTing/DBTSR)![GitHub stars](http://img.shields.io/github/stars/TeresaTing/DBTSR.svg?logo=github&label=Stars) |
| [96]  |2025 | Partial Attention Feature Aggregation Network for Lightweight Remote Sensing Image Super-Resolution | - | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/11134442) | - |
| [97]  |2025 | CCST: Lightweight Criss-Cross Swin Transformer for Remote Sensing Image Super-Resolution Under Multi-Degradation Scenarios | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11145917) | - |
| [98]  |2025 | MBF-SR: A Single-Image Super-Resolution Method for Remote Sensing Images in Dynamic Imaging Scenarios | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11146727) | [code](https://github.com/LR-ddd/MBF-SR)![GitHub stars](http://img.shields.io/github/stars/LR-ddd/MBF-SR.svg?logo=github&label=Stars) |
| [99]  |2025 | HAM: Hierarchical Attention Mamba With Spatial–Frequency Fusion for Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11151607) | - |
| [100]  |2025 | RADiffSR: A Diffusion Model for Remote Sensing Image Super-Resolution Fusing Residual Attention and Cross-Scale Dynamic Gating | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11151607) | - |
| [101]  |2025 | LTMHN: Learnable TransMamba Hybrid Network for Remote Sensing Image Superresolution | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11153044) | - |
| [102]  |2025 | A Novel VLM-Guided Diffusion Model for Remote Sensing Image Super-Resolution | - | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/11155158) | [code](https://github.com/Bluear7878/Remote-Sensing-Vision-Language-Diffusion-Model)![GitHub stars](http://img.shields.io/github/stars/Bluear7878/Remote-Sensing-Vision-Language-Diffusion-Model.svg?logo=github&label=Stars) |
| [103]  |2025 | Semantic-Guided Flow Matching for Fast and Accurate Remote Sensing Image Super-Resolution | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11155886) | - |
| [104]  |2025 | A Large-Scale Aerial and Satellite Image Dataset for Deep Learning-Based Image Super-Resolution of Very High-Resolution Remote Sensing Imagery | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11165097) | - |
| [105]  |2025 | EESAGAN: Edge-Enhanced and Structure-Aware GAN for Remote Sensing Image Super-Resolution | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11165376) | - |
| [106]  |2025 | Land-cover prior diffusion probabilistic model for remote sensing image super resolution | - | [PR](https://www.sciencedirect.com/science/article/pii/S0031320325012403) | [code](https://github.com/whuzzzz/LPDiffSR)![GitHub stars](http://img.shields.io/github/stars/whuzzzz/LPDiffSR.svg?logo=github&label=Stars) |
| [107]  |2025 | Multiscale Window Attention Channel-enhanced for Remote Sensing Image Super-Resolution | - | [IEEE GRSL](https://ieeexplore.ieee.org/abstract/document/11202533) | - |
| [108]  |2025 | Wiener Filter-Based Mamba for Remote Sensing Image Super-Resolution with Novel Degradation | - | [IEEE JSTARS](https://ieeexplore.ieee.org/abstract/document/11202325) | - |
| [109]  |2025 | DISR: A New Dual-Domain Implicit Super-Resolution Method for Remotely Sensed Imagery | - | [IEEE TGRS](https://ieeexplore.ieee.org/abstract/document/11215804) | [code](https://github.com/Liuyx-max/DISR)![GitHub stars](http://img.shields.io/github/stars/Liuyx-max/DISR.svg?logo=github&label=Stars) |

## New papers 2025-2026

Continuation of the table above (same columns). Entries [110]-[131] were collected from arXiv on 2026-09-30, prioritising optical and multispectral RSISR, Sentinel-2 and cross-sensor work, diffusion and flow-matching models, and efficiency. Hyperspectral/spectral and infrared work appears under Datasets when a benchmark is involved.

| ID | Year  | Title                  | Model                  | Published | Code |
| -- | ----- |----------------------- | ---------------------- | --------- | ---- |
| [110]  | 2024 | Enhancing Sentinel-2 Image Resolution: Evaluating Advanced Techniques based on Convolutional and Generative Neural Networks | - | [arXiv](https://arxiv.org/abs/2410.00516) | - |
| [111]  | 2025 | Beyond Pretty Pictures: Combined Single- and Multi-image Super-resolution for Sentinel-2 Images | - | [arXiv](https://arxiv.org/abs/2505.24799) | - |
| [112]  | 2025 | DiffFuSR: Super-Resolution of all Sentinel-2 Multispectral Bands using Diffusion Models | DiffFuSR | [arXiv](https://arxiv.org/abs/2506.11764) | - |
| [113]  | 2025 | Semantic-Guided Cross-Sensor Super Resolution of Remote Sensing Images: A Gated Dual Conditioning Flow Matching Model | RareFlow | [arXiv](https://arxiv.org/abs/2510.23816) | - |
| [114]  | 2025 | Trustworthy Super-Resolution of Multispectral Sentinel-2 Imagery with Latent Diffusion | LDSR-S2 | [IEEE JSTARS](https://www.semanticscholar.org/paper/Trustworthy-Super-Resolution-of-Multispectral-With-Donike-Aybar/27fa48af71d55c671c498649b5a65d57fbed13f4) | [code](https://github.com/ESAOpenSR/opensr-model) |
| [115]  | 2025 | OpenSR-SRGAN: A Flexible Super-Resolution Framework for Multispectral Earth Observation Data | OpenSR-SRGAN | [arXiv](https://arxiv.org/abs/2511.10461) | - |
| [116]  | 2025 | Segmentation-Aware Latent Diffusion for Satellite Image Super-Resolution | - | [arXiv](https://arxiv.org/abs/2511.14481) | - |
| [117]  | 2025 | History-Augmented Contrastive Learning With Soft Mixture of Experts for Blind Super-Resolution of Planetary Remote Sensing Images | - | [arXiv](https://arxiv.org/abs/2511.20045) | - |
| [118]  | 2025 | HIMOSA: Efficient Remote Sensing Image Super-Resolution with Hierarchical Mixture of Sparse Attention | HIMOSA | [arXiv](https://arxiv.org/abs/2512.00275) | - |
| [119]  | 2025 | SuperF: Neural Implicit Fields for Multi-Image Super-Resolution | SuperF | [arXiv](https://arxiv.org/abs/2512.09115) | - |
| [120]  | 2025 | SERA-H: Super-Resolution of Sentinel Time Series for Fine-Scale Canopy Height Mapping | SERA-H | [arXiv](https://arxiv.org/abs/2512.18128) | - |
| [121]  | 2026 | VibrantSR: Sub-Meter Canopy Height Models from Sentinel-2 Using Generative Flow Matching | VibrantSR | [arXiv](https://arxiv.org/abs/2601.09866) | - |
| [122]  | 2026 | InfScene-SR: Seamless Super-Resolution of Arbitrarily Large Remote-Sensing Scenes via Variance-Preserving Joint Denoising | InfScene-SR | [arXiv](https://arxiv.org/abs/2602.19736) | [code](https://github.com/TitorX/infscene-sr) |
| [123]  | 2026 | Self-Supervised Uncertainty Estimation For Super-Resolution of Satellite Images | - | [arXiv](https://arxiv.org/abs/2603.14074) | - |
| [124]  | 2026 | Remote Sensing Image Super-Resolution for Imbalanced Textures: A Texture-Aware Diffusion Framework | TexAdiff | [arXiv](https://arxiv.org/abs/2604.13994) | [code](https://github.com/ZezFuture/TexAdiff) |
| [125]  | 2026 | Flow matching for Sentinel-2 super-resolution: implementation, application, and implications | - | [arXiv](https://arxiv.org/abs/2605.00367) | - |
| [126]  | 2026 | SlimDiffSR: Toward Lightweight and Efficient Remote Sensing Image Super-Resolution via Diffusion Model Distillation | SlimDiffSR | [arXiv](https://arxiv.org/abs/2605.02198) | [code](https://github.com/wwangcece/SlimDiffSR) |
| [127]  | 2026 | Spatial-Frequency Gated Swin Transformer for Cross-Sensor Remote Sensing Super-Resolution | SFG-SwinSR | [arXiv](https://arxiv.org/abs/2605.09687) | [code](https://github.com/aminurhossain/SFG-SwinSR) |
| [128]  | 2026 | Learning to Balance: Decoupled Siamese Diffusion Transformer for Reference-Based Remote Sensing Image Super-Resolution | - | [arXiv](https://arxiv.org/abs/2605.17980) | - |
| [129]  | 2026 | Flow-based Gaussian Splatting for Continuous-Scale Remote Sensing Image Super-Resolution | - | [arXiv](https://arxiv.org/abs/2605.22147) | - |
| [130]  | 2026 | NGram-MoSE: Efficient Remote Sensing Super-Resolution via N-Gram Context and Mixture-of-Experts | NGram-MoSE | [arXiv](https://arxiv.org/abs/2606.08535) | - |
| [131]  | 2026 | Mind the Gap: Quantifying the Domain Gap in Cross-Sensor Diffusion Super-Resolution | - | [arXiv](https://arxiv.org/abs/2606.28039) | - |

## Methods at a glance

Families of methods that appear in the tables above, with representative entries by ID. A paper can belong to several families.

| Family | Main idea | Representative entries |
| ------ | --------- | ---------------------- |
| CNN baselines | Residual / recursive / multi-scale convolutional networks | [1] LGCNet, [4] DDRN, [8] HSENet |
| GAN-based | Adversarial training for sharper texture; attention, spectral or Swin variants | [10] RRSGAN, [20] SpecGAN, [31] SWCGAN, [115] OpenSR-SRGAN |
| Transformer-based | Window / token-selective attention for long-range context | [18] TransENet, [49] TTST, [61] ESTNet |
| Implicit / continuous-scale | Arbitrary scale factors through implicit functions or other continuous representations | [15] RSI-HFAS, [34] SADN, [35] FunSR, [129] Gaussian-splatting SR |
| Diffusion | Iterative denoising; latent-space variants to cut cost | [55] EDiffSR, [58] SGDM, [114] LDSR-S2, [112] DiffFuSR |
| Flow matching | Faster generative sampling than classic diffusion | [103] semantic-guided flow matching, [113] RareFlow, [125] Sentinel-2 flow matching |
| State-space (Mamba) | Linear-complexity sequence modelling for large images | [66] FMSR, [87] EMAN, [90] Rep-Mamba |
| Reference-based | Uses an extra high-resolution reference image | [10] RRSGAN, [56] RefDiff, [128] decoupled Siamese diffusion transformer |
| Blind / real-world | Unknown or complex degradation instead of bicubic downsampling | [19] kernel-aware network, [26] MDRGBSR, [43] DRSR |
| Multi-image / multi-frame | Fuses several acquisitions of the same scene | [76] HyDA-Net, [119] SuperF, plus WorldStrat, MuS2 and PROBA-V datasets |
| Semantic / vision-language guidance | Land-cover or language priors steer reconstruction | [84] SeG-SR, [102] VLM-guided diffusion, [106] land-cover prior diffusion, [116] segmentation-aware latent diffusion |
| Lightweight and distillation | Smaller models, binary networks, diffusion distillation | [21] FeNet, [32] SalDRN, [67] BLiSR, [126] SlimDiffSR |
| Mixture of experts | Routes regions or patches to specialised sub-networks | [74] heterogeneous MoE, [118] HIMOSA, [130] NGram-MoSE |
| Uncertainty and trust | Reports where the output is unreliable | [114] LDSR-S2 (pixel-wise uncertainty), [123] self-supervised uncertainty estimation |

**Common pattern in 2025-2026 work:** latent diffusion or flow matching conditioned on the low-res input (and often on semantics), trained on real cross-sensor pairs (SEN2NAIP, WorldStrat, SEN2VENµS), evaluated with downstream-aware metrics, with attention to speed (few-step sampling, distillation) and to hallucination (uncertainty maps).

## Recommended starting points

Editorial picks by J. Estevez, chosen for code availability, evaluation on real sensors, recency and how well they represent a family. They are not a ranking of accuracy: results across papers are not directly comparable because datasets, scale factors and degradation models differ.

| If you want to... | Start with |
| ----------------- | ---------- |
| Get the landscape | Surveys 2025 (ISPRS) and 2022 (Earth-Science Reviews), listed under *Survey* |
| Reproduce a solid CNN / Transformer baseline with code | [8] HSENet, [18] TransENet, [21] FeNet |
| Try continuous-scale SR | [35] FunSR, [34] SADN |
| Use diffusion with public code | [55] EDiffSR, [58] SGDM, [114] LDSR-S2 (`pip install opensr-model`) |
| Super-resolve Sentinel-2 in practice | [114] LDSR-S2 (with uncertainty map), [112] DiffFuSR (all 12 bands to 2.5 m), Satlas S2-NAIP models |
| Compare fairly on real data | opensr-test and GeoSR-Bench (see *Datasets* and *Tools and libraries*) |
| Keep cost low | [126] SlimDiffSR, [122] InfScene-SR (large scenes), [21] FeNet |

## Tools and libraries

All entries were checked on their official repositories on 2026-09-30. "Not declared" means the repository has no license stated in its README; check before reuse.

### Remote-sensing specific

| Tool | What it does | License | Link |
| ---- | ------------ | ------- | ---- |
| **opensr-model** (LDSR-S2) | Latent diffusion SR for Sentinel-2 RGB-NIR, 128x128 to 512x512, returns an uncertainty map; `pip install opensr-model` | see repo | [GitHub](https://github.com/ESAOpenSR/opensr-model) |
| **opensr-test** | Benchmark for real Sentinel-2 SR; measures consistency, spectral signature, spatial alignment, synthesis, hallucination and omission; `pip install opensr-test` | MIT | [GitHub](https://github.com/ESAOpenSR/opensr-test) |
| **OpenSR-SRGAN** | Configurable GAN framework (SRResNet, RCAB, RRDB, LKA, ESRGAN, stochastic generators), YAML-driven, PyTorch Lightning; `pip install opensr-srgan` | Apache-2.0 | [GitHub](https://github.com/ESAOpenSR/SRGAN) |
| **Satlas super-resolution** | S2-NAIP training sets (about 1.1M urban pairs and about 44M full pairs) and ESRGAN / SRCNN / HighResNet weights; 4x on Sentinel-2 time series | Apache-2.0 | [GitHub](https://github.com/allenai/satlas-super-resolution) |
| **SR4RS** | Open-source SR tool for remote sensing with pretrained models | MIT | [GitHub](https://github.com/remicres/sr4rs) |
| **TorchGeo** | PyTorch library with geospatial datasets, samplers, transforms and pretrained multispectral weights | MIT | [GitHub](https://github.com/microsoft/torchgeo) |
| **EDiffSR** | Code for the TGRS 2024 diffusion model; trained on AID, tested on DOTA, DIOR and NWPU-RESISC45 | not declared | [GitHub](https://github.com/XY-boy/EDiffSR) |
| **SGDM** | Code for semantic-guided large-factor SR with a generative diffusion prior | not declared | [GitHub](https://github.com/wwangcece/SGDM) |

### General-purpose SR toolboxes (commonly adapted to remote sensing)

| Tool | What it does | License | Link |
| ---- | ------------ | ------- | ---- |
| **BasicSR** | PyTorch restoration toolbox: EDSR, RCAN, SRGAN, ESRGAN, SwinIR, EDVR, BasicVSR and others | Apache-2.0 | [GitHub](https://github.com/XPixelGroup/BasicSR) |
| **Real-ESRGAN** | Practical blind restoration trained on purely synthetic degradations | BSD-3-Clause | [GitHub](https://github.com/xinntao/Real-ESRGAN) |
| **SwinIR** | Swin-Transformer restoration: classic, lightweight and real-world SR at 2x/3x/4x/8x | Apache-2.0 | [GitHub](https://github.com/JingyunLiang/SwinIR) |
| **MMagic** | OpenMMLab toolkit with SRCNN, SRGAN, EDSR, ESRGAN, RDN, GLEAN, LIIF, Real-ESRGAN and video SR models (last release v1.2.0, Dec 2023) | Apache-2.0 | [GitHub](https://github.com/open-mmlab/mmagic) |

## Datasets

Paired or multi-image data for training and evaluating RSISR. Real pairs come from two sensors (cross-sensor); synthetic pairs are degraded from a high-resolution image, which can hide the domain gap between training and real-world inputs.

### Sentinel-2 and cross-sensor

| Dataset | Pairs / content | Link |
| ------- | --------------- | ---- |
| **SEN2VENµS** | Sentinel-2 10/20 m patches with same-day VENµS references at 5 m; 29 locations, 132,955 patches of 256x256 px | [Zenodo](https://zenodo.org/records/6514159) / [Hugging Face](https://huggingface.co/datasets/tacofoundation/sen2venus) |
| **WorldStrat** | SPOT 6/7 imagery (1.5 m) paired with Sentinel-2 time series, about 10,000 km2, for multi-frame SR | [arXiv](https://arxiv.org/abs/2207.06418) / [Zenodo](https://zenodo.org/record/6810791) |
| **SEN2NAIP** | 2,851 cross-sensor pairs (Sentinel-2 L2A and NAIP, 0.6 m) plus 17,657 synthetic NAIP/S2-like pairs | [Hugging Face](https://huggingface.co/datasets/isp-uv-es/SEN2NAIP) |
| **OpenSR / opensr-test** | Test benchmark with three datasets built to minimise spatial and spectral misalignment; metrics for consistency, synthesis and correctness | [Hugging Face](https://huggingface.co/datasets/isp-uv-es/opensr-test) / [ESA OpenSR](https://isp.uv.es/pages/opensr/data.html) |
| **MuS2** | Real Sentinel-2 multi-image sets paired with WorldView-2 | [arXiv](https://arxiv.org/abs/2210.02745) |
| **Sentinel-2 / Sentinel-3 paired** | Time series at 10 m and 300 m over 40 regions of interest | [Zenodo](https://zenodo.org/records/19049675) |
| **Sentinel-2 + NAIP (CONUS)** | 120,851 pairs, Sentinel-2 10 m and NAIP 2.5 m (introduced with the flow-matching paper) | [arXiv](https://arxiv.org/abs/2605.00367) |
| **PROBA-V SR challenge** | 1,450 scenes (1,160 train / 290 test), 300 m low-res series and 100 m targets, at least 9 frames per scene | [ESA Kelvins](https://kelvins.esa.int/proba-v-super-resolution/) |

### Benchmarks and other modalities

| Dataset | Content | Link |
| ------- | ------- | ---- |
| **GeoSR-Bench** | About 36,000 locations, resolutions from 500 m to 0.6 m, evaluating SR through downstream tasks | [arXiv](https://arxiv.org/abs/2605.00310) |
| **RSSOD** | Super-resolution combined with small-object detection in high-resolution imagery | [arXiv](https://arxiv.org/abs/2111.03260) |
| **SyMTRS** | Synthetic aerial RGB 2048x2048 with depth maps and 2x/4x/8x variants; multi-task (depth, domain adaptation, SR) | [arXiv](https://arxiv.org/abs/2604.21801) / [GitHub](https://github.com/safouaneelg/SyMTRS) |
| **IR275K** | Infrared multi-frame SR: 594 video sequences, 275,196 frames | [arXiv](https://arxiv.org/abs/2607.22380) / [GitHub](https://github.com/InfraRecon7/IR275K) |
| **NTIRE 2026 infrared RS challenge** | First challenge on remote sensing infrared image SR | [arXiv](https://arxiv.org/abs/2604.21312) / [GitHub](https://github.com/Kai-Liu001/NTIRE2026_infraredSR) |
| **Scene datasets reused for SR** | UC Merced (2,100 images, 256x256, 0.3 m), AID (10,000 images, 30 classes), NWPU-RESISC45 (31,500 images, 45 classes): classification datasets often downsampled to evaluate SR | see each dataset's official page |

### Dataset surveys and catalogues

- [A Comprehensive Survey of Super-Resolution Remote Sensing Image Datasets: Evolution, Challenges, and Future Directions](https://www.researchgate.net/publication/394548668_A_Comprehensive_Survey_of_Super-Resolution_Remote_Sensing_Image_Datasets_Evolution_Challenges_and_Future_Directions)
- [There Are No Data Like More Data: Datasets for Deep Learning in Earth Observation](https://arxiv.org/abs/2310.19231)
- [satellite-image-deep-learning/datasets](https://github.com/satellite-image-deep-learning/datasets): general catalogue of satellite and aerial imagery datasets.

## Evaluation notes

Observations drawn from the papers and benchmarks listed above:

- **Pixel metrics are not enough.** GeoSR-Bench evaluates SR through downstream tasks rather than only fidelity metrics; opensr-test separates *consistency* (agreement with the low-res input), *synthesis* (perceived detail) and *correctness* (agreement with the reference).
- **Synthetic vs real degradation.** Models trained on synthetic low-res inputs can degrade on real cross-sensor data; the "Mind the Gap" paper studies this for diffusion models, and SEN2NAIP, SEN2VENµS and WorldStrat provide real pairs.
- **Hallucination and uncertainty.** Generative SR (diffusion, GAN, flow matching) can invent plausible detail. LDSR-S2 provides a pixel-wise uncertainty map, and a 2026 paper proposes self-supervised uncertainty estimation for satellite SR.
- **Efficiency and scale.** Recent work targets large scenes and deployment cost: InfScene-SR (arbitrarily large scenes), SlimDiffSR (diffusion distillation), HIMOSA and NGram-MoSE (efficient architectures).
- **Trend.** Diffusion and flow-matching models, Mamba/state-space models, reference-based and cross-sensor SR, and vision-language guidance are the most active directions in 2025-2026.

## Credits

- The original list (*Survey* and *Papers & Codes*, entries [1]-[109]) was compiled by **Sen Lei**, who is also an author of LGCNet, HSENet, TransENet, CDGAN, FunSR and SpecGAN. The original README asks that people who find it helpful consider citing those works, and lists these contacts: senlei@swjtu.edu.cn, senlei@buaa.edu.cn. No license was declared in the original; it is reproduced here as a base, with attribution.
- Entries [110]+, the Datasets section and the Evaluation notes were added by J. Estevez. Each title, link and dataset figure comes from the arXiv record or dataset page cited in the same row.
- Corrections and additions are welcome through issues and pull requests. If you are an author and want an entry changed or removed, please open an issue.

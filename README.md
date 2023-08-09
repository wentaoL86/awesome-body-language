 <!-- # <p align=center>`awesome gan-inversion`</p> -->
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/lxtGH/Awesome-Segmenation-With-Transformer/pulls)
![](https://img.shields.io/badge/Status-building-red)
<br />

<p align="center">
  <h1 align="center">A Survey on Deep Multi-modal Learning for Body Language Recognition and Generation</h1>
  <p align="center">
    arXiv, 2023
    <br />
    <a href="/"><strong>Li Liu</strong></a>
    ·
    <a href="/"><strong>Lufei Gao</strong></a>
    ·
    <a href="/"><strong>Wentao Lei</strong></a>
    ·
    <a href="/"><strong>Fengji Ma</strong></a>
    ·
    <a href="/"><strong>Xiaotian Lin</strong></a>
    <br />
    <a href="/"><strong>Jinting Wang</strong></a>
  </p>

  <p align="center">
    <a href='link'>
      <img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
    </a>
    <a href='link' style='padding-left: 0.5rem;'>
      <img src='https://img.shields.io/badge/Project-Page-blue?style=flat&logo=Google%20chrome&logoColor=blue' alt='S-Lab Project Page'>
    </a>
  </p>
<br />

This repo is used for recording and tracking some Multi-modal Body Language researchs,
as a supplement to our [survey](link).  
If you find any work missing or have any suggestions (papers, implementations and other resources), please don't hesitate to open an issue or pull request.
We will add the missing papers to this repo ASAP.


### 🔥News
[-2023.8.19] The second draft is on arxiv. 

[-2023.8.7 ] The first draft is on arxiv. 

### 🔥Highlight!!

[1] We re-visit and group the existing Body Language researchs from the **Multi-modal perspective.**

[2] We survey the research in 4 parts: Cued Speech, Co-speech, Sign Language, Talking Head.

[3] We survey the research in 2 directions: Recognition and Generation.

[4] Some new insight for this directions are discussed.


## Introduction

In this survey, we present the first detailed survey on Multi-modal Body Language research.

![Alt Text](Outline-paper.png)

## Summary of Contents

- [Paper List](#Paper-List)
  - [Recognition](#Recognition)
    - [Cued Speech Recognition](#Cued-Speech-Recognition)
    - [Co-speech Recognition](#Co-speech-Recognition)
    - [Sign Language Recognition](#Sign-Language-Recognition)
    - [Talking Head Recognition](#Talking-Head-Recognition)
  - [Generation](#Generation)
    - [Cued Speech Generation](#Cued-Speech-Generation)
    - [Co-speech Generation](#Co-speech-Generation)
    - [Sign Language Generation](#Co-Language-Generation)
    - [Talking Head Generation](#Talking-Head-Generation)

[//]: # (  )

## Paper-List

### Cued Speech Recognition
| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2010 | Speech Communication | Heracleous et al. | [Cued speech automatic recognition in normal-hearing and deaf subjects](https://www.sciencedirect.com/science/article/abs/pii/S0167639310000415) | N/A |
| 2012 | EUSIPCO | Heracleous et al. | [Continuous phoneme recognition in Cued Speech for French](https://ieeexplore.ieee.org/abstract/document/6333858) | N/A |
| 2018 | Interspeech | Liu et al. | [Visual Recognition of Continuous Cued Speech Using a Tandem CNN-HMM Approach](https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/2434.pdf) | N/A |
| 2020 | Liu et al. |  IEEE Transactions on Multimedia | [Re-synchronization using the hand preceding model for multi-modal fusion in automatic continuous cued speech recognition](https://ieeexplore.ieee.org/abstract/document/9016100) | N/A |
| 2021 | Papadimitriou et al. | EUSIPCO | [A Fully Convolutional Sequence Learning Approach for Cued Speech Recognition from Videos](https://ieeexplore.ieee.org/abstract/document/9287365) | N/A |
| 2021 | Papadimitriou et al. |  HCII | [Multimodal Fusion and Sequence Learning for Cued Speech Recognition from Videos](https://link.springer.com/chapter/10.1007/978-3-030-78095-1_21) | N/A |
| 2021 | Wang et al. | CoRR | [Cross-Modal Knowledge Distillation Method for Automatic Cued Speech Recognition](https://arxiv.org/abs/2106.13686) | N/A |
| 2021 | Wang et al. | CoRR | [An Attention Self-supervised Contrastive Learning based Three-stage Model for Hand Shape Feature Representation in Cued Speech](https://arxiv.org/abs/2106.14016) | N/A |
| 2022 | Sankar et al. |  ICASSP | [Multistream Neural Architectures for Cued Speech Recognition Using a Pre-Trained Visual Feature Extractor and Constrained CTC Decoding](https://ieeexplore.ieee.org/abstract/document/9746976) | N/A |
| 2022 |  Liu et al. | ISCSLP | [Objective Hand Complexity Comparison between Two Mandarin Chinese Cued Speech Systems](https://ieeexplore.ieee.org/abstract/document/10037814) | N/A |
| 2023 | Liu et al. |  ICASSP | [Cross-Modal Mutual Learning for Cued Speech Recognition](https://ieeexplore.ieee.org/abstract/document/10095271) | N/A |


#### Co-speech Recognition

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2014 | Bhattacharya et al. |  MA3HMI  | [Disposition Recognition from Spontaneous Speech Towards a Combination with Co-speech Gestures](https://link.springer.com/chapter/10.1007/978-3-319-15557-9_6) | N/A |
| 2021 |  Böck et al. | ACM MM | [Speech2AffectiveGestures: Synthesizing Co-Speech Gestures with Generative Adversarial Affective Expression Learning](https://dl.acm.org/doi/abs/10.1145/3474085.3475223) | N/A |


#### Sign Language Recognition

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2019 |  CVPR   |  Zhang et al.   | [Continuous Sign Language Recognition via Reinforcement Learning](https://ieeexplore.ieee.org/document/8802972)                                     | N/A             |
| 2020 |  ECAI   |  Zhou et al. | [Self-Attention-based Fully-Inception Networks for Continuous Sign Language Recognition](https://ieeexplore.ieee.org/document/8802972) |  N/A   |
| 2020 | ICASSP |   Li et al. | [Key Action and Joint CTC-Attention based Sign Language Recognition](https://ieeexplore.ieee.org/abstract/document/9054316) |  N/A  |
| 2020 | ECCV  | Cheng et al. | [Fully Convolutional Networks for Continuous Sign Language Recognition](https://link.springer.com/chapter/10.1007/978-3-030-58586-0_41)  | N/A |
| 2020 | ECCV | Niu et al. | [Stochastic Fine-Grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_11)  | N/A |
| 2021 | ICPR | Koishybay et al. | [Continuous Sign Language Recognition with Iterative Spatiotemporal Fine-tuning](https://ieeexplore.ieee.org/abstract/document/9412364) | N/A|
| 2022 | CVPR | Zuo et al. | [C2SLR: Consistency-Enhanced Continuous Sign Language Recognition](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html) | N/A |
| 2022 | IEEE Transactions on Multimedia | Zhou et al. | [Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation](https://ieeexplore.ieee.org/abstract/document/9354538) | N/A |
| 2022 | NeurIPS | Chen et al. | [Two-Stream Network for Sign Language Recognition and Translation](https://proceedings.neurips.cc/paper_files/paper/2022/file/6cd3ac24cdb789beeaa9f7145670fcae-Paper-Conference.pdf) | N/A |
| 2023 | CVPR | Zheng et al. | [CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition With Variational Alignment](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) | N/A |
| 2023 | TPAMI | Bilge et al. | [Towards Zero-Shot Sign Language Recognition](https://ieeexplore.ieee.org/abstract/document/9681230) | N/A
| 2023 | AAAI | Hu et al. | [Self-Emphasizing Network for Continuous Sign Language Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/25164) | https://github.com/hulianyuyy/SEN_CSLR |


#### Talking Head Recognition

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2020 |  CVPR   |      DETR       | [End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872)                                     | [Code](https://github.com/facebookresearch/detr)             |
|      |         |                 |                                                                                                                       |  N/A                                                         |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                 |                                                                                                                       |                                                              |

#### Cued Speech Generation

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
|  1998  |  ISCA  | Paul et al.     |    [Automatic Generation of Cued Speech for The Deaf: Status and Outlook](https://isca-speech.org/archive_open/archive_papers/avsp98/av98_161.pdf)                                                                                       |  N/A                                                         |
|  2008 |   AVSP   |  G ́erard et al.     |    [Retargeting cued speech hand gestures for different talking heads and speakers](https://www.isca-speech.org/archive/avsp_2008/bailly08b_avsp.html)                                                                      |                  N/A                                     |
#### Co Speech Generation

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2015 | IVA |      DCNF       | [Predicting co-verbal gestures: A deep and temporal modeling approach](https://www.stacymarsella.org/publications/pdf/ChiuIVA15.pdf)                                     | N/A            |
| 2019 | CVPR  |        S2G         |      [Learning individual styles of conversational gesture](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ginosar_Learning_Individual_Styles_of_Conversational_Gesture_CVPR_2019_paper.pdf)                                                                                                                 |  [Code](https://github.com/amirbar/speech2gesture)                                                         | 
|  2020  | EUROGRAPHICS |        StyleGestures         |      [Style-Controllable Speech-Driven Gesture Synthesis Using Normalising Flows](https://www.diva-portal.org/smash/get/diva2:1499133/FULLTEXT01.pdf)                                                                                                |      [Code](https://github.com/simonalexanderson/StyleGestures/)                                                        |
|  2021    | ICCV |        A2G         |            [Audio2Gestures: Generating Diverse Gestures from Speech Audio withConditional Variational Autoencoders](https://arxiv.org/abs/2301.06690)                                                                                                           |                                        [Code](https://jingli513.github.io/audio2gestures/)                      |
|  2021  |  IEEE VR  |          Text2Gestures       |           [Text2Gestures: A Transformer-Based Network for Generating Emotive Body Gestures for Virtual Agents](https://arxiv.org/abs/2101.11101)                                                                                                            |     [Code](https://github.com/UttaranB127/Text2Gestures)                                                     
|  2022  | Computer Graphics Forum |        ZeroEGGS             |   [ZeroEGGS: Zero-shot Example-based Gesture Generation from Speech](https://onlinelibrary.wiley.com/doi/10.1111/cgf.14734)      |   [Code](https://github.com/ubisoft/ubisoft-laforge-ZeroEGGS)
|  2022  |   CVPR    |         DiffGAN             |        [Low-Resource Adaptation for Personalized Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Ahuja_Low-Resource_Adaptation_for_Personalized_Co-Speech_Gesture_Generation_CVPR_2022_paper.pdf)                    |    N/A
|  2022  |   SIGGRAPH Asia    |          RG            |       [Rhythmic Gesticulator: Rhythm-Aware Co-Speech Gesture Synthesis with Hierarchical Neural Embeddings](https://arxiv.org/abs/2210.01448)                |  [Code](https://github.com/Aubrey-ao/HumanBehaviorAnimation)

#### Sign Language Generation

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2016 |  Universal Access in the Information Society   |      Sign3D     | [Interactive editing in French Sign Language dedicated to virtual signers: requirements and challenges](https://link.springer.com/article/10.1007/s10209-015-0411-6)                                     | N/A|
| 2018 |  AAAI   |      DETR       | [Hierarchical LSTM for Sign Language Translation](https://arxiv.org/abs/2005.12872)                                    | N/A              |
|  2020          |    IJCV         |    text2gesture             | [Text2Sign: Towards Sign Language Production Using Neural Machine Translation and Generative Adversarial Networks](https://link.springer.com/article/10.1007/s11263-019-01281-2)                                                                                                 |  N/A           |
|  2020  |    CVPR    |    ESN       |    [Everybody Sign Now:Translating Spoken Language to Photo Realistic Sign Language Video](https://arxiv.org/pdf/2011.09846.pdf)                                                                                                             |      N/A            |
| 2020     |    BMVC   |    Saunders et al.|                         [Adversarial Training for Multi-Channel Sign Language Production](https://arxiv.org/pdf/2008.12405.pdf)                                                                                           |    N/A   |
| 2022  |    ACL  |     DSM        |              [Modeling Intensification for Sign Language Generation: A Computational Approach](https://arxiv.org/abs/2203.09679)                                                                                                    |        [Code](https://github.com/Merterm/Modeling-Intensification-for-SLG)          |
|  2022  |  CVPR   |      SignGAN    |    [Signing at Scale: Learning to Co-Articulate Signs for Large-Scale Photo-Realistic Sign Language Production](https://arxiv.org/abs/2203.15354)          |       N/A                                           |
| 2023  |   CVPR   |    PoseVQ-Diffusion     |  [Vector Quantized Diffusion Model with CodeUnet for Text-to-Sign Pose Sequences Generation](https://arxiv.org/abs/2208.09141)                                                                                  |    [Code](https://github.com/cientgu/VQ-Diffusion)                                                          |
#### Talking Head Generation

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2020 |  CVPR   |      DETR       | [End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872)                                     | [Code](https://github.com/facebookresearch/detr)             |
|      |         |                 |                                                                                                                       |  N/A                                                         |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                 |                                                                                                                       |                                                              |
|      |         |                  |                                                                                                                       |                                                              |

## Acknowledgement

If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex
@article{liu2023blsurvey,
  title={A Survey on Deep Multi-modal Learning for Body Language Recognition and Generation},
  author={Liu, Li and Lufei, Gao  and Wentao, Lei and Fengji, Ma and Xiaotian, Lin and Jinting, Wang },
  journal={arXiv:xxxx},
  year={2023}
}
```
## Contact
```
avrillliu@hkust-gz.edu.cn
```
```
wentaolei@hkust-gz.edu.cn
```
## Related Repo of Our Group

Awesome-Segment-Anything [Repo](https://github.com/liliu-avril/Awesome-Segment-Anything) by Chunhui Zhang.


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
    <a href='https://arxiv.org/abs/2308.08849'>
      <img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
    </a>
    <a href='link' style='padding-left: 0.5rem;'>
      <img src='https://img.shields.io/badge/Project-Page-blue?style=flat&logo=Google%20chrome&logoColor=blue' alt='S-Lab Project Page'>
    </a>
  </p>
<br />

This repository is used for recording and tracking some Multi-modal Body Language researchs,
as a supplement to our [survey](https://arxiv.org/abs/2308.08849).  
If you find any work missing or have any suggestions (papers, implementations and other resources), please don't hesitate to open an issue or pull request or just contact us by e-mail.
We will check the problems and add the missing papers to this repo ASAP.


### 🔥News

[-2023.8.17 ] The first draft is on arxiv. 

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
  - [Challenges](#Challenges)

[//]: # (  )

## Paper-List

### Cued Speech Recognition
| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2010 | Speech Communication | Heracleous et al. | [Cued speech automatic recognition in normal-hearing and deaf subjects](https://www.sciencedirect.com/science/article/abs/pii/S0167639310000415) | N/A |
| 2012 | EUSIPCO | Heracleous et al. | [Continuous phoneme recognition in Cued Speech for French](https://ieeexplore.ieee.org/abstract/document/6333858) | N/A |
| 2018 | Interspeech | Liu et al. | [Visual Recognition of Continuous Cued Speech Using a Tandem CNN-HMM Approach](https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/2434.pdf) | N/A |
| 2020 | IEEE Transactions on Multimedia | Liu et al. | [Re-synchronization using the hand preceding model for multi-modal fusion in automatic continuous cued speech recognition](https://ieeexplore.ieee.org/abstract/document/9016100) | N/A |
| 2021 | EUSIPCO | Papadimitriou et al. | [A Fully Convolutional Sequence Learning Approach for Cued Speech Recognition from Videos](https://ieeexplore.ieee.org/abstract/document/9287365) | N/A |
| 2021 | HCII | Papadimitriou et al. | [Multimodal Fusion and Sequence Learning for Cued Speech Recognition from Videos](https://link.springer.com/chapter/10.1007/978-3-030-78095-1_21) | N/A |
| 2021 | arXiv preprint | Wang et al. |[Cross-Modal Knowledge Distillation Method for Automatic Cued Speech Recognition](https://arxiv.org/abs/2106.13686) | N/A |
| 2021 | arXiv preprint | Wang et al. | [An Attention Self-supervised Contrastive Learning based Three-stage Model for Hand Shape Feature Representation in Cued Speech](https://arxiv.org/abs/2106.14016) | N/A |
| 2022 | ICASSP |  Sankar et al. | [Multistream Neural Architectures for Cued Speech Recognition Using a Pre-Trained Visual Feature Extractor and Constrained CTC Decoding](https://ieeexplore.ieee.org/abstract/document/9746976) | N/A |
| 2022 | ISCSLP | Liu et al. | [Objective Hand Complexity Comparison between Two Mandarin Chinese Cued Speech Systems](https://ieeexplore.ieee.org/abstract/document/10037814) | N/A |
| 2023 |  ICASSP | Liu et al. | [Cross-Modal Mutual Learning for Cued Speech Recognition](https://ieeexplore.ieee.org/abstract/document/10095271) | N/A |


#### Co-speech Recognition

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2014 | MA3HMI  |  Bhattacharya et al. | [Disposition Recognition from Spontaneous Speech Towards a Combination with Co-speech Gestures](https://link.springer.com/chapter/10.1007/978-3-319-15557-9_6) | N/A |
| 2021 | ACM MM | Böck et al. | [Speech2AffectiveGestures: Synthesizing Co-Speech Gestures with Generative Adversarial Affective Expression Learning](https://dl.acm.org/doi/abs/10.1145/3474085.3475223) | N/A |


#### Sign Language Recognition

| Year |  Venue  |     Acronym     | Paper Title                                                                                                           | Code/Project                                                 |
|:----:|:-------:|:---------------:|-----------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| 2019 |  ICIP   |  Zhang et al.   | [Continuous Sign Language Recognition via Reinforcement Learning](https://ieeexplore.ieee.org/document/8802972)                                     | N/A             |
| 2020 |  ECAI   |  Zhou et al. | [Self-Attention-based Fully-Inception Networks for Continuous Sign Language Recognition](https://ieeexplore.ieee.org/document/8802972) |  N/A   |
| 2020 | ICASSP |   Li et al. | [Key Action and Joint CTC-Attention based Sign Language Recognition](https://ieeexplore.ieee.org/abstract/document/9054316) |  N/A  |
| 2020 | ECCV  | Cheng et al. | [Fully Convolutional Networks for Continuous Sign Language Recognition](https://link.springer.com/chapter/10.1007/978-3-030-58586-0_41)  | N/A |
| 2020 | ECCV | Niu et al. | [Stochastic Fine-Grained Labeling of Multi-state Sign Glosses for Continuous Sign Language Recognition](https://link.springer.com/chapter/10.1007/978-3-030-58517-4_11)  | N/A |
| 2021 | ICPR | Koishybay et al. | [Continuous Sign Language Recognition with Iterative Spatiotemporal Fine-tuning](https://ieeexplore.ieee.org/abstract/document/9412364) | N/A|
| 2022 | CVPR | Zuo et al. | [C2SLR: Consistency-Enhanced Continuous Sign Language Recognition](https://openaccess.thecvf.com/content/CVPR2022/html/Zuo_C2SLR_Consistency-Enhanced_Continuous_Sign_Language_Recognition_CVPR_2022_paper.html) | N/A |
| 2022 | IEEE Transactions on Multimedia | Zhou et al. | [Spatial-Temporal Multi-Cue Network for Sign Language Recognition and Translation](https://ieeexplore.ieee.org/abstract/document/9354538) | N/A |
| 2022 | NeurIPS | Chen et al. | [Two-Stream Network for Sign Language Recognition and Translation](https://proceedings.neurips.cc/paper_files/paper/2022/file/6cd3ac24cdb789beeaa9f7145670fcae-Paper-Conference.pdf) | N/A |
| 2023 | CVPR | Zheng et al. | [CVT-SLR: Contrastive Visual-Textual Transformation for Sign Language Recognition With Variational Alignment](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_CVT-SLR_Contrastive_Visual-Textual_Transformation_for_Sign_Language_Recognition_With_Variational_CVPR_2023_paper.html) | [Code](https://github.com/binbinjiang/CVT-SLR) |
| 2023 | TPAMI | Bilge et al. | [Towards Zero-Shot Sign Language Recognition](https://ieeexplore.ieee.org/abstract/document/9681230) | N/A |
| 2023 | AAAI | Hu et al. | [Self-Emphasizing Network for Continuous Sign Language Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/25164) | [Code](https://github.com/hulianyuyy/SEN_CSLR) |



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
|    2018  |   ECCV  |  X2Face    |  [X2Face: A network for controlling face generation using images, audio, and pose codes](https://openaccess.thecvf.com/content_ECCV_2018/html/Olivia_Wiles_X2Face_A_network_ECCV_2018_paper.html)|  N/A|
| 2018 |  ECCV   |      Chen et al.    | [Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/papers/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.pdf)                                     | [Code](https://github.com/lelechen63/3d_gan)             |
|  2019  |  NeurIPS |   Wen et al.   |  [Face Reconstruction from Voice using Generative Adversarial Networks](https://proceedings.neurips.cc/paper_files/paper/2019/file/eb9fc349601c69352c859c1faa287874-Paper.pdf)|  [Code](https://github.com/cmu-mlsp/reconstructing_faces_from_voices)|
|   2019  |  CVPR  |  Speech2Face |  [Speech2Face: Learning the Face Behind a Voice](https://openaccess.thecvf.com/content_CVPR_2019/html/Oh_Speech2Face_Learning_the_Face_Behind_a_Voice_CVPR_2019_paper.html)| N/A|
|  2019   |  ICASSP  |  Wav2Pix |   [WAV2PIX: Speech-conditioned Face Generation using Generative Adversarial Networks](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Sight%20and%20Sound/Amanda_Cardoso_Duarte_WAV2PIX_Speech-conditioned_Face_Generation_using_Generative_Adversarial_Networks_CVPRW_2019_paper.pdf)|  [Code](https://imatge-upc.github.io/wav2pix/)| 
|  2019   |  IJCV      |  Jamaludin et al.|[You Said That?: Synthesising Talking Faces from Audio](https://link.springer.com/article/10.1007/s11263-019-01150-y)|N/A|
|   2019  |    IJCAI     |         Song et al.        |   [Talking Face Generation by Conditional Recurrent Adversarial Network](https://www.ijcai.org/proceedings/2019/0129.pdf)|N/A|
|  2019    |    AAAI     |    Zhou et al.             |  [Talking face generation by adversarially disentangled audio-visual representation](https://ojs.aaai.org/index.php/AAAI/article/view/4967)      |         N/A                                                   |
|    2019  |    CVPR     |         Kefalas et al .        |          [End-to-End Speech-Driven Realistic Facial Animation with Temporal GANs](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Sight%20and%20Sound/Konstantinos_Vougioukas_End-to-End_Speech-Driven_Realistic_Facial_Animation_with_Temporal_GANs_CVPRW_2019_paper.pdf)    |    N/A                                                          |
|   2020   |    ICCASP     |     Kefalas et al .            |       [Speech-Driven Facial Animation Using Polynomial Fusion of Features](https://ieeexplore.ieee.org/abstract/document/9054469)                        |            N/A                                                  |
|   2020   |   ICASSP|   Eskimez et al.     |  [End-To-End Generation of Talking Faces from Noisy Speech](https://ieeexplore.ieee.org/abstract/document/9054103)|   N/A|
|    2020  |   IJCNN      |          Sinha et al.        |  [Identity-Preserving Realistic Talking Face Generation](https://ieeexplore.ieee.org/abstract/document/9206665)              |         N/A         |
|  2020    |  INTERSPEECH |     Wang et al.   |    [Speech Driven Talking Head Generation via Attentional Landmarks Based Representation](https://www.isca-speech.org/archive_v0/Interspeech_2020/abstracts/2304.html)|   N/A|
|  2020    |  ACM MM      |  Wav2lip           |  [A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild](https://dl.acm.org/doi/abs/10.1145/3394171.3413532)|    N/A|
|   2020   |  arXiv preprint |  Yi et al. |  [Audio-driven talking face video generation with learning-based personalized head pose](https://arxiv.org/abs/2002.10137)|  N/A|
|   2020   |  ECCV|   Chen et al.|   [Talking-Head Generation with Rhythmic Head Motion](https://link.springer.com/chapter/10.1007/978-3-030-58545-7_3#citea) | [Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion)|
|  2020    |   WACV|  Mittal et al.| [Animating Face using Disentangled Audio Representations](https://openaccess.thecvf.com/content_WACV_2020/html/Mittal_Animating_Face_using_Disentangled_Audio_Representations_WACV_2020_paper.html)| N/A|
|   2020  |  ECCV  |   MEAD     |  [MEAD: A Large-Scale Audio-Visual Dataset for Emotional Talking-Face Generation](https://link.springer.com/chapter/10.1007/978-3-030-58589-1_42)| [Code](https://wywu.github.io/projects/MEAD/MEAD.html.)|
|  2020   |  TVCG   |  Wen et al.   | [Photorealistic Audio-driven Video Portraits](https://ieeexplore.ieee.org/abstract/document/9199560)|[Code](https://github.com/xinwen-cs/AudioDVP)|
|  2021    |  CVPR   | LipSync3D    |  [LipSync3D: Data-Efficient Learning of Personalized 3D Talking Faces From Video Using Pose and Lighting Normalization](https://openaccess.thecvf.com/content/CVPR2021/html/Lahiri_LipSync3D_Data-Efficient_Learning_of_Personalized_3D_Talking_Faces_From_Video_CVPR_2021_paper.html)| N/A|
| 2021  |  The Visual Computer | Fang et al. | [Facial expression GAN for voice-driven face generation](https://link.springer.com/article/10.1007/s00371-021-02074-w#citeas)|  N/A|
|   2021   |  IJCAI  |  Zhu et al.  |  [Arbitrary talking face generation via attentional audio-visual coherence learning](https://dl.acm.org/doi/abs/10.5555/3491440.3491767)|  N/A|
|  2021    |JCAI|    Audio2head    |  [Audio2Head: Audio-driven One-shot Talking-head Generation with Natural Head Motion](https://www.ijcai.org/proceedings/2021/0152.pdf)| N/A|
|   2021   |  ACM   TOG  |  Lu et al.   |  [Live speech portraits: real-time photorealistic talking-head animation](https://dl.acm.org/doi/abs/10.1145/3478513.3480484)|  N/A|
|   2021   |   ICCV  |   FACIAL     |  [FACIAL: Synthesizing Dynamic Talking Face With Implicit Attribute Learning](https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_FACIAL_Synthesizing_Dynamic_Talking_Face_With_Implicit_Attribute_Learning_ICCV_2021_paper.html)|  N/A|
|  2021  |  ICCV  |  AD-NeRF  |   [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://openaccess.thecvf.com/content/ICCV2021/html/Guo_AD-NeRF_Audio_Driven_Neural_Radiance_Fields_for_Talking_Head_Synthesis_ICCV_2021_paper.html)|[Code](https://github.com/YudongGuo/AD-NeRF)|
|   2021   |  CVPR  |   MEAD     |  [Flow-Guided One-Shot Talking Face Generation With a High-Resolution Audio-Visual Dataset](https://openaccess.thecvf.com/content/CVPR2021/html/Zhang_Flow-Guided_One-Shot_Talking_Face_Generation_With_a_High-Resolution_Audio-Visual_Dataset_CVPR_2021_paper.html)| [Code](https://github.com/MRzzm/HDTF)
|   2021|   arXiv preprint|  Si et al.|  [Speech2Video: Cross-Modal Distillation for Speech to Video Generation](https://arxiv.org/abs/2107.04806)|N/A |
|   2021|   arXiv preprint|  Chen et al. |  [Talking Head Generation with Audio and Speech Related Facial Action Units](https://arxiv.org/abs/2110.09951)| N/A|
|  2021  |  CVPR  |  PC-AVS  |  [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Zhou_Pose-Controllable_Talking_Face_Generation_by_Implicitly_Modularized_Audio-Visual_Representation_CVPR_2021_paper.html)| [Code](https://hangznju-cuhk.github.io/projects/PC-AVS)|
|  2022|   CVPR   |  GC-VAT   | [Expressive Talking Head Generation With Granular Audio-Visual Control](https://openaccess.thecvf.com/content/CVPR2022/html/Liang_Expressive_Talking_Head_Generation_With_Granular_Audio-Visual_Control_CVPR_2022_paper.html)|   N/A|
|  2022  |  AAAI   |   Wang et al.    |  [One-Shot Talking Face Generation from Single-Speaker Audio-Visual Correlation Learning](https://ojs.aaai.org/index.php/AAAI/article/view/20154) |    N/A|
|  2022  |  ACM  SIGGRAPH|  EAMM  |   [EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://dl.acm.org/doi/abs/10.1145/3528233.3530745) |  N/A|
| 2022   |  arXiv preprint  |  SPACE | [SPACE: Speech-driven Portrait Animation with Controllable Expression](https://arxiv.org/abs/2211.09809)|N/A|
 |  2022 |  arXiv preprint |   DFA-NERF |  [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/abs/2201.00791)|   N/A|
 |    2022 |  arXiv preprint |  Yu et al.   |  [Talking Head Generation with Probabilistic Audio-to-Visual Diffusion Priors](https://arxiv.org/abs/2212.04248)|  N/A|  
 |   2022 |  ACCESS|  Bigioi et al.  |  [Pose-Aware Speech Driven Facial Landmark Animation Pipeline for Automated Dubbing](https://ieeexplore.ieee.org/abstract/document/9994681) |  N/A|
 |  2022  |  ECCV  |  DFRF  |  [Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis](https://link.springer.com/chapter/10.1007/978-3-031-19775-8_39)|   [Code](https://sstzal.github.io/DFRF/)|
 |   2022 |  ECCV  |  SSP-NeRF   |  [Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation](https://link.springer.com/chapter/10.1007/978-3-031-19836-6_7)|  [Code](https://alvinliu0.github.io/projects/SSP-NeRF)|
 |  2023 | arXiv preprint   | DIRFA    |  [Audio-Driven Talking Face Generation with Diverse yet Realistic Facial Animations](https://arxiv.org/abs/2304.08945) |  N/A|
 |   2023  |  ICASSP|    DisCoHead   |  [DisCoHead: Audio-and-Video-Driven Talking Head Generation by Disentangled Control of Head Pose and Facial Expressions](https://ieeexplore.ieee.org/abstract/document/10095670)| N/A|
 |   2023  |   ICASSP  |  OPT     |  [OPT: One-shot Pose-Controllable Talking Head Generation](https://ieeexplore.ieee.org/abstract/document/10094598)|    N/A|
 |    2023 |   ICASSP|  Zhua et al.  |   [Audio-Driven Talking Head Video Generation with Diffusion Model](https://ieeexplore.ieee.org/abstract/document/10094937)|   N/A|
|   2023   |   CVPR    |   Wang et al.   |  [Progressive Disentangled Representation Learning for Fine-Grained Controllable Talking Head Synthesis](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Progressive_Disentangled_Representation_Learning_for_Fine-Grained_Controllable_Talking_Head_Synthesis_CVPR_2023_paper.html)|  N/A|
|   2023  | ICPADS    |   Zhang et al.|  [Talking Head Generation for Media Interaction System with Feature Disentanglement](https://ieeexplore.ieee.org/abstract/document/10077905/) |   N/A|
|   2023  |   CVPR  |    SadTalker |  [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_SadTalker_Learning_Realistic_3D_Motion_Coefficients_for_Stylized_Audio-Driven_Single_CVPR_2023_paper.html)|  [Code](https://sadtalker.github.io.)|
|   2023 |  CVPR  |   DiffTalk  |  [DiffTalk: Crafting Diffusion Models for Generalized Audio-Driven Portraits Animation](https://openaccess.thecvf.com/content/CVPR2023/html/Shen_DiffTalk_Crafting_Diffusion_Models_for_Generalized_Audio-Driven_Portraits_Animation_CVPR_2023_paper.html)|  [Code](https://sstzal.github.io/DiffTalk/)|
|   2023 |  CoRR  |       |   [Multimodal-driven Talking Face Generation via a Unified Diffusion-based Generator](https://zst1406217.github.io/home_page_files/Multimodal-driven%20Talking%20Face%20Generation.pdf)|  N/A|

#### Challenges

| Year |     Task       |   Language     |  Name     | Link                                                 |
| :--: | :------------: | :---------:   |:---------: | ------------------------------------------------------------ |
| 2021 |      Sign Language Recognition      |  English   | ChaLearn Looking at People     |   [link](https://chalearnlap.cvc.uab.cat/challenge/43/description/)                       |
| 2022 |     Sign Language Recognition, Translation & Production     |  English |SLRTP   | [link](https://slrtp-2022.github.io/)     |
| 2023 |      Sign Language Recognition      |        English                        |  Google - Isolated Sign Language Recognition |   [link](https://www.kaggle.com/competitions/asl-signs)                                                      |
| 2023 |      Sign Language Recognition      | Multiple |WMT-SLT 23   |   [link](https://www.wmt-slt.com/)                     |
| 2018 |     Lip Reading Recognition     | Japanese |  SSSD    |              [link](https://www.saitoh-lab.com/SSSD/index_en.html)                                |
| 2022 |    Talking Head Generation |  English   | ViCo2022   |  [link](https://vico.solutions/challenge/2022)                                                     |
| 2023 |    Talking Head Generation     | English    |  ViCo2023     |   [link](https://vico.solutions/challenge/2023)                    |
| 2020 | Co-speech  Generation | English |  GENEA Challenge 2020 |  [link](https://genea-workshop.github.io/2020/#gesture-generation-challenge) |
| 2022 | Co-speech  Generation | English |  GENEA Challenge 2022|  [link](https://genea-workshop.github.io/2022/#gesture-generation-challenge) |
| 2023 | Co-speech  Generation | English |  GENEA Challenge 2023 |  [link](https://genea-workshop.github.io/2023/#gesture-generation-challenge) |


## Acknowledgement

If you find our survey and repository useful for your research project, please consider citing our paper:

```bibtex
@article{liu2023blsurvey,
  title={A Survey on Deep Multi-modal Learning for Body Language Recognition and Generation},
  author={Liu, Li and Lufei, Gao  and Wentao, Lei and Fengji, Ma and Xiaotian, Lin and Jinting, Wang },
  journal={arXiv:2308.08849},
  year={2023}
}
```
## Contact
```
avrillliu@hkust-gz.edu.cn
```
```
wlei117@connect.hkust-gz.edu.cn
```


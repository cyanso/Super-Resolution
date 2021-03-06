# Quick navigation

- [Important Repositories](#Important-Repositories)
  - [Awesome Paper List](#Awesome-Paper-List)
  - [Awesome Repos](#Awesome-Repos)
  - [SR Metrics](#SR-Metrics)
- [DataSets](#DataSets)
- [Papers](#Papers)
  - [Non-DL Based Approach](#Non-DL-Based-Approach)
  - [DL Based Approach](#DL-Based-Approach)
    - [2014~2017](#2014~2017)
    - [2018](#2018)
    - [2019](#2019)
    - [2020](#2020)
  - [Super Resolution Survey](#Super-Resolution-Survey)
- [Workshop for SR](#Workshop-for-SR)
- [Excellent Personal Website](#Excellent-Personal-Website)

# Super-Resolution（in progress...）

Collect some image SR related papers, datasets, metrics and repositories.

Most of these contents are referenced from [here.](<https://github.com/ChaofWang/Awesome-Super-Resolution>) Thank you!!! 

## Important Repositories

### Awesome Paper List

[Paper with code: Super Resolution](https://paperswithcode.com/task/super-resolution)

[Single-Image-Super-Resolution](https://github.com/YapengTian/Single-Image-Super-Resolution)

[Super-Resolution. Benckmark](https://github.com/huangzehao/Super-Resolution.Benckmark)

[Video-Super-Resolution](https://github.com/flyywh/Video-Super-Resolution)

[VideoSuperResolution](https://github.com/LoSealL/VideoSuperResolution)

[Awesome Super-Resolution](https://github.com/ptkin/Awesome-Super-Resolution) 

### Awesome Repos

|                             repo                             | Framework  |
| :----------------------------------------------------------: | :--------: |
| [EDSR-PyTorch](https://github.com/thstkdgus35/EDSR-PyTorch)  |  PyTorch   |
|      [RCAN-PyTorch](https://github.com/yulunzhang/RCAN)      |  PyTorch   |
|   [CARN-PyTorch](https://github.com/nmhkahn/CARN-pytorch)    |  PyTorch   |
|        [BasicSR](https://github.com/xinntao/BasicSR)         |  PyTorch   |
| [Image-Super-Resolution](https://github.com/titu1994/Image-Super-Resolution) |   Keras    |
| [image-super-resolution](https://github.com/idealo/image-super-resolution) |   Keras    |
| [Super-Resolution-Zoo](https://github.com/WolframRhodium/Super-Resolution-Zoo) |   MxNet    |
| [super-resolution](https://github.com/krasserm/super-resolution) |   Keras    |
|  [neural-enhance](https://github.com/alexjc/neural-enhance)  |   Theano   |
|          [srez](https://github.com/david-gpu/srez)           | Tensorflow |
|        [waifu2x](https://github.com/nagadomi/waifu2x)        |   Torch    |
| [Super-resolution](https://github.com/icpm/super-resolution) |  PyTorch   |
| [VideoSuperResolution](https://github.com/LoSealL/VideoSuperResolution) | Tensorflow |
| [Video-super-resolution](https://github.com/thangvubk/video-super-resolution) |  PyTorch   |

### SR Metrics

Note this table is referenced from [here](https://github.com/ptkin/Awesome-Super-Resolution).

| Metric  | Papers                                                       |
| :------ | ------------------------------------------------------------ |
| MS-SSIM | **Multiscale structural similarity for image quality assessment**, *Wang, Zhou; Simoncelli, Eero P.; Bovik, Alan C.*, **ACSSC 2003**, [[ACSSC](https://ieeexplore.ieee.org/document/1292216)], `MS-SSIM` |
| SSIM    | **Image Quality Assessment: From Error Visibility to Structural Similarity**, *Wang, Zhou; Bovik, Alan C.; Sheikh, Hamid R.; Simoncelli, Eero P*, **TIP 2004**, [[TIP](https://ieeexplore.ieee.org/document/1284395)], `SSIM` |
| IFC     | **An information fidelity criterion for image quality assessment using natural scene statistics**, *Sheikh, Hamid Rahim; Bovik, Alan Conrad; de Veciana, Gustavo de Veciana*, **TIP 2005**, [[TIP](https://ieeexplore.ieee.org/document/1532311/)], `IFC` |
| VIF     | **Image information and visual quality**, *Sheikh, Hamid Rahim; Bovik, Alan C.*, **TIP 2006**, [[TIP](https://ieeexplore.ieee.org/document/1576816)], `VIF` |
| FSIM    | **FSIM: A Feature Similarity Index for Image Quality Assessment**, *Zhang, Lin; Zhang, Lei; Mou, Xuanqin; Zhang, David*, **TIP 2011**, [[Project](http://www4.comp.polyu.edu.hk/~cslzhang/IQA/FSIM/FSIM.htm)], [[TIP](https://ieeexplore.ieee.org/document/5705575)], `FSIM` |
| NIQE    | **Making a “Completely Blind” Image Quality Analyzer**, *Mittal, Anish; Soundararajan, Rajiv; Bovik, Alan C.*, **Signal Processing Letters 2013**, [[Matlab*](https://github.com/csjunxu/Bovik_NIQE_SPL2013)], [[Signal Processing Letters](https://ieeexplore.ieee.org/document/6353522)], `NIQE` |
| Ma      | **Learning a no-reference quality metric for single-image super-resolution**, *Ma, Chao; Yang, Chih-Yuan; Yang, Xiaokang; Yang, Ming-Hsuan*, **CVIU 2017**, [[arXiv](https://arxiv.org/abs/1612.05890)], [[CVIU](https://www.sciencedirect.com/science/article/pii/S107731421630203X)], [[Matlab*](https://github.com/chaoma99/sr-metric)], [[Project](https://sites.google.com/site/chaoma99/sr-metric)], `Ma` |

## Datasets

Note this table is referenced from [here](https://github.com/LoSealL/VideoSuperResolution#link-of-datasets).

| Name                    |   Usage    |                             Link                             |           Comments            |
| :---------------------- | :--------: | :----------------------------------------------------------: | :---------------------------: |
| Set5                    |    Test    | [download](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip) | super-resolution test dataset |
| SET14                   |    Test    | [download](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip) | super-resolution test dataset |
| BSD100                  |    Test    | [download](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip) | super-resolution test dataset |
| Urban100                |    Test    | [download](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip) | super-resolution test dataset |
| Manga109                |    Test    | [download](https://www.kaggle.com/msahebi/super-resolution#SR_testing_datasets.zip) | super-resolution test dataset |
| BSD300                  | Train/Val  | [download](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/segbench/BSDS300-images.tgz) |                               |
| BSD500                  | Train/Val  | [download](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz) |                               |
| 91-Image                |   Train    | [download](http://www.ifp.illinois.edu/~jyang29/codes/ScSR.rar) |             Yang              |
| DIV2K2017               | Train/Val  |     [website](https://data.vision.ee.ethz.ch/cvl/DIV2K/)     |           NTIRE2017           |
| Real SR                 | Train/Val  | [website](https://competitions.codalab.org/competitions/21439#participate) |           NTIRE2019           |
| Waterloo                |   Train    |   [website](https://ece.uwaterloo.ca/~k29ma/exploration/)    |                               |
| VID4                    |    Test    | [download](https://people.csail.mit.edu/celiu/CVPR2011/videoSR.zip) |           4 videos            |
| MCL-V                   |   Train    |        [website](http://mcl.usc.edu/mcl-v-database/)         |           12 videos           |
| GOPRO                   | Train/Val  | [website](https://github.com/SeungjunNah/DeepDeblur_release) |       33 videos, deblur       |
| CelebA                  |   Train    | [website](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  |          Human faces          |
| Sintel                  | Train/Val  |       [website](http://sintel.is.tue.mpg.de/downloads)       |         Optical flow          |
| FlyingChairs            |   Train    | [website](https://lmb.informatik.uni-freiburg.de/resources/datasets/FlyingChairs.en.html#flyingchairs) |         Optical flow          |
| Vimeo-90k               | Train/Test |           [website](http://toflow.csail.mit.edu/)            |         90k HQ videos         |
| SR-RAW                  | Train/Test | [website](https://ceciliavision.github.io/project-pages/project-zoom.html) |   raw sensor image dataset    |
| Benchmark and DIV2k(SR) | Train/Test | [website](https://drive.google.com/drive/folders/1-99XFJs_fvQ2wFdxXrnJFcRRyPJYKN0K) |   super-resolution dataset    |

## Papers

### Non-DL Based Approach

SCSR: TIP2010, Jianchao Yang et al.[paper](https://ieeexplore.ieee.org/document/5466111/?arnumber=5466111), [code](http://www.ifp.illinois.edu/~jyang29/)

ANR: ICCV2013, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-ICCV-2013.pdf), [code](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)

A+: ACCV 2014, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-ACCV-2014.pdf), [code](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)

IA: CVPR2016, Radu Timofte et al. [paper](http://www.vision.ee.ethz.ch/~timofter/publications/Timofte-CVPR-2016.pdf)

SelfExSR: CVPR2015, Jia-Bin Huang et al. [paper](https://uofi.box.com/shared/static/8llt4ijgc39n3t7ftllx7fpaaqi3yau0.pdf), [code](https://github.com/jbhuang0604/SelfExSR)

NBSRF: ICCV2015, Jordi Salvador et al. [paper](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Salvador_Naive_Bayes_Super-Resolution_ICCV_2015_paper.pdf)

RFL: ICCV2015, Samuel Schulter et al [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Schulter_Fast_and_Accurate_2015_CVPR_paper.pdf), [code](<https://www.tugraz.at/institute/icg/research/team-bischof/samuel-schulter/>)

### DL Based Approach

#### 2014~2017

| Model      | Published                                                    | Code                                                         | Keywords                 |
| ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------ |
| SRCNN      | [ECCV14](https://arxiv.org/abs/1501.00092)                   | [Keras](https://github.com/qobilidop/srcnn)                  | CNN                      |
| RAISR      | [arXiv](https://arxiv.org/abs/1606.01299)                    | -                                                            | Google, Pixel 3          |
| ESPCN      | [CVPR16](https://arxiv.org/abs/1609.05158)                   | [Keras](https://github.com/qobilidop/srcnn)                  | Real time/SISR/VideoSR   |
| VDSR       | [CVPR16](https://arxiv.org/abs/1511.04587)                   | [Matlab](http://cv.snu.ac.kr/research/VDSR/)                 | Deep, Residual           |
| DRCN       | [CVPR16](https://arxiv.org/abs/1511.04491)                   | [Matlab](http://cv.snu.ac.kr/research/DRCN/)                 | Recurrent                |
| DRRN       | [CVPR17](http://cvlab.cse.msu.edu/pdfs/Tai_Yang_Liu_CVPR2017.pdf) | [Caffe](https://github.com/tyshiwo/DRRN_CVPR17), [PyTorch](https://github.com/jt827859032/DRRN-pytorch) | Recurrent                |
| LapSRN     | [CVPR17](http://vllab.ucmerced.edu/wlai24/LapSRN/)           | [Matlab](https://github.com/phoenix104104/LapSRN)            | Huber loss               |
| IRCNN      | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Learning_Deep_CNN_CVPR_2017_paper.pdf) | [Matlab](https://github.com/cszn/IRCNN)                      |                          |
| EDSR       | [CVPR17](https://arxiv.org/abs/1707.02921)                   | [PyTorch](https://github.com/thstkdgus35/EDSR-PyTorch)       | NTIRE17 Champion         |
| BTSRN      | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Fan_Balanced_Two-Stage_Residual_CVPR_2017_paper.pdf) | -                                                            | NTIRE17                  |
| SelNet     | [CVPR17](https://ieeexplore.ieee.org/document/8014887)       | -                                                            | NTIRE17                  |
| TLSR       | [CVPR17](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w12/papers/Xu_Fast_and_Accurate_CVPR_2017_paper.pdf) | -                                                            | NTIRE17                  |
| SRGAN      | [CVPR17](https://arxiv.org/abs/1609.04802)                   | [Tensorflow](https://github.com/tensorlayer/srgan)           | 1st proposed GAN         |
| VESPCN     | [CVPR17](https://arxiv.org/abs/1611.05250)                   | -                                                            | VideoSR                  |
| MemNet     | [ICCV17](https://arxiv.org/abs/1708.02209)                   | [Caffe](https://github.com/tyshiwo/MemNet)                   | Dense && Recurrent       |
| SRDenseNet | [ICCV17](http://openaccess.thecvf.com/content_ICCV_2017/papers/Tong_Image_Super-Resolution_Using_ICCV_2017_paper.pdf) | [PyTorch](https://github.com/wxywhu/SRDenseNet-pytorch)      | Dense                    |
| SPMC       | [ICCV17](https://arxiv.org/abs/1704.02738)                   | [Tensorflow](https://github.com/jiangsutx/SPMC_VideoSR)      | VideoSR                  |
| EnhanceNet | [ICCV17](https://arxiv.org/abs/1612.07919)                   | [TensorFlow](https://github.com/msmsajjadi/EnhanceNet-Code)  | Perceptual Loss          |
| PRSR       | [ICCV17](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dahl_Pixel_Recursive_Super_ICCV_2017_paper.pdf) | [TensorFlow](https://github.com/nilboy/pixel-recursive-super-resolution) | an extension of PixelCNN |
| AffGAN     | [ICLR17](https://arxiv.org/pdf/1610.04490.pdf)               | -                                                            |                          |

#### 2018

| Model       | Published                                                    | Code                                                         | Keywords                                   |
| ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ |
| MS-LapSRN   | [TPAMI18](https://ieeexplore.ieee.org/document/8434354)      | [Matlab](https://github.com/phoenix104104/LapSRN)            | Fast LapSRN                                |
| DCSCN       | [arXiv](https://arxiv.org/abs/1707.05425)                    | [Tensorflow](https://github.com/jiny2001/dcscn-super-resolution) |                                            |
| IDN         | [CVPR18](https://arxiv.org/abs/1803.09454)                   | [Caffe](https://github.com/Zheng222/IDN-Caffe)               | Fast                                       |
| DSRN        | [CVPR18](http://openaccess.thecvf.com/content_cvpr_2018/papers/Han_Image_Super-Resolution_via_CVPR_2018_paper.pdf) | [TensorFlow](https://github.com/WeiHan3/dsrn/tree/db21d57dfab57de3608f0372e749c6488b6b305d) | Dual state && Recurrent                    |
| RDN         | [CVPR18](https://arxiv.org/abs/1802.08797)                   | [Torch](https://github.com/yulunzhang/RDN)                   | Deep && BI-BD-DN && Dense                  |
| SRMD        | [CVPR18](https://arxiv.org/abs/1712.06116)                   | [Matlab](https://github.com/cszn/SRMD)                       | Denoise/Deblur/SR                          |
| xUnit       | [CVPR18](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kligvasser_xUnit_Learning_a_CVPR_2018_paper.pdf) | [PyTorch](https://github.com/kligvasser/xUnit)               | Spatial Activation Function                |
| DBPN        | [CVPR18](https://arxiv.org/abs/1803.02735)                   | [PyTorch](https://github.com/alterzero/DBPN-Pytorch)         | NTIRE18 Champion                           |
| WDSR        | [CVPR18](https://arxiv.org/abs/1808.08718)                   | [PyTorch](https://github.com/JiahuiYu/wdsr_ntire2018)，[TensorFlow](https://github.com/ychfan/tf_estimator_barebone/blob/master/docs/super_resolution.md) | NTIRE18 Champion                           |
| ProSRN      | [CVPR18](https://arxiv.org/abs/1804.02900)                   | [PyTorch](https://github.com/fperazzi/proSR)                 | NTIRE18 && Progressive                     |
| ZSSR        | [CVPR18](http://www.wisdom.weizmann.ac.il/~vision/zssr/)     | [Tensorflow](https://github.com/assafshocher/ZSSR)           | Zero-shot                                  |
| FRVSR       | [CVPR18](https://arxiv.org/abs/1801.04590)                   | [PDF](https://github.com/msmsajjadi/FRVSR)                   | VideoSR                                    |
| DUF         | [CVPR18](http://openaccess.thecvf.com/content_cvpr_2018/papers/Jo_Deep_Video_Super-Resolution_CVPR_2018_paper.pdf) | [Tensorflow](https://github.com/yhjo09/VSR-DUF)              | VideoSR                                    |
| TDAN        | [arXiv](https://arxiv.org/pdf/1812.02898.pdf)                | -                                                            | VideoSR && Deformable Align                |
| SFTGAN      | [CVPR18](https://arxiv.org/abs/1804.02815)                   | [PyTorch](https://github.com/xinntao/SFTGAN)                 |                                            |
| CARN        | [ECCV18](https://arxiv.org/abs/1803.08664)                   | [PyTorch](https://github.com/nmhkahn/CARN-pytorch)           | Lightweight                                |
| RCAN        | [ECCV18](https://arxiv.org/abs/1807.02758)                   | [PyTorch](https://github.com/yulunzhang/RCAN)                | Deep && BI-BD-DN && Channel-wise Attention |
| MSRN        | [ECCV18](http://openaccess.thecvf.com/content_ECCV_2018/papers/Juncheng_Li_Multi-scale_Residual_Network_ECCV_2018_paper.pdf) | [PyTorch](https://github.com/MIVRC/MSRN-PyTorch)             | Multi-scale                                |
| SRFeat      | [ECCV18](http://openaccess.thecvf.com/content_ECCV_2018/papers/Seong-Jin_Park_SRFeat_Single_Image_ECCV_2018_paper.pdf) | [Tensorflow](https://github.com/HyeongseokSon1/SRFeat)       | GAN                                        |
| TSRN        | [ECCV18](https://arxiv.org/pdf/1808.00043.pdf)               | [Pytorch](https://github.com/waleedgondal/Texture-based-Super-Resolution-Network) |                                            |
| ESRGAN      | [ECCV18](https://arxiv.org/abs/1809.00219)                   | [PyTorch](https://github.com/xinntao/ESRGAN)                 | PRIM18 region 3 Champion                   |
| EPSR        | [ECCV18](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Vasu_Analyzing_Perception-Distortion_Tradeoff_using_Enhanced_Perceptual_Super-resolution_Network_ECCVW_2018_paper.pdf) | [PyTorch](https://github.com/subeeshvasu/2018_subeesh_epsr_eccvw) | PRIM18 region 1 Champion                   |
| PESR        | [ECCV18](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Vu_Perception-Enhanced_Image_Super-Resolution_via_Relativistic_Generative_Adversarial_Networks_ECCVW_2018_paper.pdf) | [PyTorch](https://github.com/thangvubk/PESR)                 | ECCV18 workshop                            |
| FEQE        | [ECCV18](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Vu_Fast_and_Efficient_Image_Quality_Enhancement_via_Desubpixel_Convolutional_Neural_ECCVW_2018_paper.pdf) | [Tensorflow](https://github.com/thangvubk/FEQE)              | Fast                                       |
| NLRN        | [NIPS18](https://papers.nips.cc/paper/7439-non-local-recurrent-network-for-image-restoration.pdf) | [Tensorflow](https://github.com/Ding-Liu/NLRN)               | Non-local, Recurrent                       |
| SRCliqueNet | [NIPS18](https://arxiv.org/abs/1809.04508)                   | -                                                            | Wavelet                                    |

#### 2019

| Model                  | Published                                                    | Code                                                         | Keywords                                                     |
| ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| CBDNet                 | [arXiv](https://arxiv.org/abs/1807.04686)                    | [Matlab](https://github.com/GuoShi28/CBDNet)                 | Blind-denoise                                                |
| TecoGAN                | [arXiv](http://arxiv.org/abs/1811.09393)                     | [Tensorflow](https://github.com/thunil/TecoGAN)              | VideoSR GAN                                                  |
| RBPN                   | [CVPR19](https://arxiv.org/abs/1903.10128)                   | [PyTorch](https://github.com/alterzero/RBPN-PyTorch)         | VideoSR                                                      |
| SRFBN                  | [CVPR19](https://arxiv.org/abs/1903.09814)                   | [PyTorch](https://github.com/Paper99/SRFBN_CVPR19)           | Feedback && Recurrent                                        |
| AdaFM                  | [CVPR19](https://arxiv.org/pdf/1904.08118.pdf)               | [PyTorch](https://github.com/hejingwenhejingwen/AdaFM)       | Adaptive Feature Modification Layers                         |
| MoreMNAS               | [arXiv](https://arxiv.org/pdf/1901.01074.pdf)                | -                                                            | Lightweight，NAS                                             |
| FALSR                  | [arXiv](https://arxiv.org/pdf/1901.07261.pdf)                | [TensorFlow](https://ieeexplore.ieee.org/document/8434354)   | Lightweight，NAS                                             |
| Meta-SR                | [CVPR19](https://arxiv.org/pdf/1903.00875.pdf)               | [PyTorch](https://github.com/XuecaiHu/Meta-SR-Pytorch)       | Arbitrary Magnification                                      |
| AWSRN                  | [arXiv](https://arxiv.org/abs/1904.02358)                    | [PyTorch](https://github.com/ChaofWang/AWSRN)                | Lightweight                                                  |
| OISR                   | [CVPR19](http://openaccess.thecvf.com/content_CVPR_2019/papers/He_ODE-Inspired_Network_Design_for_Single_Image_Super-Resolution_CVPR_2019_paper.pdf) | [PyTorch](https://github.com/HolmesShuan/OISR-PyTorch)       | ODE-inspired Network                                         |
| DPSR                   | [CVPR19](https://arxiv.org/pdf/1903.12529.pdf)               | [PyTorch](https://github.com/cszn/DPSR)                      |                                                              |
| DNI                    | [CVPR19](https://arxiv.org/pdf/1811.10515.pdf)               | [PyTorch](https://github.com/xinntao/DNI)                    |                                                              |
| MAANet                 | [arXiv](https://arxiv.org/abs/1904.06252)                    |                                                              | Multi-view Aware Attention                                   |
| RNAN                   | [ICLR19](https://openreview.net/pdf?id=HkeGhoA5FX)           | [PyTorch](https://github.com/yulunzhang/RNAN)                | Residual Non-local Attention                                 |
| FSTRN                  | [CVPR19](https://arxiv.org/pdf/1904.02870.pdf)               | -                                                            | **VideoSR**, fast spatio-temporal residual block             |
| MsDNN                  | [arXiv](https://arxiv.org/pdf/1904.10698.pdf)                | [TensorFlow](https://github.com/shangqigao/gsq-image-SR)     | NTIRE19 real SR 21th place                                   |
| SAN                    | [CVPR19](http://www4.comp.polyu.edu.hk/~cslzhang/paper/CVPR19-SAN.pdf) | [Pytorch](https://github.com/daitao/SAN)                     | Second-order Attention, cvpr19 oral                          |
| EDVR                   | [CVPRW19](https://arxiv.org/pdf/1905.02716.pdf)              | [Pytorch](https://github.com/xinntao/EDVR)                   | **Video**, NTIRE19 video restoration and enhancement champions |
| Ensemble for VSR       | [CVPRW19](https://arxiv.org/pdf/1905.02462.pdf)              | -                                                            | **VideoSR**, NTIRE19 video SR 2nd place                      |
| TENet                  | [arXiv](https://arxiv.org/pdf/1905.02538.pdf)                | [Pytorch](https://github.com/guochengqian/TENet)             | a Joint Solution for Demosaicking, Denoising and Super-Resolution |
| MCAN                   | [arXiv](https://arxiv.org/pdf/1903.07949.pdf)                | [Pytorch](https://github.com/macn3388/MCAN)                  | Matrix-in-matrix CAN, Lightweight                            |
| IKC&SFTMD              | [CVPR19](https://arxiv.org/pdf/1904.03377.pdf)               | -                                                            | Blind Super-Resolution                                       |
| SRNTT                  | [CVPR19](https://arxiv.org/pdf/1903.00834.pdf)               | [TensorFlow](https://github.com/ZZUTK/SRNTT)                 | Neural Texture Transfer                                      |
| RawSR                  | [CVPR19](https://arxiv.org/pdf/1905.12156.pdf)               | [TensorFlow](https://drive.google.com/file/d/1yvCceNAgt4UsxZXahPFBkuL1JXyfgr8B/view) | Real Scene Super-Resolution, Raw Images                      |
| resLF                  | [CVPR19](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Residual_Networks_for_Light_Field_Image_Super-Resolution_CVPR_2019_paper.pdf) |                                                              | Light field                                                  |
| CameraSR               | [CVPR19](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Camera_Lens_Super-Resolution_CVPR_2019_paper.pdf) |                                                              | realistic image SR                                           |
| ORDSR                  | [TIP](https://arxiv.org/pdf/1904.10082.pdf)                  | [model](https://github.com/tT0NG/ORDSR)                      | DCT domain SR                                                |
| U-Net                  | [CVPRW19](https://arxiv.org/pdf/1906.04809.pdf)              |                                                              | NTIRE19 real SR 2nd place, U-Net,MixUp,Synthesis             |
| DRLN                   | [arxiv](https://arxiv.org/pdf/1906.12021.pdf)                |                                                              | Densely Residual Laplacian Super-Resolution                  |
| EDRN                   | [CVPRW19](http://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Cheng_Encoder-Decoder_Residual_Network_for_Real_Super-Resolution_CVPRW_2019_paper.pdf) | [Pytorch](https://github.com/yyknight/NTIRE2019_EDRN)        | NTIRE19 real SR 9th places                                   |
| FC2N                   | [arXiv](https://arxiv.org/pdf/1907.03221.pdf)                |                                                              | Fully Channel-Concatenated                                   |
| GMFN                   | [BMVC2019](https://arxiv.org/pdf/1907.04253.pdf)             | [Pytorch](https://github.com/liqilei/GMFN)                   | Gated Multiple Feedback                                      |
| CNN&TV-TV Minimization | [BMVC2019](https://arxiv.org/pdf/1907.05380.pdf)             |                                                              | TV-TV Minimization                                           |
| HRAN                   | [arXiv](https://arxiv.org/pdf/1907.05514.pdf)                |                                                              | Hybrid Residual Attention Network                            |
| PPON                   | [arXiv](https://arxiv.org/pdf/1907.10399.pdf)                | [code](https://github.com/Zheng222/PPON)                     | Progressive Perception-Oriented Network                      |
| SROBB                  | [ICCV19](https://arxiv.org/pdf/1908.07222.pdf)               |                                                              | Targeted Perceptual Loss                                     |
| RankSRGAN              | [ICCV19](https://arxiv.org/pdf/1908.06382.pdf)               | [PyTorch](https://github.com/WenlongZhang0724/RankSRGAN)     | oral, rank-content loss                                      |
| s-LWSR                 | [arXiv](https://arxiv.org/pdf/1909.10774v1.pdf)              |                                                              | Lightweight Network                                          |
| ESRN                   | [AAAI2020](https://arxiv.org/pdf/1909.11409v1.pdf)           |                                                              |                                                              |
| MGAN                   | [arXiv](https://arxiv.org/pdf/1909.11937v1.pdf)              |                                                              |                                                              |
| IMDN                   | [ACM MM 2019](https://arxiv.org/pdf/1909.11856v1.pdf)        | [PyTorch](https://github.com/Zheng222/IMDN)                  | Lightweight Network                                          |
| WDST                   | [arXiv](https://arxiv.org/pdf/1910.04074.pdf)                |                                                              | perception-distortion tradeoff                               |
| HBPN                   | [arXiv](https://arxiv.org/pdf/1906.06874.pdf)                | [PyTorch](https://github.com/Holmes-Alan/HBPN)               |                                                              |
| ABPN                   | [arXiv](https://arxiv.org/pdf/1910.04476.pdf)                | [PyTorch](https://github.com/Holmes-Alan/ABPN)               |                                                              |
| PFNL                   | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yi_Progressive_Fusion_Video_Super-Resolution_Network_via_Exploiting_Non-Local_Spatio-Temporal_Correlations_ICCV_2019_paper.pdf) | [Tensorflow](https://github.com/psychopa4/PFNL)              | VideoSR oral,Non-Local Spatio-Temporal Correlations          |
| EBRN                   | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Qiu_Embedded_Block_Residual_Network_A_Recursive_Restoration_Model_for_Single-Image_ICCV_2019_paper.pdf) |                                                              | Embedded Block Residual Network                              |
| Deep SR-ITM            | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Deep_SR-ITM_Joint_Learning_of_Super-Resolution_and_Inverse_Tone-Mapping_for_ICCV_2019_paper.pdf) | [matlab](https://github.com/sooyekim/Deep-SR-ITM)            | SDR to HDR, 4K SR                                            |
| Feature SR             | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Noh_Better_to_Follow_Follow_to_Be_Better_Towards_Precise_Supervision_ICCV_2019_paper.pdf) |                                                              | Super-Resolution for Small Object Detection                  |
| STFAN                  | [ICCV19](https://arxiv.org/pdf/1904.12257.pdf)               | [PyTorch](https://github.com/sczhou/STFAN)                   | Video Deblurring                                             |
| KMSR                   | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Kernel_Modeling_Super-Resolution_on_Real_Low-Resolution_Images_ICCV_2019_paper.pdf) | [PyTorch](https://github.com/IVRL/Kernel-Modeling-Super-Resolution) | GAN for blur-kernel estimation                               |
| JDSR                   | [arXiv](https://arxiv.org/pdf/1911.03558v1.pdf)              |                                                              | Demosaicing and SR                                           |
| CFSNet                 | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_CFSNet_Toward_a_Controllable_Feature_Space_for_Image_Restoration_ICCV_2019_paper.pdf) | [PyTorch](https://github.com/qibao77/CFSNet)                 | Controllable Feature                                         |
| FSRnet                 | [ICCV19](http://openaccess.thecvf.com/content_ICCV_2019/papers/Gu_Fast_Image_Restoration_With_Multi-Bin_Trainable_Linear_Units_ICCV_2019_paper.pdf) |                                                              | Multi-bin Trainable Linear Units                             |
| SAM+VAM                | [ICCVW19](https://arxiv.org/pdf/1911.08711.pdf)              |                                                              |                                                              |

#### 2020

| Model      | Published                                                    | Code                                                | Keywords                             |
| ---------- | ------------------------------------------------------------ | --------------------------------------------------- | ------------------------------------ |
| FFA-Net    | [AAAI2020](https://arxiv.org/pdf/1911.07559.pdf)             | [Pytorch](https://github.com/zhilin007/FFA-Net)     | Image Dehazing                       |
| RC-Net     | [arXiv](https://arxiv.org/pdf/1910.08853.pdf)                | [matlab](https://github.com/cswin/RC-Nets)          | Image Denoising and Super-resolution |
| IR-NAS     | [arXiv](https://arxiv.org/pdf/1909.08228v2.pdf)              |                                                     | NAS                                  |
| SISR-CA-OA | [arXiv](https://arxiv.org/pdf/1912.04016v1.pdf)              |                                                     | Fast &Channel-Attention              |
| DSGAN      | [arXiv](https://arxiv.org/pdf/1911.07850v1.pdf)              |                                                     | Real-World Super-Resolution          |
| ADCSR      | [arXiv](https://arxiv.org/pdf/1912.08002v1.pdf)              |                                                     |                                      |
| SCN        | [AAAI2020](https://arxiv.org/pdf/1912.09028.pdf)             |                                                     | Scale-wise Convolution               |
| MLSR       | [arXiv](https://arxiv.org/pdf/2001.02905.pdf)                |                                                     | Self-supervised                      |
| GAN-based  | [arXiv](https://arxiv.org/pdf/2001.02381.pdf)                |                                                     | Real-world SR                        |
| ESRGAN+    | [arXiv](https://arxiv.org/abs/2001.08073)                    |                                                     |                                      |
| SOF-VSR    | [TIP](https://arxiv.org/abs/2001.02129) [ACCV](https://arxiv.org/abs/1809.08573) | [Pytorch](https://github.com/LongguangWang/SOF-VSR) | Video SR                             |

### Super Resolution Survey

[1] Wenming Yang, Xuechen Zhang, Yapeng Tian, Wei Wang, Jing-Hao Xue. Deep Learning for Single Image Super-Resolution: A Brief Review. arxiv, 2018. [paper](https://arxiv.org/pdf/1808.03344.pdf)

[2]Saeed Anwar, Salman Khan, Nick Barnes. A Deep Journey into Super-resolution: A survey. arxiv, 2019.[paper](https://arxiv.org/pdf/1904.07523.pdf)

[3]Wang, Z., Chen, J., & Hoi, S. C. (2019). Deep learning for image super-resolution: A survey. arXiv preprint arXiv:1902.06068.[paper](https://arxiv.org/abs/1902.06068)

## Workshop for SR

NTIRE17 [papers](http://openaccess.thecvf.com/CVPR2017_workshops/CVPR2017_W12.py)

NTIRE18 [papers](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W13.py)

PIRM18 [web](https://pirm2018.org/)

NTIRE19 [papers](http://openaccess.thecvf.com/CVPR2019_workshops/CVPR2019_NTIRE.py)

AIM19 [papers](http://openaccess.thecvf.com/ICCV2019_workshops/ICCV2019_AIM.py)

## Excellent  Personal Website

[Manri Cheon](https://manricheon.github.io/)

[Yulun Zhang](http://yulunzhang.com/)

[Yapeng Tian](http://yapengtian.org/)

[Xintao Wang](https://xinntao.github.io/)


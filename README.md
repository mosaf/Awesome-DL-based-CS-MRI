# <p align=center>`Awesome Deep learning-based compressed sensing-MRI`</p> # 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

:fire::fire: This is a collection of awesome articles about deep learning in MRI reconstruction:fire::fire:

- Our survey paper on MedIA: [Deep learning-based compressed sensing magnetic resonance imaging: a systematic revie](coming soon) :heart:
- Our survey paper on arXiv: [Deep learning-based compressed sensing magnetic resonance imaging: a systematic revie](coming soon) :heart:

#### Citation
```python
@article{safari2024dlcsmri,
  title={Deep learning-based compressed sensing magnetic resonance imaging: a systematic review},
  author={Safari, Mojtaba and Eidex, Zach and ...  and Yang, Xiaofeng},
  journal={Soon},
  pages={Soon},
  year={Soon},
  publisher={Soon}
}
```

## Updates

[//]: # (- **Fourth release:** Coming soon!)

[//]: # (- We have now achieved more than 1K stars 🌟—thank you community for your support! If you're interested in contributing to this repository, please don't hesitate to send me a message. Thank you!)

[//]: # (- Check out our new paper accepted in MICCAI 2023 PRIME Workshop: [DermoSegDiff: A Boundary-aware Segmentation Diffusion Model for Skin Lesion Delineation]&#40;https://arxiv.org/abs/2308.02959&#41; 🥳)

[//]: # (- **Third release:** June 3, 2023)

[//]: # (- :sunglasses: April 8, 2023: Our paper is accepted for publication in the **Medical Image Analysis Journal &#40;IF: 13.83&#41;** :sunglasses:)

[//]: # (- **Second release:** March 29, 2023)
- **First release:** April 14, 2024

## Contents

[//]: # (- [Survey Papers]&#40;#survey-papers&#41;)

- [Papers](#papers)
  - [End-to-end](#End-to-end)
  - [Unroll models](#unroll-models)
    - [Unroll optimization](#Unroll-optimization)
    - [DC layers](#DC-layer)
  - [Self-supervised](#Self-supervise)
  - [Federated learning](#Federated-Learning)
- [Dataset](#dataset)


## Papers

### End-to-end


**NPB-REC: A non-parametric Bayesian deep-learning approach for undersampled MRI reconstruction with uncertainty estimation** \
*Khawaled, Samah, and Moti Freiman* \
[05 February 2024] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1016/j.artmed.2024.102798)] [[Github](https://github.com/samahkh/NPB-REC)]



**High-Frequency Space Diffusion Models for Accelerated MRI** \
*Cao, Chentao, Zhuo-Xu Cui, Yue Wang, Shaonan Liu, Taijin Chen, Hairong Zheng, Dong Liang, and Yanjie Zhu* \
[09 January 2024] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2024.3351702)] [[Github](https://github.com/Aboriginer/HFS-SDE)]


**MA-RECON: Mask-aware deep-neural-network for robust fast MRI k-space interpolation** \
*Avidan, Nitzan, and Moti Freiman* \
[29 November 2023] [Comput. Methods Programs Biomed. Update.]<br>
[[Paper](https://doi.org/10.1016/j.cmpb.2023.107942)] [[Github](https://github.com/nitzanavidan/PD_Recon)]


**High-resolution spiral real-time cardiac cine imaging with deep learning-based rapid image reconstruction and quantification** \
*Wang, Junyu, Marina Awad, Ruixi Zhou, Zhixing Wang, Xitong Wang, Xue Feng, Yang Yang, Craig Meyer, Christopher M. Kramer, and Michael Salerno* \
[05 November 2023] [MICCAI]<br>
[[Paper](https://doi.org/10.1002/nbm.5051)]


**Highly-accelerated CEST MRI using frequency-offset-dependent k-space sampling and deep-learning reconstruction** \
*Xu, Jianping, Tao Zu, Yi‐Cheng Hsu, Xiaoli Wang, Kannie WY Chan, and Yi Zhang* \
[22 October 2023] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29889)] [[Github](https://github.com/easyCEST/CEST-PSnetwork)]


**A Deep Learning-Based Integrated Framework for Quality-Aware Undersampled Cine Cardiac MRI Reconstruction and Analysis** \
*Machado, Inês and Puyol-Antón, Esther and Hammernik, Kerstin and Cruz, Gastão and Ugurlu, Devran and Olakorede, Ihsane and Oksuz, Ilkay and Ruijsink, Bram and Castelo-Branco, Miguel and Young, Alistair and Prieto, Claudia and Schnabel, Julia and King, Andrew* \
[02 October 2023] [TMI]<br>
[[Paper](https://doi.org/10.1109/TBME.2023.3321431)]





**Learning ADC maps from accelerated radial k-space diffusion-weighted MRI in mice using a deep CNN-transformer model** \
*Li, Yuemeng, Miguel Romanello Joaquim, Stephen Pickup, Hee Kwon Song, Rong Zhou, and Yong Fan* \
[20 August 2023] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29833)] [[Github](https://github.com/ymli39/DeepADC-Net-Learning-Apparent-Diffusion-Coefficient-Maps)]



**Noise2Recon: Enabling SNR-robust MRI reconstruction with semi-supervised and self-supervised learning** \
*Desai, Arjun D., Batu M. Ozturkler, Christopher M. Sandino, Robert Boutin, Marc Willis, Shreyas Vasanawala, Brian A. Hargreaves, Christopher Ré, John M. Pauly, and Akshay S. Chaudhari* \
[10 July 2023] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29759)] [[Github](https://github.com/ad12/meddlr)]


**Accelerated Cardiac MRI Cine with Use of Resolution Enhancement Generative Adversarial Inline Neural Network** \
*Siyeop Yoon, Shiro Nakamori, Amine Amyar, Salah Assana, Julia Cirillo, Manuel A. Morales, Kelvin Chow, Xiaoming Bi, Patrick Pierce, Beth Goddu, Jennifer Rodriguez, Long H. Ngo, Warren J. Manning, and Reza Nezafat* \
[30 May 2023] [Radiology]<br>
[[Paper](https://doi.org/10.1148/radiol.222878)]


**Dual-domain accelerated MRI reconstruction using transformers with learning-based undersampling** \
*Hong, Guan Qiu, Yuan Tao Wei, William AW Morley, Matthew Wan, Alexander J. Mertens, Yang Su, and Hai-Ling Margaret Cheng* \
[23 February 2023] [CMIG]<br>
[[Paper](https://doi.org/10.1016/j.compmedimag.2023.102206)]


**Hierarchical Perception Adversarial Learning Framework for Compressed Sensing MRI** \
*Z. Gao, Y. Guo, J. Zhang, T. Zeng and G. Yang* \
[30 January 2023] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2023.3240862)] 


**Accelerated cardiac diffusion tensor imaging using deep neural network** \
*Liu, Shaonan, Yuanyuan Liu, Xi Xu, Rui Chen, Dong Liang, Qiyu Jin, Hui Liu, Guoqing Chen, and Yanjie Zhu* \
[05 January 2023] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/acaa86)]





**SwinGAN: A dual-domain Swin Transformer-based generative adversarial network for MRI reconstruction** \
*Zhao, Xiang, Tiejun Yang, Bingjie Li, and Xin Zhang* \
[31 December 2022] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2022.106513)] [[Github](https://github.com/learnerzx/SwinGAN)]

**Improving accelerated MRI by deep learning with sparsified complex data** \
*Jin, Zhaoyang, and Qing‐San Xiang* \
[08 December 2022] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29556)]

**SuperMAP: Deep ultrafast MR relaxometry with joint spatiotemporal undersampling** \
*Li, Hongyu, Mingrui Yang, Jee Hun Kim, Chaoyi Zhang, Ruiying Liu, Peizhou Huang, Dong Liang, Xiaoliang Zhang, Xiaojuan Li, and Leslie Ying* \
[21 September 2022] [Magn. Reson. Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29411)] 

**Signal intensity informed multi-coil encoding operator for physics-guided deep learning reconstruction of highly accelerated myocardial perfusion CMR** \
*Demirel, Omer Burak, Burhaneddin Yaman, Chetan Shenoy, Steen Moeller, Sebastian Weingärtner, and Mehmet Akçakaya* \
[21 September 2022] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29453)] [[Github](https://github.com/obdemirel/SIIM)]


**Deep learning for fast low-field MRI acquisitions** \
*Ayde, Reina, Tobias Senft, Najat Salameh, and Mathieu Sarracanie* \
[06 July 2022] [Sci. Rep.]<br>
[[Paper](https://doi.org/10.1038/s41598-022-14039-7)] 


**DBGAN: A dual-branch generative adversarial network for undersampled MRI reconstruction** \
*Liu, Xianzhe, Hongwei Du, Jinzhang Xu, and Bensheng Qiu* \
[24 March 2022] [Magn. Reson. Imaging]<br>
[[Paper](https://doi.org/10.1016/j.mri.2022.03.003)] 




**Adaptive convolutional neural networks for accelerating magnetic resonance imaging via k-space data interpolation** \
*Du, Tianming, Honggang Zhang, Yuemeng Li, Stephen Pickup, Mark Rosen, Rong Zhou, Hee Kwon Song, and Yong Fan* \
[16 May 2021] [Med. Image Anal.]<br>
[[Paper](https://doi.org/10.1016/j.media.2021.102098)] [[Github](https://gitlab.com/qgpmztmf/acnn-k-space)]



**Magnetic resonance parameter mapping using model-guided self-supervised deep learning** \
*Liu, Fang, Richard Kijowski, Georges El Fakhri, and Li Feng* \
[19 January 2021] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.28659)]


**Reconstruction of multicontrast MR images through deep learning** \
*Do, Won‐Joon, Sunghun Seo, Yoseob Han, Jong Chul Ye, Seung Hong Choi, and Sung‐Hong Park* \
[28 January 2020] [Med. Phys.]<br>
[[Paper](https://doi.org/10.1002/mp.14006)] 

 
**_k_-Space Deep Learning for Accelerated MRI** \
*Han, Yoseo, Leonard Sunwoo, and Jong Chul Ye* \
[05 July 2019] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2019.2927101)] [[Github](https://github.com/hanyoseob/k-space-deep-learning)]



**Deep learning for undersampled MRI reconstruction** \
*Hyun, Chang Min, Hwa Pyung Kim, Sung Min Lee, Sungchul Lee, and Jin Keun Seo* \
[25 June 2018] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/aac71a)] 


**Ultra-Fast T2-Weighted MR Reconstruction Using Complementary T1-Weighted Information** \
*Xiang, Lei, Yong Chen, Weitang Chang, Yiqiang Zhan, Weili Lin, Qian Wang, and Dinggang Shen* \
[26 September 2018] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-030-00928-1_25)]


**Accelerating T2 mapping of the brain by integrating deep learning priors with low-rank and sparse modeling** \
*Meng, Ziyu, Rong Guo, Yudu Li, Yue Guan, Tianyao Wang, Yibo Zhao, Brad Sutton, Yao Li, and Zhi‐Pei Liang* \
[29 September 2020] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.28526)]










---
### Unroll model
#### Unroll optimization

**A Deep Framework Assembling Principled Modules for CS-MRI: Unrolling Perspective, Convergence Behaviors, and Practical Modeling** \
*Liu, Risheng, Yuxi Zhang, Shichao Cheng, Zhongxuan Luo, and Xin Fan* \
[04 August 2020] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2020.3014193)] [[GitHub](-)] 

---

#### DC layer

**DCT-net: Dual-domain cross-fusion transformer network for MRI reconstruction** \
*Wang, Bin, Yusheng Lian, Xingchuang Xiong, Han Zhou, Zilong Liu, and Xiaohao Zhou* \
[17 January 2024] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2024.01.007)]

**DSMENet: Detail and Structure Mutually Enhancing Network for under-sampled MRI reconstruction** \
*Wang, Yueze, Yanwei Pang, and Chuan Tong* \
[13 October 2022] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2022.106204)]
---

#### Self-supervise

**DC-SiamNet: Deep contrastive Siamese network for self-supervised MRI reconstruction.** \
*Yan, Yanghui, Tiejun Yang, Xiang Zhao, Chunxia Jiao, Aolin Yang, and Jianyu Miao* \
[28 October 2023] [Computers in Biology and Medicine] \
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107619)] [[GitHub](-)]

---

### Federated Learning

**Adaptive channel-modulated personalized federated learning for magnetic resonance image reconstruction** \
*Lyu, Jun, Yapeng Tian, Qing Cai, Chengyan Wang, and Jing Qin* \
[16 August 2023] [Computers in Biology and Medicine] \
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107330)] [[GitHub](https://github.com/)]

**Federated End-to-End Unrolled Models for Magnetic Resonance Image Reconstruction** \
*Levac, Brett R., Marius Arvinte, and Jonathan I. Tamir* \
[16 March 2023] [Bioengineering] \
[[Paper](https://doi.org/10.3390/bioengineering10030364)] [[GitHub](https://github.com/utcsilab/Unrolled_FedLrn)]


**Federated Learning of Generative Image Priors for MRI Reconstruction** \
*Elmas, Gokberk, Salman UH Dar, Yilmaz Korkmaz, Emir Ceyani, Burak Susam, Muzaffer Ozbey, Salman Avestimehr, and Tolga Çukur* \
[09 November 2022] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2022.3220757)] [[Github](https://github.com/icon-lab/FedGIMP)]


**Specificity-Preserving Federated Learning for MR Image Reconstruction** \
*Feng, Chun-Mei, Yunlu Yan, Shanshan Wang, Yong Xu, Ling Shao, and Huazhu Fu* \
[26 August 2022] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2022.3202106)] [[Github](https://github.com/chunmeifeng/FedMRI/tree/main)]



**Multi-institutional Collaborations for Improving Deep Learning-based Magnetic Resonance Image Reconstruction Using Federated Learning** \
*Guo, Pengfei, Puyang Wang, Jinyuan Zhou, Shanshan Jiang, and Vishal M. Patel* \
[10 March 2021] [CVPR]<br>
[[Paper](https://doi.org/10.48550/arXiv.2103.02148)] [[Github](https://github.com/guopengf/FL-MRCM)]



---
---

### Dataset

**fastMRI ....** \
*Sai Shankar Narasimhan, Shubhankar Agarwal, Oguzhan Akcin, Sujay Sanghavi, Sandeep Chinchali* \
[5th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.02682)]

Some table with imaging parameters ...


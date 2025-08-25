# <p align=center>`Awesome Deep learning-based MRI Reconstruction`</p> # 


[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/mosaf/Awesome-DL-based-CS-MRI) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)



:fire::fire: This is a collection of awesome articles about deep learning in MRI reconstruction:fire::fire:

[//]: # (- Our survey paper on MedIA: [Deep learning-based compressed sensing magnetic resonance imaging: a systematic revie]&#40;coming soon&#41; :heart:)
- Our survey paper on arXiv: [Advancing MRI Reconstruction: A Systematic Review of Deep Learning and Compressed Sensing Integration](https://arxiv.org/abs/2501.14158) :heart:


#### Citation
```python
@article{SAFARI2026108291,
title = {Advancing MRI reconstruction: A systematic review of deep learning and compressed sensing integration},
journal = {Biomedical Signal Processing and Control},
volume = {111},
pages = {108291},
year = {2026},
issn = {1746-8094},
doi = {https://doi.org/10.1016/j.bspc.2025.108291},
url = {https://www.sciencedirect.com/science/article/pii/S174680942500802X},
author = {Mojtaba Safari and Zach Eidex and Chih-Wei Chang and Richard L.J. Qiu and Xiaofeng Yang},
keywords = {Compressed sensing, Magnetic resonance imaging, MRI reconstruction, FastMRI, MRI acceleration, Deep MRI reconstruction, Accelerated MRI reconstruction},
}

arXiv
@article{safari2024fast,
      title={Advancing MRI Reconstruction: A Systematic Review of Deep Learning and Compressed Sensing Integration}, 
      author={Mojtaba Safari and Zach Eidex and Chih-Wei Chang and Richard L. J. Qiu and Xiaofeng Yang},
      year={2025},
      eprint={2501.14158},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2501.14158}, 
}
```
![Overview](./figures/overview.svg)
## Updates


- **First release:** April 14, 2024
- **Second release:** January 25, 2025
## Contents

[//]: # (- [Survey Papers]&#40;#survey-papers&#41;)

- [Tutorials](#tutorials)
- [Papers](#papers)
  - [End-to-end](#End-to-end)
  - [Unrolled models](#unrolled-model)
    - [Unrolled optimization](#Unrolled-optimization)
    - [DC layers](#DC-layer)
  - [Self-supervised](#Self-supervise)
  - [Federated learning](#Federated-Learning)
- [Dataset](#dataset)

# Tutorials
### GitHub and GoogleColab
* [**FastMRI Reconstruction examples (MATLAB)**](https://github.com/Wangzc420/FastMRI-Reconstruction-examples)
* [**MRI acquisition & image reconstruction**](https://github.com/philouc/mri_acq_recon_tutorial)
* [**MRI Reconstruction Using GRAPPA**](https://github.com/tetianadadakova/Tutorial-MRI-Reconstruction-Using-GRAPPA)
* [**Unrolled network on complex-valued data with complex-valued**](https://colab.research.google.com/github/ISMRM-MIT-CMR/CMR-DL-challenge/blob/master/tutorial_reconstruction_complex.ipynb#scrollTo=Rx0c4JCcC8OA)
* [**CMR Deep learning reconstruction**](https://ismrm-mit-cmr.github.io/CMR-DL-challenge/)


### YouTube
* [**Dynamic MRI Reconstruction**](https://www.youtube.com/watch?v=ku7yZcahciU)
* [**Deep dive into non-Cartesian reconstruction with BART**](https://www.youtube.com/watch?v=usAI5S6OPuc)
* [**Deep dive into 3D Cartesian reconstruction with BART**](https://www.youtube.com/watch?v=nBqECv531CU)


# Papers

### End-to-end

**LMO: Linear Mamba Operator for MRI Reconstruction** \
*Li, Wei and Jiang, Jiawei and Wu, Jie and Yu, Kaihao and Zheng, Jianwei* \
[2025] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_LMO_Linear_Mamba_Operator_for_MRI_Reconstruction_CVPR_2025_paper.pdf)] [[Github](https://github.com/ZhengJianwei2/LMO)] 


**DGEDDGAN: A dual-domain generator and edge-enhanced dual discriminator generative adversarial network for MRI reconstruction** \
*Qiaohong Liu, Weikun Zhang, Yuting Zhang, Xiaoxiang Han, Yuanjie Lin, Xinyu Li, Keyan Chen* \
[08 March 2025] [Magnetic Resonance Imaging]<br>
[[Paper](https://doi.org/10.1016/j.mri.2025.110381)]


**SHFormer: Dynamic spectral filtering convolutional neural network and high-pass kernel generation transformer for adaptive MRI reconstruction** \
*Sriprabha Ramanarayanan, Rahul G.S., Mohammad Al Fahim, Keerthi Ram, Ramesh Venkatesan, Mohanasankar Sivaprakasam* \
[08 March 2025] [Neural Networks]<br>
[[Paper](https://doi.org/10.1016/j.neunet.2025.107334)] [[Github](https://github.com/sriprabhar/SHFormer)] 


**Lightweight Hypercomplex MRI Reconstruction: A Generalized Kronecker Parameterized Approach** \
*Haosen Zhang, Jiahao Huang, Yinzhe Wu, Congren Dai, Fanwen Wang, Zhenxuan Zhang, and Guang Yang* \
[11 March 2025] [preprint arXiv]<br>
[[Paper](https://arxiv.org/abs/2503.05063)] 


**AutoSamp: Autoencoding k-Space Sampling via Variational Information Maximization for 3D MRI** \
*Cagan Alkan, Morteza Mardani, Congyu Liao, Zhitao Li, Shreyas S. Vasanawala, and John M. Pauly* \
[15 August 2024] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2024.3443292)] [[Github](https://github.com/alkanc/autosamp)] 



**Highly-accelerated CEST MRI using frequency-offset-dependent k-space sampling and deep-learning reconstruction** \
*Chuyu Liu, Zhongsen Li, Zhensen Chen, Benqi Zhao, Zhuozhao Zheng, and Xiaolei Song* \
[16 April 2024] [Med. Res. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.30089)]


**Paired conditional generative adversarial network for highly accelerated liver 4D MRI** \
*Di Xu, Xin Miao, Hengjie Liu, Jessica E Scholey, Wensha Yang, Mary Feng, Michael Ohliger, Hui Lin, Yi Lao, and Yang Yang* \
[17 June 2024] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ad5489)]


**DiffGAN: An adversarial diffusion model with local transformer for MRI reconstruction** \
*Xiang Zhao, Tiejun Yang, Bingjie Li, Aolin Yang, Yanghui Yan, and Chunxia Jiao* \
[15 March 2024] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2024.03.017)]


**Deep unfolding network with spatial alignment for multi-modal MRI reconstruction** \
*Hao Zhang, Qi Wang, Jun Shi, Shihui Ying, and Zhijie Wen* \
[05 February 2024] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2024.103331)]


**NPB-REC: A non-parametric Bayesian deep-learning approach for undersampled MRI reconstruction with uncertainty estimation** \
*Khawaled, Samah, and Moti Freiman* \
[05 February 2024] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1016/j.artmed.2024.102798)] [[Github](https://github.com/samahkh/NPB-REC)]


**Domain transformation learning for MR image reconstruction from dual domain input** \
*Changheun Oh, Jun-Young Chung, and Yeji Han* \
[3 February 2024] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2024.108098)][[Github](https://github.com/changheunoh/hybrid_eternet_fastmri)] 


**FEFA: Frequency Enhanced Multi-Modal MRI Reconstruction With Deep Feature Alignment** \
*Xuanmin Chen, Liyan Ma, Shihui Ying, Dinggang Shen, and Tieyong Zeng* \
[2024] [JBHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2024.3432139)] 

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


**Unsupervised MRI Reconstruction via Zero-Shot Learned Adversarial Transformers** \
*Yilmaz Korkmaz, Salman U. H. Dar, Mahmut Yurt, Muzaffer Özbey, Tolga Çukur* \
[27 January 2022] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2022.3147426)] [[Github](https://github.com/icon-lab/SLATER)]



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
### Unrolled model
#### Unrolled optimization

**Dual-Domain Self-Consistency-Enhanced Deep Unfolding Network for accelerated MRI reconstruction** \
*Zhijie Wang, Jinbao Wei, Gang Yang, Aiping Liu, Wei Wei, Bensheng Qiu, and Xun Chen* \
[5 August 2025] [Computer Methods and Programs in Biomedicine] \
[[Paper](https://doi.org/10.1016/j.cmpb.2025.108995][[Github](https://github.com/wangzj1997/DSDUN.git)]


**Unsupervised 4D-flow MRI reconstruction based on partially-independent generative modeling and complex-difference sparsity constraint** \
*Zhongsen Li, Aiqi Sun, Haining Wei, Wenxuan Chen, Chuyu Liu, Haozhong Sun, Chenlin Du, and Rui Li* \
[10 August 2025] [Medical Image Analysis] \
[[Paper](https://doi.org/10.1016/j.media.2025.103769)][[Github](https://github.com/lizs17/Unsup_4DFlow_MRI)]


**MCU-Net: A multi-prior collaborative deep unfolding network with gates-controlled spatial attention for accelerated MRI reconstruction** \
*Xiaoyu Qiao, Weisheng Li, Guofen Wang, Yuping Huang* \
[15 February 2025] [Neurocomputing] \
[[Paper](https://doi.org/10.1016/j.neucom.2025.129771)]

**Digging Deeper in Gradient for Unrolling-based Accelerated MRI Reconstruction** \
*Faming Fang, Tingting Wang, Guixu Zhang, Fang Li* \
[07 January 2025] [IEEE TPAMI] \
[[Paper](https://doi.org/10.1109/TPAMI.2025.3540218)]



**Spatial-frequency aware zero-centric residual unfolding network for MRI reconstruction** \
*Yupeng Lian, Zhiwei Liu, Jin Wang, and Shuai Lu* \
[22 January 2025] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2025.110334)]


**Progressive Divide-and-Conquer via Subsampling Decomposition for Accelerated MRI** \
*Chong Wang, Lanqing Guo, Yufei Wang, Hao Cheng, Yi Yu, Bihan Wen* \
[2024] [CVPR 2024 Highlight] \
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Progressive_Divide-and-Conquer_via_Subsampling_Decomposition_for_Accelerated_MRI_CVPR_2024_paper.html)][[Github](https://github.com/ChongWang1024/PDAC)]

**An improved low-rank plus sparse unrolling network method for dynamic magnetic resonance imaging** \
*Marc Vornehm, Jens Wetzl, Daniel Giese, Florian Fürnrohr, Jianing Pang, Kelvin Chow, Rolf Gebker, Rizwan Ahmad, and Florian Knoll* \
[28 November 2024] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.17501)]



**CineVN: Variational network reconstruction for rapid functional cardiac cine MRI** \
*Marc Vornehm, Jens Wetzl, Daniel Giese, Florian Fürnrohr, Jianing Pang, Kelvin Chow, Rolf Gebker, Rizwan Ahmad, and Florian Knoll* \
[28 October 2024] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.30260)] [[Github](https://github.com/marcvornehm/CineVN)]

**Adaptive Knowledge Distillation for High-Quality Unsupervised MRI Reconstruction With Model-Driven Priors** \
*Xiaoyu Qiao, Weisheng Li, Yuping Huang and Lijian Yang* \
[6 June 2024] [J-HBI] \
[[Paper](https://doi.org/10.1109/JBHI.2024.3365784 )] [[Github](https://github.com/BITwzl/unsupervised_mri_reconstruction)]


**Score-based Generative Priors Guided Model-driven Network for MRI Reconstruction** \
*Xiaoyu Qiao, Weisheng Li, Yuping Huang and Lijian Yang* \
[5 May 2024] [preprint arXiv] \
[[Paper](https://arxiv.org/pdf/2405.02958)] 

**A Collaborative Model-driven Network for MRI Reconstruction** \
*Xiaoyu Qiao, Weisheng Lia, Guofen Wan, and Yuping Huang* \
[05 May 2024] [preprint arXiv] \
[[Paper](https://arxiv.org/pdf/2402.03383v2)] 


**Feasibility of Artificial Intelligence Constrained Compressed SENSE Accelerated 3D Isotropic T1 VISTA Sequence For Vessel Wall MR Imaging: Exploring the Potential of Higher Acceleration Factors Compared to Traditional Compressed SENSE** \
*Yue Ma, Mengmeng Wang, Yuting Qiao, Yafei Wen, Yi Zhu, Ke Jiang, Jianxiu Lian, Dan Tong* \
[04 March 2024] [Academic Radiology] \
[[Paper](https://doi.org/10.1016/j.acra.2024.03.041)] 


**Improving quantitative MRI using self-supervised deep learning with model reinforcement: Demonstration for rapid T1 mapping** \
*Wanyu Bian, Albert Jang, and Fang Liu* \
[11 February 2024] [Med. Res. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.30045)]




**Ferumoxytol-Enhanced Cardiac Cine MRI Reconstruction Using a Variable-Splitting Spatiotemporal Network** \
*Chang Gao, Zhengyang Ming, Kim-Lien Nguyen, Jianing Pang, Arash Bedayat, Brian M. Dale, Xiaodong Zhong, and J. Paul Finn* \
[05 February 2024] [JMRI]<br>
[[Paper](https://doi.org/10.1002/jmri.29295)]

**A Faithful Deep Sensitivity Estimation for Accelerated Magnetic Resonance Imaging** \
*Wang, Zi, Haoming Fang, Chen Qian, Boxuan Shi, Lijun Bao, Liuhong Zhu, Jianjun Zhou, and Xiaobo Qu* \
[05 February 2024] [J-BHI] \
[[Paper](https://doi.org/10.1109/JBHI.2024.3360128)] 

**Predictive uncertainty in deep learning–based MR image reconstruction using deep ensembles: Evaluation on the fastMRI data set** \
*Thomas Küstner, Kerstin Hammernik, Daniel Rueckert, Tobias Hepp, Sergios Gatidis* \
[28 January 2024] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.30030)]  [[Github](https://github.com/midas-tum/recon_uncertainty)]

**On retrospective k-space subsampling schemes for deep MRI reconstruction** \
*George Yiasemis, Clara I. Sánchez, Jan-Jakob Sonke, and Jonas Teuwen* \
[04 January 2024] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2023.12.012)] 



**Radial magnetic resonance image reconstruction with a deep unrolled projected fast iterative soft-thresholding network** \
*Biao Qu, Jialue Zhang, Taishan Kang, Jianzhong Lin, Meijin Lin, Huajun She, Qingxia Wu, Meiyun Wang, and Gaofeng Zheng * \
[19 November 2023] [Computers in Biology and Medicine] \
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107707)] 



**Accelerating CEST imaging using a model-based deep neural network with synthetic training data** \
*Xu, Jianping, Tao Zu, Yi‐Cheng Hsu, Xiaoli Wang, Kannie WY Chan, and Yi Zhang* \
[22 October 2023] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.29889)] [[Github](https://github.com/YiZhangMRI/CEST-VN)]


**Joint Cross-Attention Network With Deep Modality Prior for Fast MRI Reconstruction** \
*Kaicong Sun, Qian Wang, and Dinggang Shen* \
[11 September 2023] [TMI] \
[[Paper](https://doi.org/10.1002/mrm.29547)] [[Github](https://github.com/sunkg/jCAN)]


**Adapting model-based deep learning to multiple acquisition conditions: Ada-MoDL** \
*Aniket Pramanik, Sampada Bhave, Saurav Sajib, Samir D. Sharma, and Mathews Jacob* \
[18 June 2023] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.29750)] 



**MEDL-Net: A model-based neural network for MRI reconstruction with enhanced deep learned regularizers** \
*Xiaoyu Qiao, Yuping Huang, and Weisheng Li* \
[19 January 2023] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.29575)] [[Github](https://github.com/joexy312/MEDL-Net/tree/master)]



**Deep Learning Reconstruction Enables Prospectively Accelerated Clinical Knee MRI** \
*Patricia M. Johnson, Dana J. Lin, Jure Zbontar, C. Lawrence Zitnick, Anuroop Sriram, Matthew Muckley, James S. Babb, Mitchell Kline, Gina Ciavarra, Erin Alaia, Mohammad Samim, William R. Walter, Liz Calderon, Thomas Pock, Daniel K. Sodickson, Michael P. Recht, and Florian Knoll* \
[17 January 2023] [Radiology] \
[[Paper](https://doi.org/10.1148/radiol.220425)] [[Github](https://github.com/facebookresearch/fastMRI/tree/main/fastmri_examples/RadiologyJohnson2022)]





**A Joint Group Sparsity-based deep learning for multi-contrast MRI reconstruction** \
*Guo, Di, Gushan Zeng, Hao Fu, Zi Wang, Yonggui Yang, and Xiaobo Qu* \
[08 December 2022] [J. Magn. Reson.] \
[[Paper](https://doi.org/10.1016/j.jmr.2022.107354)]


**An untrained deep learning method for reconstructing dynamic MR images from accelerated model-based data** \
*Kalina P. Slavkova, Julie C. DiCarlo, Viraj Wadhwa, Sidharth Kumar, Chengyue Wu, John Virostko, Thomas E. Yankeelov, and Jonathan I. Tamir* \
[05 December 2022] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.29684)] [[Github](https://github.com/kslav/cdr_mri/tree/master)]



**Highly accelerated MR parametric mapping by undersampling the k-space and reducing the contrast number simultaneously with deep learning** \
*Liu, Shaonan, Haoxiang Li, Yuanyuan Liu, Guanxun Cheng, Gang Yang, Haifeng Wang, Hairong Zheng, Dong Liang, and Yanjie Zhu* \
[08 September 2022] [PMB] \
[[Paper](https://doi.org/10.1088/1361-6560/ac8c81)]


**One-Dimensional Deep Low-Rank and Sparse Network for Accelerated MRI** \
*Zi Wang, Chen Qian, Di Guo, Hongwei Sun, Rushuai Li, Bo Zhao, and Xiaobo Qu* \
[31 August 2022] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2022.3203312)] [[Online Tool](https://csrc.xmu.edu.cn/CloudBrain.html)]


**A cascade of preconditioned conjugate gradient networks for accelerated magnetic resonance imaging** \
*Moogyeong Kim and Wonzoo Chung* \
[29 August 2022] [Computer Methods and Programs in Biomedicine] \
[[Paper](https://doi.org/10.1016/j.cmpb.2022.107090)]




**Simultaneously optimizing sampling pattern for joint acceleration of multi-contrast MRI using model-based deep learning** \
*Sunghun Seo, Huan Minh Luu, Seung Hong Choi, and Sung-Hong Park* \
[09 June 2022] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.15790)]


**High fidelity deep learning-based MRI reconstruction with Instance-wise discriminative feature matching loss** \
*Ke Wang, Jonathan I. Tamir, Alfredo De Goyeneche, Uri Wollner, Rafi Brada, Stella X. Yu, and Michael Lustig* \
[03 April 2022] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.29227)] [[Github](https://github.com/mikgroup/UFLoss/tree/main)]



**Accelerating susceptibility-weighted imaging with deep learning by complex-valued convolutional neural network (ComplexNet): validation in clinical brain imaging.** \
*Caohui Duan, Yongqin Xiong, Kun Cheng, Sa Xiao, Jinhao Lyu, Cheng Wang, Xiangbing Bian, Jing Zhang, Dekang Zhang, Ling Chen, Xin Zhou, and Xin Lou* \
[19 February 2022] [European Radiology] \
[[Paper](https://doi.org/10.1007/s00330-022-08638-1)]



**Learning Data Consistency and its Application to Dynamic MR Imaging** \
*Jing Cheng, Zhuo-Xu Cui, Wenqi Huang, Ziwen Ke, Leslie Ying, Haifeng Wang, Yanjie Zhu, and Dong Liang* \
[12 July 2021] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1109/TMI.2021.3096232)]



**Systematic evaluation of iterative deep neural networks for fast parallel MRI reconstruction with sensitivity-weighted coil combination** \
*Hammernik, Kerstin, Jo Schlemper, Chen Qin, Jinming Duan, Ronald M. Summers, and Daniel Rueckert* \
[10 June 2021] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.28827)] [[Github](https://github.com/khammernik/sigmanet)]


**Accelerated multicontrast reconstruction for synthetic MRI using joint parallel imaging and variable splitting networks** \
*Kanghyun Ryu, Jae-Hun Lee, Yoonho Nam, Sung-Min Gho, Ho-Sung Kim, and Dong-Hyun Kim* \
[18 March 2021] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.14848)] [[Github](https://github.com/KHRyu8985/Joint_Reconstruction_Synthetic_MR)]


**On the regularization of feature fusion and mapping for fast MR Multi-contrast imaging via iterative networks** \
*Xinwen Liu, Jing Wang, Hongfu Sun, Shekhar S. Chandra, Stuart Crozier, and Feng Liu* \
[02 January 2021] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2020.12.019)] 



**RUN-UP: Accelerated multishot diffusion-weighted MRI reconstruction using** \
*Liu, Risheng, Yuxi Zhang, Shichao Cheng, Zhongxuan Luo, and Xin Fan* \
[11 August 2020] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.28446)]



**A Deep Framework Assembling Principled Modules for CS-MRI: Unrolling Perspective, Convergence Behaviors, and Practical Modeling** \
*Liu, Risheng, Yuxi Zhang, Shichao Cheng, Zhongxuan Luo, and Xin Fan* \
[04 August 2020] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2020.3014193)]




**Accelerating cardiac cine MRI using a deep learning-based ESPIRiT reconstruction** \
*Sandino, Christopher M., Peng Lai, Shreyas S. Vasanawala, and Joseph Y. Cheng* \
[22 July 2020] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.28420)]



**Self-supervised learning of physics-guided reconstruction neural networks without fully sampled reference data** \
*Burhaneddin Yaman, Seyed Amir Hossein Hosseini, Steen Moeller, Jutta Ellermann, Kâmil Uğurbil, and Mehmet Akçakaya* \
[02 July 2020] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.28378)] [[Github](https://github.com/byaman14/SSDU)]






**A feature-based convolutional neural network for reconstruction of interventional MRI** \
*Blanca Zufiria, Suhao Qiu, Kang Yan, Ruiyang Zhao, Runke Wang, Huajun She, Chengcheng Zhang, Bomin Sun, Pawel Herman, Yiping Du, and Yuan Feng* \
[19 December 2019] [NMR Biomed.] \
[[Paper](https://doi.org/10.1002/nbm.4231)]


**A Deep Information Sharing Network for Multi-Contrast Compressed Sensing MRI Reconstruction** \
*Liyan Sun, Zhiwen Fan, Xueyang Fu, Yue Huang, Xinghao Ding, and John Paisley* \
[09 July 2019] [Transactions on Image Processing] \
[[Paper](https://doi.org/10.1109/TIP.2019.2925288)]


**Parallel imaging and convolutional neural network combined fast MR image reconstruction: Applications in low-latency accelerated real-time imaging** \
*Ziwu Zhou, Fei Han, Vahid Ghodrati, Yu Gao, Wotao Yin, Yingli Yang, and Peng Hu* \
[28 May 2019] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.13628)]







---

#### DC layer


**Robust Cardiac Cine MRI Reconstruction with Spatiotemporal Diffusion Model** \
*Zi Wang, Jiahao Huang, Mingkai Huang, Chengyan Wang, Guang Yang, and Xiaobo Qu* \
[13 August 2025] [IEEE Transactions on Computational Imaging]<br>
[[Paper](https://doi.org/10.1109/TCI.2025.3598421)]


**A parallel dual-domain crossing network combining attention enhancement and multimodal fusion for MRI reconstruction** \
*Yanqing Li, Hongqing Zhu, Tong Hou, Ning Chen, Bingcang Huang, Weiping Lu, Ying Wang, and Suyi Yang* \
[10 July 2025] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.108326)][[Github](https://github.com/YanQLi/AMC-Net)]


**CS-SwinGAN: A swin-transformer-based generative adversarial network with compressed sensing pre-enhancement for multi-coil MRI reconstruction** \
*Haikang Zhang, Zongqi Li, Qingming Huang, Luying Huang, Yicheng Huang, Wentao Wang, and Bing Shen* \
[24 May 2025] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.108120)][[Github](https://github.com/notmayday/CS-SwinGAN_MC_Rec)]



**Dual-path network with dual-domain fusion and cross-attention for MRI reconstruction** \
*Wenqi Chen, Zhirong Gao, Yuan He, Jingxuan Wanyan, and Chengyi Xiong* \
[24 May 2025] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.108181)]




**FDuDoCLNet: Fully dual-domain contrastive learning network for parallel MRI reconstruction** \
*Huiyao Zhang, Tiejun Yang, Heng Wang, Jiacheng Fan, Wenjie Zhang, and Mingzhu Ji* \
[24 January 2025] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2025.110336)] 


**Ensemble and low-frequency mixing with diffusion models for accelerated MRI reconstruction** \
*Yejee Shin, Geonhui Son, Dosik Hwang, and Taejoon Eo* \
[17 January 2025] [MedIA]<br>
[[Paper](https://doi.org/10.1016/j.media.2025.103477)][[Github](https://github.com/yejees/ELF-Diff)]


**Unsupervised reconstruction of accelerated cardiac cine MRI using neural fields** \
*Tabita Catalán, Matías Courdurier, Axel Osses, Anastasia Fotaki, René Botnar, Francisco Sahli-Costabal, and Claudia Prieto* \
[12 December 2024] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2024.109467)] 


**Highly accelerated MRI via implicit neural representation guided posterior sampling of diffusion models** \
*Jiayue Chu, Chenhe Du, Xiyue Lin, Xiaoqun Zhang, Lihui Wang, Yuyao Zhang, and Hongjiang Wei* \
[23 November 2024] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2024.103398)] 

**SPIRiT-Diffusion: Self-Consistency Driven Diffusion Model for Accelerated MRI** \
*Zhuo-Xu Cui, Chentao Cao, Yue Wang, Sen Jia, Jing Cheng, and Xin Liu* \
[03 October 2024] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2024.3473009)][[Github](https://github.com/zhyjSIAT/SPIRiT-Diffusion)]

**CRNN-Refined Spatiotemporal Transformer for Dynamic MRI reconstruction** \
*Bin Wang, Yusheng Lian, Xingchuang Xiong, Hongbin Han, and Zilong Liu* \
[13 September 2024] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2024.109133)][[Github](https://github.com/XWangBin/CST-Net)] 


**SPICER: Self-supervised learning for MRI with automatic coil sensitivity estimation and reconstruction** \
*Yuyang Hu, Weijie Gan, Chunwei Ying, Tongyao Wang, Cihat Eldeniz, Jiaming Liu, Yasheng Chen, Hongyu An, and Ulugbek S. Kamilov* \
[23 June 2024] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.30121)] 



**MLMFNet: A multi-level modality fusion network for multi-modal accelerated MRI reconstruction** \
*Xiuyun Zhou, Zhenxi Zhang, Hongwei Du, Bensheng Qiu* \
[24 April 2024] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2024.04.028)] 


**DIRECTION: Deep cascaded reconstruction residual-based feature modulation network for fast MRI reconstruction** \
*Yong Sun , Xiaohan Liu, Yiming Liu, Ruiqi Jin, and Yanwei Pang* \
[18 April 2024] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2024.04.023)] 

**Attention-Based MultiOffset Deep Learning Reconstruction of Chemical Exchange Saturation Transfer (AMO-CEST) MRI** \
*Zhikai Yang, Dinggang Shen, Kannie W. Y. Chan, and Jianpan Huang* \
[22 May 2024] [J-HBI] \
[[Paper](https://doi.org/10.1109/JBHI.2024.3404225)] 

**MRI reconstruction with enhanced self-similarity using graph convolutional network** \
*Yong Sun , Xiaohan Liu, Yiming Liu, Ruiqi Jin, and Yanwei Pang* \
[17 March 2023] [BMC Medical Imaging]<br>
[[Paper](https://doi.org/10.1186/s12880-024-01297-2)] 



**Deep-learning-based reconstruction of undersampled MRI to reduce scan times: a multicentre, retrospective, cohort study** \
*Aditya Rastogi, Gianluca Brugnara, Martha Foltyn-Dumitru, Mustafa Ahmed Mahmutoglu, Chandrakanth J Preetha, Erich Kobler, Irada Pflüger, et al.* \
[26 February 2024] [The Lancet Oncology]<br>
[[Paper](https://doi.org/10.1016/S1470-2045(23)00641-1)] 




**DCT-net: Dual-domain cross-fusion transformer network for MRI reconstruction** \
*Wang, Bin, Yusheng Lian, Xingchuang Xiong, Han Zhou, Zilong Liu, and Xiaohao Zhou* \
[17 January 2024] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2024.01.007)]


**Encoding Enhanced Complex CNN for Accurate and Highly Accelerated MRI** \
*Li, Zimeng, Sa Xiao, Cheng Wang, Haidong Li, Xiuchao Zhao, Caohui Duan, Qian Zhou et al.* \
[09 January 2024] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2024.3351211)] [[Github](https://github.com/zimli/EN2-convolution-network)] 




**Joint MAPLE: Accelerated joint T1 and T2s mapping with scan-specific Self-supervised networks** \
*Amir Heydari, Abbas Ahmadi, Tae Hyung Kim, and Berkin Bilgic* \
[05 January 2024] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29989)] [[Github](https://github.com/AmirHeydariGit/joint_maple/tree/main)] 



**Multi-Contrast Complementary Learning for Accelerated MR Imaging** \
*Bangjun Li, Weifeng Hu, Chun-Mei Feng, Yujun Li, Zhi Liu, and Yong Xu* \
[29 December 2023] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2023.3348328)]


**IMJENSE: Scan-specific Implicit Representation for Joint Coil Sensitivity and Image Estimation in Parallel MRI** \
*Ruimin Feng, Qing Wu, Jie Feng, Huajun She, Chunlei Liu, Yuyao Zhang, and Hongjiang Wei* \
[13 December 2023] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2023.3342156)] [[Github](https://github.com/AMRI-Lab/IMJENSE)]


**McSTRA: A multi-branch cascaded swin transformer for point spread function-guided robust MRI reconstruction** \
*Mevan Ekanayake, Kamlesh Pawar, Mehrtash Harandi, Gary Egan, and Zhaolin Chen* \
[13 December 2023] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107775)]



**DC-SiamNet: Deep contrastive Siamese network for self-supervised MRI reconstruction** \
*Yanghui Yan, Tiejun Yang, Xiang Zhao, Chunxia Jiao, Aolin Yang, and Jianyu Miao* \
[28 October 2023] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107619)]


**Adaptive diffusion priors for accelerated MRI reconstruction** \
*Alper Güngör, Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Hasan A. Bedel, Gokberk Elmas, Muzaffer Ozbey, and Tolga Çukur* \
[20 June 2023] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2023.102872)] [[Github](https://github.com/icon-lab/AdaDiff)]



**Deep learning based MRI reconstruction with transformer** \
*Zhengliang Wu, Weibin Liao, Chao Yan, Mangsuo Zhao, Guowen Liu, Ning Ma, and Xuesong Li* \
[01 March 2023] [Computer Methods and Programs in Biomedicine]<br>
[[Paper](https://doi.org/10.1016/j.cmpb.2023.107452)] [[Github](https://github.com/BITwzl/KTMR)]


**Deep compressed sensing MRI via a gradient-enhanced fusion model** \
*Yuxiang Dai, Chengyan Wang, and He Wang* \
[25 January 2023] [Med. Phys.]<br>
[[Paper](https://doi.org/10.1002/mp.16164)]




**A Conditional Normalizing Flow for Accelerated Multi-Coil MR Imaging** \
*Jeffrey Wen, Rizwan Ahmad, and Philip Schniter* \
[02 June 2023] [ICML]<br>
[[Paper](https://doi.org/10.48550/arXiv.2306.01630)] [[Github](https://github.com/jwen307/mri_cnf)]


**Accelerated respiratory-resolved 4D-MRI with separable spatio-temporal neural networks** \
*Maarten L. Terpstra, Matteo Maspero, Joost J. C. Verhoeff, and Cornelis A. T. van den Berg* \
[01 August 2023] [Med. Phys.]<br>
[[Paper](https://doi.org/10.1002/mp.16643)] [[Github](https://gitlab.com/computational-imaging-lab/modest)]





**Deep supervised dictionary learning by algorithm unrolling-Application to fast 2D dynamic MR image reconstruction** \
*Andreas Kofler, Marie-Christine Pali, Tobias Schaeffter, and Christoph Kolbitsch* \
[24 December 2022] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.16182)] [[Github](https://github.com/koflera/End2End-DLMRI?tab=readme-ov-file)]


**Parallel non-Cartesian spatial-temporal dictionary learning neural networks (stDLNN) for accelerating 4D-MRI** \
*Zhijun Wang, Huajun She, Yufei Zhang, and Yiping P. Du* \
[24 November 2022] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2022.102701)] [[Github](https://github.com/mrieeart/stDLNN)]


**Exploring the Acceleration Limits of Deep Learning Variational Network-based Two-dimensional Brain MRI** \
*Alireza Radmanesh, Matthew J. Muckley , Tullie Murrell, Emma Lindsey, Anuroop Sriram, Florian Knoll, Daniel K. Sodickson, and Yvonne W. Lui* \
[02 November 2022] [Radiology]<br>
[[Paper](https://doi.org/10.1148/ryai.210313)] 




**DSMENet: Detail and Structure Mutually Enhancing Network for under-sampled MRI reconstruction** \
*Wang, Yueze, Yanwei Pang, and Chuan Tong* \
[13 October 2022] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2022.106204)]


**Assessment of data consistency through cascades of independently recurrent inference machines for fast and robust accelerated MRI reconstruction** \
*D Karkalousos, S Noteboom, H E Hulst, F M Vos, and M W A Caan* \
[08 June 2022] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ac6cc2)] [[Github](https://github.com/wdika/mridc)]


**Pyramid Convolutional RNN for MRI Image Reconstruction** \
*Eric Z. Chen, Puyang Wang, Xiao Chen, Terrence Chen, and Shanhui Sun* \
[22 February 2022] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2022.3153849)] [[Github](https://github.com/js3611/Deep-MRI-Reconstruction)]



**Complementary time-frequency domain networks for dynamic parallel MR image reconstruction** \
*Chen Qin, Jinming Duan, Kerstin Hammernik, Jo Schlemper, Thomas Küstner, René Botnar, Claudia Prieto, Anthony N. Price, Joseph V. Hajnal, and Daniel Rueckert* \
[13 July 2021] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.28917)] [[Github](https://github.com/cq615/kt-Dynamic-MRI-Reconstruction)]




**A deep cascade of ensemble of dual domain networks with gradient-based T1 assistance and perceptual refinement for fast MRI reconstruction** \
*Balamurali Murugesan, Sriprabha Ramanarayanan, Sricharan Vijayarangan, Keerthi Ram, Naranamangalam R Jagannathan, and Mohanasankar Sivaprakasam* \
[24 May 2021] [CMIG] \
[[Paper](https://doi.org/10.1016/j.compmedimag.2021.101942)]





**Accelerating quantitative MR imaging with the incorporation of B1 compensation using deep learning** \
*Yan Wu, Yajun Ma, Jiang Du, and Lei Xing* \
[29 June 2020] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2020.06.011)]




**DeepcomplexMRI: Exploiting deep residual network for fast Parallel MR imaging with complex convolution** \
*Shanshan Wang, Huitao Cheng, Leslie Ying, Taohui Xiao, Ziwen Ke, Hairong Zheng, and Dong Liang* \
[08 February 2020] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2020.02.002)]





**Highly undersampled magnetic resonance imaging reconstruction using autoencoding priors** \
*Qiegen Liu, Qingxin Yang, Huitao Cheng, Shanshan Wang, Minghui Zhang, and Dong Liang* \
[20 August 2019] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.27921)] 



**Self-Attention Convolutional Neural Network for Improved MR Image Reconstruction** \
*Yan Wu, Yajun Ma, Jing Liu, Jiang Du, and Lei Xing* \
[01 April 2019] [Information Science] \
[[Paper](https://doi.org/10.1016/j.ins.2019.03.080)] 



**A Deep Cascade of Convolutional Neural Networks for Dynamic MR Image Reconstruction** \
*Jo Schlemper, Jose Caballero, Joseph V. Hajnal, Anthony N. Price, and Daniel Rueckert* \
[13 October 2017] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2017.2760978)]  [[Github](https://github.com/js3611/Deep-MRI-Reconstruction)]





---

#### Self-supervise


**AeSPa : Attention-guided Self-supervised Parallel Imaging for MRI Reconstruction** \
*Joo, Jinho and Kim, Hyeseong and Won, Hyeyeon and Lee, Deukhee and Eo, Taejoon and Hwang, Dosik* \
[2025] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Joo_AeSPa__Attention-guided_Self-supervised_Parallel_Imaging_for_MRI_Reconstruction_CVPR_2025_paper.pdf)] [[Github](https://github.com/joojinho97/AeSPa)] 


**Robust multi-coil MRI reconstruction via self-supervised denoising** \
*Asad Aali, Marius Arvinte, Sidharth Kumar, Yamin I. Arefeen, Jonathan I. Tamir* \
[02 June 2025] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.30591)] [[Github](https://github.com/utcsilab/gsure-diffusion-mri)] 



**Joint MAPLE: Accelerated joint T1 and T2s mapping with scan-specific Self-supervised networks** \
*Amir Heydari, Abbas Ahmadi, Tae Hyung Kim, and Berkin Bilgic* \
[05 January 2024] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29989)] [[Github](https://github.com/AmirHeydariGit/joint_maple/tree/main)] 


**DC-SiamNet: Deep contrastive Siamese network for self-supervised MRI reconstruction** \
*Yanghui Yan, Tiejun Yang, Xiang Zhao, Chunxia Jiao, Aolin Yang, and Jianyu Miao* \
[28 October 2023] [Computers in Biology and Medicine]<br>
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107619)]


**Noise2Recon: Enabling SNR-robust MRI reconstruction with semi-supervised and self-supervised learning** \
*Desai, Arjun D., Batu M. Ozturkler, Christopher M. Sandino, Robert Boutin, Marc Willis, Shreyas Vasanawala, Brian A. Hargreaves, Christopher Ré, John M. Pauly, and Akshay S. Chaudhari* \
[10 July 2023] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.29759)] [[Github](https://github.com/ad12/meddlr)]


**Dual-domain self-supervised learning for accelerated non-Cartesian MRI reconstruction** \
*Bo Zhou, Jo Schlemper, Neel Dey, Seyed Sadegh Mohseni Salehi, Kevin Sheth, Chi Liu, James S. Duncan, and Michal Sofka* \
[18 July 2022] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2022.102538)] [[Github](https://github.com/ad12/meddlr)]


**Magnetic resonance parameter mapping using model-guided self-supervised deep learning** \
*Liu, Fang, Richard Kijowski, Georges El Fakhri, and Li Feng* \
[19 January 2021] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.28659)]








---

### Federated Learning

**Generative Autoregressive Transformers for Model-Agnostic Federated MRI Reconstruction** \
*Valiyeh A. Nezhad, Gokberk Elmas, Bilal Kabas, Fuat Arslan, Tolga Çukur*\
[06 February 2025] [preprint arXiv] \
[[Paper](https://doi.org/10.48550/arXiv.2502.04521)] [[Github](https://github.com/icon-lab/FedGAT)]

**FAME: A Federated Adversarial Learning Framework for Privacy-Preserving MRI Reconstruction** \
*Shahzad Ahmed, Jinchao Feng, Javed Ferzund, Muhammad Yaqub, Muhammad Usman Ali, Malik Abdul Manan, and Abdul Raheem* \
[25 January 2025] [Appl Magn Reson] \
[[Paper](https://doi.org/10.1007/s00723-025-01749-0)]


**Generalizable Reconstruction for Accelerating MR Imaging via Federated Learning With Neural Architecture Search** \
*Ruoyou Wu, Cheng Li, Juan Zou, Xinfeng Liu, Hairong Zheng, and Shanshan Wang* \
[22 July 2024] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2024.3432388)] [[GitHub](https://github.com/ternencewu123/GAutoMRI)]



**Adaptive channel-modulated personalized federated learning for magnetic resonance image reconstruction** \
*Lyu, Jun, Yapeng Tian, Qing Cai, Chengyan Wang, and Jing Qin* \
[16 August 2023] [Computers in Biology and Medicine] \
[[Paper](https://doi.org/10.1016/j.compbiomed.2023.107330)] 

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


**Self-supervised learning of physics-guided reconstruction neural networks without fully sampled reference data** \
*Burhaneddin Yaman, Seyed Amir Hossein Hosseini, Steen Moeller, Jutta Ellermann, Kâmil Uğurbil, and Mehmet Akçakaya* \
[02 July 2020] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.28378)] [[Github](https://github.com/byaman14/SSDU)]




---

# Dataset

### fastMRI Dataset
*Center for Advanced Imaging Innovation and Research (CAI2R), Department of Radiology at NYU School of Medicine and NYU Langone Health* \
`Multi-coil raw k-space data` [[Dataset](https://fastmri.med.nyu.edu/)] [[Github](https://github.com/facebookresearch/fastMRI)] <br>
* Imaging region
  *  Brain
  * Knee
  * Prostate
  * Breast

### IXI Dataset
*Imperial College London* \
`Single-coil magnitude image data` [[Dataset](https://brain-development.org/ixi-dataset/)] <br>
* Imaging region
  *  Brain



### BraTS Dataset
*multi-institutional* \
`Single-coil magnitude image data` [[Dataset](http://braintumorsegmentation.org/)] <br>
* Imaging region
  *  Brain



### Atria Segmentation Challenge

`Single-coil magnitude image data` [[Dataset](https://www.cardiacatlas.org/atriaseg2018-challenge/)] <br>
* Imaging region
  *  Cardiac


### Cardiovascular Magnetic Resonance Imaging

`Multi-coil raw k-space data` [[Dataset](https://github.com/MRIOSU/OCMR?tab=readme-ov-file)] <br>
* Imaging region
  *  Cardiovascular



### MRIdata

`Multi-coil raw k-space data` [[Dataset](http://mridata.org/)] <br>
* **Imaging region**
  *  Knee

### Calgary-Campinas

`Multi-coil raw k-space data` [[Dataset](https://www.ccdataset.com/)] <br>
* **Imaging region**
  *  Brain


### K2S

`Multi-coil raw k-space data` [[Dataset](https://k2s.grand-challenge.org/)] <br>
* **Imaging region**
  *  Knee
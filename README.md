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
- **Third release:** September 21, 2026
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

**Acceleration-dependent variability in simultaneous T1/T2 mapping with a hybrid (mixed) sequence: a phantom comparison of SENSE, compressed sensing, and deep learning reconstructions** \
*Masayuki Kanamoto, Yuki Matta, Toshiki Tateishi, Hiroyuki Tsushima, and Tetsuya Tsujikawa* \
[January 2027] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2026.110787)]


**Performance of a deep learning algorithm on deep learning reconstruction-accelerated prostate biparametric MRI: A preliminary study** \
*Young Joon Lee, Moon Hyung Choi, Robert Grimm, Heinrich von Busch, and Marcel Dominik Nickel* \
[December 2026] [European Journal of Radiology]<br>
[[Paper](https://doi.org/10.1016/j.ejrad.2026.113227)]


**Ai-assisted compressed sensing with deep learning reconstruction for accelerated rectal MRI: A prospective intra-individual study of image quality and preoperative staging** \
*Yuedi Ma, Dongqiu Shan, Junhui Yuan, Xiaoxian Zhang, Dechang Yuan, Guangguang An, Nannan Zhao, Zhikai Zhang, Yifan Liu, Xuejun Chen, Yue Wu, and Chunmiao Xu* \
[December 2026] [European Journal of Radiology]<br>
[[Paper](https://doi.org/10.1016/j.ejrad.2026.113191)]


**Enabling highly accelerated multi-shot IVIM-DWI with a Data-sharing-guided framework: Joint image reconstruction and biomarker estimation** \
*Chenglang Yuan, Shihui Chen, Liyuan Liang, Xiaorui Xu, Hailin Xiong, Tianbaige Liu, Yi Li, Qiting Wu, Wing Yat Cheung, Edward S. Hui, Qi Dou, and Hing-Chiu Chang* \
[October 2026] [NeuroImage]<br>
[[Paper](https://doi.org/10.1016/j.neuroimage.2026.122233)]


**Multi-contrast MRI acceleration via post-reconstruction fusion** \
*Alexander Nazarov, Nahum Kiryati, Dani Roizen, Ariel Kerpel, Chen Hoffmann, Gahl Greenberg, and Arnaldo Mayer* \
[14 September 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.104297)]


**HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction** \
*Hongli Chen, Pengcheng Fang, Yuxia Chen, Yingxuan Ren, Jing Hao, Fangfang Tang, Xiaohao Cai, Shanshan Shan, and Feng Liu* \
[2026] [AAAI]<br>
[[Paper](https://doi.org/10.1609/aaai.v40i4.37277)]


**The Challenge of Rendering Abnormalities Accurately Using Deep Learning-Based Reconstruction in Accelerated Brain MRI: A Disproportionate Loss of Clinically Relevant Image Information at Higher Rates of Acceleration** \
*Shengjia Chen, Patricia M. Johnson, and Yvonne W. Lui* \
[14 September 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001308)]


**Optimizing Brachial Plexus Diffusion Tensor Imaging: The Impact of Deep Learning Reconstruction and Simultaneous Multislice Acceleration on Single-shot Echo-planar Imaging** \
*Euddeum Shim, Sungwon Ham, Baek Hyun Kim, Woo Young Kang, Chang Ho Kang, Kyung-Sik Ahn, Kyu-Chong Lee, In Young Choi, InSeong Kim, and Hangseok Choi* \
[02 September 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001284)]


**A spatiotemporal dependency-aware lightweight CNN-ViT network for 3D MRF with a balanced acceleration strategy** \
*Jintao Wei, Huihui Ye, Bingchen Shao, Longtao Ma, Qiuping Ding, Zihan Zhou, Xiaozhi Cao, Jianhui Zhong, and Hongjian He* \
[September 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.104147)]


**DAINet: Dual-alignment implicit network for accelerated multi-contrast MRI reconstruction** \
*Zhijie Wang, Aiping Liu, Jinbao Wei, Gang Yang, Yue Yu, Wei Wei, and Xun Chen* \
[September 2026] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2026.110571)]


**Recurrent Mamba for efficient and high-fidelity MRI reconstruction** \
*Zhaoming Hou, Boying Wu, Guoqing Chen, Qiyu Jin, Dong Liang, and Tieyong Zeng* \
[September 2026] [Expert Systems with Applications]<br>
[[Paper](https://doi.org/10.1016/j.eswa.2026.132329)]


**Completely free-breathing cardiac MRI using deep learning reconstruction reduces sedation and scan time in children** \
*Aditi Gupta, William Long, Sara Young, Brian Blasiole, Nicholas Mouzakis, Alessandro Scotti, Kyoko Fujimoto, Tarek Alsaied, Mary Schiff, Adam Christopher, and Laura Olivieri* \
[27 August 2026] [Pediatric Radiology]<br>
[[Paper](https://doi.org/10.1007/s00247-026-06749-1)]


**Robust T 1 ρ , T 2 , and T 2 * mapping via spin-locked MOLED with synthetic data-driven deep learning reconstruction** \
*Weikun Chen, Qing Lin, Taishan Kang, Jian Wu, Yuchen Zheng, Jianfa Chen, Shuhui Cai, and Congbo Cai* \
[26 August 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae9a2a)]


**Multi-Frequency Feature Guided Progressive Divide-and-Conquer Network for Accelerated MRI Reconstruction** \
*Hanshuo Zhu, Xiaozhen Ren, Xiaqiong Fan, Zhipeng Guo, and Tiejun Yang* \
[04 August 2026] [J. Imaging Inform. Med.]<br>
[[Paper](https://doi.org/10.1007/s10278-026-02170-0)]


**GCL-RCA-Net: an RCA-RemUNet-enhanced graph-contrastive framework for hybrid data-driven and dual-branch physics-guided parallel MRI reconstruction** \
*Mahian Kabir Joarder and Md Kamrul Hasan* \
[03 August 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae88b2)]


**Information-Theoretic Optimization for Task-Adapted Compressed Sensing Magnetic Resonance Imaging** \
*Xinyu Peng, Ziyang Zheng, Wenrui Dai, Duoduo Xue, Shaohui Li, Chenglin Li, Junni Zou, and Hongkai Xiong* \
[August 2026] [IEEE TPAMI]<br>
[[Paper](https://doi.org/10.1109/TPAMI.2026.3683201)]


**Seeking Common Ground While Reserving Differences: Multiple Anatomy Collaborative Framework for Undersampled MRI Reconstruction** \
*Jiangpeng Yan, Chenghui Yu, Hanbo Chen, Zhe Xu, Junzhou Huang, Xiu Li, and Jianhua Yao* \
[August 2026] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2025.3602999)]


**Accelerated Cardiac MRI Using Deep Learning Cine Imaging: Validation in Pediatric Patients both with and without Congenital Heart Disease** \
*Jonathan Kochav, Junjie Ma, Sachin Jambawalikar, Maggie Fung, Patrick Quarterman, Amee Shah, Kanwal Farooqi, Amara Majeed, Simone Jhaveri, Alexandra Channing, Sophia Hsien, Martin Janich, and Michael P. DiLorenzo* \
[August 2026] [JCMR]<br>
[[Paper](https://doi.org/10.1016/j.jocmr.2026.102793)]


**Clinical evaluation of deep learning accelerated 3D magnetic resonance cholangiopancreatography at 1.5 T and 3 T** \
*Ivan Jambor, Ranjodh S. Dhami, Madhangi Parameswaran, Eugene Milshteyn, Ajeetkumar Gaddipati, Mary Thomas, Arnaud Guidon, Ty Cashen, Miraj Rawal, Nabih Nakrour, Azadeh Tabari, Susie Y. Huang, Clare Tempany-Afdhal, Mukesh G. Harisinghani, and Rory L. Cochran* \
[August 2026] [European Journal of Radiology]<br>
[[Paper](https://doi.org/10.1016/j.ejrad.2026.112906)]


**Accelerated 7T 3D DESS MR Neurography of the Cervical Spine Using CS-CAIPIRINHA and Deep Learning Reconstruction** \
*Frederik Abel, Constantin von Deuster, Andreas J. Walch, Dominik Paul, Marcel Dominik Nickel, and Reto Sutter* \
[24 July 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001305)]


**Training Deep Learning Based Dynamic MR Image Reconstruction Using Synthetic Fractals** \
*Anirudh Raman, Olivier Jaubert, Mark Wrobel, Tina Yao, Ruaraidh Campbell, Rebecca R Baker, Ruta Virsinskaite, Daniel Knight, Michael Quail, Jennifer A Steeden, and Vivek Muthurangu* \
[19 July 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70521)]


**Vessel Wall Imaging in 1.5 T MRI Using Deep Learning Reconstruction: Prospective Evaluation of Interchangeability With Standard 3 T MRI** \
*Arwed Elias Michael, Haidara Almansour, Roman Paul, Dominik Nickel, Ralph Strecker, Alexander Brockmann, Vanessa Schoeffling, Sebastian Altmann, and Ahmed E. Othman* \
[07 July 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001290)]


**Accelerated Deep-Learning-Based Image Reconstruction for 3D T2 Dark-Fluid in Imaging of Multiple Sclerosis** \
*Sebastian Altmann, Mario A.A. Mercado, Arwed Elias Michael, Mariya Kondova, Roman H. Paul, Marcel Dominik Nickel, Vanessa Ines Schöffling, Vinzenz Fleischer, Marc A. Brockmann, and Ahmed E. Othman* \
[06 July 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001300)]


**Clinical Evaluation of A-LIKNet: Deep Learning-accelerated Single-breath-hold CINE Magnetic Resonance Imaging for Cardiac Function Assessment** \
*Jens Kübler, Stanislau Chekan, Siying Xu, Aya Ghoul, Andreas Lingg, Florian Hagen, Jan-Michael Brendel, Konstantin Nikolaou, Thomas Küstner, and Patrick Krumm* \
[01 July 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001243)]


**Simultaneous multi-slice Cardiac Diffusion Tensor Imaging with variable CAIPIRINHA shifts and artefact-aware AI** \
*Michael Tänzer, Eun Ji Lim, Huaqi Harvey Qiu, Camila Munoz, Andrew Scott, Dudley Pennell, Pedro Ferreira, Daniel Rueckert, Guang Yang, and Sonia Nielles-Vallespin* \
[July 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.104115)]


**End-to-End Co-Optimization of Adaptive k-space Sampling and Reconstruction for Dynamic MRI** \
*George Yiasemis, Jan-Jakob Sonke, and Jonas Teuwen* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v315/yiasemis26a.html)]


**Beyond Diffusion: Consistency Models for One-Step, High-Fidelity MRI Reconstruction** \
*Mary-Brenda Akoda and Chen Qin* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v315/akoda26a.html)]


**T1-PILOT: Physics-Informed Learned Optimized Trajectories for T1 Mapping Acceleration** \
*Tamir Shor, Moti Freiman, Chaim Baskin, and Alex Bronstein* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v315/shor26a.html)]


**MASC: Metal-Aware Sampling and Correction via Reinforcement Learning for Accelerated MRI** \
*Zhengyi Lu, Ming Lu, Chongyu Qu, Junchao Zhu, Junlin Guo, Marilyn Lionts, Yanfan Zhu, Yuechen Yang, Tianyuan Yao, Jayasai Rajagopal, Bennett Allan Landman, Xiao Wang, Xinqiang Yan, and Yuankai Huo* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v315/lu26a.html)]


**Rapid multi-parametric quantitative MRI via deep learning-based synthetic-to-real reconstruction and 3D SSFP-MOLED imaging** \
*Jingying Yang, Liuhong Zhu, Kai Xiong, Jianfeng Bao, Qinqin Yang, Weikun Chen, Taishan Kang, Jianjun Zhou, Jianzhong Lin, Liangjie Lin, Zhong Chen, Shuhui Cai, and Congbo Cai* \
[July 2026] [NeuroImage]<br>
[[Paper](https://doi.org/10.1016/j.neuroimage.2026.121985)]


**Spatial-temporal and physical constrained deep learning model for simultaneous T1 and T2 reconstruction and mapping (STEP)** \
*Runyu Yang, Haozhong Sun, Xiaoqi Lin, Haokun Li, and Huijun Chen* \
[July 2026] [QIMS]<br>
[[Paper](https://doi.org/10.21037/qims-2025-1563)]


**Complex-valued Multi-scale Hybrid Attention Network for Fast MRI via Sparsified Data Learning** \
*Yongchun Ma, Yuanzhen Tang, and Zhaoyang Jin* \
[30 June 2026] [J. Imaging Inform. Med.]<br>
[[Paper](https://doi.org/10.1007/s10278-026-02089-6)]


**A Deep Dual-Domain Interaction Reconstruction Framework With Adaptive Gating Fusion for Low-Field MRI** \
*Yuan Yang, Sirui Wang, Hanyu Zhang, Yitao Liu, Yuchen Wu, Zhengxiu Wu, Rongsheng Lu, and Xiaowen Jiang* \
[12 June 2026] [NMR Biomed.]<br>
[[Paper](https://doi.org/10.1002/nbm.70330)]


**Reliability of Whole-Liver Liver-Fat-Quantification Between Deep Learning-Accelerated and Standard Volumetric Interpolated Breath-hold Examination Dixon Sequences in a Prospective Oncology Cohort** \
*Stephan Rau, Anna Fink, Ralph Strecker, Marcel Dominik Nickel, Lea Jigme Michel, Vlad Sacalean, Kai Falko Kästingschäfer, David Klemm, Alexander Rau, Fabian Bamberg, Jakob Weiss, and Maximilian Frederik Russe* \
[June 2026] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001242)]


**Phase-map synthesis from magnitude-only MR images using conditional score-based diffusion models with application in training of accelerated MRI reconstruction models** \
*M. Berk Sahin, Dilek Yalcinkaya, Abolfazl Hashemi, and Behzad Sharif* \
[2026] [CVPR Workshop]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/html/Sahin_Phase-map_synthesis_from_magnitude-only_MR_images_using_conditional_score-based_diffusion_CVPRW_2026_paper.html)] [[Github](https://github.com/BerkMSahin/phase-map-synthesis-with-SBDM)]


**FSSCAN: Frequency-Spatial Skip Connection Attention Network for complex-valued MRI reconstruction** \
*Madhu Kashania, Ankit Rajpal, and Aman Gaur* \
[June 2026] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2026.109923)]


**Clinical evaluation of accelerated breath-held and free-breathing cine cardiac MRI using model-based deep learning reconstruction (SonicDL) in children and young adults** \
*Murat Kocaoglu, Hieu Ta, Sean M. Lang, Cara E. Morin, and Amol Pednekar* \
[28 May 2026] [Pediatric Radiology]<br>
[[Paper](https://doi.org/10.1007/s00247-026-06676-1)]


**Aleatoric uncertainty in accelerated prostate MRI reconstruction: echo-train dropout versus Gaussian noise Monte Carlo sampling** \
*Quintin van Lohuizen, Stefan J. Fransen, Henkjan Huisman, Jelmer M. Wolterink, Thomas C. Kwee, Derya Yakar, and Frank F. J. Simonis* \
[26 May 2026] [MAGMA]<br>
[[Paper](https://doi.org/10.1007/s10334-026-01369-0)]


**Knowledge-guided multi-geometric window transformer for cardiac cine MRI reconstruction** \
*Jun Lyu, Guangming Wang, Yunqi Wang, Jing Qin, and Chengyan Wang* \
[May 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.103936)] [[Github](https://github.com/MICV-Lab/KGMgT)]


**Toward Modality- and Sampling-Universal Learning Strategies for Accelerating Cardiovascular Imaging: Summary of the CMRxRecon2024 Challenge** \
*Fanwen Wang, Zi Wang, Yan Li, Jun Lyu, Chen Qin, Shuo Wang, Kunyuan Guo, Mengting Sun, Mingkai Huang, Haoyu Zhang, Michael Tänzer, Qirong Li, Xinran Chen, Jiahao Huang, Yinzhe Wu, Haosen Zhang, Kian Anvari Hamedani, Yuntong Lyu, Longyu Sun, Qing Li, Tianxing He, Lizhen Lan, Qiong Yao, Ziqiang Xu, Bingyu Xin, Dimitris N. Metaxas, Narges Razizadeh, Shahabedin Nabavi, George Yiasemis, Jonas Teuwen, Zhenxi Zhang, Sha Wang, Chi Zhang, Daniel B. Ennis, Zhihao Xue, Chenxi Hu, Ruru Xu, Ilkay Oksuz, Donghang Lyu, Yanxin Huang, Xinrui Guo, Ruqian Hao, Jaykumar H. Patel, Guanke Cai, Binghua Chen, Yajing Zhang, Sha Hua, Zhensen Chen, Qi Dou, Xiahai Zhuang, Qian Tao, Wenjia Bai, Jing Qin, He Wang, Claudia Prieto, Michael Markl, Alistair Young, Hao Li, Xihong Hu, Lianming Wu, Xiaobo Qu, Guang Yang, and Chengyan Wang* \
[May 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2025.3641610)] [[Github](https://github.com/CmrxRecon/CMRxRecon2024)]


**Adaptive K-Space Radial Sampling for Cardiac MRI with Reinforcement Learning** \
*Ruru Xu and Ilkay Oksuz* \
[2026] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_19)] [[Github](https://github.com/Ruru-Xu/RL-kspace-Radial-Sampling)]


**CRUNet-MR-Univ: A Foundation Model for Diverse Cardiac MRI Reconstruction** \
*Donghang Lyu, Marius Staring, Hildo J. Lamb, and Mariya Doneva* \
[2026] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_29)]


**Physics-Informed Spatial-Scaling Transformer for Accelerated MRI Reconstruction** \
*Valiyeh Ansarian Nezhad and Tolga Çukur* \
[2026] [ISBI]<br>
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515372)]


**Causality-driven dual-domain network enhanced by Gaussian splatting for magnetic resonance image reconstruction** \
*Tong Hou, Hongqing Zhu, Zhong Zheng, Kai Chen, Ying Wang, and Bingcang Huang* \
[May 2026] [Neural Networks]<br>
[[Paper](https://doi.org/10.1016/j.neunet.2025.108472)]


**Branch Learning in MRI: More Data, More Models, More Training** \
*Yuyang Li, Yipin Deng, Zijian Zhou, and Peng Hu* \
[2026] [MICCAI Workshop]<br>
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_32)]


**On the Utility of Foundation Models for Fast MRI : Vision-Language-Guided Image Reconstruction** \
*Ruimin Feng, Xingxin He, Ronald Mercer, Zachary Stewart, and Fang Liu* \
[07 April 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70374)]


**Diagnostic assessment of artificial intelligence reconstruction on accelerated prostate MRI: a retrospective, paired, multi-reader multi-case study** \
*Quintin van Lohuizen, Stefan Johannes Fransen, George Yiasemis, Jasper Jonathan Twilt, Christian Roest, Yuki Arita, Jacob Borstlap, Jurgen J. Fütterer, Maarten de Rooij, Dennis B. Rouw, Ivo G. Schoots, Baris Turkbey, Samuel Joseph Withey, Frank F. J. Simonis, Henkjan Huisman, Thomas Christian Kwee, Jonas Teuwen, and Derya Yakar* \
[02 April 2026] [European Radiology]<br>
[[Paper](https://doi.org/10.1007/s00330-026-12479-7)]


**Feasibility of Free-breathing Deep Learning-reconstructed Single-Shot Cine MRI in Participants with Arrhythmia: Comparison with Conventional Segmented Cine MRI** \
*Nan Zhang, Fan Du, Caizhong Chen, Xiuzheng Yue, Mengsu Zeng, and Hang Jin* \
[01 April 2026] [Radiology: Cardiothoracic Imaging]<br>
[[Paper](https://doi.org/10.1148/ryct.250298)]


**Evaluating Structural Uncertainty in Accelerated MRI: Are Voxelwise Measures Useful Surrogates?** \
*Luca L. C. Trautmann, Peter A. Wijeratne, Itamar Ronen, and Ivor J. A. Simpson* \
[2026] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-09513-8_49)]


**Image Content Matters: An Image Content Aware State Space Model for Accelerated MRI Reconstruction** \
*Yucong Meng, Zhiwei Yang, Kexue Fu, Zhijian Song, and Yonghong Shi* \
[2026] [AAAI]<br>
[[Paper](https://doi.org/10.1609/aaai.v40i10.37748)]


**Benchmarking Hybrid CNN -Transformer Versus Pure Transformer Architectures for Accelerated Hyperpolarized 129 Xe MRI Reconstruction** \
*Ramtin Babaeipour, Matthew S. Fox, Grace Parraga, and Alexei Ouriadov* \
[27 March 2026] [JMRI]<br>
[[Paper](https://doi.org/10.1002/jmri.70314)]


**DH-Mamba: Exploring Dual-Domain Hierarchical State Space Models for MRI Reconstruction** \
*Yucong Meng, Zhiwei Yang, Kexue Fu, Zhijian Song, and Yonghong Shi* \
[March 2026] [IEEE TCSVT]<br>
[[Paper](https://doi.org/10.1109/TCSVT.2025.3614828)] [[Github](https://github.com/XiaoMengLiLiLi/DH-Mamba)]


**Mamba-driven multi-modality MRI reconstruction via scale diversity fusion and frequency purification** \
*Tong Hou, Hongqing Zhu, Zhong Zheng, Kai Chen, Ying Wang, and Bingcang Huang* \
[March 2026] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.109111)]


**Multi-contrast feature cross entanglement network for joint MR image reconstruction and super-resolution** \
*Guoqing Ge, Weisheng Li, Yucheng Shu, and Xiaoyu Qiao* \
[March 2026] [Knowledge-Based Systems]<br>
[[Paper](https://doi.org/10.1016/j.knosys.2026.115368)]


**GL-mamba-net: A magnetic resonance imaging restoration network with global-local mamba** \
*Ke Liang, Zhijin Lin, Jie Yang, Teng Yu, Jieru Chi, and Feng Liu* \
[February 2026] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2025.110574)]


**Multi-contrast low-field MRI acceleration with k-space progressive learning and image-space hybrid attention fusion** \
*Xiaohan Xing, Qi Chen, Lequan Yu, Liang Qiu, Lingting Zhu, Lei Xing, and Lianli Liu* \
[January 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2025.103833)]


**Near-Real-Time Multi-Parametric Quantitative MRI using Parallel Non-Cartesian 6D Spatial-Temporal Dictionary Learning Neural Networks** \
*Zhijun Wang, Wenlong Feng, Sifan Wu, Huajun She, Zekang Ding, and Yiping P. Du* \
[2026] [IEEE TBME]<br>
[[Paper](https://doi.org/10.1109/TBME.2026.3685550)]


**Scan-Adaptive MRI Undersampling Using Neighbor-Based Optimization (SUNO)** \
*Siddhant Gautam, Angqi Li, Nicole Seiberlich, Jeffrey A. Fessler, and Saiprasad Ravishankar* \
[2026] [IEEE Transactions on Computational Imaging]<br>
[[Paper](https://doi.org/10.1109/TCI.2026.3653330)] [[Github](https://github.com/sidgautam95/adaptive-sampling-mri-suno)]


**Deep learning reconstruction for fast cardiovascular magnetic resonance imaging protocol: A comparative study with conventional cardiovascular magnetic resonance** \
*Yiying Hua, Hongfei Lu, Shiya Wang, Xiuzheng Yue, Fan Du, Nan Zhang, Mengmeng Yu, Yinyin Chen, Mengsu Zeng, and Hang Jin* \
[2026] [JCMR]<br>
[[Paper](https://doi.org/10.1016/j.jocmr.2025.102017)]


**Ultrafast deep learning super-resolution single-shot T2-weighted imaging for robust edema visualization in cardiovascular magnetic resonance** \
*Taraneh Aziz-Safaie, Christoph Katemann, Johannes M. Peeters, Oliver M. Weber, Leon M. Bischoff, Dmitrij Kravchenko, Narine Mesropyan, Thomas M. Vollbrecht, Lucia D. Beissel, Claus C. Pieper, Daniel Kuetting, Julian A. Luetkens, and Alexander Isaak* \
[2026] [JCMR]<br>
[[Paper](https://doi.org/10.1016/j.jocmr.2026.102708)]


**PaDIS-MRI: Patch-Based Diffusion for Data-Efficient, Radiologist-Preferred MRI Reconstruction** \
*Rohan Sanda, Asad Aali, Andrew Johnston, Eduardo Pontes Reis, Gordon Wetzstein, and Sara Fridovich-Keil*\
[2025] [Proceedings of Machine Learning Research ]<br>
[[Paper](https://openreview.net/forum?id=ZtJqKA730g)][[Github](https://github.com/voilalab/PaDIS-MRI)] 

**Frequency-spatial synergistic network for accelerated multi-contrast MRI reconstruction** \
*Ke Li, Dong Liang, Guoqing Chen, Qiyu Jin, and  Tieyong Zeng* \
[2025] [Computerized Medical Imaging and Graphics]<br>
[[Paper](https://doi.org/10.1016/j.compmedimag.2025.102682)]

**LMO: Linear Mamba Operator for MRI Reconstruction** \
*Li, Wei and Jiang, Jiawei and Wu, Jie and Yu, Kaihao and Zheng, Jianwei* \
[2025] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_LMO_Linear_Mamba_Operator_for_MRI_Reconstruction_CVPR_2025_paper.pdf)] [[Github](https://github.com/ZhengJianwei2/LMO)] 


**Conjugate gradient and deep learning reconstructions: reduced time without affecting image quality and nodule detection** \
*Yoshiharu Ohno, Yoshiyuki Ozawa, Takahiro Ueda, Masahiko Nomura, Natsuka Yazawa, Maiko Shinohara, Kaori Yamamoto, Yuichiro Sano, Masato Ikedo, Masanori Ozaki, Masao Yui, Shohei Harada, Saki Takeda, Akiyoshi Iwase, Takeshi Yoshikawa, and Daisuke Takenaka* \
[24 December 2025] [European Radiology]<br>
[[Paper](https://doi.org/10.1007/s00330-025-12153-4)]


**Model-based spatiotemporal synthetic data generation framework and deep-learning reconstruction for real-time MRI oxygen extraction fraction mapping** \
*Zejun Wu, Qinqin Yang, Nuowei Ge, Jiechao Wang, Liuhong Zhu, Jianjun Zhou, Jianfeng Bao, Jianfa Chen, Lina Xu, Zhong Chen, Jianhui Zhong, Shuhui Cai, and Congbo Cai* \
[09 December 2025] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae2380)]


**Artificial Intelligence-Accelerated vs. Conventional Diffusion-Weighted Imaging for Prostate MRI: Comparing Quality and Quantitative Metrics** \
*Vlad Sacalean, Oliver Gebler, Wei Liu, Ralph Strecker, Elisabeth Weiland, Fabian Bamberg, Jakob Weiß, Maximilian F. Russe, and Hannes Engel* \
[December 2025] [Academic Radiology]<br>
[[Paper](https://doi.org/10.1016/j.acra.2025.12.003)]


**Accelerated RAKI reconstruction for multi-slice cardiac cine applications** \
*Lucile Quillien, Julien Oster, and Pierre‐André Vuissoz* \
[19 November 2025] [Med. Phys.]<br>
[[Paper](https://doi.org/10.1002/mp.70145)]


**Magnetic resonance image processing transformer for general accelerated image restoration** \
*Guoyao Shen, Mengyu Li, Stephan Anderson, Chad W. Farris, and Xin Zhang* \
[17 November 2025] [Sci. Rep.]<br>
[[Paper](https://doi.org/10.1038/s41598-025-23851-w)]


**DDMamba: A Dual-Domain Mamba for Multi-Modal Magnetic Resonance Imaging Reconstruction With Fourier Fusion** \
*Zhijin Lin, Jie Yang, Teng Yu, Jieru Chi, and Feng Liu* \
[02 November 2025] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70148)]


**Fast and Robust Single-Shot Cine Cardiac MRI Using Deep Learning Super-Resolution Reconstruction** \
*Taraneh Aziz-Safaie, Leon M. Bischoff, Christoph Katemann, Johannes M. Peeters, Dmitrij Kravchenko, Narine Mesropyan, Lucia D. Beissel, Tatjana Dell, Oliver M. Weber, Claus C. Pieper, Daniel Kütting, Julian A. Luetkens, and Alexander Isaak* \
[October 2025] [Investigative Radiology]<br>
[[Paper](https://doi.org/10.1097/RLI.0000000000001186)]


**FDGANet: Frequency dynamic graph attention network for undersampled MRI reconstruction** \
*Yushan Xie, Dongping Xiong, Heng Zhao, Hong Zhou, Bingo Wing-Kuen Ling, and Xiaozhi Zhang* \
[October 2025] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.107933)]


**DGEDDGAN: A dual-domain generator and edge-enhanced dual discriminator generative adversarial network for MRI reconstruction** \
*Qiaohong Liu, Weikun Zhang, Yuting Zhang, Xiaoxiang Han, Yuanjie Lin, Xinyu Li, Keyan Chen* \
[08 March 2025] [Magnetic Resonance Imaging]<br>
[[Paper](https://doi.org/10.1016/j.mri.2025.110381)]


**SHFormer: Dynamic spectral filtering convolutional neural network and high-pass kernel generation transformer for adaptive MRI reconstruction** \
*Sriprabha Ramanarayanan, Rahul G.S., Mohammad Al Fahim, Keerthi Ram, Ramesh Venkatesan, Mohanasankar Sivaprakasam* \
[08 March 2025] [Neural Networks]<br>
[[Paper](https://doi.org/10.1016/j.neunet.2025.107334)] [[Github](https://github.com/sriprabhar/SHFormer)] 


**Lightweight Hypercomplex MRI Reconstruction: A Generalized Kronecker-Parameterized Approach** \
*Haosen Zhang, Jiahao Huang, Yinzhe Wu, Congren Dai, Fanwen Wang, Zhenxuan Zhang, and Guang Yang* \
[02 January 2026] [MLMI, MICCAI Workshop]<br>
[[Paper](https://doi.org/10.1007/978-3-032-09513-8_10)]


**Improving Deep Learning for Accelerated MRI With Data Filtering** \
*Kang Lin, Anselm Krainovic, Kun Wang, and Reinhard Heckel* \
[2025] [NeurIPS]<br>
[[Paper](https://doi.org/10.52202/085713-5696)]


**Towards Prospective Medical Image Reconstruction via Knowledge-Informed Dynamic Optimal Transport** \
*Taoran Zheng, Yan Yang, Xing Li, Xiang Gu, Jian Sun, and Zongben Xu* \
[2025] [NeurIPS]<br>
[[Paper](https://doi.org/10.52202/085713-1368)] [[Github](https://github.com/TaoranZheng717/KIDOT)]


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
**Physics-Driven Autoregressive State Space Models for Medical Image Reconstruction** \
*Bilal Kabas, Fuat Arslan, Valiyeh A. Nezhad, Kader K. Oguz, Saban Ozturk, Emine U. Saritas, and Tolga Cukur* \
[2026] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2026.3716153)] [[Github](https://github.com/icon-lab/MambaRoll)]


**Efficient Unrolled Networks for Large-Scale 3D Inverse Problems** \
*Romain Vo and Julián Tachella* \
[2026] [CVPR] \
[[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Vo_Efficient_Unrolled_Networks_for_Large-Scale_3D_Inverse_Problems_CVPR_2026_paper.html)]


**PnP-CM: Consistency Models as Plug-and-Play Priors for Inverse Problems** \
*Merve Gulle, Junno Yun, Yasar Utku Alcalar, and Mehmet Akcakaya* \
[2026] [CVPR] \
[[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Gulle_PnP-CM_Consistency_Models_as_Plug-and-Play_Priors_for_Inverse_Problems_CVPR_2026_paper.html)] [[Github](https://github.com/MerveGulle/PnP-CM)]


**SDUM: A Scalable Deep Unrolled Model for Universal Cardiac MRI Reconstruction** \
*Puyang Wang, Pengfei Guo, Keyi Chai, Jinyuan Zhou, Daguang Xu, and Shanshan Jiang* \
[2026] [ECCV] \
[[Paper](https://doi.org/10.1007/978-3-032-37435-6_21)] [[Github](https://github.com/NVIDIA-Medtech/NV-Raw2insights-MRI)]


**SSCA-DIPNet: Structured Sparse and Channel-Attentive Deep Image Prior Network for Highly-Accelerated MRI** \
*Yue Yin, Da Cao, Can Hu, Yue Jiang, Run Zhang, Jinsong Xia, Wei Wang, XiuHan Li, and Lei Duan* \
[15 September 2026] [Biomed. Phys. Eng. Express] \
[[Paper](https://doi.org/10.1088/2057-1976/aea7a1)]


**A plug-and-play method for guided multi-contrast MRI reconstruction based on content/style modeling** \
*Chinmay Rao, Matthias van Osch, Nicola Pezzotti, Jeroen de Bresser, Mark van Buchem, Laurens Beljaards, Jakob Meineke, Elwin de Weerdt, Huangling Lu, Mariya Doneva, and Marius Staring* \
[September 2026] [Medical Image Analysis] \
[[Paper](https://doi.org/10.1016/j.media.2026.104160)]


**A Deep Nonlinear Subspace Modeling and Reconstruction for Diffusion-Weighted Imaging Using Denoising Auto-Encoder** \
*Julius Glaser, Zhengguo Tan, Annika Hofmann, Frederik Bernd Laun, and Florian Knoll* \
[04 August 2026] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70496)]


**Adaptive low-rank plus sparse unrolling network with multi-scale attention for dynamic MRI reconstruction** \
*Xiaotong Liu, Jingfei He, Chenghu Mi, and Abdelmounim Boudi* \
[August 2026] [Biomedical Signal Processing and Control] \
[[Paper](https://doi.org/10.1016/j.bspc.2026.110317)]


**Robust radial MRI reconstruction under multi-scenario mismatch via deep prior guided weighted sparsity** \
*Biao Qu, Taishan Kang, Zhipeng Feng, Shaomao Lü, Cina Zheng, Huajun She, Chenchen Dai, Yamei Luo, Jia Wu, and Jianjun Zhou* \
[August 2026] [Expert Systems with Applications] \
[[Paper](https://doi.org/10.1016/j.eswa.2026.132330)]


**Fully 3D Unrolled Magnetic Resonance Fingerprinting Reconstruction via Staged Pretraining and Implicit Gridding** \
*Yonatan Urman, Mark Nishimura, Daniel R. Abraham, Xiaozhi Cao, and Kawin Setsompop* \
[29 July 2026] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70500)]


**Mamba2SVN: a Mamba2 and reconstruction-cooperative sensitivity refinement-based variational network for parallel MRI reconstruction** \
*Haiyuan Li, Jizhong Duan, Haibo Tao, Zhenyu Huang, Peng Ding, and Yu Liu* \
[23 June 2026] [PMB] \
[[Paper](https://doi.org/10.1088/1361-6560/ae788b)]


**Robust Physics-Based Deep MRI Reconstruction via Diffusion Purification** \
*Ismail R. Alkhouri, Shijun Liang, Rongrong Wang, Qing Qu, and Saiprasad Ravishankar* \
[May 2026] [IEEE TNNLS] \
[[Paper](https://doi.org/10.1109/TNNLS.2025.3631742)]


**GENRE-CMR: Generalizable Deep Learning for Diverse Multi-domain Cardiac MRI Reconstruction** \
*Kian Anvari Hamedani, Narges Razizadeh, Shahabedin Nabavi, and Mohsen Ebrahimi Moghaddam* \
[2026] [MICCAI] \
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_27)] [[Github](https://github.com/kiananvari/GENRE-CMR)]


**HierAdaptMR: Cross-Center Cardiac MRI Reconstruction with Hierarchical Feature Adapters** \
*Ruru Xu and Ilkay Oksuz* \
[2026] [MICCAI] \
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_28)] [[Github](https://github.com/Ruru-Xu/HierAdaptMR)]


**VTransFormer: A Deep Unrolled Foundation Model for Multi-center Multimodal Accelerated Cardiac MRI Reconstruction** \
*Neda Tavakoli, Mingzhen Li, Santiago López-Tapia, Amir Ali Rahsepar, Aggelos K. Katsaggelos, and Daniel Kim* \
[2026] [MICCAI] \
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_31)]


**Dual-Branch Deep Unfolding Network for Compressed Sensing MRI Reconstruction** \
*Yujie Liu, Yu Luo, Jie Ling, Lieqing Lin, Ye Wu, and Shun Yao* \
[May 2026] [J-BHI] \
[[Paper](https://doi.org/10.1109/JBHI.2025.3624136)]


**FGMamba: A feature-guided deep unfolding network with state space models for efficient MRI reconstruction** \
*Jiawei Pan, Yu Luo, Ziyi Chen, Min Li, Jie Ling, Jing Qin, and Shun Yao* \
[May 2026] [Biomedical Signal Processing and Control] \
[[Paper](https://doi.org/10.1016/j.bspc.2026.109542)] [[Github](https://github.com/Jiawei-pan/FGMamba)]


**JSDU-Net: Joint sensitivity-learning driven deep unfolding network for accelerated radial MRI reconstruction** \
*Biao Qu, Huajun She, Qingxia Wu, Pingping Jie, Qi Yao, Liulu Zhang, Yuting Fu, Yamei Luo, Taishan Kang, and Gaofeng Zheng* \
[May 2026] [Expert Systems with Applications] \
[[Paper](https://doi.org/10.1016/j.eswa.2026.131351)]


**E2D-Unroll: efficient equivariant deformable unrolling networks for cardiac cine MRI reconstruction** \
*Yuliang Zhu, Zhaochi Wen, Shiying Ke, Yulin Wang, Zhuo-Xu Cui, Qingyong Zhu, Yuanyuan Liu, Jianfeng Ren, Jing Cheng, Chengbo Wang, and Dong Liang* \
[24 April 2026] [PMB] \
[[Paper](https://doi.org/10.1088/1361-6560/ae5c53)]


**Reconstruction of Under-Sampled Images and Concurrent Optimization of Sampling Masks for 3D Carotid Simultaneous Non-Contrast Angiography and intraPlaque Hemorrhage MRI With Model Based Deep Learning Architecture ( deepSNAP )** \
*Jiachen Ji, Chuyu Liu, Qinxin Wang, Shuo Chen, Zhongsen Li, Le He, Xihai Zhao, and Rui Li* \
[23 April 2026] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70401)]


**Graph-Fista-Net: An Interpretable Graph Unrolling Network for Fast Compressed Sensing MRI** \
*Aromal C. J and Sumit Datta* \
[2026] [ISBI] \
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515756)]


**Consistency Models for Fast MRI Using Regularization by Denoising** \
*Merve Gülle, Junno Yun, Yaşar Utku Alçalar, and Mehmet Akçakaya* \
[2026] [ISBI] \
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11516008)]


**Revisiting MRI Reconstruction Using a Combination of Complex and Magnitude Measurements with Learned Priors** \
*Mahdi Saberi and Mehmet Akçakaya* \
[2026] [ISBI] \
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515989)]


**Phase-Correction Strategies for Physics-Driven Deep Learning Reconstruction of Accelerated Non-Cartesian Multi-Echo fMRI** \
*Mahdi Saberi, Zidan Yu, Christoph Rettenmeier, Andrew Stenger, and Mehmet Akçakaya* \
[2026] [ISBI] \
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515729)]


**A dense recurrent unrolling network leveraging spatio-temporal priors for highly-accelerated dynamic MRI** \
*Bin Wang, Yusheng Lian, Wan Zhang, Zilong Liu, Xiaojie Hu, Beiqing Huang, and Yuanyuan Wang* \
[April 2026] [MRI] \
[[Paper](https://doi.org/10.1016/j.mri.2025.110595)]


**Deep-Learning-Based Image Reconstruction to Improve End-Diastolic and Systolic Cardiac T1 Mapping** \
*Daniel Amsel, Jens Wetzl, Daniel Giese, Christoph Tillmanns, Rolf Gebker, Kelvin Chow, Michaela Schmidt, Andreas Lingg, Jens Kübler, Patrick Krumm, and Thomas Küstner* \
[19 March 2026] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70353)]


**FlowVN Trained on a Single Dataset Enables Rapid Reconstruction of Highly Accelerated 4D Flow MRI Across Multiple Sites** \
*Sohaib Ayaz Qazi, Tamara Bianchessi, Federica Viola, Chiara Trenti, Erik Ylipää, Tino Ebbers, and Petter Dyverfeldt* \
[26 February 2026] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70317)]


**A Trust-Guided Approach to MR Image Reconstruction With Side Information** \
*Arda Atalık, Sumit Chopra, and Daniel K. Sodickson* \
[January 2026] [TMI] \
[[Paper](https://doi.org/10.1109/TMI.2025.3594363)] [[Github](https://github.com/sodicksonlab/TGVN)]


**Super-MoCo-MoDL: A combined super-resolution and motion-corrected undersampled deep-learning reconstruction framework for three-dimensional whole-heart cardiac magnetic resonance imaging** \
*Andrew Phair, Simon J. Littlewood, Anastasia Fotaki, Thomas J. Fletcher, Lina Felsner, Won-Yong Kim, Claudia Prieto, and René Botnar* \
[2026] [JCMR] \
[[Paper](https://doi.org/10.1016/j.jocmr.2025.101990)]


**A Convergent Generalized Krylov Subspace Method for Compressed Sensing MRI Reconstruction With Gradient-Driven Denoisers** \
*Tao Hong, Umberto Villa, and Jeffrey A. Fessler* \
[2026] [IEEE Transactions on Computational Imaging] \
[[Paper](https://doi.org/10.1109/TCI.2026.3655489)]


**Deep equilibrium-adversarial robust unfolding network for MRI reconstruction** \
*Tian Zhou, Kun Shang, Congcong Liu, Zhuoxu Cui, and Dong Liang* \
[13 December 2025] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.70185)]


**Jointly Learned 3D Non-Cartesian Sampling With Wave Encoding and Reconstruction for Neurovascular Phase Contrast MRI** \
*Chenwei Tang, Brock W. Jolicoeur, James Rice, Caroline A. Doctor, Zaynab S. Yardim, Leonardo A. Rivera‐Rivera, Laura B. Eisenmenger, and Kevin M. Johnson* \
[08 December 2025] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70215)]


**Deep Separable Spatiotemporal Learning for Fast Dynamic Cardiac MRI** \
*Zi Wang, Min Xiao, Yirong Zhou, Chengyan Wang, Naiming Wu, Yi Li, Yiwen Gong, Shufu Chang, Yinyin Chen, Liuhong Zhu, Jianjun Zhou, Congbo Cai, He Wang, Xianwang Jiang, Di Guo, Guang Yang, and Xiaobo Qu* \
[December 2025] [IEEE TBME] \
[[Paper](https://doi.org/10.1109/TBME.2025.3574090)]


**DUN-SRE: Deep Unrolling Network With Spatiotemporal Rotation Equivariance for Dynamic MRI Reconstruction** \
*Yuliang Zhu, Jing Cheng, Qi Xie, Zhuo-Xu Cui, Qingyong Zhu, Yuanyuan Liu, Xin Liu, Jianfeng Ren, Chengbo Wang, and Dong Liang* \
[December 2025] [JSTSP] \
[[Paper](https://doi.org/10.1109/JSTSP.2025.3618589)] [[Github](https://github.com/zhuyuliang0106/DUN-SRE-for-Dynamic-MRI-Reconstruction)]


**STAND-Net: Lightning-Fast MRI Reconstruction via Stage-Aware Deep Unrolling With Neural Tensor Decomposition** \
*Maosong Ran, Ziyuan Yang, Tao Wang, Zhiwen Wang, Jingfeng Lu, and Yi Zhang* \
[December 2025] [JSTSP] \
[[Paper](https://doi.org/10.1109/JSTSP.2025.3632569)]


**Accelerated Chemical Exchange Saturation Transfer Imaging With Deep Unrolling Networks and Synthetic Brain Tumor Datasets** \
*Yuyan Wang, Junjie Wen, Jianping Xu, Zhechuan Dai, Yi‐Cheng Hsu, Kannie W. Y. Chan, and Yi Zhang* \
[05 November 2025] [Magn. Reson. in Med.] \
[[Paper](https://doi.org/10.1002/mrm.70172)]


**Transformer–Mamba based dynamic threshold generation for dual frame network and its application in compressed sensing MRI** \
*Yu‑ang Xiao and Yueming Su*\
[22 October 2025] [EURASIP Journal on Advances in Signal Processing] \
[[Paper](https://doi.org/10.1186/s13634-025-01259-y)][[Github](https://github.com/ladderlab-xjtu/LF-MRI)]




**Robust MRI Reconstruction by Smoothed Unrolling (SMUG)** \
*Shijun Liang, Van Hoang Minh Nguyen, Jinghan Jia, Ismail R. Alkhouri, Sijia Liu, and Saiprasad Ravishankar* \
[October 2025] [JSTSP] \
[[Paper](https://doi.org/10.1109/JSTSP.2025.3615540)] [[Github](https://github.com/sjames40/SMUG_journal)]


**Model-unrolled fast MRI with weakly supervised lesion enhancement** \
*Fangmao Ju, Yuzhu He, Fan Wang, Xianjun Li, Chen Niu, Chunfeng Lian, Jianhua Ma*\
[7 September 2025] [Medical Image Analysis] \
[[Paper](https://doi.org/10.1016/j.media.2025.103806)][[Github](https://github.com/ladderlab-xjtu/LF-MRI)]



**Unsupervised 4D-flow MRI reconstruction based on partially-independent generative modeling and complex-difference sparsity constraint** \
*Zhongsen Li, Aiqi Sun, Haining Wei, Wenxuan Chen, Chuyu Liu, Haozhong Sun, Chenlin Du, Rui Li*\
[10 August 2025] [Medical Image Analysis] \
[[Paper](https://doi.org/10.1016/j.media.2025.103769)][[Github](https://github.com/lizs17/Unsup_4DFlow_MRI)]


**Anatomy-Aware Deep Unrolling for Task-Oriented Acceleration of Multi-Contrast MRI** \
*Yuzhu He, Chunfeng Lian, Ruyi Xiao, Fangmao Ju, Chao Zou, and Zongben Xu*\
[7 September 2025] [IEEE TMI] \
[[Paper](https://doi.org/10.1109/TMI.2025.3568157)][[Github](https://github.com/ladderlab-xjtu/A2MC-MRI)]


**Dual-Domain Self-Consistency-Enhanced Deep Unfolding Network for accelerated MRI reconstruction** \
*Zhijie Wang, Jinbao Wei, Gang Yang, Aiping Liu, Wei Wei, Bensheng Qiu, and Xun Chen* \
[5 August 2025] [Computer Methods and Programs in Biomedicine] \
[[Paper](https://doi.org/10.1016/j.cmpb.2025.108995)][[Github](https://github.com/wangzj1997/DSDUN.git)]



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


**Time-Embedded Algorithm Unrolling for Computational MRI** \
*Junno Yun, Yasar Utku Alcalar, and Mehmet Akcakaya* \
[2025] [NeurIPS] \
[[Paper](https://doi.org/10.52202/085713-3140)] [[Github](https://github.com/JN-Yun/TE-Unrolling-MRI)]


**Convergent Complex Quasi-Newton Proximal Methods for Gradient-Driven Denoisers in Compressed Sensing MRI Reconstruction** \
*Tao Hong, Zhaoyi Xu, Se Young Chun, Luis Hernandez-Garcia, and Jeffrey A. Fessler* \
[2025] [IEEE Transactions on Computational Imaging] \
[[Paper](https://doi.org/10.1109/TCI.2025.3625052)]


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


**Score-based generative priors-guided model-driven Network for MRI reconstruction** \
*Xiaoyu Qiao, Weisheng Li, Bin Xiao, Yuping Huang, and Lijian Yang* \
[July 2025] [Biomedical Signal Processing and Control] \
[[Paper](https://doi.org/10.1016/j.bspc.2025.107564)]

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

**Guided MRI Reconstruction via Schrödinger Bridge** \
*Yue Wang, Yuanbiao Yang, Zhuo-xu Cui, Tian Zhou, Bingsheng Huang, Hairong Zheng, Dong Liang, and Yanjie Zhu* \
[2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2026.3725165)]


**From Coarse to Continuous: Progressive Refinement Implicit Neural Representation for Motion-Robust Anisotropic MRI Reconstruction** \
*Zhenxuan Zhang, Lipei Zhang, Yanqi Cheng, Zi Wang, Fanwen Wang, Haosen Zhang, Yue Yang, Yinzhe Wu, Jiahao Huang, Angelica I. Aviles-Rivero, Zhifan Gao, Guang Yang, and Peter J. Lally* \
[2026] [Transactions on Image Processing]<br>
[[Paper](https://doi.org/10.1109/TIP.2026.3678052)]


**ADOBI: Adaptive Diffusion Bridge for Blind Inverse Problems With Application to MRI Reconstruction** \
*Yuyang Hu, Albert Peng, Weijie Gan, and Ulugbek S. Kamilov* \
[2026] [IEEE Transactions on Computational Imaging]<br>
[[Paper](https://doi.org/10.1109/TCI.2026.3678407)] [[Github](https://github.com/wustl-cig/adobiwww)]


**A Detail-Preserving Latent Diffusion Model for Arbitrarily Accelerated MR Imaging** \
*Zhongjian Jiang, Kaicong Sun, and Dinggang Shen* \
[2026] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-09513-8_17)]


**Multi-Modal Iterative Refinement Network with K-space Posterior Correction for MRI reconstruction** \
*Xin Tang, Yubao Sun, Ziyu Sheng, and Junxia Li* \
[November 2026] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2026.110729)]


**LDPM-v2: Towards undersampled MRI reconstruction with multimodal one-step latent diffusion prior** \
*Jingwei Guan, Xingjian Tang, Linge Li, Yanlin Wu, Kai Tong, Junjie Wu, Li Yan, and Xingyu Zeng* \
[October 2026] [CMIG]<br>
[[Paper](https://doi.org/10.1016/j.compmedimag.2026.102818)]


**Highly Accelerating Joint Intracranial and Carotid Vessel Wall Imaging Using ESPIRiT -Driven Diffusion Model Reconstruction** \
*Tian Zhou, Yulong Qi, Sen Jia, Lei Zhang, Fei Feng, Zhuo‐Xu Cui, and Dong Liang* \
[14 September 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70567)]


**Autocalibration signal-guided multi-frequency diffusion model for dynamic MRI reconstruction** \
*Yu Guan, Wenchao Deng, Qi Qi, Minghui Zhang, Haikun Qi, Xiang Ji, and Qiegen Liu* \
[09 September 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/aea51a)]


**q3-MuPa: Quick, quiet, quantitative multi-parametric MRI using physics-informed diffusion models** \
*Shishuai Wang, Florian Wiesinger, Noemi Sgambelluri, Carolin Pirkl, Stefan Klein, Juan A. Hernandez-Tamames, and Dirk H.J. Poot* \
[September 2026] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2026.110699)]


**Memory-efficient image reconstruction using diffusion models for accelerated 3D non-Cartesian UTE imaging** \
*Jonas Petersen, Stefan Sommer, and Thomas Küstner* \
[19 August 2026] [MAGMA]<br>
[[Paper](https://doi.org/10.1007/s10334-026-01403-1)]


**MotionDPS: Motion-Compensated 3-D Brain MRI Reconstruction** \
*Antonio Ortiz-Gonzalez, Erich Kobler, Lukas Schletter, and Alexander Effland* \
[August 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2026.3705847)]


**Accelerating Stroke MRI With Diffusion Probabilistic Models Through Large-Scale Pre-Training and Target-Specific Fine-Tuning** \
*Yamin Arefeen, Sidharth Kumar, Steven Warach, Hamidreza Saber, and Jonathan Isaac Tamir* \
[09 July 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70501)]


**Noise-aware adaptive diffusion sampling for accelerated knee MRI reconstruction** \
*Dabin Kim and Hongki Lim* \
[03 June 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae6af5)]


**Learning Fourier-Constrained Diffusion Bridges for MRI Reconstruction** \
*M. Usama Mirza, Onat Dalmaz, Hasan A. Bedel, Gokberk Elmas, Yilmaz Korkmaz, Alper Gungor, Salman U. H. Dar, Kader K. Oguz, and Tolga Çukur* \
[June 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2026.3673956)]


**Breaking the Continuum: Discrete Distribution Learning for Structural MRI Reconstruction** \
*Tianle Lyu, Mengjingcheng Mo, Ting Wen, Zhen Song, Zinan Xiong, and Yanjie Zhu* \
[2026] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Lyu_Breaking_the_Continuum_Discrete_Distribution_Learning_for_Structural_MRI_Reconstruction_CVPR_2026_paper.html)]


**Are Natural-Domain Foundation Models Effective for Accelerated Cardiac MRI Reconstruction?** \
*Anam Hashmi, Mayug Maniparambil, Julia Dietlmeier, Kathleen M Curran, and Noel E O'Connor* \
[2026] [CVPR Workshop]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/html/Hashmi_Are_Natural-Domain_Foundation_Models_Effective_for_Accelerated_Cardiac_MRI_Reconstruction_CVPRW_2026_paper.html)] [[Github](https://github.com/Hashmi360/CMR-Recon)]


**Fast and Robust Diffusion Posterior Sampling for MR Image Reconstruction Using the Preconditioned Unadjusted Langevin Algorithm** \
*Moritz Blumenthal, Tina Holliber, Jonathan I. Tamir, and Martin Uecker* \
[10 May 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70416)]


**Sparse Subspace Diffusion Model for Physically Consistent Accelerated MRI Reconstruction** \
*Xiangyao Deng, Zhiqiang Shen, Sanuwani Dayarathna, Juan P. Meneses, Sergio Uribe, and Zhaolin Chen* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v315/deng26a.html)]


**Highly Undersampled MRI Reconstruction via a Single Posterior Sampling of Diffusion Models** \
*Jin Liu, Qing Lin, Zhuang Xiong, Shanshan Shan, Chunyi Liu, Min Li, Feng Liu, G. Bruce Pike, Hongfu Sun, and Yang Gao* \
[May 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2026.3654585)]


**HiMaC: Histogram-Driven and Mask-Aware Consistency Models for MRI Reconstruction** \
*Qiudi He, Kai Zhao, Kaifeng Pang, Qi Miao, Sanghyeok Lim, Changsuk Oh, Alex Ling Yu Hung, and Kyunghyun Sung* \
[2026] [ISBI]<br>
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515378)]


**Making 3D Diffusion Easier: Autocalibration-Signal-Conditioned Diffusion Model for Dynamic Mri Reconstruction** \
*Zi Wang, Liutao Yang, Fanwen Wang, Yinzhe Wu, Zhenxuan Zhang, Ling Huang, and Guang Yang* \
[2026] [ISBI]<br>
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515678)]


**Efficient Complex-Valued MR Image Reconstruction Using a Real-Value Trained Conditional Diffusion Model** \
*Satoshi Ito and Tomoki Sawai* \
[2026] [ISBI]<br>
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515531)]


**Dynamic Transformer Based on Wavelet and Diffusion Prior Guidance for Cardiac Cine MRI Reconstruction** \
*Bolun Zhao and Jun Lyu* \
[01 May 2026] [Sensors]<br>
[[Paper](https://doi.org/10.3390/s26092842)]


**TC-KANRecon: High-Quality and Accelerated MRI Reconstruction via Adaptive KAN Mechanisms and Intelligent Feature Scaling** \
*Ruiquan Ge, Xiao Yu, Yifei Chen, Fan Jia, Shenghao Zhu, Dong Zeng, Changmiao Wang, Qiegen Liu, and Shanzhou Niu* \
[May 2026] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2025.3626343)]


**KFDualUNet: Enhancing MRI Reconstruction Generalization Through Cross-Domain Synergistic Learning with Dual Cascaded UNets and K-Space Physical Constraints** \
*Ye Wang and Rongjun Ge* \
[2026] [MICCAI Workshop]<br>
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_30)]


**Domain-Conditioned and Temporal-Guided Diffusion Modeling for Accelerated Dynamic MRI Reconstruction** \
*Liping Zhang, Iris Yuwen Zhou, Sydney B. Montesi, Li Feng, and Fang Liu* \
[24 March 2026] [NMR Biomed.]<br>
[[Paper](https://doi.org/10.1002/nbm.70256)]


**A Spatio-Temporal Diffusion Model for Cardiac Real-Time Imaging** \
*Oliver Schad, Julius Frederik Heidenreich, Nils Petri, Viktor Hartung, Alena Kollmann, Thorsten Alexander Bley, Peter Nordbeck, Bernhard Petritsch, and Tobias Wech* \
[18 February 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70303)]


**J-Score: Joint Distribution Learning With Score-Based Diffusion for Accelerating T1ρ Mapping** \
*Congcong Liu, Yuanyuan Liu, Chentao Cao, Jing Cheng, Qingyong Zhu, Tian Zhou, Chen Luo, Yanjie Zhu, Haifeng Wang, Zhuo-Xu Cui, and Dong Liang* \
[February 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2025.3606660)]


**Robust simultaneous multislice MRI reconstruction using slice-wise learned generative diffusion priors** \
*Shoujin Huang, Guanxiong Luo, Yunlin Zhao, Yilong Liu, Yuwan Wang, Kexin Yang, Jingzhe Liu, Hua Guo, Min Wang, Lingyan Zhang, and Mengye Lyu* \
[February 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2025.103851)] [[Github](https://github.com/Solor-pikachu/ROGER)]


**Cardiac MRI Reconstruction Using Diffusion Priors and Multi-Scale Transformer-Based Feature Modeling** \
*Jun Lyu, Bolun Zhao, Selwa A. F. Al-Hazzaa, M. Shamim Hossain, and Chengyan Wang* \
[2026] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2026.3713886)]


**AMK-CDiffNet: Adaptive-multiscale K-space cold diffusion network for fast MRI reconstruction** \
*Bingchen Dong, Gengshen Wu, Xia Feng, Yi Liu, and Jungong Han* \
[February 2026] [Expert Systems with Applications]<br>
[[Paper](https://doi.org/10.1016/j.eswa.2025.129384)]


**Fast unconditional diffusion model for accelerated MRI reconstruction** \
*Guijiao Zhao, Chen Zhou, Jianxing Liu, Yue Hu, and Peng Li* \
[January 2026] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2025.110551)]


**Sub-DM: Subspace Diffusion Model With Orthogonal Decomposition for MRI Reconstruction** \
*Yu Guan, Qinrong Cai, Wei Li, Qiuyun Fan, Dong Liang, and Qiegen Liu* \
[2026] [IEEE Transactions on Computational Imaging]<br>
[[Paper](https://doi.org/10.1109/TCI.2026.3653305)]


**Highly accelerated whole-brain T2 mapping using non-cartesian acquisition and model-based implicit neural representation reconstruction** \
*Tianyi Xiao, Bei Liu, Huajun She, and Yiping P. Du* \
[December 2025] [NeuroImage]<br>
[[Paper](https://doi.org/10.1016/j.neuroimage.2025.121614)]


**PixelINR: Scan-specific self-supervised MRI reconstruction based on implicit neural representations** \
*Songxiao Yang, Yafei Ou, and Masatoshi Okutomi* \
[10 October 2025] [Biomedical Signal Processing and Control]<br>
[[Paper](https://doi.org/10.1016/j.bspc.2025.108838)][[Github](https://github.com/YSongxiao/PixelINR)]




**Neural Space-Time Modeling for Motion-Corrected MR Reconstruction** \
*Aizada Nurdinova, Wenqi Huang, Daniel Raz Abraham, Jaehyeok Bae, Yimeng Lin, Kawin Setsompop, and Brian Andrew Hargreaves* \
[2025] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-06103-4_12)]


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

**Self-Supervised Feature Learning for Cardiac Cine MR Image Reconstruction** \
*Siying Xu, Marcel Früh, Kerstin Hammernik, Andreas Lingg, Jens Kübler, Patrick Krumm, Daniel Rueckert, Sergios Gatidis, and Thomas Küstner* \
[23 May 2025] [IEEE Transactions on Medical Imaging]<br>
[[Paper](https://doi.org/10.1109/TMI.2025.3570226)][[Github](https://github.com/midas-tum/SSFL-Recon)]


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


**Dual-Domain Multipath Self-Supervised Diffusion Model for Accelerated MRI Reconstruction** \
*Yuxuan Zhang, Jinkui Hao, and Bo Zhou* \
[2026] [IEEE TNNLS]<br>
[[Paper](https://doi.org/10.1109/TNNLS.2026.3688183)] [[Github](https://github.com/Advanced-AI-in-Medicine-and-Physics-Lab/DMSM)]


**Unsupervised Motion-Compensated Decomposition for Cardiac MRI Reconstruction via Neural Representation** \
*Xuanyu Tian, Lixuan Chen, Qing Wu, Xiao Wang, Jie Feng, Yuyao Zhang, and Hongjiang Wei* \
[2026] [AAAI]<br>
[[Paper](https://doi.org/10.1609/aaai.v40i11.37914)]


**Zero-shot Implicit Neural Manifold Representation (INMR) for Ultra-high Temporal Resolution Dynamic MRI** \
*Jie Feng, Rui Luo, Tian Zeng, Xin Shen, Haikun Qi, Yuyao Zhang, Dong Liang, and Hongjiang Wei* \
[2026] [AAAI]<br>
[[Paper](https://doi.org/10.1609/aaai.v40i5.37395)]


**Prospective Dynamic 3D MRI Reconstruction via Latent-Space Motion Tracking from Single Measurement** \
*Lixuan Chen, Zhongnan Liu, Jesse Hamilton, James M. Balter, Jeong Joon Park, and Liyue Shen* \
[2026] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Chen_Prospective_Dynamic_3D_MRI_Reconstruction_via_Latent-Space_Motion_Tracking_from_CVPR_2026_paper.html)]


**Self-supervised reconstruction framework via motion- and physics-informed learning for four-dimensional magnetic resonance fingerprinting** \
*Chenyang Liu, Lu Wang, Xiang Wang, Peilin Wang, Weihang Liao, Fan Zhang, Ziyi Zeng, Xinzhi Teng, Jiarui Zhu, Junyi Yan, Yat-Lam Wong, Victor Ho-fun Lee, Peng Cao, Jing Qin, Tian Li, and Jing Cai* \
[November 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.104240)]


**MINeR: Direction-modulated implicit neural representation enables ultrafast multi-shell diffusion MRI** \
*Tian Zeng, Jie Feng, Tong Sun, Guoyan Lao, Ming Zhang, Longchun Wang, Jingquan Liu, Yuyao Zhang, and Hongjiang Wei* \
[September 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.104205)] [[Github](https://github.com/AMRI-Lab/MINeR)]


**Optimized Multi-Contrast Self-Supervised MRI Reconstruction Using Learned K-Space Partitioning** \
*Brenden Kadota, Charles Millard, and Mark Chiew* \
[September 2026] [IEEE TBME]<br>
[[Paper](https://doi.org/10.1109/TBME.2026.3713846)]


**Benchmarking Self-Supervised Learning Methods for Accelerated MRI Reconstruction** \
*Andrew Wang, Steven McDonagh, and Mike Davies* \
[29 August 2026] [MELBA]<br>
[[Paper](https://doi.org/10.59275/j.melba.2026-b6a3)] [[Github](https://github.com/Andrewwango/ssibench)]


**3D MR Fingerprinting for Quantitative Bladder Wall T 1 , T 2 , and M 0 Mapping in Healthy Subjects at 1.5 T and 3 T** \
*Shane A. Wells, Giulia M. Ippolito, Melis Ozkan, Wilson Sui, Anne P. Cameron, and Jesse I. Hamilton* \
[28 July 2026] [NMR Biomed.]<br>
[[Paper](https://doi.org/10.1002/nbm.70366)]


**Generative MR Multitasking With Complex-Harmonic Cardiac Encoding: Bridging the Gap Between Gated Imaging and Real-Time Imaging** \
*Xinguo Fang and Anthony G. Christodoulou* \
[14 July 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70509)]


**Bilevel Optimized Implicit Neural Representation for Scan-Specific Accelerated MRI Reconstruction** \
*Hongze Yu, Jeffrey A. Fessler, and Yun Jiang* \
[July 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2026.3686724)]


**Re-Visible Dual-Domain Self-Supervised Deep Unfolding Network for MRI Reconstruction** \
*Hao Zhang, Qi Wang, Jian Sun, Zhijie Wen, Jun Shi, and Shihui Ying* \
[July 2026] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2025.3647429)]


**VQ-SToRM: Vector-Quantized Smoothness Regularization on Manifolds for Free-Breathing, Ungated Real-Time Cardiac MRI Reconstruction** \
*Mahrusa Billah, Junpu Hu, and Qing Zou* \
[30 June 2026] [Bioengineering]<br>
[[Paper](https://doi.org/10.3390/bioengineering13070764)]


**Hybrid learning: a combination of self-supervised and supervised learning for joint MRI reconstruction and denoising in low-field MRI** \
*Haoyang Pei, Nikola Janjušević, Renqing Luo, Ding Xia, Xiang Xu, William Moore, Yao Wang, Hersh Chandarana, and Li Feng* \
[25 June 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae792b)]


**Zero-Shot Self-Supervised Learning of Single Breath-Hold Magnetic Resonance Cholangiopancreatography ( MRCP ) Reconstruction** \
*Jinho Kim, Marcel Dominik Nickel, and Florian Knoll* \
[12 June 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70467)]


**Joint Supervised and Self-supervised Learning for MRI Reconstruction** \
*George Yiasemis, Nikita Moriakov, Clara I. Sánchez, Jan-Jakob Sonke, and Jonas Teuwen* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v301/yiasemis26a.html)] [[Github](https://github.com/NKI-AI/direct)]


**Family of Deep Image Prior Networks for Accelerated 3D LGE-MRI Acquisition with Enhanced Reconstruction** \
*Md Hasibul Husain Hisham, Shireen Elhabian, Ganesh Adluru, Andrew Arai, Eugene Kholmovski, Ravi Ranjan, and Edward Dibella* \
[2026] [MIDL]<br>
[[Paper](https://proceedings.mlr.press/v301/hisham26a.html)]


**INAR: Implicit Neural Anatomically Guided Reconstruction for Sodium MRI** \
*Asli Alpman, Hongjiang Wei, and Chunlei Liu* \
[2026] [CVPR Workshop]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2026W/CV4Clinic2026/html/Alpman_INAR_Implicit_Neural_Anatomically_Guided_Reconstruction_for_Sodium_MRI_CVPRW_2026_paper.html)]


**Self-supervised domain adaptation with hypernetworks for compressive sensing MRI reconstruction** \
*Libya Thomas and Joseph Zacharias* \
[June 2026] [Applied Soft Computing]<br>
[[Paper](https://doi.org/10.1016/j.asoc.2026.115015)]


**SELFIE: Self-Supervised Learning for Fast Dynamic Golden-Angle Radial MRI** \
*Melanie Schellenberg, Anthony Mekhanik, Victor Murray, Pamela Argiriadi, Yulia Lakhman, Galina Levin, Oguz Akin, and Ricardo Otazo* \
[20 May 2026] [NMR Biomed.]<br>
[[Paper](https://doi.org/10.1002/nbm.70309)]


**Three-Dimensional MRI Reconstruction With 3D Gaussian Representations: Tackling the Undersampling Problem** \
*Tengya Peng, Ruyi Zha, Zhen Li, Xiaofeng Liu, and Qing Zou* \
[May 2026] [TMI]<br>
[[Paper](https://doi.org/10.1109/TMI.2025.3642134)]


**KP-INR: A Dual-Branch Implicit Neural Representation Model for Cardiac Cine MRI Reconstruction** \
*Donghang Lyu, Marius Staring, Mariya Doneva, Hildo J. Lamb, and Nicola Pezzotti* \
[2026] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-17734-6_6)]


**Physics-Guided Self-Supervised Implicit Neural Representation for Accelerated $\text{T}_{1\rho }$ Mapping** \
*Yuanyuan Liu, Jinwen Xie, Jianhao Wu, Zhuo-Xu Cui, Qingyong Zhu, Jing Cheng, Haifeng Wang, Zhen Song, Dong Liang, and Yanjie Zhu* \
[May 2026] [IEEE TBME]<br>
[[Paper](https://doi.org/10.1109/TBME.2025.3618476)]


**Time-Conditioned Zero-Shot Self-Supervised Reconstruction for Accelerated 3D Ultra-Low-Field MRI** \
*Mart W. J. van Straten, Beatrice Lena, Chloé Najac, Ruben van den Broek, Peter Börnert, Andrew Webb, and Yiming Dong* \
[28 April 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70407)]


**Population-Prior-Assisted Implicit Neural Representations for Instance-Specific Unsupervised Accelerated Mri Reconstruction** \
*Chushu Shen, Hengjie Liu, Dan Ruan, and Debiao Li* \
[2026] [ISBI]<br>
[[Paper](https://doi.org/10.1109/ISBI61048.2026.11515804)]


**Phase-constrained zero-shot self-supervised learning for BLADE liver MRI reconstruction** \
*Uten Yarach, Sorravit Akrasirakul, Hendrik Mattern, and Oliver Speck* \
[11 April 2026] [MAGMA]<br>
[[Paper](https://doi.org/10.1007/s10334-026-01359-2)]


**CSSL-ISRVN: consistency self-supervised learning integrating ISTANet and sensitivity refinement-enhanced variational network for accelerated MRI reconstruction** \
*Jizhong Duan, Yuqian Chen, Haibo Tao, Junfeng Wang, and Yu Liu* \
[24 March 2026] [PMB]<br>
[[Paper](https://doi.org/10.1088/1361-6560/ae50a8)]


**Rapid spatio-temporal MR fingerprinting using physics-informed implicit neural representation** \
*Chaoguang Gong, Lixian Zou, Peng Li, Xingyang Wu, Yangzi Qiao, Zhanqi Hu, Xiaoyan Wang, Yihang Zhou, Kai Wang, Yue Hu, and Haifeng Wang* \
[March 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2026.103935)]


**PISCO: Self-supervised k-space regularization for improved neural implicit k-space representations of dynamic MRI** \
*Veronika Spieker, Hannah Eichhorn, Wenqi Huang, Jonathan K. Stelter, Tabita Catalan, Rickmer F. Braren, Daniel Rueckert, Francisco Sahli Costabal, Kerstin Hammernik, Dimitrios C. Karampinos, Claudia Prieto, and Julia A. Schnabel* \
[March 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2025.103890)] [[Github](https://github.com/compai-lab/2025-pisco-spieker)]


**S 3 CNet: self-supervised Siamese cooperative network for accelerating magnetic resonance imaging reconstruction** \
*Chenghu Geng, Mingfeng Jiang, Dongsheng Ruan, Jiacheng Chen, Zhifeng Chen, Xiaocheng Yang, Ling Xia, and Feng Liu* \
[10 February 2026] [Med. Phys.]<br>
[[Paper](https://doi.org/10.1002/mp.70321)]


**Rosette Cardiac MR Fingerprinting for Simultaneous T 1 , T 2 , T2*, and Fat Fraction Mapping Using a Multi-Echo Deep Image Prior Reconstruction** \
*Evan Cummings, Gastao Cruz, Jacob Richardson, Sydney Kaplan, Jesse Hamilton, and Nicole Seiberlich* \
[09 February 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70299)]


**Neural Fields for Highly Accelerated 2D Cine Phase Contrast MRI** \
*Pablo Arratia, Martin J. Graves, Mary McLean, Carolin Pirkl, Carola‐Bibiane Schönlieb, Timo Schirmer, Florian Wiesinger, and Matthias J. Ehrhardt* \
[03 February 2026] [Advanced Science]<br>
[[Paper](https://doi.org/10.1002/advs.202519788)]


**Free-breathing dynamic MRI reconstruction via joint time-dependent coil sensitivity estimation using implicit neural representation** \
*Xin Shen, Jie Feng, Zhenghao Li, Qing Zou, Yuyao Zhang, and Hongjiang Wei* \
[February 2026] [Medical Image Analysis]<br>
[[Paper](https://doi.org/10.1016/j.media.2025.103847)] [[Github](https://github.com/AMRI-Lab/IMJ-PLUS)]


**High-Resolution Diffusion-Weighted Imaging With Self-Gated Self-Supervised Unrolled Reconstruction** \
*Zhengguo Tan, Patrick A. Liebig, Annika Hofmann, Frederik B. Laun, and Florian Knoll* \
[22 January 2026] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70250)]


**Unsupervised Dynamic MRI Reconstruction via Low-Rank Patch-Based Tensor Functions with Implicit Neural Representation** \
*Yuanyuan Liu, Yuanbiao Yang, Jing Cheng, Zhuo-Xu Cui, Qingyong Zhu, Congcong Liu, Yuliang Zhu, Jingran Xu, Hairong Zheng, Dong Liang, and Yanjie Zhu* \
[2026] [J-BHI]<br>
[[Paper](https://doi.org/10.1109/JBHI.2026.3726594)]


**A multi-dynamic low-rank deep image prior for three-dimensional real-time cardiovascular magnetic resonance imaging** \
*Chong Chen, Marc Vornehm, Zhenyu Bu, Preethi Chandrasekaran, Muhammad A. Sultan, Syed M. Arshad, Yingmin Liu, Yuchi Han, and Rizwan Ahmad* \
[2026] [JCMR]<br>
[[Paper](https://doi.org/10.1016/j.jocmr.2025.102015)]


**Implicit Neural Representation-Based MRI Reconstruction Method With Sensitivity Map Constraints** \
*Lixuan Rao, Xinlin Zhang, Yiman Huang, Tao Tan, Huihong Sun, Jixiao Sun, and Tong Tong* \
[2026] [IEEE TIM]<br>
[[Paper](https://doi.org/10.1109/TIM.2026.3662877)]


**Cardiac MR Fingerprinting at 0.55T Using a Deep Image Prior for Joint T 1 , T 2 , and M 0 Mapping** \
*Zhongnan Liu, Zexuan Liu, Imran Rashid, Mauricio Stanzione Galizia, Christopher Scoma, William Truesdell, Prachi Agarwal, Nicole Seiberlich, Liyue Shen, and Jesse Hamilton* \
[22 January 2026] [JMRI]<br>
[[Paper](https://doi.org/10.1002/jmri.70239)]


**AeSPa : Attention-guided Self-supervised Parallel Imaging for MRI Reconstruction** \
*Joo, Jinho and Kim, Hyeseong and Won, Hyeyeon and Lee, Deukhee and Eo, Taejoon and Hwang, Dosik* \
[2025] [CVPR]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Joo_AeSPa__Attention-guided_Self-supervised_Parallel_Imaging_for_MRI_Reconstruction_CVPR_2025_paper.pdf)] [[Github](https://github.com/joojinho97/AeSPa)] 


**INR Meets Multi-contrast MRI Reconstruction** \
*Natascha Niessen, Carolin M. Pirkl, Ana Beatriz Solana, Hannah Eichhorn, Veronika Spieker, Wenqi Huang, Tim Sprenger, Marion I. Menzel, Julia A. Schnabel, and on behalf of the PREDICTOM consortium* \
[2025] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-06103-4_3)]


**Self-supervised Motion-Compensated Reconstruction for Cardiac Cine MRI** \
*Siying Xu, Aya Ghoul, Kerstin Hammernik, Jens Kuebler, Patrick Krumm, Andreas Lingg, Daniel Rueckert, Sergios Gatidis, and Thomas Küstner* \
[2025] [MICCAI]<br>
[[Paper](https://doi.org/10.1007/978-3-032-06103-4_10)] [[Github](https://github.com/midas-tum/SSL-MoCo)]


**Accelerating Multiparametric Quantitative MRI Using Self-Supervised Scan-Specific Implicit Neural Representation With Model Reinforcement** \
*Ruimin Feng, Albert Jang, Xingxin He, and Fang Liu* \
[19 December 2025] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70227)]


**Self-Supervised Joint Reconstruction and Denoising of T2 -Weighted PROPELLER MRI of the Lung at 0.55T** \
*Jingjia Chen, Haoyang Pei, Christoph Maier, Mary Bruno, Qiuting Wen, Seon‐Hi Shin, William Moore, Hersh Chandarana, and Li Feng* \
[12 December 2025] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.70224)]


**Zero-Shot Dynamic MRI Reconstruction With Global-to-Local Diffusion Model** \
*Yu Guan, Kunlong Zhang, Qi Qi, Dong Wang, Ziwen Ke, Shaoyu Wang, Dong Liang, and Qiegen Liu* \
[31 August 2025] [NMR Biomed.]<br>
[[Paper](https://doi.org/10.1002/nbm.70128)]


**Robust multi-coil MRI reconstruction via self-supervised denoising** \
*Asad Aali, Marius Arvinte, Sidharth Kumar, Yamin I. Arefeen, Jonathan I. Tamir* \
[02 June 2025] [Magn. Reson. in Med.]<br>
[[Paper](https://doi.org/10.1002/mrm.30591)] [[Github](https://github.com/utcsilab/gsure-diffusion-mri)] 



**Fast MRI for All: Bridging Access Gaps by Training without Raw Data** \
*Yasar Utku Alcalar, Merve Gulle, and Mehmet Akcakaya* \
[2025] [NeurIPS]<br>
[[Paper](https://doi.org/10.52202/085713-0516)] [[Github](https://github.com/ualcalar17/CUPID)]


**D2SA: Dual-Stage Distribution and Slice Adaptation for Efficient Test-Time Adaptation in MRI Reconstruction** \
*Lipei Zhang, Rui Sun, Zhongying Deng, Yanqi Cheng, Carola-Bibiane Schönlieb, and Angelica Aviles-Rivero* \
[2025] [NeurIPS]<br>
[[Paper](https://doi.org/10.52202/085713-3774)]


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

**TTP-SSFL: Test-Time Personalization Self-Supervised Federated Learning for Accelerating MR Image Reconstruction** \
*Chenghu Geng, Mingfeng Jiang, Dongsheng Ruan, Chengjin Yu, Hong Sun, Feng Liu, Ling Xia, and Guang Yang* \
[2026] [IEEE TNNLS] \
[[Paper](https://doi.org/10.1109/TNNLS.2026.3703424)]


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


### CMRxRecon2025
*Human Phenome Institute, Fudan University, Shanghai, China* \
`Multi-coil raw k-space data` [[Dataset](https://www.synapse.org/Synapse:syn64952554/datasets/)] [[Github](https://github.com/CmrxRecon/CMRxRecon2025)] <br>
* Imaging region
  * Cardiac MRI
    *  T1, T2, T2* maps
    * T1w and T2w
    * T1ρ
    * Black blood
    * Phase contrast
    * LGE
    * Perfusion


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
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

**A Faithful Deep Sensitivity Estimation for Accelerated Magnetic Resonance Imaging** \
*Wang, Zi, Haoming Fang, Chen Qian, Boxuan Shi, Lijun Bao, Liuhong Zhu, Jianjun Zhou, and Xiaobo Qu* \
[05 February 2024] [J-BHI] \
[[Paper](https://doi.org/10.1109/JBHI.2024.3360128)] 



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

**DCT-net: Dual-domain cross-fusion transformer network for MRI reconstruction** \
*Wang, Bin, Yusheng Lian, Xingchuang Xiong, Han Zhou, Zilong Liu, and Xiaohao Zhou* \
[17 January 2024] [MRI]<br>
[[Paper](https://doi.org/10.1016/j.mri.2024.01.007)]


**Deep supervised dictionary learning by algorithm unrolling-Application to fast 2D dynamic MR image reconstruction** \
*Andreas Kofler, Marie-Christine Pali, Tobias Schaeffter, and Christoph Kolbitsch* \
[24 December 2022] [Med. Phys.] \
[[Paper](https://doi.org/10.1002/mp.16182)] [[Github](https://github.com/koflera/End2End-DLMRI?tab=readme-ov-file)]


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


# You Can See Clearly Now !
By [Xiang Chen](https://cxtalk.github.io/), Yufeng Li, Yufeng Huang

## 1 Description
   * A collection of awesome low-light image enhancement methods. Papers, codes and datasets are maintained.

## 2 Related Work
### 2.1 Datasets
------------
* VV [[download](https://sites.google.com/site/vonikakis/datasets)]
* SID [[download](https://cchen156.github.io/SID.html)]
* LOL [[download](https://daooshee.github.io/BMVC2018website/)]
* NPE [[download](http://blog.sina.com.cn/s/blog_a0a06f190101cvon.html)]
* MEF [[download](http://ivc.uwaterloo.ca/database/MEF/MEF-Database.php)]
* SCIE [[download](https://github.com/csjcai/SICE)]
* LIME [[download](http://cs.tju.edu.cn/orgs/vision/~xguo/LIME.htm)]
* DICM [[download](http://mcl.korea.ac.kr/projects/LDR/LDR_TEST_IMAGES_DICM.zip)]
* BIMEF [[download](https://drive.google.com/drive/folders/0B_FjaR958nw_djVQanJqeEhUM1k)]
* ExDark [[download](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset/tree/master/Dataset)]
* MIT-Adobe FiveK [[download](https://data.csail.mit.edu/graphics/fivek/)]

### 2.2 Papers
------------
### 2020
* Atoum et al, Color-wise Attention Network for Low-light Image Enhancement. [[paper](https://arxiv.org/pdf/1911.08681.pdf)][code]
* Lv et al, Attention Guided Low-light Image Enhancement with a Large Scale Low-light Simulation Dataset. [[paper](https://arxiv.org/pdf/1908.00682.pdf)][code]
* Guo et al, Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement. [[paper](https://arxiv.org/pdf/2001.06826.pdf)][[code](https://github.com/Li-Chongyi/Zero-DCE)]

### 2019
* Wang et al, Underexposed Photo Enhancement using Deep Illumination Estimation. [[paper](https://drive.google.com/file/d/1CCd0NVEy0yM2ulcrx44B1bRPDmyrgNYH/view)][[code](https://github.com/wangruixing/DeepUPE)]
* Loh et al, Low-light image enhancement using Gaussian Process for features retrieval. [[paper](http://cs-chan.com/doc/SPIC2019.pdf)][[code](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset/tree/master/SPIC)]
* Zhang et al, Kindling the Darkness: A Practical Low-light Image Enhancer. [[paper](https://arxiv.org/pdf/1905.04161.pdf)][[code](https://github.com/zhangyhuaee/KinD)]
* Ren et al, Low-Light Image Enhancement via a Deep Hybrid Network. [[paper](https://ieeexplore.ieee.org/document/8692732)][[code](https://drive.google.com/file/d/1WYQd5z9NXW-IOWLSH3w70t3XnLUAHnAZ/view)]
* Jiang et al, EnlightenGAN: Deep Light Enhancement without Paired Supervision. [[paper](https://arxiv.org/pdf/1906.06972.pdf)][[code](https://github.com/TAMU-VITA/EnlightenGAN)]

### 2018
* Chen et al, Learning to See in the Dark. [[paper](http://cchen156.web.engr.illinois.edu/paper/18CVPR_SID.pdf)][[code](https://github.com/cchen156/Learning-to-See-in-the-Dark)]
* Wei et al, Deep Retinex Decomposition for Low-Light Enhancement. [[paper](https://arxiv.org/pdf/1808.04560)][[code](https://github.com/weichen582/RetinexNet)]
* Wang et al, GLADNet: Low-Light Enhancement Network with Global Awareness. [[paper](https://ieeexplore.ieee.org/document/8373911)][[code](https://github.com/weichen582/GLADNet)]
* Lv et al, MBLLEN: Low-light Image/Video Enhancement Using CNNs. [[paper](http://bmvc2018.org/contents/papers/0700.pdf)][[code](https://github.com/Lvfeifan/MBLLEN)]
* Jiang et al, Deep Refinement Network for Natural Low-Light Image Enhancement in Symmetric Pathways. [[paper](https://www.mdpi.com/2073-8994/10/10/491/pdf)][code]
* Cai et al, Learning a Deep Single Image Contrast Enhancer from Multi-Exposure Images. [[paper](http://www4.comp.polyu.edu.hk/~cslzhang/paper/SICE.pdf)][[code](https://github.com/csjcai/SICE)]

### 2017
* GHARBI et al, Deep Bilateral Learning for Real-Time Image Enhancement. [[paper](https://groups.csail.mit.edu/graphics/hdrnet/data/hdrnet.pdf)][[code](https://github.com/google/hdrnet)]
* Shen et al, MSR-net:Low-light Image Enhancement Using Deep Convolutional Network. [[paper](https://arxiv.org/pdf/1711.02488.pdf)][code]
* Tao et al, LLCNN: A convolutional neural network for low-light image enhancement. [[paper](https://ieeexplore.ieee.org/abstract/document/8305143)][[code](https://github.com/BestJuly/LLCNN)]

### 2016
* Lore et al, LLNet: A Deep Autoencoder approach to Natural Low-light Image Enhancement. [[paper](https://arxiv.org/pdf/1511.03995.pdf)][[code](https://github.com/kglore/llnet_color)]
* Guo et al, LIME: Low-Light Image Enhancement via Illumination Map Estimation. [[paper](https://ieeexplore.ieee.org/document/7782813)][[code](https://github.com/Sy-Zhang/LIME)]

## 3 Image Quality Assessment Metrics
* PSNR (Peak Signal-to-Noise Ratio) [[matlab code]](https://www.mathworks.com/help/images/ref/psnr.html) [[python code]](https://github.com/aizvorski/video-quality)
* SSIM (Structural Similarity) [[matlab code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[python code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)
* VIF (Visual Quality) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/Evalution_VIF/eva-VIF.htm)
* FSIM (Feature Similarity) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm)
* NIQE (Naturalness Image Quality Evaluator) [[matlab code]](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)[[python code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)

## 4 Note
* The above content is constantly updated, welcome continuous attention!

## 5 Contact
* If you have any question, please feel free to contact Xiang Chen (Email: cx@cvgpu.com).
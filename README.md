# Awesome Self-Supervised Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome Self-Supervised Learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search)

#### Why Self-Supervised?
Self-Supervised Learning has become an exciting direction in AI community. 
  - Jitendra Malik: "Supervision is the opium of the AI researcher"
  - Alyosha Efros: "The AI revolution will not be supervised"
  - Yann LeCun: "self-supervised learning is the cake, supervised learning is the icing on the cake, reinforcement learning is the cherry on the cake"

## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://jason718.github.io/) or add [pull request](https://github.com/jason718/Awesome-Self-Supervised-Learning/pulls)

Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents
- [Computer Vision (CV)](#computer-vision)
  - [Survey](#survey)
  - [Image Representation Learning](#image-representation-learning)
  - [Video Representation Learning](#video-representation-learning)
  - [Geometry](#geometry)
  - [Audio](#audio)
  - [Others](#others)
- [Machine Learning](#machine-learning)
  - [Reinforcement Learning](#reinforcement-learning)
- [Robotics](#robotics)  
- [Natural Language Processing (NLP)](#nlp)  
- [Talks](#talks)
- [Thesis](#thesis)

## Computer Vision
### Survey
- Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey.
  [[pdf]](https://arxiv.org/pdf/1902.06162.pdf)
  - Longlong Jing and Yingli Tian.


### Image Representation Learning

#### Benchmark code
FAIR Self-Supervision Benchmark [[repo]](https://github.com/facebookresearch/fair_self_supervision_benchmark): various benchmark (and legacy) tasks for evaluating quality of visual representations learned by various self-supervision approaches. 

#### 2015
- Unsupervised Visual Representation Learning by Context Prediction.
  [[pdf]](https://arxiv.org/abs/1505.05192)
  [[code]](http://graphics.cs.cmu.edu/projects/deepContext/)
  - Doersch, Carl and Gupta, Abhinav and Efros, Alexei A. *ICCV 2015*

- Unsupervised Learning of Visual Representations using Videos.
  [[pdf]](http://www.cs.cmu.edu/~xiaolonw/papers/unsupervised_video.pdf) 
  [[code]](http://www.cs.cmu.edu/~xiaolonw/unsupervise.html)
  - Wang, Xiaolong and Gupta, Abhinav. *ICCV 2015*

- Learning to See by Moving. 
  [[pdf]](http://arxiv.org/abs/1505.01596)
  [[code]](https://people.eecs.berkeley.edu/~pulkitag/lsm/lsm.html)
  - Agrawal, Pulkit and Carreira, Joao and Malik, Jitendra. *ICCV 2015*

- Learning image representations tied to ego-motion.
  [[pdf]](http://vision.cs.utexas.edu/projects/egoequiv/ijcv_bestpaper_specialissue_egoequiv.pdf) 
  [[code]](http://vision.cs.utexas.edu/projects/egoequiv/)
  - Jayaraman, Dinesh and Grauman, Kristen. *ICCV 2015*

#### 2016
- Joint Unsupervised Learning of Deep Representations and Image Clusters. 
  [[pdf]](https://arxiv.org/pdf/1604.03628.pdf) 
  [[code-torch]](https://github.com/jwyang/JULE.torch)
  [[code-caffe]](https://github.com/jwyang/JULE-Caffe)
  - Jianwei Yang, Devi Parikh, Dhruv Batra. *CVPR 2016*
  
- Unsupervised Deep Embedding for Clustering Analysis.
  [[pdf]](https://arxiv.org/pdf/1511.06335.pdf) 
  [[code]](https://github.com/piiswrong/dec)
  - Junyuan Xie, Ross Girshick, and Ali Farhadi. *ICML 2016*
  
- Slow and steady feature analysis: higher order temporal coherence in video. 
  [[pdf]](http://vision.cs.utexas.edu/projects/slowsteady/cvpr16.pdf)
  - Jayaraman, Dinesh and Grauman, Kristen. *CVPR 2016*

- Context Encoders: Feature Learning by Inpainting. 
  [[pdf]](https://people.eecs.berkeley.edu/~pathak/papers/cvpr16.pdf)
  [[code]](https://people.eecs.berkeley.edu/~pathak/context_encoder/)
  - Pathak, Deepak and  Krahenbuhl, Philipp and Donahue, Jeff and Darrell, Trevor and Efros, Alexei A. *CVPR 2016*

- Colorful Image Colorization.
  [[pdf]](https://arxiv.org/abs/1603.08511)
  [[code]](http://richzhang.github.io/colorization/)
  - Zhang, Richard and Isola, Phillip and Efros, Alexei A. *ECCV 2016*

- Unsupervised Learning of Visual Representations by Solving Jigsaw Puzzles.
  [[pdf]](http://arxiv.org/abs/1603.09246)
  [[code]](http://www.cvg.unibe.ch/research/JigsawPuzzleSolver.html)
  - Noroozi, Mehdi and Favaro, Paolo. *ECCV 2016*

- Ambient Sound Provides Supervision for Visual Learning.
  [[pdf]](http://arxiv.org/pdf/1608.07017) 
  [[code]](http://andrewowens.com/ambient/index.html)
  - Owens, Andrew and Wu, Jiajun and McDermott, Josh and Freeman, William and Torralba, Antonio. *ECCV 2016*

- Learning Representations for Automatic Colorization. 
  [[pdf]](http://arxiv.org/pdf/1603.06668.pdf)
  [[code]](http://people.cs.uchicago.edu/~larsson/colorization/)
  - Larsson, Gustav and Maire, Michael and Shakhnarovich, Gregory. *ECCV 2016*

-   Unsupervised Visual Representation Learning by Graph-based Consistent Constraints.
    [\[pdf\]](http://faculty.ucmerced.edu/mhyang/papers/eccv16_feature_learning.pdf)
    [\[code\]](https://github.com/dongli12/FeatureLearning)
    -   Li, Dong and Hung, Wei-Chih and Huang, Jia-Bin and Wang, Shengjin and Ahuja, Narendra and Yang, Ming-Hsuan. *ECCV 2016*

#### 2017
- Adversarial Feature Learning. 
  [[pdf]](https://arxiv.org/pdf/1605.09782.pdf)
  [[code]](https://github.com/jeffdonahue/bigan)
  - Donahue, Jeff and Krahenbuhl, Philipp and Darrell, Trevor. *ICLR 2017*
  
- Self-supervised learning of visual features through embedding images into text topic spaces.
  [[pdf]](https://arxiv.org/pdf/1705.08631.pdf)
  [[code]](https://github.com/lluisgomez/TextTopicNet)
  - L. Gomez* and Y. Patel* and M. Rusiñol and D. Karatzas and C.V. Jawahar. *CVPR 2017*
  
- Split-Brain Autoencoders: Unsupervised Learning by Cross-Channel Prediction.
  [[pdf]](https://arxiv.org/abs/1611.09842) 
  [[code]](https://github.com/richzhang/splitbrainauto)
  - Zhang, Richard and Isola, Phillip and Efros, Alexei A. *CVPR 2017*

- Learning Features by Watching Objects Move.
  [[pdf]](https://people.eecs.berkeley.edu/~pathak/papers/cvpr17.pdf) 
  [[code]](https://people.eecs.berkeley.edu/~pathak/unsupervised_video/)
  - Pathak, Deepak and Girshick, Ross and Dollar, Piotr and  Darrell, Trevor and Hariharan, Bharath. *CVPR 2017*
  
- Colorization as a Proxy Task for Visual Understanding. 
  [[pdf]](http://arxiv.org/abs/1703.04044) 
  [[code]](http://people.cs.uchicago.edu/~larsson/color-proxy/)
  - Larsson, Gustav and Maire, Michael and Shakhnarovich, Gregory. *CVPR 2017*

-   DeepPermNet: Visual Permutation Learning.
    [\[pdf\]](https://arxiv.org/pdf/1704.02729.pdf)
    [\[code\]](https://github.com/rfsantacruz/deep-perm-net)
    -   Cruz, Rodrigo Santa and Fernando, Basura and Cherian, Anoop and Gould, Stephen. *CVPR 2017*

- Unsupervised Learning by Predicting Noise.
  [[pdf]](https://arxiv.org/abs/1704.05310) 
  [[code]](https://github.com/facebookresearch/noise-as-targets)
  - Bojanowski, Piotr and Joulin, Armand. *ICML 2017*

- Multi-task Self-Supervised Visual Learning. 
  [[pdf]](https://arxiv.org/abs/1708.07860)
  - Doersch, Carl and Zisserman, Andrew. *ICCV 2017*

- Representation Learning by Learning to Count.
  [[pdf]](https://arxiv.org/abs/1708.06734)
  - Noroozi, Mehdi and Pirsiavash, Hamed and Favaro, Paolo. *ICCV 2017*

- Transitive Invariance for Self-supervised Visual Representation Learning.
  [[pdf]](https://arxiv.org/pdf/1708.02901.pdf)
  - Wang, Xiaolong and He, Kaiming and Gupta, Abhinav. *ICCV 2017*

- Look, Listen and Learn. 
  [[pdf]](https://arxiv.org/pdf/1705.08168.pdf)
  - Relja, Arandjelovic and Zisserman, Andrew. *ICCV 2017*

- Unsupervised Representation Learning by Sorting Sequences. 
  [[pdf]](https://arxiv.org/pdf/1708.01246.pdf) 
  [[code]](https://github.com/HsinYingLee/OPN)
  - Hsin-Ying Lee, Jia-Bin Huang, Maneesh Kumar Singh, and Ming-Hsuan Yang. *ICCV 2017*

#### 2018

- Unsupervised Feature Learning via Non-parameteric Instance Discrimination
  [[pdf]](https://arxiv.org/pdf/1805.01978.pdf) 
  [[code]](https://github.com/zhirongw/lemniscate.pytorch)
  - Zhirong Wu, Yuanjun Xiong and X Yu Stella and Dahua Lin. *CVPR 2018*

- Learning Image Representations by Completing Damaged Jigsaw Puzzles. 
  [[pdf]](https://arxiv.org/pdf/1802.01880.pdf)
  - Kim, Dahun and Cho, Donghyeon and Yoo, Donggeun and Kweon, In So. *WACV 2018*
  
- Unsupervised Representation Learning by Predicting Image Rotations. 
  [[pdf]](https://openreview.net/forum?id=S1v4N2l0-)
  [[code]](https://github.com/gidariss/FeatureLearningRotNet)
  - Spyros Gidaris and Praveer Singh and Nikos Komodakis. *ICLR 2018*
  
- Improvements to context based self-supervised learning. 
  [[pdf]](https://arxiv.org/abs/1711.06379)
  - Terrell Mundhenk and Daniel Ho and Barry Chen. *CVPR 2018*
  
- Self-Supervised Feature Learning by Learning to Spot Artifacts.
  [[pdf]](https://arxiv.org/pdf/1806.05024.pdf)
  [[code]](https://github.com/sjenni/LearningToSpotArtifacts)
  - Simon Jenni and Universität Bern and Paolo Favaro. *CVPR 2018*
  
- Boosting Self-Supervised Learning via Knowledge Transfer. 
  [[pdf]](https://www.csee.umbc.edu/~hpirsiav/papers/transfer_cvpr18.pdf)
  - Mehdi Noroozi and Ananth Vinjimoor and Paolo Favaro and Hamed Pirsiavash. *CVPR 2018*
  
- Cross-domain Self-supervised Multi-task Feature Learning Using Synthetic Imagery. 
  [[pdf]](https://arxiv.org/abs/1711.09082)
  [[code]](https://github.com/jason718/game-feature-learning)
  - Zhongzheng Ren and Yong Jae Lee. *CVPR 2018*
  
- ShapeCodes: Self-Supervised Feature Learning by Lifting Views to Viewgrids.
  [[pdf]](https://arxiv.org/pdf/1709.00505.pdf)
  - Dinesh Jayaraman*, UC Berkeley; Ruohan Gao, University of Texas at Austin; Kristen Grauman. *ECCV 2018*

- Deep Clustering for Unsupervised Learning of Visual Features
    [[pdf]](https://research.fb.com/wp-content/uploads/2018/09/Deep-Clustering-for-Unsupervised-Learning-of-Visual-Features.pdf)
    - Mathilde Caron, Piotr Bojanowski, Armand Joulin, Matthijs Douze. *ECCV 2018*

- Cross Pixel Optical-Flow Similarity for Self-Supervised Learning.
  [[pdf]](http://www.robots.ox.ac.uk/~vgg/publications/2018/Mahendran18/mahendran18.pdf)
  - Aravindh Mahendran, James Thewlis, Andrea Vedaldi. *ACCV 2018*

#### 2019

- Representation Learning with Contrastive Predictive Coding.
  [[pdf]](https://arxiv.org/abs/1807.03748)
  - Aaron van den Oord, Yazhe Li, Oriol Vinyals.

- Self-Supervised Learning via Conditional Motion Propagation.
  [[pdf]](http://www.robots.ox.ac.uk/~vgg/publications/2018/Mahendran18/mahendran18.pdf)
  [[code]](https://github.com/XiaohangZhan/conditional-motion-propagation)
  - Xiaohang Zhan, Xingang Pan, Ziwei Liu, Dahua Lin, and Chen Change Loy. *CVPR 2019*

- Self-Supervised Representation Learning by Rotation Feature Decoupling.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/html/Feng_Self-Supervised_Representation_Learning_by_Rotation_Feature_Decoupling_CVPR_2019_paper.html)
  [[code]](https://github.com/philiptheother/FeatureDecoupling)
  - Zeyu Feng; Chang Xu; Dacheng Tao. *CVPR 2019*

- Revisiting Self-Supervised Visual Representation Learning.
  [[pdf]](https://arxiv.org/abs/1901.09005)
  [[code]](https://github.com/google/revisiting-self-supervised)
  - Alexander Kolesnikov; Xiaohua Zhai; Lucas Beye. CVPR 2019

- AET vs. AED: Unsupervised Representation Learning by Auto-Encoding Transformations rather than Data.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_AET_vs._AED_Unsupervised_Representation_Learning_by_Auto-Encoding_Transformations_Rather_CVPR_2019_paper.pdf)
  [[code]](https://github.com/maple-research-lab/AET)
  - Liheng Zhang, Guo-Jun Qi, Liqiang Wang, Jiebo Luo. *CVPR 2019*

- Unsupervised Deep Learning by Neighbourhood Discovery.
  [[pdf]](http://proceedings.mlr.press/v97/huang19b.html).
  [[code]](https://github.com/Raymond-sci/AND).
  - Jiabo Huang, Qi Dong, Shaogang Gong, Xiatian Zhu. *ICML 2019*
  
- Contrastive Multiview Coding.
  [[pdf]](https://arxiv.org/abs/1906.05849)
  [[code]](https://github.com/HobbitLong/CMC/)
  - Yonglong Tian and Dilip Krishnan and Phillip Isola.

- Large Scale Adversarial Representation Learning.
  [[pdf]](https://arxiv.org/abs/1907.02544)
  - Jeff Donahue, Karen Simonyan.

- Learning Representations by Maximizing Mutual Information Across Views.
  [[pdf]](https://arxiv.org/pdf/1906.00910)
  - Philip Bachman, R Devon Hjelm, William Buchwalter

 - Selfie: Self-supervised Pretraining for Image Embedding. 
    [[pdf]](https://arxiv.org/abs/1906.02940) 
    - Trieu H. Trinh, Minh-Thang Luong, Quoc V. Le
   
 - Data-Efficient Image Recognition with Contrastive Predictive Coding
    [[pdf]](https://arxiv.org/abs/1905.09272)
    - Olivier J. He ́naff, Ali Razavi, Carl Doersch, S. M. Ali Eslami, Aaron van den Oord

 - Using Self-Supervised Learning Can Improve Model Robustness and Uncertainty
    [[pdf]](https://arxiv.org/pdf/1906.12340)
    [[code]](https://github.com/hendrycks/ss-ood)
    - Dan Hendrycks, Mantas Mazeika, Saurav Kadavath, Dawn Song. *NeurIPS 2019*

 - Momentum Contrast for Unsupervised Visual Representation Learning
    [[pdf]](https://arxiv.org/pdf/1911.05722.pdf)
    - Kaiming He, Haoqi Fan, Yuxin Wu, Saining Xie, Ross Girshick. *FAIR*

### Video Representation Learning

- Unsupervised Learning of Video Representations using LSTMs.
  [[pdf]](https://arxiv.org/pdf/1502.04681.pdf)
  [[code]](https://github.com/emansim/unsupervised-videos)
  - Srivastava, Nitish and Mansimov, Elman and Salakhudinov, Ruslan. *ICML 2015*

- Shuffle and Learn: Unsupervised Learning using Temporal Order Verification. 
  [[pdf]](http://arxiv.org/abs/1603.08561) 
  [[code]](https://github.com/imisra/shuffle-tuple)
  - Ishan Misra, C. Lawrence Zitnick and Martial Hebert. *ECCV 2016*
  
- LSTM Self-Supervision for Detailed Behavior Analysis
  [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Brattoli_LSTM_Self-Supervision_for_CVPR_2017_paper.pdf)
  - Biagio Brattoli*, Uta Büchler*, Anna-Sophia Wahl, Martin E. Schwab, and Björn Ommer. *CVPR 2017*
  
- Self-Supervised Video Representation Learning With Odd-One-Out Networks. 
  [[pdf]](https://arxiv.org/abs/1611.06646) 
  - Basura Fernando and Hakan Bilen and Efstratios Gavves and Stephen Gould. *CVPR 2017*

- Unsupervised Learning of Long-Term Motion Dynamics for Videos. 
  [[pdf]](https://arxiv.org/pdf/1701.01821.pdf)
  - Luo, Zelun and Peng, Boya and Huang, De-An and Alahi, Alexandre and Fei-Fei, Li. *CVPR 2017*

- Geometry Guided Convolutional Neural Networks for Self-Supervised Video Representation Learning.
  [[pdf]](http://ai.ucsd.edu/~haosu/papers/cvpr18_geometry_predictive_learning.pdf) 
  - Chuang Gan and Boqing Gong and Kun Liu and Hao Su and Leonidas J. Guibas. *CVPR 2018*
  
- Improving Spatiotemporal Self-Supervision by Deep Reinforcement Learning.
  [[pdf]](https://arxiv.org/abs/1807.11293)
  - Biagio Brattoli*, Uta Büchler*, and Björn Ommer. *ECCV 2018*

- Self-supervised learning of a facial attribute embedding from video.
  [[pdf]](http://www.robots.ox.ac.uk/~vgg/publications/2018/Wiles18a/wiles18a.pdf)
  - Wiles, O.*, Koepke, A.S.*, Zisserman, A. *BMVC 2018*

- Self-Supervised Video Representation Learning with Space-Time Cubic Puzzles. 
  [[pdf]](https://arxiv.org/pdf/1811.09795.pdf)
  - Kim, Dahun and Cho, Donghyeon and Yoo, Donggeun and Kweon, In So. *AAAI 2019*

- Self-Supervised Spatio-Temporal Representation Learning for Videos by Predicting Motion and Appearance Statistics.
  [[pdf]](https://arxiv.org/abs/1904.03597)
  - Jiangliu Wang; Jianbo Jiao; Linchao Bao; Shengfeng He; Yunhui Liu; Wei Liu. CVPR 2019

- DynamoNet: Dynamic Action and Motion Network.
  [[pdf]](https://arxiv.org/pdf/1904.11407.pdf)
  - Ali Diba; Vivek Sharma, Luc Van Gool, Rainer Stiefelhagen. *ICCV 2019*

- Learning Correspondence from the Cycle-consistency of Time.
  [[pdf]](https://arxiv.org/abs/1903.07593) 
  [[code]](https://github.com/xiaolonw/TimeCycle)
  - Xiaolong Wang*, Allan Jabri* and Alexei A. Efros. *CVPR 2019*

- Joint-task Self-supervised Learning for Temporal Correspondence.
  [[pdf]](https://arxiv.org/abs/1909.11895) 
  [[code]](https://github.com/Liusifei/UVC)
  - Xueting Li*, Sifei Liu*, Shalini De Mello, Xiaolong Wang, Jan Kautz, and Ming-Hsuan Yang. *NIPS 2019*

### Geometry
-   Self-supervised Learning of Motion Capture.
    [[pdf]](https://arxiv.org/pdf/1712.01337.pdf)
    [[code]](https://github.com/htung0101/3d_smpl)
    [[web]](https://sites.google.com/view/selfsupervisedlearningofmotion/)
    -   Tung, Hsiao-Yu and Tung, Hsiao-Wei and Yumer, Ersin and Fragkiadaki, Katerina. *NIPS 2017*

-   Unsupervised Learning of Depth and Ego-Motion from Video. 
    [[pdf]](https://arxiv.org/pdf/1704.07813.pdf)
    [[code]](https://github.com/tinghuiz/SfMLearner)
    [[web]](https://people.eecs.berkeley.edu/~tinghuiz/projects/SfMLearner/)
    -   Zhou, Tinghui and Brown, Matthew and Snavely, Noah and Lowe, David G. *CVPR 2017*
    
- Active Stereo Net: End-to-End Self-Supervised Learning for Active Stereo Systems.
  [[project]](http://asn.cs.princeton.edu/)
  - Yinda Zhang*, Sean Fanello, Sameh Khamis, Christoph Rhemann, Julien Valentin, Adarsh Kowdle, Vladimir Tankovich, Shahram Izadi, Thomas Funkhouser. *ECCV 2018*

- Self-Supervised Relative Depth Learning for Urban Scene Understanding.
  [[pdf]](https://people.cs.umass.edu/~hzjiang/files/ssr_depth.pdf)
  [[project]](https://people.cs.umass.edu/~hzjiang/projects/ssr_depth/)
  - Huaizu Jiang*, Erik Learned-Miller, Gustav Larsson, Michael Maire, Greg Shakhnarovich. *ECCV 2018*

- Geometry-Aware Learning of Maps for Camera Localization.
  [[pdf]](https://arxiv.org/abs/1712.03342)
  [[code]](https://github.com/NVlabs/geomapnet)
  - Samarth Brahmbhatt, Jinwei Gu, Kihwan Kim, James Hays, and Jan Kautz. CVPR 2018

- Self-supervised Learning of Geometrically Stable Features Through Probabilistic Introspection.
  [[pdf]](https://arxiv.org/abs/1804.01552)
  [[web]](http://www.robots.ox.ac.uk/~vgg/research/probabilistic_introspection/)
  - David Novotny, Samuel Albanie, Diane Larlus, Andrea Vedaldi. CVPR 2018

- Self-Supervised Learning of 3D Human Pose Using Multi-View Geometry.
  [[pdf]](https://arxiv.org/abs/1903.02330)
  - Muhammed Kocabas; Salih Karagoz; Emre Akbas. CVPR 2019

- SelFlow: Self-Supervised Learning of Optical Flow.
  [[pdf]](https://arxiv.org/abs/1904.03597)
  - Jiangliu Wang; Jianbo Jiao; Linchao Bao; Shengfeng He; Yunhui Liu; Wei Liu. CVPR 2019

- Unsupervised Learning of Landmarks by Descriptor Vector Exchange.
  [[pdf]](https://arxiv.org/abs/1908.06427)
  [[code]](https://github.com/jamt9000/DVE)
  [[web]](http://www.robots.ox.ac.uk/~vgg/research/DVE/)
  - James Thewlis, Samuel Albanie, Hakan Bilen, Andrea Vedaldi. ICCV 2019

 

### Audio
- Audio-Visual Scene Analysis with Self-Supervised Multisensory Features.
  [[pdf]](https://arxiv.org/pdf/1804.03641.pdf)
  [[code]](https://github.com/andrewowens/multisensory)
  - Andrew Owens, Alexei A. Efros. *ECCV 2018*
  
- Objects that Sound.
  [[pdf]](https://arxiv.org/pdf/1712.06651.pdf)
  -  R. Arandjelović, A. Zisserman. *ECCV 2018* 
  
- Learning to Separate Object Sounds by Watching Unlabeled Video.
  [[pdf]](https://arxiv.org/abs/1804.01665)
  [[project]](http://vision.cs.utexas.edu/projects/separating_object_sounds/)
  - Ruohan Gao, Rogerio Feris, Kristen Grauman.  *ECCV 2018*
  
- The Sound of Pixels.
  [[pdf]]( https://arxiv.org/pdf/1907.11879.pdf )
  [[project]](https://github.com/hangzhaomit/Sound-of-Pixels)
  - Zhao, Hang and Gan, Chuang and Rouditchenko, Andrew and Vondrick, Carl and McDermott, Josh and Torralba, Antonio. *ECCV 2018*

- Learnable PINs: Cross-Modal Embeddings for Person Identity.
  [[pdf]](https://arxiv.org/abs/1805.00833)
  [[web]](http://www.robots.ox.ac.uk/~vgg/research/LearnablePins/)
  - Arsha Nagrani, Samuel Albanie, Andrew Zisserman. ECCV 2018


- Cooperative Learning of Audio and Video Models from Self-Supervised Synchronization. 
  [[pdf]](http://papers.nips.cc/paper/8002-cooperative-learning-of-audio-and-video-models-from-self-supervised-synchronization.pdf)
  - Bruno Korbar,Dartmouth College, Du Tran, Lorenzo Torresani. *NIPS 2018*
  
- Self-Supervised Generation of Spatial Audio for 360° Video.
  [[pdf]](http://papers.nips.cc/paper/7319-self-supervised-generation-of-spatial-audio-for-360-video.pdf)
  - Pedro Morgado, Nuno Nvasconcelos, Timothy Langlois, Oliver Wang. *NIPS 2018*
  
- TriCycle: Audio Representation Learning from Sensor Network Data Using Self-Supervision
  [[pdf]](http://www.justinsalamon.com/uploads/4/3/9/4/4394963/cartwright_tricycle_waspaa2019.pdf)
  - Mark Cartwright, Jason Cramer, Justin Salamon, Juan Pablo Bello. *WASPAA 2019*

### Others
- Self-learning Scene-specific Pedestrian Detectors using a Progressive Latent Model.
  [[pdf]](https://arxiv.org/abs/1611.07544)
  - Qixiang Ye, Tianliang Zhang, Qiang Qiu, Baochang Zhang, Jie Chen, Guillermo Sapiro. *CVPR 2017*
- Free Supervision from Video Games.
  [[pdf]](http://www.philkr.net/papers/2018-06-01-cvpr/2018-06-01-cvpr.pdf)
  [[project+code]](http://www.philkr.net/fsv/)
  - Philipp Krähenbühl. *CVPR 2018*
- Fighting Fake News: Image Splice Detection via Learned Self-Consistency
  [[pdf]](https://arxiv.org/pdf/1805.04096.pdf)
  [[code]](https://github.com/minyoungg/selfconsistency)
  - Minyoung Huh*, Andrew Liu*, Andrew Owens, Alexei A. Efros. *ECCV 2018*
- Self-supervised Tracking by Colorization (Tracking Emerges by Colorizing Videos).
  [[pdf]](https://www.cs.columbia.edu/~vondrick//videocolor.pdf)
  - Carl Vondrick*, Abhinav Shrivastava, Alireza Fathi, Sergio Guadarrama, Kevin Murphy. *ECCV 2018*
- High-Fidelity Image Generation With Fewer Labels.
  [[pdf]](https://arxiv.org/pdf/1903.02271.pdf)
  - Mario Lucic*, Michael Tschannen*, Marvin Ritter*, Xiaohua Zhai, Olivier Bachem, Sylvain Gelly.
- Self-supervised Fitting of Articulated Meshes to Point Clouds.
  - Chun-Liang Li, Tomas Simon, Jason Saragih, Barnabás Póczos and Yaser Sheikh. *CVPR 2019*
- SCOPS: Self-Supervised Co-Part Segmentation. 
  - Wei-Chih Hung, Varun Jampani, Sifei Liu, Pavlo Molchanov, Ming-Hsuan Yang, and Jan Kautz. *CVPR 2019*
- Self-Supervised GANs via Auxiliary Rotation Loss. 
  - Ting Chen; Xiaohua Zhai; Marvin Ritter; Mario Lucic; Neil Houlsby. *CVPR 2019*
- Self-Supervised Adaptation of High-Fidelity Face Models for Monocular Performance Tracking.
  - Jae Shin Yoon; Takaaki Shiratori; Shoou-I Yu; Hyun Soo Park. *CVPR 2019*
- Multi-Task Self-Supervised Object Detection via Recycling of Bounding Box Annotations.
  - Wonhee Lee; Joonil Na; Gunhee Kim. *CVPR 2019*
- Self-Supervised Convolutional Subspace Clustering Network.
  - Junjian Zhang; Chun-Guang Li; Chong You; Xianbiao Qi; Honggang Zhang; Jun Guo; Zhouchen Lin. *CVPR 2019*
- Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation.
  - Xin Wang; Qiuyuan Huang; Asli Celikyilmaz; Jianfeng Gao; Dinghan Shen; Yuan-Fang Wang; William Yang Wang; Lei Zhang. *CVPR 2019*
- Unsupervised 3D Pose Estimation With Geometric Self-Supervision.
  - Ching-Hang Chen; Ambrish Tyagi; Amit Agrawal; Dylan Drover; Rohith MV; Stefan Stojanov; James M. Rehg. *CVPR 2019*
- Learning to Generate Grounded Image Captions without Localization Supervision. [[pdf]](https://arxiv.org/pdf/1906.00283.pdf)
  - Chih-Yao Ma; Yannis Kalantidis; Ghassan AlRegib; Peter Vajda; Marcus Rohrbach; Zsolt Kira.
- VideoBERT: A Joint Model for Video and Language Representation Learning [[pdf]](https://arxiv.org/pdf/1904.01766.pdf)
  - Chen Sun, Austin Myers, Carl Vondrick, Kevin Murphy, Cordelia Schmid. *ICCV 2019*
- S4L: Self-Supervised Semi-Supervised Learning
  [[pdf]](https://arxiv.org/pdf/1905.03670.pdf)
  - Xiaohua Zhai, Avital Oliver, Alexander Kolesnikov, Lucas Beyer
- Countering Noisy Labels By Learning From Auxiliary Clean Labels [[pdf]]( https://arxiv.org/pdf/1905.13305.pdf )
  - Tsung Wei Tsai, Chongxuan Li, Jun Zhu

## Machine Learning
-   Self-taught Learning: Transfer Learning from Unlabeled Data.
    [[pdf]](https://ai.stanford.edu/~hllee/icml07-selftaughtlearning.pdf)
    -   Raina, Rajat and Battle, Alexis and Lee, Honglak and Packer,
        Benjamin and Ng, Andrew Y. *ICML 2007*

-   Representation Learning: A Review and New Perspectives.
    [[pdf]](https://arxiv.org/pdf/1206.5538.pdf)
    -   Bengio, Yoshua and Courville, Aaron and Vincent, Pascal. *TPAMI 2013*.

### Reinforcement Learning
- Curiosity-driven Exploration by Self-supervised Prediction. 
  [[pdf]](http://pathak22.github.io/noreward-rl/resources/icml17.pdf) 
  [[code]](https://pathak22.github.io/noreward-rl/index.html#sourceCode)
  - Deepak Pathak, Pulkit Agrawal, Alexei A. Efros, and Trevor Darrell. *ICML 2017*

- Large-Scale Study of Curiosity-Driven Learning.
  [[pdf]](https://pathak22.github.io/large-scale-curiosity/resources/largeScaleCuriosity2018.pdf) 
  - Yuri Burda*, Harri Edwards*, Deepak Pathak*, Amos Storkey, Trevor Darrell and Alexei A. Efros

- Playing hard exploration games by watching YouTube.
  [[pdf]](https://papers.nips.cc/paper/7557-playing-hard-exploration-games-by-watching-youtube.pdf) 
  - Yusuf Aytar, Tobias Pfaff, David Budden, Tom Le Paine, Ziyu Wang, Nando de Freitas. *NIPS 2018*
  
- Unsupervised State Representation Learning in Atari.
  [[pdf]](https://arxiv.org/pdf/1906.08226.pdf)
  [[code]](https://github.com/mila-iqia/atari-representation-learning)
  - Ankesh Anand, Evan Racah, Sherjil Ozair, Yoshua Bengio, Marc-Alexandre Côté, R Devon Hjelm. *NeurIPS 2019*


## Robotics

### 2006
- Improving Robot Navigation Through Self-Supervised Online Learning
  [[pdf]](http://www.roboticsproceedings.org/rss02/p04.pdf)
  - Boris Sofman, Ellie Lin, J. Andrew Bagnell, Nicolas Vandapel, and Anthony Stentz
  
- Reverse Optical Flow for Self-Supervised Adaptive Autonomous Robot Navigation
  [[pdf]](https://www.cs.ait.ac.th/~mdailey/cvreadings/Lookingbill-ReverseOptical.pdf)
  - A. Lookingbill, D. Lieb, J. Rogers and J. Curry

### 2009
- Learning Long-Range Vision for Autonomous Off-Road Driving
  [[pdf]](http://yann.lecun.com/exdb/publis/pdf/hadsell-jfr-09.pdf)
  - Raia Hadsell, Pierre Sermanet, Jan Ben, Ayse Erkan, Marco Scoffier, Koray Kavukcuoglu, Urs Muller, Yann LeCun

### 2012
- Self-supervised terrain classification for planetary surface exploration rovers
  [[pdf]](https://pdfs.semanticscholar.org/66b7/eef326d1db1fa2b19d5dc6b84d3d2a95b76c.pdf)
  - Christopher A. Brooks, Karl Iagnemma 
  
### 2014
- Terrain Traversability Analysis Using Multi-Sensor Data Correlation by a Mobile Robot
  [[pdf]](http://sensor.eng.shizuoka.ac.jp/pdf/2014/SII.pdf)
  - Mohammed Abdessamad Bekhti, Yuichi Kobayashi and Kazuki Matsumura
  
### 2015
- Online self-supervised learning for dynamic object segmentation
  [[pdf]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.875.5829&rep=rep1&type=pdf)
  - Vitor Guizilini and Fabio Ramos, The International Journal of Robotics Research

- Self-Supervised Online Learning of Basic Object Push Affordances
  [[pdf]](http://abr.ijs.si/pdf/1429861734-RidgeIJARS2015.pdf)
  - Barry Ridge, Ales Leonardis, Ales Ude, Miha Denisa, and Danijel Skocaj
  
- Self-supervised learning of grasp dependent tool affordances on the iCub Humanoid robot
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7139640)
  - Tanis Mar, Vadim Tikhanoff, Giorgio Metta, and Lorenzo Natale

### 2016
- Persistent self-supervised learning principle: from stereo to monocular vision for obstacle avoidance
  [[pdf]](https://arxiv.org/pdf/1603.08047.pdf)
  - Kevin van Hecke, Guido de Croon, Laurens van der Maaten, Daniel Hennes, and Dario Izzo

- The Curious Robot: Learning Visual Representations via Physical Interactions. 
  [[pdf]](https://arxiv.org/pdf/1604.01360v2)
  - Lerrel Pinto and Dhiraj Gandhi and Yuanfeng Han and Yong-Lae Park and Abhinav Gupta. *ECCV 2016*

-   Learning to Poke by Poking: Experiential Learning of Intuitive Physics.
    [\[pdf\]](https://arxiv.org/abs/1606.07419)
    -   Agrawal, Pulkit and Nair, Ashvin V and Abbeel, Pieter and Malik, Jitendra and Levine, Sergey. *NIPS 2016*

-   Supersizing Self-supervision: Learning to Grasp from 50K Tries and
    700 Robot Hours. [\[pdf\]](https://arxiv.org/pdf/1509.06825.pdf)
    -   Pinto, Lerrel and Gupta, Abhinav. *ICRA 2016*
    
### 2017
-  Supervision via Competition: Robot Adversaries for Learning Tasks.
   [[pdf]](https://arxiv.org/pdf/1610.01685.pdf)
   - Pinto, Lerrel and Davidson, James and Gupta, Abhinav. *ICRA 2017*

- Multi-view Self-supervised Deep Learning for 6D Pose Estimation in the Amazon Picking Challenge.
  [[pdf]](https://arxiv.org/pdf/1803.09956.pdf) 
  [[Project]](http://apc.cs.princeton.edu/)
  - Andy Zeng, Kuan-Ting Yu, Shuran Song, Daniel Suo, Ed Walker Jr., Alberto Rodriguez, Jianxiong Xiao. *ICRA 2017* 

- Combining Self-Supervised Learning and Imitation for Vision-Based Rope Manipulation.
  [[pdf]](https://arxiv.org/abs/1703.02018) 
  [[Project]](https://ropemanipulation.github.io/)
  - Ashvin Nair*, Dian Chen*, Pulkit Agrawal*, Phillip Isola, Pieter Abbeel, Jitendra Malik, Sergey Levine. *ICRA 2017*

- Learning to Fly by Crashing
  [[pdf]](https://arxiv.org/abs/1704.05588)
  - Dhiraj Gandhi, Lerrel Pinto, Abhinav Gupta *IROS 2017*
  
- Self-supervised learning as an enabling technology for future space exploration robots: ISS experiments on monocular distance learning
  [[pdf]](http://www.esa.int/gsp/ACT/doc/AI/pub/ACT-RPR-AI-2017-ACTA-SSL.pdf)
  - K. van Hecke, G. C. de Croon, D. Hennes, T. P. Setterfield, A. Saenz- Otero, and D. Izzo

- Unsupervised Perceptual Rewards for Imitation Learning.
  [[pdf]](https://arxiv.org/abs/1612.06699)
  [[project]](https://sermanet.github.io/rewards/)
  - Sermanet, Pierre and Xu, Kelvin and Levine, Sergey. *RSS 2017*

- Self-Supervised Visual Planning with Temporal Skip Connections.
  [[pdf]](http://arxiv.org/pdf/1710.05268)
  - Frederik Ebert, Chelsea Finn, Alex X. Lee, Sergey Levine. *CoRL2017*

### 2018
- CASSL: Curriculum Accelerated Self-Supervised Learning. 
  [[pdf]](https://arxiv.org/pdf/1708.01354.pdf) 
  - Adithyavairavan Murali, Lerrel Pinto, Dhiraj Gandhi, Abhinav Gupta. *ICRA 2018*

- Time-Contrastive Networks: Self-Supervised Learning from Video. 
  [[pdf]](https://arxiv.org/pdf/1609.09475.pdf) 
  [[Project]](https://sermanet.github.io/imitate/)
  - Pierre Sermanet and Corey Lynch and Yevgen Chebotar and Jasmine Hsu and Eric Jang and Stefan Schaal and Sergey Levine. *ICRA 2018*

- Self-Supervised Deep Reinforcement Learning with Generalized Computation Graphs for Robot Navigation. 
  [[pdf]](http://arxiv.org/pdf/1709.10489) 
  - Gregory Kahn, Adam Villaflor, Bosen Ding, Pieter Abbeel, Sergey Levine. *ICRA 2018*

- Learning Actionable Representations from Visual Observations. 
  [[pdf]](https://arxiv.org/pdf/1609.09475.pdf) 
  [[Project]](https://sermanet.github.io/imitate/)
  - Dwibedi, Debidatta and Tompson, Jonathan and Lynch, Corey and Sermanet, Pierre. *IROS 2018* 
  
- Learning Synergies between Pushing and Grasping with Self-supervised Deep Reinforcement Learning.
  [[pdf]](https://arxiv.org/abs/1808.00928) 
  [[Project]](https://sites.google.com/view/actionablerepresentations/)
  - Andy Zeng, Shuran Song, Stefan Welker, Johnny Lee, Alberto Rodriguez, Thomas Funkhouser. *IROS 2018* 
  
- Visual Reinforcement Learning with Imagined Goals.
  [[pdf]](https://arxiv.org/abs/1807.04742) 
  [[Project]](https://sites.google.com/site/visualrlwithimaginedgoals/)
  - Ashvin Nair*, Vitchyr Pong*, Murtaza Dalal, Shikhar Bahl, Steven Lin, Sergey Levine.*NeurIPS 2018*

- Grasp2Vec: Learning Object Representations from Self-Supervised Grasping.
  [[pdf]](https://arxiv.org/pdf/1811.06964.pdf) 
  [[Project]](https://sites.google.com/site/grasp2vec/home)
  - Eric Jang*, Coline Devin*, Vincent Vanhoucke, Sergey Levine. *CoRL 2018*

- Robustness via Retrying: Closed-Loop Robotic Manipulation with Self-Supervised Learning.
  [[pdf]](https://arxiv.org/pdf/1810.03043.pdf) 
  [[Project]](https://sites.google.com/view/robustness-via-retrying)
  - Frederik Ebert, Sudeep Dasari, Alex X. Lee, Sergey Levine, Chelsea Finn. *CoRL 2018*

### 2019
- Learning Long-Range Perception Using Self-Supervision from Short-Range Sensors and Odometry.
  [[pdf]](https://arxiv.org/abs/1809.07207)
  - Mirko Nava, Jerome Guzzi, R. Omar Chavez-Garcia, Luca M. Gambardella, Alessandro Giusti. *Robotics and Automation Letters*

- Learning Latent Plans from Play. 
  [[pdf]](https://arxiv.org/pdf/1903.01973.pdf) 
  [[Project]](https://learning-from-play.github.io/)
  - COREY LYNCH, MOHI KHANSARI, TED XIAO, VIKASH KUMAR, JONATHAN TOMPSON, SERGEY LEVINE, PIERRE SERMANET


## NLP
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.
  [[pdf]](https://arxiv.org/abs/1810.04805)
  [[link]](https://github.com/google-research/bert)
  - Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. *NAACL 2019 Best Long Paper*

- Self-Supervised Dialogue Learning
  [[pdf]](https://arxiv.org/pdf/1907.00448.pdf)
  - Jiawei Wu, Xin Wang, William Yang Wang. *ACL 2019*

- Self-Supervised Learning for Contextualized Extractive Summarization
  [[pdf]](https://arxiv.org/pdf/1906.04466.pdf)
  - Hong Wang, Xin Wang, Wenhan Xiong, Mo Yu, Xiaoxiao Guo, Shiyu Chang, William Yang Wang. *ACL 2019*
  
## Talks
- The power of Self-Learning Systems. Demis Hassabis (DeepMind).
  [[link]](https://youtu.be/wxis9FrCHbw)
- Supersizing Self-Supervision: Learning Perception and Action without Human Supervision. Abhinav Gupta (CMU).
  [[link]](https://simons.berkeley.edu/talks/abhinav-gupta-2017-3-28)
- Self-supervision, Meta-supervision, Curiosity: Making Computers Study Harder. Alyosha Efros (UCB) 
  [[link]](https://business.facebook.com/academics/videos/1632981350086599)
- Unsupervised Visual Learning Tutorial. *CVPR 2018* 
  [[part 1]](https://www.youtube.com/watch?v=gSqmUOAMwcc) 
  [[part 2]](https://www.youtube.com/watch?v=BijK_US6A0w)
- Self-Supervised Learning. Andrew Zisserman (Oxford & Deepmind). 
  [[pdf]](https://project.inria.fr/paiss/files/2018/07/zisserman-self-supervised.pdf)
- Graph Embeddings, Content Understanding, & Self-Supervised Learning. Yann LeCun. (NYU & FAIR)
  [[pdf]](https://drive.google.com/file/d/12pDCno02FJPDEBk4iGuuaj8b2rr48Hh0/view)
  [[video]](https://www.youtube.com/watch?v=UGPT64wo7lU)
- Self-supervised learning: could machines learn like humans? Yann LeCun @EPFL. 
  [[video]](https://www.youtube.com/watch?v=7I0Qt7GALVk)
- Week 9 (b): CS294-158 Deep Unsupervised Learning(Spring 2019). Alyosha Efros @UC Berkeley. 
  [[video]](https://www.youtube.com/watch?v=PX11C5Vfo9U)

## Thesis
- Supervision Beyond Manual Annotations for Learning Visual Representations. Carl Doersch. [[pdf]](http://www.carldoersch.com/docs/thesis.pdf).
- Image Synthesis for Self-Supervised Visual Representation Learning. Richard Zhang. [[pdf]](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-36.pdf).
- Visual Learning beyond Direct Supervision. Tinghui Zhou. [[pdf]](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-128.pdf).
- Visual Learning with Minimal Human Supervision. Ishan Misra. [[pdf]](https://www.ri.cmu.edu/publications/visual-learning-with-minimal-human-supervision/).

## License
To the extent possible under law, [Zhongzheng Ren](https://jason718.github.io/) has waived all copyright and related or neighboring rights to this work.

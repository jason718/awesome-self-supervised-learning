# Awesome Self-Supervised Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome Self-Supervised Learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search)

Self-Supervised Learning has become an exciting direction in Computer Vision, Machine Learning, and Robotics community. These are some of the awesome resources! 

## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://jason718.github.io/) or add [pull request](https://github.com/jason718/Awesome-Self-Supervised-Learning/pulls)

Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2 and Author 3. *Conference'Year*
```

## Table of Contents
- [Computer Vision](#computer-vision)
  - [Image Representation Learning](#image-representation-learning)
  - [Video Representation Learning](#video-representation-learning)
  - [Geometry](#geometry)
- [Machine Learning](#machine-learning)
  - [Reinforcement Learning](#reinforcement-learning)
- [Robotics](#robotics)  
- [Talks](#talks)

## Computer Vision
### Image Representation Learning
#### 2015
- Unsupervised Visual Representation Learning by Context Prediction. [[pdf]](https://arxiv.org/abs/1505.05192) [[code]](http://graphics.cs.cmu.edu/projects/deepContext/)
  - Doersch, Carl and Gupta, Abhinav and Efros, Alexei A. *ICCV 2015*

- Unsupervised Learning of Visual Representations using Videos. [[pdf]](http://www.cs.cmu.edu/~xiaolonw/papers/unsupervised_video.pdf) [[code]](http://www.cs.cmu.edu/~xiaolonw/unsupervise.html)
  - Wang, Xiaolong and Gupta, Abhinav. *ICCV 2015*

- Learning to See by Moving.  [[pdf]](http://arxiv.org/abs/1505.01596) [[code]](https://people.eecs.berkeley.edu/~pulkitag/lsm/lsm.html)
  - Agrawal, Pulkit and Carreira, Joao and Malik, Jitendra. *ICCV 2015*

- Learning image representations tied to egomotion. [[pdf]](http://vision.cs.utexas.edu/projects/egoequiv/ijcv_bestpaper_specialissue_egoequiv.pdf) [[code]](http://vision.cs.utexas.edu/projects/egoequiv/)
  - Jayaraman, Dinesh and Grauman, Kristen. *ICCV 2015*

#### 2016
- Slow and steady feature analysis: higher order temporal coherence in video. [[pdf]](http://vision.cs.utexas.edu/projects/slowsteady/cvpr16.pdf)
   - Jayaraman, Dinesh and Grauman, Kristen. *CVPR 2016*

- Context Encoders: Feature Learning by Inpainting. [[pdf]](https://people.eecs.berkeley.edu/~pathak/papers/cvpr16.pdf) [[code]](https://people.eecs.berkeley.edu/~pathak/context_encoder/)
  - Pathak, Deepak and  Krahenbuhl, Philipp and Donahue, Jeff and Darrell, Trevor and Efros, Alexei A. *CVPR 2016*

- Colorful Image Colorization. [[pdf]](https://arxiv.org/abs/1603.08511) [[code]](http://richzhang.github.io/colorization/)
  - Zhang, Richard and Isola, Phillip and Efros, Alexei A. *ECCV 2016*

- Unsupervised Learning of Visual Representations by Solving Jigsaw Puzzles. [[pdf]](http://arxiv.org/abs/1603.09246) [[code]](http://www.cvg.unibe.ch/research/JigsawPuzzleSolver.html)
  - Noroozi, Mehdi and Favaro, Paolo. *ECCV 2016*

- Ambient Sound Provides Supervision for Visual Learning. [[pdf]](http://arxiv.org/pdf/1608.07017) [[code]](http://andrewowens.com/ambient/index.html)
  - Owens, Andrew and Wu, Jiajun and McDermott, Josh and Freeman, William and Torralba, Antonio. *ECCV 2016*

- Learning Representations for Automatic Colorization. [[pdf]](http://arxiv.org/pdf/1603.06668.pdf) [[code]](http://people.cs.uchicago.edu/~larsson/colorization/)
  - Larsson, Gustav and Maire, Michael and Shakhnarovich, Gregory. *ECCV 2016*

#### 2017
- Adversarial Feature Learning. [[pdf]](https://arxiv.org/pdf/1605.09782.pdf) [[code]](https://github.com/jeffdonahue/bigan)
  - Donahue, Jeff and Krahenbuhl, Philipp and Darrell, Trevor. *ICLR 2017*
  
- Self-supervised learning of visual features through embedding images into text topic spaces. [[pdf]](https://arxiv.org/pdf/1705.08631.pdf) [[code]](https://github.com/lluisgomez/TextTopicNet)
  - L. Gomez* and Y. Patel* and M. Rusiñol and D. Karatzas and C.V. Jawahar. *CVPR 2017*
  
- Split-Brain Autoencoders: Unsupervised Learning by Cross-Channel Prediction. [[pdf]](https://arxiv.org/abs/1611.09842) [[code]](https://github.com/richzhang/splitbrainauto)
  - Zhang, Richard and Isola, Phillip and Efros, Alexei A. *CVPR 2017*

- Learning Features by Watching Objects Move. [[pdf]](https://people.eecs.berkeley.edu/~pathak/papers/cvpr17.pdf) [[code]](https://people.eecs.berkeley.edu/~pathak/unsupervised_video/)
  - Pathak, Deepak and Girshick, Ross and Dollar, Piotr and  Darrell, Trevor and Hariharan, Bharath. *CVPR 2017*
  
- Colorization as a Proxy Task for Visual Understanding. [[pdf]](http://arxiv.org/abs/1703.04044) [[code]](http://people.cs.uchicago.edu/~larsson/color-proxy/)
  - Larsson, Gustav and Maire, Michael and Shakhnarovich, Gregory. *CVPR 2017*

- Unsupervised Learning by Predicting Noise. [[pdf]](https://arxiv.org/abs/1704.05310) [[code]](https://github.com/facebookresearch/noise-as-targets)
  - Bojanowski, Piotr and Joulin, Armand. *ICML 2017*

- Multi-task Self-Supervised Visual Learning. [[pdf]](https://arxiv.org/abs/1708.07860)
  - Doersch, Carl and Zisserman, Andrew. *ICCV 2017*

- Representation Learning by Learning to Count. [[pdf]](https://openreview.net/forum?id=S1v4N2l0-)
  - Noroozi, Mehdi and Pirsiavash, Hamed and Favaro, Paolo. *ICCV 2017*

- Transitive Invariance for Self-supervised Visual Representation Learning. [[pdf]](https://arxiv.org/pdf/1708.02901.pdf)
  - Wang, Xiaolong and He, Kaiming and Gupta, Abhinav. *ICCV 2017*

- Look, Listen and Learn.  [[pdf]](https://arxiv.org/pdf/1705.08168.pdf)
  - Relja, Arandjelovic and Zisserman, Andrew. *ICCV 2017*

- Unsupervised Representation Learning by Sorting Sequences. [[pdf]](https://arxiv.org/pdf/1708.01246.pdf) [[code]](https://github.com/HsinYingLee/OPN)
  - Hsin-Ying Lee, Jia-Bin Huang, Maneesh Kumar Singh, and Ming-Hsuan Yang. *ICCV 2017*

#### 2018

- Frustum PointNets for 3D Object Detection from RGB-D Data. [[pdf]](https://arxiv.org/pdf/1711.08488.pdf)
  - Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas. *CVPR 2018*

- Unsupervised Representation Learning by Predicting Image Rotations. [[pdf]](https://openreview.net/forum?id=S1v4N2l0-)
  - Spyros Gidaris and Praveer Singh and Nikos Komodakis. *ICLR 2018*
  
- Improvements to context based self-supervised learning. [[pdf]](https://arxiv.org/abs/1711.06379)
  - Terrell Mundhenk and Daniel Ho and Barry Chen. *CVPR 2018*
  
- Self-Supervised Feature Learning by Learning to Spot Artifacts.
  - Simon Jenni and Universität Bern and Paolo Favaro. *CVPR 2018*
  
- Boosting Self-Supervised Learning via Knowledge Transfer. [[pdf]](https://www.csee.umbc.edu/~hpirsiav/papers/transfer_cvpr18.pdf)
  - Mehdi Noroozi and Ananth Vinjimoor and Paolo Favaro and Hamed Pirsiavash. *CVPR 2018*
  
- Cross-domain Self-supervised Multi-task Feature Learning Using Synthetic Imagery. [[pdf]](https://arxiv.org/abs/1711.09082)
  - Zhongzheng Ren and Yong Jae Lee. *CVPR 2018*


### Video Representation Learning
- Shuffle and Learn: Unsupervised Learning using Temporal Order Verification. [[pdf]](http://arxiv.org/abs/1603.08561) [[code]](https://github.com/imisra/shuffle-tuple)
  - Ishan Misra, C. Lawrence Zitnick and Martial Hebert. *ECCV 2016*
  
- Self-Supervised Video Representation Learning With Odd-One-Out Networks. [[pdf]](https://arxiv.org/abs/1611.06646) 
  - Basura Fernando and Hakan Bilen and Efstratios Gavves and Stephen Gould. *CVPR 2017*
  
- Geometry Guided Convolutional Neural Networks for Self-Supervised Video Representation Learning.  [[pdf]](http://ai.ucsd.edu/~haosu/papers/cvpr18_geometry_predictive_learning.pdf) 
  - Chuang Gan and Boqing Gong and Kun Liu and Hao Su and Leonidas J. Guibas. *CVPR 2018*

### Geometry
- Self-Supervised Depth Learning for Urban Scene Understanding. [[pdf]](https://arxiv.org/abs/1712.04850)
  - Huaizu Jiang and Erik Learned-Miller and Gustav Larsson and Michael Maire and Greg Shakhnarovich. *Arxiv 2017*


## Machine Learning
### Reinforcement Learning
- Curiosity-driven Exploration by Self-supervised Prediction. [[pdf]](http://pathak22.github.io/noreward-rl/resources/icml17.pdf) [[code]](https://pathak22.github.io/noreward-rl/index.html#sourceCode)
  - Deepak Pathak, Pulkit Agrawal, Alexei A. Efros, and Trevor Darrell. *ICML 2017*

- coming soon...

## Robotics
- The Curious Robot: Learning Visual Representations via Physical Interactions. [[pdf]](https://arxiv.org/pdf/1604.01360v2)
  - Lerrel Pinto and Dhiraj Gandhi and Yuanfeng Han and Yong-Lae Park and Abhinav Gupta. *ECCV 2016*

- Time-Contrastive Networks: Self-Supervised Learning from Video. [[pdf]](https://arxiv.org/abs/1704.06888) [[Project]](https://sermanet.github.io/imitate/)
  - Pierre Sermanet and Corey Lynch and Yevgen Chebotar and Jasmine Hsu and Eric Jang and Stefan Schaal and Sergey Levine. *ICRA 2018*

## Talks
- Supersizing Self-Supervision: Learning Perception and Action without Human Supervision. Abhinav Gupta (CMU) [[link]](https://simons.berkeley.edu/talks/abhinav-gupta-2017-3-28)

## License
To the extent possible under law, [Zhongzheng Ren](https://jason718.github.io/) has waived all copyright and related or neighboring rights to this work.

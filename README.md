


# Awesome Pruning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

  

A curated list of neural network pruning and related resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers) and [Awesome-NAS](https://github.com/D-X-Y/Awesome-NAS).


Please feel free to [pull requests](https://github.com/he-y/awesome-Pruning/pulls) or [open an issue](https://github.com/he-y/awesome-Pruning/issues) to add papers.

  

## Table of Contents

  

- [Type of Pruning](#type-of-pruning)

- [2019 Venues](#2019)
- [2018 Venues](#2018)
- [2017 Venues](#2017)
- [2016 Venues](#2016)
- [2015 Venues](#2015)




### Type of Pruning

|  Type |  `F` |  `W`  |  `Other` |
|:------------|:--------------:|:----------------------:|:----------:|
| Explanation | Filter pruning | Weight pruning | other types |


### 2019

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Filter Pruning via Geometric Median for Deep Convolutional Neural Networks Acceleration](https://arxiv.org/abs/1811.00250) | CVPR **(Oral)** | `F` |[github](https://github.com/he-y/filter-pruning-geometric-median)|
| [Towards Optimal Structured CNN Pruning via Generative Adversarial Learning](https://arxiv.org/abs/1903.09291) | CVPR | `F` | [github](https://github.com/ShaohuiLin/GAL)  |
| [Centripetal SGD for Pruning Very Deep Convolutional Networks with Complicated Structure](https://arxiv.org/abs/1904.03837) | CVPR | `F` | [github](https://github.com/ShawnDing1994/Centripetal-SGD)|
| [On Implicit Filter Level Sparsity in Convolutional Neural Networks](https://arxiv.org/abs/1811.12495) | CVPR | `F` | - |
| [Structured Pruning of Neural Networks with Budget-Aware Regularization](https://arxiv.org/abs/1811.09332) | CVPR | `F` | -|
| [Importance Estimation for Neural Network Pruning](http://jankautz.com/publications/Importance4NNPruning_CVPR19.pdf) | CVPR | `F` | -|
| [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://arxiv.org/abs/1903.03777) | CVPR | `Other` | [github](https://github.com/lixincn2015/Partial-Order-Pruning) |
| Variational Convolutional Neural Network Pruning | CVPR | - | -|
| [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635) | ICLR **(Best)** | `F` | [github](https://github.com/google-research/lottery-ticket-hypothesis)|
| [Rethinking the Value of Network Pruning](https://arxiv.org/abs/1810.05270) | ICLR | `F` | [github](https://github.com/Eric-mingjie/rethinking-network-pruning)|
| [Dynamic Channel Pruning: Feature Boosting and Suppression](https://arxiv.org/abs/1810.05331)| ICLR | `F` | [github](https://github.com/deep-fry/mayo)|
| [SNIP: Single-shot Network Pruning based on Connection Sensitivity](https://arxiv.org/abs/1810.02340)| ICLR | `F` | [github](https://github.com/namhoonlee/snip-public)|
| [Collaborative Channel Pruning for Deep Networks](http://proceedings.mlr.press/v97/peng19c.html)| ICML | `F` | -|
| [Approximated Oracle Filter Pruning for Destructive CNN Width Optimization github](https://arxiv.org/abs/1905.04748)| ICML | `F` | -|
| [EigenDamage: Structured Pruning in the Kronecker-Factored Eigenbasis4](https://arxiv.org/abs/1905.05934)| ICML | `W` | [github](https://github.com/alecwangcq/EigenDamage-Pytorch)|


### 2018
|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Rethinking the Smaller-Norm-Less-Informative Assumption in Channel Pruning of Convolution Layers](https://arxiv.org/abs/1802.00124)| ICLR | `F` | [github](https://github.com/jack-willturner/batchnorm-pruning)|
| [To prune, or not to prune: exploring the efficacy of pruning for model compression](https://arxiv.org/abs/1710.01878)| ICLR | `W` | -|
| [Learning Sparse Neural Networks through L0 Regularization](https://arxiv.org/abs/1712.01312)| ICLR | `F` | [github](https://github.com/AMLab-Amsterdam/L0_regularization)|
| [Discrimination-aware Channel Pruning for Deep Neural Networks](https://arxiv.org/abs/1810.11809)| NIPS | `F` | [github](https://github.com/SCUT-AILab/DCP)|
| [Frequency-Domain Dynamic Pruning for Convolutional Neural Networks](https://papers.nips.cc/paper/7382-frequency-domain-dynamic-pruning-for-convolutional-neural-networks.pdf)| NIPS | `W` | - |
| [Amc: Automl for model compression and acceleration on mobile devices](https://arxiv.org/abs/1802.03494)| ECCV | `F` | [github](https://github.com/Tencent/PocketFlow#channel-pruning)|
| [Data-Driven Sparse Structure Selection for Deep Neural Networks](https://arxiv.org/abs/1707.01213)| ECCV | `F` | [github](https://github.com/TuSimple/sparse-structure-selection)|
| [Coreset-Based Neural Network Compression](https://arxiv.org/abs/1807.09810) | ECCV | `F` | [github](https://github.com/metro-smiles/CNN_Compression)|
|[Constraint-Aware Deep Neural Network Compression](http://www.sfu.ca/~ftung/papers/constraintaware_eccv18.pdf) | ECCV | `W` | [github](https://github.com/ChanganVR/ConstraintAwareCompression)|
|[A Systematic DNN Weight Pruning Framework using Alternating Direction Method of Multipliers](https://arxiv.org/abs/1804.03294)| ECCV | `W` | [github](https://github.com/KaiqiZhang/admm-pruning)|
| [PackNet: Adding Multiple Tasks to a Single Network by Iterative Pruning](https://arxiv.org/abs/1711.05769)| CVPR | `F` | [github](https://github.com/arunmallya/packnet)|
| [NISP: Pruning Networks using Neuron Importance Score Propagation](https://arxiv.org/abs/1711.05908)| CVPR | `F` | -|
| [CLIP-Q: Deep Network Compression Learning by In-Parallel Pruning-Quantization](http://www.sfu.ca/~ftung/papers/clipq_cvpr18.pdf)| CVPR | `W` | -|
| [“Learning-Compression” Algorithms for Neural Net Pruning](http://faculty.ucmerced.edu/mcarreira-perpinan/papers/cvpr18.pdf)| CVPR | `W` | -|
|  [Soft Filter Pruning for Accelerating Deep Convolutional Neural Networks](https://arxiv.org/abs/1808.06866)| IJCAI | `F` | [github](https://github.com/he-y/soft-filter-pruning)|


### 2017

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)| ICLR | `F` | [github](https://github.com/Eric-mingjie/rethinking-network-pruning/tree/master/imagenet/l1-norm-pruning)|
|[Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/abs/1611.06440)| ICLR | `W` | [github](https://github.com/Tencent/PocketFlow#channel-pruning) [pytorch](https://github.com/jacobgil/pytorch-pruning)|
|[Net-Trim: Convex Pruning of Deep Neural Networks with Performance Guarantee](https://arxiv.org/abs/1611.05162)| NIPS | `W` | [github](https://github.com/DNNToolBox/Net-Trim-v1)|
|[Learning to Prune Deep Neural Networks via Layer-wise Optimal Brain Surgeon](https://arxiv.org/abs/1705.07565)| NIPS | `W` | [github](https://github.com/csyhhu/L-OBS)|
|[Runtime Neural Pruning](https://papers.nips.cc/paper/6813-runtime-neural-pruning) | NIPS | `F` |  - |
|  [Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning](https://arxiv.org/abs/1611.05128)|CVPR|`F` |-|
|  [ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://arxiv.org/abs/1707.06342)|ICCV|`F` | [github](https://github.com/Roll920/ThiNet)|
|  [Channel pruning for accelerating very deep neural networks](https://arxiv.org/abs/1707.06168)|ICCV|`F` | [github](https://github.com/yihui-he/channel-pruning)|
| [Learning Efficient Convolutional Networks Through Network Slimming](https://arxiv.org/abs/1708.06519)|ICCV|`F` | [github](https://github.com/Eric-mingjie/network-slimming)|


### 2016

|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding](https://arxiv.org/abs/1510.00149) | ICLR **(Best)** | `W` | [github](https://github.com/mightydeveloper/Deep-Compression-PyTorch)|
| [Dynamic Network Surgery for Efficient DNNs](https://arxiv.org/abs/1608.04493) | NIPS | `W` | [github](https://github.com/DAVIDNEWGATE/Project)|

### 2015
|  Title  | Venue  | Type | Code |
|:--------|:--------:|:--------:|:--------:|
| [Learning both Weights and Connections for Efficient Neural Networks](https://arxiv.org/abs/1506.02626) | NIPS | `W` |[github](https://github.com/jack-willturner/DeepCompression-PyTorch)|



## Related Repo
[Awesome-model-compression-and-acceleration](https://github.com/memoiry/Awesome-model-compression-and-acceleration)

[EfficientDNNs](https://github.com/MingSun-Tse/EfficientDNNs)

[Embedded-Neural-Network](https://github.com/ZhishengWang/Embedded-Neural-Network)

[awesome-AutoML-and-Lightweight-Models](https://github.com/guan-yuan/awesome-AutoML-and-Lightweight-Models)

[Model-Compression-Papers](https://github.com/chester256/Model-Compression-Papers)

[knowledge-distillation-papers](https://github.com/lhyfst/knowledge-distillation-papers)

[Network-Speed-and-Compression](https://github.com/mrgloom/Network-Speed-and-Compression)


# Awesome Pruning at Initialization [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A comprehensive survey of recent papers on Neural Network Pruning at Initialization (PaI).

[[Survey](https://arxiv.org/abs/2103.06460) | [Code](https://github.com/MingSun-Tse/Smile-Pruning)]

**2018**
- 2018-ICLR-[Deep rewiring: Training very sparse deep networks](https://arxiv.org/abs/1711.05136)
- 2018-ICML-[Stronger generalization bounds for deep nets via a compression approach](http://proceedings.mlr.press/v80/arora18b.html)
- 2018-Nature Communications-[Scalable training of artificial neural networks with adaptive sparse connectivity inspired by network science](https://www.nature.com/articles/s41467-018-04316-3)

**2019**
- 2019-ICLR-[Snip: Single-shot network pruning based on connection sensitivity](https://arxiv.org/abs/1810.02340)
- 2019-ICLR-[The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://openreview.net/forum?id=rJl-b3RcF7) [Best Paper!] [[Code 1](https://github.com/google-research/lottery-ticket-hypothesis)] [[Code 2](https://github.com/facebookresearch/open_lth)]
- 2019-ICML-[Parameter efficient training of deep convolutional neural networks by dynamic sparse reparameterization](http://proceedings.mlr.press/v97/mostafa19a.html)
- 2019-NIPS-[Deconstructing lottery tickets: Zeros, signs, and the supermask](https://papers.nips.cc/paper/2019/hash/1113d7a76ffceca1bb350bfe145467c6-Abstract.html)
- 2019-NIPS-[One ticket to win them all: generalizing lottery ticket initializations across datasets and optimizers](https://papers.nips.cc/paper/2019/hash/a4613e8d72a61b3b69b32d040f89ad81-Abstract.html) [[Code](https://github.com/varungohil/Generalizing-Lottery-Tickets)]
- 2019.7-[Sparse networks from scratch: Faster training without losing performance](https://arxiv.org/abs/1907.04840) [[ICLR'20 rejected version](https://openreview.net/forum?id=ByeSYa4KPS)] [[Code](https://github.com/TimDettmers/sparse_learning)]


**2020**
- 2020-ICLR-[Picking Winning Tickets Before Training By Preserving Gradient Flow](https://openreview.net/pdf?id=SkgsACVKPH) [[Code](https://github.com/alecwangcq/GraSP)]
- 2020-ICLR-[Playing the lottery with rewards and multiple languages: Lottery tickets in RL and NLP](https://openreview.net/forum?id=S1xnXRVFwH)
- 2020-ICLR-[Drawing early-bird tickets: Towards more efficient training of deep networks](https://arxiv.org/abs/1909.11957) (Spotlight)
- 2020-ICLR-[The Early Phase of Neural Network Training](https://openreview.net/forum?id=Hkl1iRNFwS)
- 2020-ICLR-[A signal propagation perspective for pruning neural networks at initialization](https://arxiv.org/abs/1906.06307)
- 2020-ICLR-[Comparing Rewinding and Fine-tuning in Neural Network Pruning](https://openreview.net/forum?id=S1gSj0NKvB) [[Code](https://github.com/lottery-ticket/rewinding-iclr20-public)] (Oral)
- 2020-ICLR-[Dynamic Sparse Training: Find Efficient Sparse Network From Scratch With Trainable Masked Layers](https://arxiv.org/abs/2005.06870)
- 2020-ICLR reject-[Gradient Flow in Sparse Neural Networks and How Lottery Tickets Win](https://openreview.net/forum?id=V1N4GEWki_E)
- 2020-CVPR-[What's hidden in a randomly weighted neural network?](https://arxiv.org/abs/1911.13299)
- 2020-ICML-[Proving the Lottery Ticket Hypothesis: Pruning is All You Need](https://arxiv.org/abs/2002.00585)
- 2020-ICML-[Rigging the Lottery: Making All Tickets Winners](https://arxiv.org/abs/1911.11134) [[Code](https://github.com/google-research/rigl)]
- 2020-ICML-[Linear Mode Connectivity and the Lottery Ticket Hypothesis](https://arxiv.org/abs/1912.05671)
- 2020-ICML-[Finding trainable sparse networks through neural tangent transfer](https://arxiv.org/abs/2006.08228)
- 2020-NIPS-[Sanity-Checking Pruning Methods: Random Tickets can Win the Jackpot](https://proceedings.neurips.cc//paper/2020/hash/eae27d77ca20db309e056e3d2dcd7d69-Abstract.html)
- 2020-NIPS-[Logarithmic Pruning is All You Need](https://papers.nips.cc/paper/2020/hash/1e9491470749d5b0e361ce4f0b24d037-Abstract.html)
- 2020-NIPS-[Winning the Lottery with Continuous Sparsification](https://papers.nips.cc/paper/2020/hash/83004190b1793d7aa15f8d0d49a13eba-Abstract.html)
- 2020-NIPS-[Movement Pruning: Adaptive Sparsity by Fine-Tuning](https://proceedings.neurips.cc/paper/2020/hash/eae15aabaa768ae4a5993a8a4f4fa6e4-Abstract.html)
- 2020-NIPS-[The Lottery Ticket Hypothesis for Pre-trained BERT Networks](https://arxiv.org/abs/2007.12223)
- 2020-Neural Computing and Applications-[Sparse evolutionary deep learning with over one million artificial neurons on commodity hardware](https://link.springer.com/article/10.1007/s00521-020-05136-7)
- 2020-NIPS-[Train-by-Reconnect: Decoupling Locations of Weights from their Values](https://arxiv.org/abs/2003.02570)
- 2020-NIPS-[Pruning neural networks without any data by iteratively conserving synaptic flow](https://arxiv.org/abs/2006.05467)
- 2020.2-[Calibrate and Prune: Improving Reliability of Lottery Tickets Through Prediction Calibration](https://arxiv.org/abs/2002.03875)
- 2020.9-[The Hardware Lottery](https://arxiv.org/abs/2009.06489)
- 2020.10-[The Sooner The Better: Investigating Structure of Early Winning Lottery Tickets](https://openreview.net/forum?id=BJlNs0VYPB)

**2021**
- 2021-ICLR-[Pruning Neural Networks at Initialization: Why Are We Missing the Mark?](https://openreview.net/forum?id=Ig-VyQc-MLK)
- 2021-ICLR-[Long Live the Lottery- The Existence of Winning Tickets in Lifelong Learning](https://openreview.net/pdf?id=LXMSvPmsm0g)
- 2021-ICLR-[Robust Pruning at Initialization](https://openreview.net/forum?id=vXj_ucZQ4hA)
- 2021-ICLR-[Multi-Prize Lottery Ticket Hypothesis: Finding Accurate Binary Neural Networks by Pruning A Randomly Weighted Network](https://openreview.net/forum?id=U_mat0b9iv) [[PyTorch Code](https://github.com/chrundle/biprop)]
- 2021-ICLR-[Layer-adaptive Sparsity for the Magnitude-based Pruning](https://openreview.net/forum?id=H6ATjJ0TKdf) [[Code](https://github.com/jaeho-lee/layer-adaptive-sparsity)]
- 2021-ICLR-[Progressive skeletonization: Trimming more fat from a network at initialization](https://openreview.net/forum?id=9GsFOUyUPi)
- 2021-CVPR-[The Lottery Tickets Hypothesis for Supervised and Self-supervised Pre-training in Computer Vision Models](https://arxiv.org/abs/2012.06908)
- 2021-ICML-[Lottery Ticket Implies Accuracy Degradation, Is It a Desirable Phenomenon?](https://arxiv.org/abs/2102.11068)
- 2021-ICML-[A Unified Lottery Ticket Hypothesis for Graph Neural Networks](http://proceedings.mlr.press/v139/chen21p.html)
- 2021-ICML-[Do we actually need dense over-parameterization? in-time over-parameterization in sparse training](https://proceedings.mlr.press/v139/liu21y.html)
- 2021-ICML-[Efficient Lottery Ticket Finding: Less Data is More](http://proceedings.mlr.press/v139/zhang21c.html)
- 2021-NIPS-[The Elastic Lottery Ticket Hypothesis](https://arxiv.org/abs/2103.16547) [[Code](https://github.com/VITA-Group/ElasticLTH)]
- 2021-NIPS-[Training Neural Networks with Fixed Sparse Masks](https://proceedings.neurips.cc/paper/2021/hash/cb2653f548f8709598e8b5156738cc51-Abstract.html) [[Code](https://github.com/varunnair18/FISH)]
- 2021-NIPS-[Validating the Lottery Ticket Hypothesis with Inertial Manifold Theory](https://openreview.net/forum?id=h6EWbx5xTj7) [[Code](https://github.com/DMML-AU/IMC)] (Code link seems invalid now...)
- 2021-NIPS-[Sparse Training via Boosting Pruning Plasticity with Neuroregeneration](https://proceedings.neurips.cc/paper/2021/hash/5227b6aaf294f5f027273aebf16015f2-Abstract.html) [[Code](https://github.com/VITA-Group/GraNet)]
- 2021-NIPS-[Sanity Checks for Lottery Tickets: Does Your Winning Ticket Really Win the Jackpot?](https://proceedings.neurips.cc/paper/2021/file/6a130f1dc6f0c829f874e92e5458dced-Paper.pdf)
- 2021-ACL-[Parameter-Efficient Transfer Learning with Diff Pruning](https://arxiv.org/abs/2012.07463)
- 2021.6-[Why is Pruning at Initialization Immune to Reinitializing and Shuffling](https://arxiv.org/pdf/2107.01808.pdf)
- 2021.7-[Connectivity Matters: Neural Network Pruning Through the Lens of Effective Sparsity](https://arxiv.org/abs/2107.02306)

**2022**
- 2022-ICLR-[Dual Lottery Ticket Hypothesis](https://openreview.net/forum?id=fOsN52jn25l)
- 2022-ICLR-[The Unreasonable Effectiveness of Random Pruning: Return of the Most Naive Baseline for Sparse Training](https://openreview.net/forum?id=VBZJ_3tz-t)
- 2022-ICLR-[Deep Ensembling with No Overhead for either Training or Testing: The All-Round Blessings of Dynamic Sparsity](https://openreview.net/forum?id=RLtqs6pzj1-)
- 2022-ICLR-[Pixelated butterfly: Simple and efficient sparse training for neural network models](https://openreview.net/pdf?id=Nfl-iXa-y7R) [[Code](https://github.com/HazyResearch/pixelfly)]

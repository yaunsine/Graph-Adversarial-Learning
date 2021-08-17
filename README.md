# ⚔🛡 Awesome Graph Adversarial Learning (Updating 251 papers)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Contributions Welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

<a class="toc" id="table-of-contents"></a>

- [⚔🛡 Awesome Graph Adversarial Learning (Updating 251 papers)](#-awesome-graph-adversarial-learning-updating-251-papers)
- [👀Quick Look](#quick-look)
- [⚔Attack](#attack)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
- [🛡Defense](#defense)
  - [2021](#2021-1)
  - [2020](#2020-1)
  - [2019](#2019-1)
  - [2018](#2018-1)
  - [2017](#2017-1)
- [🔐Certification](#certification)
- [⚖Stability](#stability)
- [🚀Others](#others)
- [📃Survey](#survey)
- [⚙Toolbox](#toolbox)
- [🔗Resource](#resource)

<img width = "500"  height =300 src="imgs/wordcloud.png" >

This repository contains Attack-related papers, Defense-related papers, Robustness Certification papers, etc., ranging from 2017 to 2021. 
If you find this repo useful, please cite:
*A Survey of Adversarial Learning on Graph, Arxiv'20*, [Link](https://arxiv.org/abs/2003.05730)

```bibtex
@article{chen2020survey,
  title={A Survey of Adversarial Learning on Graph},
  author={Chen, Liang and Li, Jintang and Peng, Jiaying and Xie, 
        Tao and Cao, Zengxu and Xu, Kun and He, Xiangnan and Zheng, Zibin},
  journal={arXiv preprint arXiv:2003.05730},
  year={2020}
}
```

# 👀Quick Look

| [By Alphabet](Categorized/alphabet.md) | [By Year](Categorized/year.md) | [By Venue](Categorized/venue.md) | [Papers with Code](Categorized/papers_with_code.md) |

If you want to get a quick look at the recently updated papers in the repository (in 30 days), you can refer to [📍this](Categorized/recent.md).



# ⚔Attack



## 2021
[💨 Back to Top](#table-of-contents)

+ **Stealing Links from Graph Neural Networks**, *[📝USENIX Security](https://www.usenix.org/system/files/sec21summer_he.pdf)*
+ **PATHATTACK: Attacking Shortest Paths in Complex Networks**, *[📝Arxiv](https://arxiv.org/abs/2104.03761)*
+ **Structack: Structure-based Adversarial Attacks on Graph Neural Networks**, *[📝ACM Hypertext](https://arxiv.org/abs/2107.11327)*, *[:octocat:Code](https://github.com/sqrhussain/structack)*
+ **Optimal Edge Weight Perturbations to Attack Shortest Paths**, *[📝Arxiv](https://arxiv.org/abs/2107.03347)*
+ **GReady for Emerging Threats to Recommender Systems? A Graph Convolution-based Generative Shilling Attack**, *[📝Information Sciences](https://arxiv.org/abs/2107.10457)*
+ **Graph Adversarial Attack via Rewiring**, *[📝KDD](https://dl.acm.org/doi/abs/10.1145/3447548.3467416)*, *[:octocat:Code](https://github.com/alge24/ReWatt)*
+ **Membership Inference Attack on Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2101.06570)*
+ **BinarizedAttack: Structural Poisoning Attacks to Graph-based Anomaly Detection**, *[📝Arxiv](https://arxiv.org/abs/2106.09989)*
+ **Adversarial Attack on Graph Neural Networks as An Influence Maximization Problem**, *[📝Arxiv](https://arxiv.org/abs/2106.10785)*
+ **TDGIA: Effective Injection Attacks on Graph Neural Networks**, *[📝KDD](https://dl.acm.org/doi/abs/10.1145/3447548.3467314)*, *[:octocat:Code](https://github.com/THUDM/tdgia)*
+ **Adversarial Attack Framework on Graph Embedding Models with Limited Knowledge**, *[📝Arxiv](https://arxiv.org/abs/2105.12419)*
+ **Adversarial Attack on Large Scale Graph**, *[📝TKDE](https://arxiv.org/abs/2009.03488)*, *[:octocat:Code](https://github.com/EdisonLeeeee/SGAttack)*
+ **Black-box Gradient Attack on Graph Neural Networks: Deeper Insights in Graph-based Attack and Defense**, *[📝Arxiv](https://arxiv.org/abs/2104.15061)*
+ **Joint Detection and Localization of Stealth False Data Injection Attacks in Smart Grids using Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2104.11846)*
+ **Universal Spectral Adversarial Attacks for Deformable Shapes**, *[📝CVPR](https://arxiv.org/abs/2104.03356)*
+ **SAGE: Intrusion Alert-driven Attack Graph Extractor**, *[📝KDD Workshop](https://arxiv.org/abs/2107.02783)*, *[:octocat:Code](https://github.com/tudelft-cda-lab/SAGE)*
+ **Adversarial Diffusion Attacks on Graph-based Traffic Prediction Models**, *[📝Arxiv](https://arxiv.org/abs/2104.09369)*, *[:octocat:Code](https://github.com/LYZ98/Adversarial-Diffusion-Attacks-on-Graph-based-Traffic-Prediction-Models)*
+ **VIKING: Adversarial Attack on Network Embeddings via Supervised Network Poisoning**, *[📝PAKDD](https://arxiv.org/abs/2102.07164)*, *[:octocat:Code](https://github.com/virresh/viking)*
+ **Explainability-based Backdoor Attacks Against Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2104.03674)*
+ **GraphAttacker: A General Multi-Task GraphAttack Framework**, *[📝Arxiv](https://arxiv.org/abs/2101.06855)*, *[:octocat:Code](https://github.com/honoluluuuu/GraphAttacker)*
+ **Attacking Graph Neural Networks at Scale**, *[📝AAAI workshop](https://www.dropbox.com/s/ddrwoswpz3wwx40/Robust_GNNs_at_Scale__AAAI_Workshop_2020_CameraReady.pdf?dl=0)*
+ **Node-Level Membership Inference Attacks Against Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2102.05429)*
+ **Reinforcement Learning For Data Poisoning on Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2102.06800)*
+ **Graph Backdoor**, *[📝USENIX Security](https://arxiv.org/abs/2006.11890)*
+ **DeHiB: Deep Hidden Backdoor Attack on Semi-Supervised Learning via Adversarial Perturbation**, *[📝AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/17266)*
+ **Graphfool: Targeted Label Adversarial Attack on Graph Embedding**, *[📝Arxiv](https://arxiv.org/abs/2102.12284)*
+ **Towards Revealing Parallel Adversarial Attack on Politician Socialnet of Graph Structure**, *[📝Security and Communication Networks](https://www.hindawi.com/journals/scn/2021/6631247)*
+ **Network Embedding Attack: An Euclidean Distance Based Method**, *[📝MDATA](https://link.springer.com/chapter/10.1007%2F978-3-030-71590-8_8)*
+ **Preserve, Promote, or Attack? GNN Explanation via Topology Perturbation**, *[📝Arxiv](https://arxiv.org/abs/2103.12256)*
+ **Jointly Attacking Graph Neural Network and its Explanations**, *[📝Arxiv](https://arxiv.org/abs/2108.03388)*
+ **Graph Stochastic Neural Networks for Semi-supervised Learning**, *[📝Arxiv](https://papers.nips.cc/paper/2020/file/e586a4f55fb43a540c2e9dab45e00f53-Paper.pdf)*, *[:octocat:Code](https://github.com/GSNN/GSNN)*
+ **Iterative Deep Graph Learning for Graph Neural Networks: Better and Robust Node Embeddings**, *[📝Arxiv](https://arxiv.org/abs/2006.13009)*, *[:octocat:Code](https://github.com/hugochan/IDGL)*

## 2020
[💨 Back to Top](#table-of-contents)

+ **A Graph Matching Attack on Privacy-Preserving Record Linkage**, *[📝CIKM](https://dl.acm.org/doi/abs/10.1145/3340531.3411931)*
+ **Semantic-preserving Reinforcement Learning Attack Against Graph Neural Networks for Malware Detection**, *[📝Arxiv](https://arxiv.org/abs/2009.05602)*
+ **Adaptive Adversarial Attack on Graph Embedding via GAN**, *[📝SocialSec](https://link.springer.com/chapter/10.1007/978-981-15-9031-3_7)*
+ **Scalable Adversarial Attack on Graph Neural Networks with Alternating Direction Method of Multipliers**, *[📝Arxiv](https://arxiv.org/abs/2009.10233)*
+ **One Vertex Attack on Graph Neural Networks-based Spatiotemporal Forecasting**, *[📝ICLR OpenReview](https://openreview.net/forum?id=W0MKrbVOxtd)*
+ **Single-Node Attack for Fooling Graph Neural Networks**, *[📝ICLR OpenReview](https://openreview.net/forum?id=u4WfreuXxnk)*, *[:octocat:Code](https://github.com/benfinkelshtein/SINGLE)*
+ **Black-Box Adversarial Attacks on Graph Neural Networks as An Influence Maximization Problem**, *[📝ICLR OpenReview](https://openreview.net/forum?id=sbyjwhxxT8K)*
+ **Adversarial Attacks on Deep Graph Matching**, *[📝NeurIPS](https://papers.nips.cc/paper/2020/file/ef126722e64e98d1c33933783e52eafc-Paper.pdf)*
+ **Black-Box Adversarial Attacks on Graph Neural Networks with Limited Node Access**, *[📝NeurIPS](https://arxiv.org/abs/2006.05057)*
+ **Attacking Graph-Based Classification without Changing Existing Connections**, *[📝ACSAC](https://cse.sc.edu/~zeng1/papers/2020-acsac-graph.pdf)*
+ **Cross Entropy Attack on Deep Graph Infomax**, *[📝IEEE ISCAS](https://ieeexplore.ieee.org/document/9180817)*
+ **Model Extraction Attacks on Graph Neural Networks: Taxonomy and Realization**, *[📝Arxiv](https://arxiv.org/abs/2010.12751)*
+ **Learning to Deceive Knowledge Graph Augmented Models via Targeted Perturbation**, *[📝ICLR](https://arxiv.org/abs/2010.12872)*, *[:octocat:Code](https://github.com/INK-USC/deceive-KG-models)*
+ **Towards More Practical Adversarial Attacks on Graph Neural Networks**, *[📝NeurIPS](https://arxiv.org/abs/2006.05057)*, *[:octocat:Code](https://github.com/Mark12Ding/GNN-Practical-Attack)*
+ **Adversarial Label-Flipping Attack and Defense for Graph Neural Networks**, *[📝ICDM](http://shichuan.org/doc/97.pdf)*, *[:octocat:Code](https://github.com/MengmeiZ/LafAK)*
+ **Exploratory Adversarial Attacks on Graph Neural Networks**, *[📝ICDM](https://ieeexplore.ieee.org/document/9338329)*, *[:octocat:Code](https://github.com/EpoAtk/EpoAtk)*
+ **A Targeted Universal Attack on Graph Convolutional Network**, *[📝Arxiv](https://arxiv.org/abs/2011.14365)*, *[:octocat:Code](https://github.com/Nanyuu/TUA)*
+ **Query-free Black-box Adversarial Attacks on Graphs**, *[📝Arxiv](https://arxiv.org/abs/2012.06757)*
+ **An Efficient Adversarial Attack on Graph Structured Data**, *[📝IJCAI Workshop](https://www.aisafetyw.org/programme)*
+ **Reinforcement Learning-based Black-Box Evasion Attacks to Link Prediction in Dynamic Graphs**, *[📝Arxiv](https://arxiv.org/abs/2009.00163)*
+ **Efficient Evasion Attacks to Graph Neural Networks via Influence Function**, *[📝Arxiv](https://arxiv.org/abs/2009.00203)*
+ **Backdoor Attacks to Graph Neural Networks**, *[📝ICLR OpenReview](https://arxiv.org/abs/2006.11165)*
+ **Link Prediction Adversarial Attack Via Iterative Gradient Attack**, *[📝IEEE Trans](https://ieeexplore.ieee.org/abstract/document/9141291)*
+ **Adversarial Attack on Hierarchical Graph Pooling Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2005.11560)*
+ **Adversarial Attack on Community Detection by Hiding Individuals**, *[📝WWW](https://arxiv.org/abs/2001.07933)*, *[:octocat:Code](https://github.com/halimiqi/CD-ATTACK)*
+ **Manipulating Node Similarity Measures in Networks**, *[📝AAMAS](https://arxiv.org/abs/1910.11529)*
+ **A Restricted Black-box Adversarial Framework Towards Attacking Graph Embedding Models**, *[📝AAAI](https://arxiv.org/abs/1908.01297)*, *[:octocat:Code](https://github.com/SwiftieH/GFAttack)*
+ **Indirect Adversarial Attacks via Poisoning Neighbors for Graph Convolutional Networks**, *[📝BigData](https://arxiv.org/abs/2002.08012)*
+ **Non-target-specific Node Injection Attacks on Graph Neural Networks: A Hierarchical Reinforcement Learning Approach**, *[📝WWW](http://faculty.ist.psu.edu/vhonavar/Papers/www20.pdf)*
+ **An Efficient Adversarial Attack on Graph Structured Data**, *[📝IJCAI Workshop](https://www.aisafetyw.org/programme)*
+ **Practical Adversarial Attacks on Graph Neural Networks**, *[📝ICML Workshop](https://grlplus.github.io/papers/8.pdf)*
+ **Adversarial Attacks on Graph Neural Networks: Perturbations and their Patterns**, *[📝TKDD](https://dl.acm.org/doi/10.1145/3394520)*
+ **Adversarial Attacks on Link Prediction Algorithms Based on Graph Neural Networks**, *[📝Asia CCS](https://iqua.ece.toronto.edu/papers/wlin-asiaccs20.pdf)*
+ **Scalable Attack on Graph Data by Injecting Vicious Nodes**, *[📝ECML-PKDD](https://arxiv.org/abs/2004.13825)*
+ **Attackability Characterization of Adversarial Evasion Attack on Discrete Data**, *[📝KDD](https://dl.acm.org/doi/10.1145/3394486.3403194)*
+ **MGA: Momentum Gradient Attack on Network**, *[📝Arxiv](https://arxiv.org/abs/2002.11320)*
+ **Adversarial Attacks to Scale-Free Networks: Testing the Robustness of Physical Criteria**, *[📝Arxiv](https://arxiv.org/abs/2002.01249)*
+ **Graph Universal Adversarial Attacks: A Few Bad Actors Ruin Graph Learning Models**, *[📝Arxiv](https://arxiv.org/abs/2002.04784)*, *[:octocat:Code](https://github.com/chisam0217/Graph-Universal-Attack)*
+ **Adversarial Perturbations of Opinion Dynamics in Networks**, *[📝Arxiv](https://arxiv.org/abs/2003.07010)*
+ **Network disruption: maximizing disagreement and polarization in social networks**, *[📝Arxiv](https://arxiv.org/abs/2003.08377)*, *[:octocat:Code](https://github.com/mayee107/network-disruption)*
+ **Adversarial attack on BC classification for scale-free networks**, *[📝AIP Chaos](https://aip.scitation.org/doi/10.1063/5.0003707)*

## 2019
[💨 Back to Top](#table-of-contents)

+ **Time-aware Gradient Attack on Dynamic Network Link Prediction**, *[📝Arxiv](https://arxiv.org/abs/1911.10561)*
+ **Attacking Graph Convolutional Networks via Rewiring**, *[📝Arxiv](https://arxiv.org/abs/1906.03750)*
+ **Unsupervised Euclidean Distance Attack on Network Embedding**, *[📝Arxiv](https://arxiv.org/abs/1905.11015)*
+ **Structured Adversarial Attack Towards General Implementation and Better Interpretability**, *[📝ICLR](https://arxiv.org/abs/1808.01664)*, *[:octocat:Code](https://github.com/KaidiXu/StrAttack)*
+ **Generalizable Adversarial Attacks with Latent Variable Perturbation Modelling**, *[📝Arxiv](https://arxiv.org/abs/1905.10864)*
+ **Vertex Nomination, Consistent Estimation, and Adversarial Modification**, *[📝Arxiv](https://arxiv.org/abs/1905.01776)*
+ **PeerNets Exploiting Peer Wisdom Against Adversarial Attacks**, *[📝ICLR](https://arxiv.org/abs/1806.00088)*, *[:octocat:Code](https://github.com/tantara/PeerNets-pytorch)*
+ **Network Structural Vulnerability A Multi-Objective Attacker Perspective**, *[📝IEEE Trans](https://ieeexplore.ieee.org/document/8275029)*
+ **Multiscale Evolutionary Perturbation Attack on Community Detection**, *[📝Arxiv](https://arxiv.org/abs/1910.09741)*
+ **αCyber: Enhancing Robustness of Android Malware Detection System against Adversarial Attacks on Heterogeneous Graph based Model**, *[📝CIKM](https://dl.acm.org/doi/10.1145/3357384.3357875)*
+ **Adversarial Attacks on Node Embeddings via Graph Poisoning**, *[📝ICML](https://arxiv.org/abs/1809.01093)*, *[:octocat:Code](https://github.com/abojchevski/node_embedding_attack)*
+ **GA Based Q-Attack on Community Detection**, *[📝TCSS](https://arxiv.org/abs/1811.00430)*
+ **Data Poisoning Attack against Knowledge Graph Embedding**, *[📝IJCAI](https://arxiv.org/abs/1904.12052)*
+ **Adversarial Attacks on Graph Neural Networks via Meta Learning**, *[📝ICLR](https://arxiv.org/abs/1902.08412)*, *[:octocat:Code](https://github.com/danielzuegner/gnn-meta-attack)*
+ **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective**, *[📝IJCAI](https://arxiv.org/abs/1906.04214)*, *[:octocat:Code](https://github.com/KaidiXu/GCN_ADV_Train)*
+ **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense**, *[📝IJCAI](https://arxiv.org/abs/1903.01610)*, *[:octocat:Code](https://github.com/stellargraph/stellargraph/tree/develop/demos/interpretability)*
+ **A Unified Framework for Data Poisoning Attack to Graph-based Semi-supervised Learning**, *[📝NeurIPS](https://arxiv.org/abs/1910.14147)*, *[:octocat:Code](https://github.com/xuanqing94/AdvSSL)*
+ **Attacking Graph-based Classification via Manipulating the Graph Structure**, *[📝CCS](https://arxiv.org/abs/1903.00553)*

## 2018
[💨 Back to Top](#table-of-contents)

+ **Fake Node Attacks on Graph Convolutional Networks**, *[📝Arxiv](https://arxiv.org/abs/1810.10751)*
+ **Data Poisoning Attack against Unsupervised Node Embedding Methods**, *[📝Arxiv](https://arxiv.org/abs/1810.12881)*
+ **Fast Gradient Attack on Network Embedding**, *[📝Arxiv](https://arxiv.org/abs/1809.02797)*
+ **Attack Tolerance of Link Prediction Algorithms: How to Hide Your Relations in a Social Network**, *[📝Arxiv](https://arxiv.org/abs/1809.00152)*
+ **Adversarial Attacks on Neural Networks for Graph Data**, *[📝KDD](https://arxiv.org/abs/1805.07984)*, *[:octocat:Code](https://github.com/danielzuegner/nettack)*
+ **Hiding Individuals and Communities in a Social Network**, *[📝Nature Human Behavior](https://arxiv.org/abs/1608.00375)*
+ **Attacking Similarity-Based Link Prediction in Social Networks**, *[📝AAMAS](https://arxiv.org/abs/1809.08368)*
+ **Adversarial Attack on Graph Structured Data**, *[📝ICML](https://arxiv.org/abs/1806.02371)*, *[:octocat:Code](https://github.com/Hanjun-Dai/graph_adversarial_attack)*

## 2017
[💨 Back to Top](#table-of-contents)

+ **Practical Attacks Against Graph-based Clustering**, *[📝CCS](https://arxiv.org/abs/1708.09056)*
+ **Adversarial Sets for Regularising Neural Link Predictors**, *[📝UAI](https://arxiv.org/abs/1707.07596)*, *[:octocat:Code](https://github.com/uclmr/inferbeddings)*



# 🛡Defense

## 2021
[💨 Back to Top](#table-of-contents)

+ **Learning to Drop: Robust Graph Neural Network via Topological Denoising**, *[📝WSDM](https://arxiv.org/abs/2011.07057)*, *[:octocat:Code](https://github.com/flyingdoog/PTDNet)*
+ **How effective are Graph Neural Networks in Fraud Detection for Network Data?**, *[📝Arxiv](https://arxiv.org/abs/2105.14568)*
+ **Graph Sanitation with Application to Node Classification**, *[📝Arxiv](https://arxiv.org/abs/2105.09384)*
+ **Understanding Structural Vulnerability in Graph Convolutional Networks**, *[📝IJCAI](https://arxiv.org/abs/2108.06280)*, *[:octocat:Code](https://github.com/EdisonLeeeee/MedianGCN)*
+ **A Robust and Generalized Framework for Adversarial Graph Embedding**, *[📝Arxiv](https://arxiv.org/abs/2105.10651)*, *[:octocat:Code](https://github.com/RingBDStack/AGE)*
+ **Integrated Defense for Resilient Graph Matching**, *[📝ICML](http://proceedings.mlr.press/v139/ren21c/ren21c.pdf)*
+ **Unveiling Anomalous Nodes Via Random Sampling and Consensus on Graphs**, *[📝ICASSP](https://ieeexplore.ieee.org/abstract/document/9414953)*
+ **Robust Network Alignment via Attack Signal Scaling and Adversarial Perturbation Elimination**, *[📝WWW](http://eng.auburn.edu/users/yangzhou/papers/RNA.pdf)*
+ **Adversarial Graph Augmentation to Improve Graph Contrastive Learning**, *[📝Arxiv](https://arxiv.org/abs/2106.05819)*
+ **Information Obfuscation of Graph Neural Network**, *[📝ICML](https://arxiv.org/pdf/2009.13504.pdf)*, *[:octocat:Code](https://github.com/liaopeiyuan/GAL)*
+ **Improving Robustness of Graph Neural Networks with Heterophily-Inspired Designs**, *[📝Arxiv](https://arxiv.org/abs/2106.07767)*
+ **On Generalization of Graph Autoencoders with Adversarial Training**, *[📝ECML](https://arxiv.org/abs/2107.02658)*
+ **DeepInsight: Interpretability Assisting Detection of Adversarial Samples on Graphs**, *[📝ECML](https://arxiv.org/abs/2106.09501)*
+ **Elastic Graph Neural Networks**, *[📝ICML](http://proceedings.mlr.press/v139/liu21k/liu21k.pdf)*, *[:octocat:Code](https://github.com/lxiaorui/ElasticGNN)*
+ **Robust Counterfactual Explanations on Graph Neural Networks**, *[📝Arxiv](https://arxiv.org/abs/2107.04086)*
+ **Node Similarity Preserving Graph Convolutional Networks**, *[📝WSDM](https://arxiv.org/abs/2011.09643)*, *[:octocat:Code](https://github.com/ChandlerBang/SimP-GCN)*
+ **Enhancing Robustness and Resilience of Multiplex Networks Against Node-Community Cascading Failures**, *[📝IEEE TSMC](https://ieeexplore.ieee.org/abstract/document/9415463)*
+ **NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data**, *[📝TKDE](https://arxiv.org/abs/2106.11865)*, *[:octocat:Code](https://github.com/ICHproject/NetFense)*
+ **Robust Graph Learning Under Wasserstein Uncertainty**, *[📝Arxiv](https://arxiv.org/abs/2105.04210)*
+ **Towards Robust Graph Contrastive Learning**, *[📝Arxiv](https://arxiv.org/abs/2102.13085)*
+ **Expressive 1-Lipschitz Neural Networks for Robust Multiple Graph Learning against Adversarial Attacks**, *[📝ICML](http://proceedings.mlr.press/v139/zhao21e.html)*
+ **UAG: Uncertainty-Aware Attention Graph Neural Network for Defending Adversarial Attacks**, *[📝AAAI](https://arxiv.org/abs/2009.10235)*
+ **Uncertainty-Matching Graph Neural Networks to Defend Against Poisoning Attacks**, *[📝AAAI](https://arxiv.org/abs/2009.14455)*
+ **Power up! Robust Graph Convolutional Network against Evasion Attacks based on Graph Powering**, *[📝AAAI](https://arxiv.org/abs/1905.10029)*, *[:octocat:Code](https://www.dropbox.com/sh/p36pzx1ock2iamo/AABEr7FtM5nqwC4i9nICLIsta?dl=0)*
+ **Personalized privacy protection in social networks through adversarial modeling**, *[📝AAAI](https://www.cs.uic.edu/~elena/pubs/biradar-ppai21.pdf)*
+ **Interpretable Stability Bounds for Spectral Graph Filters**, *[📝Arxiv](https://arxiv.org/abs/2102.09587)*
+ **Randomized Generation of Adversary-Aware Fake Knowledge Graphs to Combat Intellectual Property Theft**, *[📝AAAI](http://34.94.61.102/paper_AAAI-9475.html)*
+ **Unified Robust Training for Graph NeuralNetworks against Label Noise**, *[📝Arxiv](https://arxiv.org/abs/2103.03414)*
+ **An Introduction to Robust Graph Convolutional Networks**, *[📝Arxiv](https://arxiv.org/abs/2103.14807)*
+ **E-GraphSAGE: A Graph Neural Network based Intrusion Detection System**, *[📝Arxiv](https://arxiv.org/abs/2103.16329)*
+ **Spatio-Temporal Sparsification for General Robust Graph Convolution Networks**, *[📝Arxiv](https://arxiv.org/abs/2103.12256)*
+ **Robust graph convolutional networks with directional graph adversarial training**, *[📝Applied Intelligence](https://link.springer.com/article/10.1007/s10489-021-02272-y)*
+ **Detection and Defense of Topological Adversarial Attacks on Graphs**, *[📝AISTATS](http://proceedings.mlr.press/v130/zhang21i.html)*
+ **Unveiling the potential of Graph Neural Networks for robust Intrusion Detection**, *[📝Arxiv](https://arxiv.org/abs/2107.14747)*, *[:octocat:Code](https://github.com/BNN-UPC/GNN-NIDS)*
+ **Adversarial Robustness of Probabilistic Network Embedding for Link Prediction**, *[📝Arxiv](https://arxiv.org/abs/2107.01936)*

## 2020
[💨 Back to Top](#table-of-contents)

+ **Ricci-GNN: Defending Against Structural Attacks Through a Geometric Approach**, *[📝ICLR OpenReview](https://openreview.net/forum?id=_qoQkWNEhS)*
+ **Provable Overlapping Community Detection in Weighted Graphs**, *[📝NeurIPS](https://arxiv.org/abs/2004.07150)*
+ **Variational Inference for Graph Convolutional Networks in the Absence of Graph Data and Adversarial Settings**, *[📝NeurIPS](https://arxiv.org/abs/1906.01852)*, *[:octocat:Code](https://github.com/ebonilla/VGCN)*
+ **Graph Random Neural Networks for Semi-Supervised Learning on Graphs**, *[📝NeurIPS](https://arxiv.org/abs/2005.11079)*, *[:octocat:Code](https://github.com/Grand20/grand)*
+ **Reliable Graph Neural Networks via Robust Aggregation**, *[📝NeurIPS](https://arxiv.org/abs/2010.15651)*, *[:octocat:Code](https://github.com/sigeisler/reliable_gnn_via_robust_aggregation)*
+ **Towards Robust Graph Neural Networks against Label Noise**, *[📝ICLR OpenReview](https://openreview.net/forum?id=H38f_9b90BO)*
+ **Graph Adversarial Networks: Protecting Information against Adversarial Attacks**, *[📝ICLR OpenReview](https://openreview.net/forum?id=Q8ZdJahesWe)*, *[:octocat:Code](https://github.com/liaopeiyuan/GAL)*
+ **A Novel Defending Scheme for Graph-Based Classification Against Graph Structure Manipulating Attack**, *[📝SocialSec](https://link.springer.com/chapter/10.1007/978-981-15-9031-3_26)*
+ **Iterative Deep Graph Learning for Graph Neural Networks: Better and Robust Node Embeddings**, *[📝NeurIPS](https://arxiv.org/abs/2006.13009)*, *[:octocat:Code](https://github.com/hugochan/IDGL)*
+ **Node Copying for Protection Against Graph Neural Network Topology Attacks**, *[📝Arxiv](https://arxiv.org/abs/2007.06704)*
+ **Community detection in sparse time-evolving graphs with a dynamical Bethe-Hessian**, *[📝NeurIPS](https://arxiv.org/abs/2006.04510)*
+ **Unsupervised Adversarially-Robust Representation Learning on Graphs**, *[📝Arxiv](https://arxiv.org/abs/2012.02486)*
+ **A Feature-Importance-Aware and Robust Aggregator for GCN**, *[📝CIKM](https://dl.acm.org/doi/abs/10.1145/3340531.3411983)*, *[:octocat:Code](https://github.com/LiZhang-github/LA-GCN)*
+ **Anti-perturbation of Online Social Networks by Graph Label Transition**, *[📝Arxiv](https://arxiv.org/abs/2010.14121)*
+ **Graph Information Bottleneck**, *[📝NeurIPS](https://arxiv.org/abs/2010.12811)*, *[:octocat:Code](http://snap.stanford.edu/gib/)*
+ **Adversarial Detection on Graph Structured Data**, *[📝PPMLP](https://dl.acm.org/doi/abs/10.1145/3411501.3419424)*
+ **Graph Contrastive Learning with Augmentations**, *[📝NeurIPS](https://arxiv.org/abs/2010.13902)*, *[:octocat:Code](https://github.com/Shen-Lab/GraphCL)*
+ **Learning Graph Embedding with Adversarial Training Methods**, *[📝IEEE Transactions on Cybernetics](https://arxiv.org/abs/1901.01250)*
+ **I-GCN: Robust Graph Convolutional Network via Influence Mechanism**, *[📝Arxiv](https://arxiv.org/abs/2012.06110)*
+ **Adversary for Social Good: Protecting Familial Privacy through Joint Adversarial Attacks**, *[📝AAAI](https://ojs.aaai.org//index.php/AAAI/article/view/6791)*
+ **Smoothing Adversarial Training for GNN**, *[📝IEEE TCSS](https://ieeexplore.ieee.org/abstract/document/9305289?casa_token=fTXIL3hT1yIAAAAA:I4fn-GlF0PIwzPRC87SayRi5_pi2ZDDuSancEsY96A4O4bUBEsp0hSYMNJVGVzMgBWxycYN9qu6D)*
+ **Graph Structure Reshaping Against Adversarial Attacks on Graph Neural Networks**, *[📝None](None)*, *[:octocat:Code](https://github.com/GraphReshape/GraphReshape)*
+ **RoGAT: a robust GNN combined revised GAT with adjusted graphs**, *[📝Arxiv](https://arxiv.org/abs/2009.13038)*
+ **ResGCN: Attention-based Deep Residual Modeling for Anomaly Detection on Attributed Networks**, *[📝Arxiv](https://arxiv.org/abs/2009.14738)*
+ **Adversarial Perturbations of Opinion Dynamics in Networks**, *[📝Arxiv](https://arxiv.org/abs/2003.07010)*
+ **Adversarial Privacy Preserving Graph Embedding against Inference Attack**, *[📝Arxiv](https://arxiv.org/abs/2008.13072)*, *[:octocat:Code](https://github.com/uJ62JHD/Privacy-Preserving-Social-Network-Embedding)*
+ **Robust Graph Learning From Noisy Data**, *[📝IEEE Trans](https://ieeexplore.ieee.org/abstract/document/8605364)*
+ **GNNGuard: Defending Graph Neural Networks against Adversarial Attacks**, *[📝NeurIPS](https://arxiv.org/abs/2006.08149)*, *[:octocat:Code](https://github.com/mims-harvard/GNNGuard)*
+ **Transferring Robustness for Graph Neural Network Against Poisoning Attacks**, *[📝WSDM](https://arxiv.org/abs/1908.07558)*, *[:octocat:Code](https://github.com/tangxianfeng/PA-GNN)*
+ **All You Need Is Low (Rank): Defending Against Adversarial Attacks on Graphs**, *[📝WSDM](https://dl.acm.org/doi/abs/10.1145/3336191.3371789)*, *[:octocat:Code](https://github.com/DSE-MSU/DeepRobust)*
+ **How Robust Are Graph Neural Networks to Structural Noise?**, *[📝DLGMA](https://arxiv.org/abs/1912.10206)*
+ **Robust Detection of Adaptive Spammers by Nash Reinforcement Learning**, *[📝KDD](https://arxiv.org/abs/2006.06069)*, *[:octocat:Code](https://github.com/YingtongDou/Nash-Detect)*
+ **Graph Structure Learning for Robust Graph Neural Networks**, *[📝KDD](https://arxiv.org/abs/2005.10203)*, *[:octocat:Code](https://github.com/DSE-MSU/DeepRobust)*
+ **On The Stability of Polynomial Spectral Graph Filters**, *[📝ICASSP](https://ieeexplore.ieee.org/abstract/document/9054072)*, *[:octocat:Code](https://github.com/henrykenlay/spgf)*
+ **On the Robustness of Cascade Diffusion under Node Attacks**, *[📝WWW](https://www.cs.au.dk/~karras/robustIC.pdf)*, *[:octocat:Code](https://github.com/allogn/robustness)*
+ **Friend or Faux: Graph-Based Early Detection of Fake Accounts on Social Networks**, *[📝WWW](https://arxiv.org/abs/2004.04834)*
+ **Towards an Efficient and General Framework of Robust Training for Graph Neural Networks**, *[📝ICASSP](https://arxiv.org/abs/2002.10947)*
+ **Robust Graph Representation Learning via Neural Sparsification**, *[📝ICML](https://proceedings.icml.cc/static/paper_files/icml/2020/2611-Paper.pdf)*
+ **Robust Training of Graph Convolutional Networks via Latent Perturbation**, *[📝ECML-PKDD](https://www.cs.uic.edu/~zhangx/papers/JinZha20.pdf)*
+ **Robust Collective Classification against Structural Attacks**, *[📝Preprint](http://www.auai.org/uai2020/proceedings/119_main_paper.pdf)*
+ **Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters**, *[📝CIKM](https://arxiv.org/abs/2008.08692)*, *[:octocat:Code](https://github.com/safe-graph/DGFraud)*
+ **Topological Effects on Attacks Against Vertex Classification**, *[📝Arxiv](https://arxiv.org/abs/2003.05822)*
+ **Tensor Graph Convolutional Networks for Multi-relational and Robust Learning**, *[📝Arxiv](https://arxiv.org/abs/2003.07729)*
+ **DefenseVGAE: Defending against Adversarial Attacks on Graph Data via a Variational Graph Autoencoder**, *[📝Arxiv](https://arxiv.org/abs/2006.08900)*, *[:octocat:Code](https://github.com/zhangao520/defense-vgae)*
+ **Dynamic Knowledge Graph-based Dialogue Generation with Improved Adversarial Meta-Learning**, *[📝Arxiv](https://arxiv.org/abs/2004.08833)*
+ **AANE: Anomaly Aware Network Embedding For Anomalous Link Detection**, *[📝ICDM](https://ieeexplore.ieee.org/document/9338406)*
+ **Provably Robust Node Classification via Low-Pass Message Passing**, *[📝ICDM](https://shenghua-liu.github.io/papers/icdm2020-provablerobust.pdf)*

## 2019
[💨 Back to Top](#table-of-contents)

+ **Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure**, *[📝TKDE](https://arxiv.org/abs/1902.08226)*, *[:octocat:Code](https://github.com/fulifeng/GraphAT)*
+ **Bayesian graph convolutional neural networks for semi-supervised classification**, *[📝AAAI](https://arxiv.org/abs/1811.11103)*, *[:octocat:Code](https://github.com/huawei-noah/BGCN)*
+ **Target Defense Against Link-Prediction-Based Attacks via Evolutionary Perturbations**, *[📝Arxiv](https://arxiv.org/abs/1809.05912)*
+ **Examining Adversarial Learning against Graph-based IoT Malware Detection Systems**, *[📝Arxiv](https://arxiv.org/abs/1902.04416)*
+ **Adversarial Embedding: A robust and elusive Steganography and Watermarking technique**, *[📝Arxiv](https://arxiv.org/abs/1912.01487)*
+ **Graph Interpolating Activation Improves Both Natural and Robust Accuracies in Data-Efficient Deep Learning**, *[📝Arxiv](https://arxiv.org/abs/1907.06800)*, *[:octocat:Code](https://github.com/BaoWangMath/DNN-DataDependentActivation)*
+ **Adversarial Defense Framework for Graph Neural Network**, *[📝Arxiv](https://arxiv.org/abs/1905.03679)*
+ **GraphSAC: Detecting anomalies in large-scale graphs**, *[📝Arxiv](https://arxiv.org/abs/1910.09589)*
+ **Edge Dithering for Robust Adaptive Graph Convolutional Networks**, *[📝Arxiv](https://arxiv.org/abs/1910.09590)*
+ **Can Adversarial Network Attack be Defended?**, *[📝Arxiv](https://arxiv.org/abs/1903.05994)*
+ **GraphDefense: Towards Robust Graph Convolutional Networks**, *[📝Arxiv](https://arxiv.org/abs/1911.04429)*
+ **Adversarial Training Methods for Network Embedding**, *[📝WWW](https://arxiv.org/abs/1908.11514)*, *[:octocat:Code](https://github.com/wonniu/AdvT4NE_WWW2019)*
+ **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense**, *[📝IJCAI](https://arxiv.org/abs/1903.01610)*, *[:octocat:Code](https://github.com/DSE-MSU/DeepRobust)*
+ **Improving Robustness to Attacks Against Vertex Classification**, *[📝MLG@KDD](http://eliassi.org/papers/benmiller-mlg2019.pdf)*
+ **Adversarial Robustness of Similarity-Based Link Prediction**, *[📝ICDM](https://arxiv.org/abs/1909.01432)*
+ **αCyber: Enhancing Robustness of Android Malware Detection System against Adversarial Attacks on Heterogeneous Graph based Model**, *[📝CIKM](https://dl.acm.org/doi/10.1145/3357384.3357875)*
+ **Batch Virtual Adversarial Training for Graph Convolutional Networks**, *[📝ICML](https://arxiv.org/abs/1902.09192)*, *[:octocat:Code](https://github.com/thudzj/BVAT)*
+ **Latent Adversarial Training of Graph Convolution Networks**, *[📝LRGSD@ICML](https://graphreason.github.io/papers/35.pdf)*, *[:octocat:Code](https://github.com/cshjin/LATGCN)*
+ **Characterizing Malicious Edges targeting on Graph Neural Networks**, *[📝ICLR OpenReview](https://arxiv.org/abs/1906.04214)*, *[:octocat:Code](https://github.com/KaidiXu/GCN_ADV_Train)*
+ **Comparing and Detecting Adversarial Attacks for Graph Deep Learning**, *[📝RLGM@ICLR](https://rlgm.github.io/papers/57.pdf)*
+ **Virtual Adversarial Training on Graph Convolutional Networks in Node Classification**, *[📝PRCV](https://arxiv.org/abs/1902.11045)*
+ **Robust Graph Convolutional Networks Against Adversarial Attacks**, *[📝KDD](http://pengcui.thumedialab.com/papers/RGCN.pdf)*, *[:octocat:Code](https://github.com/thumanlab/nrlweb/blob/master/static/assets/download/RGCN.zip)*
+ **Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications**, *[📝NAACL](https://arxiv.org/abs/1905.00563)*, *[:octocat:Code](https://github.com/pouyapez/criage)*
+ **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective**, *[📝IJCAI](https://arxiv.org/abs/1906.04214)*, *[:octocat:Code](https://github.com/KaidiXu/GCN_ADV_Train)*

## 2018
[💨 Back to Top](#table-of-contents)

+ **Adversarial Personalized Ranking for Recommendation**, *[📝SIGIR](https://dl.acm.org/citation.cfm?id=3209981)*, *[:octocat:Code](https://github.com/hexiangnan/adversarial_personalized_ranking)*

## 2017
[💨 Back to Top](#table-of-contents)

+ **Adversarial Sets for Regularising Neural Link Predictors**, *[📝UAI](https://arxiv.org/abs/1707.07596)*, *[:octocat:Code](https://github.com/uclmr/inferbeddings)*



# 🔐Certification
[💨 Back to Top](#table-of-contents)

+ **Certified Robustness of Graph Neural Networks against Adversarial Structural Perturbation**, *[KDD'2021](https://dl.acm.org/doi/abs/10.1145/3447548.3467295)*, *[:octocat:Code](https://github.com/binghuiwang/CertifyGNN)*
+ **Collective Robustness Certificates**, *[📝ICLR'2021](https://openreview.net/forum?id=ULQdiUTHe3y)*
+ **Adversarial Immunization for Improving Certifiable Robustness on Graphs**, *[📝WSDM'2021](https://arxiv.org/abs/2007.09647)*
+ **Certifying Robustness of Graph Laplacian Based Semi-Supervised Learning**, *[📝ICLR OpenReview'2021](https://openreview.net/forum?id=cQyybLUoXxc)*
+ **Robust Certification for Laplace Learning on Geometric Graphs**, *[📝MSML’2021](https://arxiv.org/abs/2104.10837)*
+ **Improving the Robustness of Wasserstein Embedding by Adversarial PAC-Bayesian Learning**, *[📝AAAI'2020](http://staff.ustc.edu.cn/~hexn/papers/aaai20-adversarial-embedding.pdf)*
+ **Certified Robustness of Graph Convolution Networks for Graph Classification under Topological Attacks**, *[📝NeurIPS'2020](https://www.cs.uic.edu/~zhangx/papers/Jinetal20.pdf)*, *[:octocat:Code](https://github.com/RobustGraph/RoboGraph)*
+ **Certified Robustness of Community Detection against Adversarial Structural Perturbation via Randomized Smoothing**, *[📝WWW'2020](https://arxiv.org/abs/2002.03421)*
+ **Efficient Robustness Certificates for Discrete Data: Sparsity - Aware Randomized Smoothing for Graphs, Images and More**, *[📝ICML'2020](https://proceedings.icml.cc/book/2020/file/4f7b884f2445ef08da9bbc77b028722c-Paper.pdf)*, *[:octocat:Code](https://github.com/abojchevski/sparse_smoothing)*
+ **Abstract Interpretation based Robustness Certification for Graph Convolutional Networks**, *[📝ECAI'2020](http://ecai2020.eu/papers/31_paper.pdf)*
+ **Certifiable Robustness of Graph Convolutional Networks under Structure Perturbation**, *[📝KDD'2020](https://dl.acm.org/doi/10.1145/3394486.3403217)*, *[:octocat:Code](https://github.com/danielzuegner/robust-gcn-structure)*
+ **Certified Robustness of Graph Classification against Topology Attack with Randomized Smoothing**, *[📝NeurIPS'2020](https://arxiv.org/abs/2009.05872)*
+ **Certifiable Robustness and Robust Training for Graph Convolutional Networks**, *[📝KDD'2019](https://arxiv.org/abs/1906.12269)*, *[:octocat:Code](https://www.kdd.in.tum.de/research/robust-gcn/)*
+ **Certifiable Robustness to Graph Perturbations**, *[📝NeurIPS'2019](http://papers.nips.cc/paper/9041-certifiable-robustness-to-graph-perturbations)*, *[:octocat:Code](https://github.com/abojchevski/graph_cert)*



# ⚖Stability
[💨 Back to Top](#table-of-contents)

+ **Shift-Robust GNNs: Overcoming the Limitations of Localized Graph Training data**, *[📝Arxiv'2021](https://www.ijcai.org/Proceedings/2020/181)*
+ **Stability of Graph Convolutional Neural Networks to Stochastic Perturbations**, *[📝Arxiv'2021](https://arxiv.org/abs/2106.10526)*
+ **Graph and Graphon Neural Network Stability**, *[📝Arxiv'2020](https://arxiv.org/abs/2008.01767)*
+ **On the Stability of Graph Convolutional Neural Networks under Edge Rewiring**, *[📝Arxiv'2020](https://arxiv.org/abs/2010.13747)*
+ **Stability of Graph Neural Networks to Relative Perturbations**, *[📝ICASSP'2020](https://ieeexplore.ieee.org/document/9054341)*
+ **Graph Neural Networks: Architectures, Stability and Transferability**, *[📝Arxiv'2020](https://arxiv.org/abs/2008.01767)*
+ **Should Graph Convolution Trust Neighbors? A Simple Causal Inference Method**, *[📝Arxiv'2020](https://arxiv.org/abs/2010.11797)*
+ **Stability Properties of Graph Neural Networks**, *[📝Arxiv'2019](https://arxiv.org/abs/1905.04497)*
+ **Stability and Generalization of Graph Convolutional Neural Networks**, *[📝KDD'2019](https://arxiv.org/abs/1905.01004)*, *[:octocat:Code](https://github.com/raspberryice/ala-gcn)*
+ **When Do GNNs Work: Understanding and Improving Neighborhood Aggregation**, *[📝IJCAI Workshop'2019](https://www.ijcai.org/Proceedings/2020/181)*, *[:octocat:Code](https://github.com/raspberryice/ala-gcn)*



# 🚀Others
[💨 Back to Top](#table-of-contents)

+ **Perturbation Sensitivity of GNNs**, *[📝cs224w'2019](http://snap.stanford.edu/class/cs224w-2019/project/26424139.pdf)*
+ **Generating Adversarial Examples with Graph Neural Networks**, *[📝UAI'2021](https://arxiv.org/abs/2105.14644)*
+ **SIGL: Securing Software Installations Through Deep Graph Learning**, *[📝USENIX'2021](https://www.usenix.org/system/files/sec21summer_han-xueyuan.pdf)*
+ **FLAG: Adversarial Data Augmentation for Graph Neural Networks**, *[📝Arxiv'2020](https://arxiv.org/abs/2010.09891)*, *[:octocat:Code](https://github.com/devnkong/FLAG)*
+ **Dynamic Knowledge Graph-based Dialogue Generation with Improved Adversarial Meta-Learning**, *[📝Arxiv'2020](https://arxiv.org/abs/2004.08833)*
+ **Watermarking Graph Neural Networks by Random Graphs**, *[📝Arxiv'2020](https://arxiv.org/abs/2011.00512)*



# 📃Survey
[💨 Back to Top](#table-of-contents)
+ **Adversarial Attacks and Defenses on Graphs: A Review, A Tool and Empirical Studies**, *[📝SIGKDD Explorations'2021](https://arxiv.org/abs/2003.00653)*
+ **Deep Graph Structure Learning for Robust Representations: A Survey**, *[📝IJCAI Survey track'2021](https://arxiv.org/abs/2103.03036)*
+ **Graph Neural Networks Taxonomy, Advances and Trends**, *[📝Arxiv'2020](https://arxiv.org/abs/2012.08752)*
+ **A Survey of Adversarial Learning on Graph**, *[📝Arxiv'2020](https://arxiv.org/abs/2003.05730)*
+ **Adversarial Attacks and Defenses on Graphs: A Review and Empirical Study**, *[📝Arxiv'2020](https://arxiv.org/abs/2003.00653)*
+ **Adversarial Attacks and Defenses in Images, Graphs and Text: A Review**, *[📝Arxiv'2019](https://arxiv.org/abs/1909.08072)*
+ **Adversarial Attack and Defense on Graph Data: A Survey**, *[📝Arxiv'2018](https://arxiv.org/abs/1812.10528)*
+ **Deep Learning on Graphs A Survey**, *[📝Arxiv'2018](https://arxiv.org/abs/1812.04202)*





# ⚙Toolbox
[💨 Back to Top](#table-of-contents)

+ **DeepRobust: a Platform for Adversarial Attacks and Defenses**, *[📝AAAI’2021](https://ojs.aaai.org/index.php/AAAI/article/view/18017)*, [**:octocat:DeepRobust**](https://github.com/DSE-MSU/DeepRobust)
+ **GraphGallery: A Platform for Fast Benchmarking and Easy Development of Graph Neural Networks Based Intelligent Software**, *[📝ICSE Demo‘2021](https://ieeexplore.ieee.org/abstract/document/9402641)*, [**:octocat:GraphGallery**](https://github.com/EdisonLeeeee/GraphGallery)
+ **Evaluating Graph Vulnerability and Robustness using TIGER**, *[📝Arxiv‘2021](https://arxiv.org/abs/2006.05648)*, [**:octocat:TIGER**](https://github.com/safreita1/TIGER)
+ **Graph Robustness Benchmark: Rethinking and Benchmarking Adversarial Robustness of Graph Neural Networks**, *[📝NeurIPS Openreview ’2021](https://openreview.net/forum?id=pBwQ82pYha)*, [**:octocat:Graph Robustness Benchmark (GRB)**](https://github.com/thudm/grb)

  

# 🔗Resource
[💨 Back to Top](#table-of-contents)

+ **Awesome Adversarial Learning on Recommender System** [:octocat:CodeLink](https://github.com/EdisonLeeeee/RS-Adversarial-Learning)
+ **Awesome Graph Attack and Defense Papers** [:octocat:CodeLink](https://github.com/ChandlerBang/awesome-graph-attack-papers)
+ **Graph Adversarial Learning Literature** [:octocat:CodeLink](https://github.com/safe-graph/graph-adversarial-learning-literature)
+ **A Complete List of All (arXiv) Adversarial Example Papers** [🌐Link](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)
+ **Adversarial Attacks and Defenses Frontiers, Advances and Practice**, *KDD'20 tutorial*, [🌐Link](https://sites.google.com/view/kdd-2020-attack-and-defense)




# Awesome-Graph-Neural-Networks-for-Brain-Graph-Learning

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs) 
![GitHub stars](https://img.shields.io/github/stars/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs?color=yellow&label=Stars)
![GitHub forks](https://img.shields.io/github/forks/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs?color=blue&label=Forks) 
![](https://visitor-badge.glitch.me/badge?page_id=littleTreeme)

:fire::fire: This is a collection of awesome papers about graph neural networks for brain graph learning, datasets and tools.

## Contents
- [Surveys](#surveys)
- [Prediction-Based Static Brain Graph Learning](#Prediction-Based-Static-Brain-Graph-Learning)
- [Interpretation-Based Static Brain Graph Learning](#Interpretation-Based-Static-Brain-Graph-Learning)
- [Prediction-Based Dynamic Brain Graph Learning](#Prediction-Based-Dynamic-Brain-Graph-Learning)
- [Interpretation-Based Dynamic Brain Graph Learning](#Interpretation-Based-Dynamic-Brain-Graph-Learning)
- [Prediction-Based Multi-Modal Brain Graph Learning](#Prediction-Based-Multi-Modal-Brain-Graph-Learning)
- [Interpretation-Based Multi-Modal Brain Graph Learning](#Interpretation-Based-Multi-Modal-Brain-Graph-Learning)
- [Brain Neuroimaging Datasets](#Brain-Neuroimaging-Datasets)
- [Brain Graph Analysis Tools](#Brain-Graph-Analysis-Tools)


----------
## The framework of brain graph learning based on GNNs
![framework](figures/framework.png)

## Surveys

| **Paper Title** | **Venue** | **Year** | **Code** |
| ----------------- | --- | -- | -- |
| [Benchmarking Graph Neural Networks for FMRI analysis](https://arxiv.org/pdf/2211.08927.pdf) | _Arxiv_ | 2022 |[[Code]](https://github.com/elgazzarr/fMRI-GNNs) |
| [Graph neural networks for image‐guided disease diagnosis: A review](https://onlinelibrary.wiley.com/doi/pdfdirect/10.1002/ird3.20) | _iRADIOLOGY_ | 2023 |-|
| [NeuroGraph: Benchmarks for Graph Machine Learning in Brain Connectomics](https://arxiv.org/pdf/2306.06202.pdf) | _Arxiv_ | 2023 | [[Code]](https://anwar-said.github.io/anwarsaid/neurograph.html) |
| [GNN4EEG: A Benchmark and Toolkit for Electroencephalography Classification with Graph Neural Network](https://arxiv.org/pdf/2309.15515.pdf) | _Arxiv_ | 2023 | [[Code]](https://github.com/Miracle-2001/GNN4EEG)|
| [A Survey of EEG Analysis based on Graph Neural Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9742089) |_CECIT Conference_ | 2021 |-|
| [BrainGB: A Benchmark for Brain Network Analysis With Graph Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9933896) |_IEEE TMI_ | 2022 |[[Code]](https://github.com/HennyJie/BrainGB)|
| [Graph Neural Networks and Their Current Applications in Bioinformatics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8360394/) |_Frontiers in genetics_ | 2021 |-|
| [Graph Neural Networks in Network Neuroscience](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9903566) |_IEEE TPAMI_ | 2022 |-|

----------
## The toy example of different types of brain graph generated
![brain](figures/brain%20graph.png)

----------

## Prediction-Based Static Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 | DGAIB | - |
| [TRANSFORMER-BASED HIERARCHICAL CLUSTERING FOR BRAIN NETWORK ANALYSIS](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10230606&casa_token=OKhpWBQq180AAAAA:qixJ2W7ilRW7kfCdECM1uMEv78cJ73HDKJypuyWn5TnaKY0BkczOpwZ6nk5umdfeVZtyCQ&tag=1) | _ISBI_ | 2023 | THC | - |
| [Graph Neural Network based Alzheimer’s Disease Classification using Structural Brain Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10024076&casa_token=hIyHTDMW_2kAAAAA:ihzZ0qw-rCeoRDa6qjOEHbBd8o9ocfkEJ4UNlUUJWvFtW_1bAxFeBp9O5csOQdzNJhfxJA) | _ICTer_ | 2022 |  | - |[[Code]](https://github.com/Subaramva/GNN)|
| [GRAPH CONVOLUTIONAL NEURAL NETWORKS FOR ALZHEIMER’S DISEASE CLASSIFICATION](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8759531&casa_token=aZolVSZ6WMAAAAAA:E8riXHrmgdKRph3D4pKElqlFU0HWi1NV3pNLXevkYjtfKXSQiIX9-3GPOwu_Js3hGulWMg) | _ISBI_ | 2019 | GCNN |- |
| [TSEN: TRANSFORMER AND SNOWBALL GRAPH CONVOLUTION LEARNING FOR BRAIN FUNCTIONAL NETWORK CLASSIFICATION](https://arxiv.org/pdf/2303.16132.pdf) | _Arxiv_ | 2023 | TSEN | [[Code]](https://github.com/largeapp/TSEN) |
| [GNEA: A Graph Neural Network with ELM Aggregator for Brain Network Classification](https://www.hindawi.com/journals/complexity/2020/8813738/) | _Complexity Journal_ | 2020 | GNEA | - |
| [Hi-GCN: A hierarchical graph convolution network for graph embedding learning of brain network and brain disorders prediction]( https://www.sciencedirect.com/science/article/pii/S0010482520304273?casa_token=zTi-i1OA8R4AAAAA:GgqPf28cPE-sAAuxvaqpcEl-kIY84r7hUWyKGvD61KN8QAzpRqzo3don4iXIGKdhX4FljQ) | _Comput. Biol. Med._ | 2020 | Hi-GCN | [[Code]](https://github.com/haojiang1/hi-GCN) |
| [A Graph Attention Neural Network for Diagnosing ASD with fMRI Data](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9669849&casa_token=MTyuvlZTI3QAAAAA:exXxjVImpiT7KFE2gS_F00YxSkVSVvzVLoICM9SoEctDdDNblIQ53pedt2hxWLsHl93mIg ) | _BIBM_ | 2021 | - |- |
| [BrainMixup: Data Augmentation for GNN-based Functional Brain Network Analysis ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10020662&casa_token=4qOSUY3BVcQAAAAA:rygG3mzSWMsnFiNyyBYfaKUYZtRi15plVy6l1hYie2e5fLC6cJSo3C02SimfJhjUGmScJA) | _Big Data_ | 2022 | - | - |
| [ BRAIN NETWORK TRANSFORMER]( https://proceedings.neurips.cc/paper_files/paper/2022/file/a408234a9b80604a9cf6ca518e474550-Paper-Conference.pdf) | _NeurIPS_ | 2022 | BRAINNETTF | [[Code]](https://github.com/Wayfear/BrainNetworkTransformer) |
| [BrainVGAE: End-to-End Graph Neural Networks for Noisy fMRI Dataset](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9994963&casa_token=V00-89HzU_MAAAAA:2uBPUSubvtWPfBe-TtJAqooaqpIeHuMpVh6qspyWV_Pk0F14D0ZXnsjkhqYY3R2XpOIaNw) | _BIBM_ | 2022 | - | - |
| [Classification of First-Episode Schizophrenia, Chronic Schizophrenia and Healthy Control Based on Brain Network of Mismatch Negativity by Graph Neural Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9515994) | _TNSRE_ | 2021 | - | - |
| [ Deep reinforcement learning guided graph neural networks for brain network analysis](https://www.sciencedirect.com/science/article/pii/S0893608022002507?casa_token=KFewXixEefMAAAAA:fGzD8g8xtjcCFB0Bux2KO2j0yTuBXe98vpH98pZRg9IZo3yKCrhrx5USv9ATd9GtpfpIxg) | _Neural Networks_ | 2022 | BN-GNN |[[Code]](https://github.com/RingBDStack/BNGNN) |
| [EEG-GNN: Graph Neural Networks for Classification of Electroencephalogram (EEG) Signals](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9630194&casa_token=LKFHAvrzSRMAAAAA:a8LKc73XLvB4JN8LK9H6eMlC8wZWae14zEkY_HHBzevZ2W_uM5amllUFPA4JCpiW0mrZMw) | _EMBC_ | 2021 | - | - |
| [PTGB: Pre-Train Graph Neural Networks for Brain Network Analysis ](https://arxiv.org/pdf/2305.14376.pdf) | _CHIL_ | 2022 | PTGB | [[Code]](https://github.com/Owen-Yang-18/BrainNN-PreTrain)  |
| [ Data-Efficient Brain Connectome Analysis via Multi-Task Meta-Learning](https://dl.acm.org/doi/pdf/10.1145/3534678.3542680) | _KDD_ | 2022 | MML | [[Code]](https://github.com/Owen-Yang-18/BrainNN-PreTrain)  |
| [Population Graph GNNs for Brain Age Prediction](https://grlplus.github.io/papers/71.pdf) | _ICML Workshop_ | 2020 | - | [[Code]](https://github.com/kamilest/brain-age-gnn) |

----------

## Interpretation-Based Static Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [ TOWARDS A MORE STABLE AND GENERAL SUBGRAPH INFORMATION BOTTLENECK ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10094812&casa_token=TjG3cECWwHkAAAAA:hJ6tVO7iElBE8T_losRO_ukwfPUBV1awuh9gOFHMkbEJBvdN8uqQpnp3OrB5xQ1ctFZE-g&tag=1) | _ICASSP_ | 2023 | - |  [[Code]](https://github.com/SJYuCNEL/brain-and-Information-Bottleneck)  |
| [ Deep dag learning of effective brain connectivity for fmri analysis]( https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10230429&casa_token=yuNv3Z-dOxcAAAAA:53qn0dKk2bmkw8QgTj76G7j1SHrJVl5Ib0J3al_au8U7bkMLZVfoThNys01XeH2zKPsJCQ) | _ISBI_ | 2023 | DABNet | - |
| [GAT LI: a graph attention network based learning and interpreting method for functional brain network classification](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04295-1) | _BMC Bioinformatics_ | 2021 | GAT-LI | - |
| [Pooling Regularized Graph Neural Network for fMRI Biomarker Analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7544244/) | _MICCAI_ | 2020 | PR-GNN |- |
| [Investigating Brain Connectivity with Graph Neural Networks and GNNExplainer ]( https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9956201&casa_token=4nHCXv_yCzAAAAAA:E8O4xFI4cEp0XRRW0eB9zLDzZ-sAXCrXh15gN-a9ZmxumEwVCxhP4UZkbRMZeJ990pmSkg) | _ICPR_ | 2022 | - | - |
| [Interpretable Graph Neural Networks for Connectome-Based Brain Disorder Analysis]( https://arxiv.org/pdf/2207.00813.pdf) | _MICCAI_ | 2022 | IBGNN | [[Code]](https://github.com/HennyJie/IBGNN.git) |
| [ Adaptive Gated Graph Convolutional Network for Explainable Diagnosis of Alzheimer’s Disease using EEG Data](https://arxiv.org/pdf/2304.05874.pdf) | _Arxiv_ | 2023 | AGGCN | - |
| [Interpretable Sparsification of Brain Graphs: Better Practices and Effective Designs for Graph Neural Networks](https://arxiv.org/pdf/2306.14375.pdf) | _KDD_ | 2023 |  IGS |[[Code]](https://github.com/motivationss/IGS) |
| [Contrastive Graph Pooling for Explainable Classification of Brain Networks]( https://arxiv.org/pdf/2307.11133.pdf) | _Arxiv_ | 2023 | ContrastPool | - |
| [Brain Networks and Intelligence: A Graph Neural Network Based Approach to Resting State fMRI Data](https://arxiv.org/pdf/2311.03520.pdf ) | _Arxiv_ | 2023 | BrainRGIN | [[Code]](https://github.com/bishalth01/Brain-ROI-Aware-Graph-Isomorphism-NetworksBrainRGIN-)   |
| [ Classification of Brain Disorders in rs-fMRI via Local-to-Global Graph Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9936686&casa_token=08WIe6MyOYAAAAAA:KJD6n3VVd3Vs05A0fKPtElfGWRTz93VW_96KIQ-UF-fDx8CniPvxu2yqorLH18mr5uL9fA) | _TMI_ | 2023 | LG-GNN | [[Code]](https://github.com/cnuzh/LG-GNN)  |
| [Dementia analysis from functional connectivity network with graph neural networks]( https://www.sciencedirect.com/science/article/pii/S0306457322000309?casa_token=WiLyJQu02M0AAAAA:lc32wQxTCKDbeNtzNXA5YVtEBvm4aiJjznwq8E_xDZ_x2Zs6zqXxsqRG-pnTvOqfRO4rPA) | _IPM_ | 2022 | - |- |
| [ Graph Neural Network for Interpreting Task-fMRI Biomarkers]( https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7519579/) | _MICCAI_ | 2019 | t-fMRI | - |
| [ Community-Aware Transformer for Autism Prediction in fMRI Connectome ](https://arxiv.org/pdf/2307.10181.pdf) | _MICCAI_ | 2023 | Com-BrainTF | [[Code]](https://github.com/ubc-tea/Com-BrainTF.) |
| [FC–HAT: Hypergraph attention network for functional brain network classification](https://www.sciencedirect.com/science/article/pii/S0020025522007307?casa_token=stTW8Oy-au4AAAAA:0XJtoDfU1_mvPHLhXBkmTT114ihccpUiT7i5L6G1PsJNKnk_vxNpa95WvqqjDGZSjwCxUw) | _Information Sciences_ | 2022 |  FC–HAT | [[Code]](https://github.com/uuup123/FC–HAT)  |
| [ BrainGNN: Interpretable Brain Graph Neural Network for fMRI Analysis]( https://www.sciencedirect.com/science/article/pii/S1361841521002784?casa_token=tesOeiHg9n4AAAAA:4_A6aBwjG0FOY_Rfu7cenN4RZSFtfAr50gxdcxRnO2tsjKa1JaAjOdqKPztSlXIu7IITMw) | _Med. Image Anal._ | 2021 | BrainGNN | [[Code]](https://github.com/xxlya/BrainGNN_Pytorch)   |
| [BrainIB: Interpretable Brain Network-based Psychiatric Diagnosis with Graph Information Bottleneck](https://arxiv.org/pdf/2205.03612.pdf) | _Arxiv_ | 2023 | BrainIB | - |
| [FBNetGen: Task-aware GNN-based fMRI Analysis via Functional Brain Network Generation](https://proceedings.mlr.press/v172/kan22a/kan22a.pdf) | _MIDL_ | 2022 | FBNetGen | [[Code]]( https://github.com/Wayfear/FBNETGEN.) |
| [ BRAINNPT: PRE-TRAINING TRANSFORMER NETWORKS FOR BRAIN FUNCTIONAL NETWORK CLASSIFICATION](https://arxiv.org/pdf/2305.01666.pdf) | _Arxiv_ | 2023 |  BrainNPT | -|

----------

## Prediction-Based Dynamic Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [Multi-Scale Dynamic Graph Learning for Brain Disorder Detection With Functional MRI](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10233901) | _IEEE TNSRE_ | 2023 | MDGL | - |
| [Modeling spatio-temporal patterns of holistic functional brain networks via multi-head guided attention graph neural networks](https://www.sciencedirect.com/science/article/pii/S1361841522001657) | _Med. Image Anal._ | 2022 | Multi-Head GAGNN |  [[Code]](https://github.com/JDYan/Multi-Head-GAGNNs) |
| [Spatio-Temporal Graph Convolution for Resting-State fMRI Analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7700758/) | _MICCAI_ | 2020 | STGCN | [[Code]](https://github.com/sgadgil6/cnslab_fmri) |

----------

## Interpretation-Based Dynamic Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [Explainable fMRI-based brain decoding via spatial temporal-pyramid graph convolutional network ](https://onlinelibrary.wiley.com/doi/pdf/10.1002/hbm.26255) | _Hum. Brain Mapp._ | 2023 | STpGCN | - |
| [HDGL: A HIERARCHICAL DYNAMIC GRAPH REPRESENTATION LEARNING MODEL FOR BRAIN DISORDER CLASSIFICATION ](https://arxiv.org/pdf/2311.02903.pdf) | _Arxiv_ | 2023 | HDGL | - |

----------

## Prediction-Based Multi-Modal Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [Multi-View Multi-Graph Embedding for Brain Network Clustering Analysis ](https://ojs.aaai.org/index.php/AAAI/article/view/11288) | _AAAI_ | 2018 | M2E | [[Code]](https://github.com/yeliu918/M2E) |
| [Brain multigraph prediction using topology-aware adversarial graph neural ](https://www.sciencedirect.com/science/article/pii/S1361841521001365) | _Med. Image Anal._ | 2021 | TopoGAN | [[Code]](https://github.com/basiralab/topoGAN) |
| [Community-preserving Graph Convolutions for Structural and Functional Joint Embedding of Brain Networks ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9005586) | _Big Data_ | 2019 | SCP-GCN| - |
| [Heterogeneous Graph-Based Multimodal Brain Network Learning](https://arxiv.org/pdf/2110.08465.pdf) | _Arxiv_ | 2021 | HebrainGNN |[[Code]](https://github.com/shigen97/HebrainGNN) |
| [Joint Embedding of Structural and Functional Brain Networks with Graph Neural Networks for Mental Illness Diagnosis ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9871118) | _EMBC_ | 2022 | BrainNN | - |
| [Multi-Modal Graph Learning for Disease Prediction ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9733917) | _TMI_ | 2022 | MMGL | [[Code]](https://github.com/SsGood/MMGL) |
| [Multi-Modal Non-Euclidean Brain Network Analysis With Community Detection and Convolutional Autoencoder ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9773106) | _TETCI_ | 2022 | M2CDCA | - |
| [Multiplex Graph Networks for Multimodal Brain Network Analysis ](https://arxiv.org/pdf/2108.00158.pdf) | _Arxiv_ | 2021 | MGNet | [[Code]](https://github.com/ZhaomingKong/MGNets.) |
| [Multi-View Brain Network Analysis with Cross-View Missing Network Generation ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9995283) | _BIBM_ | 2022 | GroGen | [[Code]](https://github.com/GongxuLuo/CroGen) |
| [Multi-view Graph Embedding with Hub Detection for Brain Network Analysis ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8215586) | _ICDM_ | 2017 | MVGE-HD | - |
| [Multi-View Tensor Graph Neural Networks Through Reinforced Aggregation ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9711926) | _TKDE_ | 2023 | RTGNN | [[Code]](https://github.com/RingBDStack/RTGNN) |
| [Overlapping Community Detection in Multi view Brain Network ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8621075) | _BIBM_ | 2018 | oComm | - |

----------

## Interpretation-Based Multi-Modal Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [Autistic Spectrum Disorders Diagnose with Graph Neural Networks](https://dl.acm.org/doi/pdf/10.1145/3581783.3613818) | _MM_ | 2023 | - | - |
| [A graph neural network framework for causal inference in brain networks ](https://www.nature.com/articles/s41598-021-87411-8) | _Scientific Reports_ | 2021 | DCRNN | - |
| [Multimodal Triplet Attention Network for Brain Disease Diagnosis](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9857948) | _TMI_ | 2022 | - | - |
| [Multimodal graph coarsening for interpretable, MRI-based brain graph neural network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9690626) | _MLSP Workshop_ | 2021 | MM-GNN |- |
| [MSTGC: Multi-Channel Spatio-Temporal Graph Convolution Network for Multi-Modal Brain Networks Fusion ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10123964) | _TNSRE_ | 2023 | MSTGC | - |
| [Mapping Multi-modal Brain Connectome for Brain Disorder Diagnosis via Cross-modal Mutual Learning ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10182318) | _TMI_ | 2023 | Cross-GNN | - |
| [Interpretable graph convolutional network of multi-modality brain imaging for alzheimer's disease diagnosis](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9761449) | _ISBI_ | 2022 | - | - |
| [Multimodal Brain Connectomics-Based Prediction of Parkinson’s Disease Using Graph Attention Networks ](https://www.frontiersin.org/articles/10.3389/fnins.2021.741489/full) | _Frontiers in genetics_ | 2022 | - | - |
| [Deep Representation Learning for Multimodal Brain Networks ](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8293685/) | _MICCAI_ | 2020 | DMBN | - |
| [BraceNet: Graph-Embedded Neural Network for Brain Network Analysis ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10021060) | _Big Data_ | 2022 | BraceNet | - |
| [Multi-modal Graph Neural Network for Early Diagnosis of Alzheimer's Disease from sMRI and PET Scans ](https://www.sciencedirect.com/science/article/pii/S001048252300793X) | _Comput. Biol. Med._ | 2023 | - | - |

----------

## Brain Neuroimaging Datasets

| **Dataset** | **Data Source** | **Modality Type** | **Data Link** |
| -- | :--------------: | :---: | :--: |
| ABIDE | Autism Spectrum Disorder | fMRI  | [[Link]](http://fcon_1000.projects.nitrc.org/indi/abide/) | 
| ADNI | Alzheimer Disorder | fMRI, PET | [[Link]](http://www.loni.ucla.edu/ADNI/Data/index.shtml.) |
| PPMI | Parkinson Disorder | fMRI | [[Link]](https://www.ppmi-info.org/) | 
| HIV | Human Immunodeficiency Virus Disorder | fMRI, DTI | - |
| BP | Bipolar Disorder | fMRI, DTI | - |
| HCP | Human Connectome Project | fMRI | [[Link]](https://db.humanconnectome.org/) |
| ABCD | Adolescent Brain Cognitive Development Study | fMRI | [[Link]](https://abcdstudy.org) |
| ADHD |  Attention Deficit Hyperactivity Disorder | fMRI | - |
| Biopoint | Autism Spectrum Disorder | fMRI | - |
| HIV | Human Immunodeficiency Virus Disorder | fMRI, DTI | - |
| UKB | The United Kingdom Biobank | fMRI | [[Link]](https://www.ukbiobank.ac.uk/) |
| NCANDA | The national consortium on alcohol and neurodevelopment in adolescence  | fMRI | - |
| PNC | Philadelphia Neuroimaging Cohort  | fMRI | [[Link]](https://www.nitrc.org/projects/pnc) |

----------

## Brain Graph Analysis Tools

### fMRI Preprocessing Tools

- SPM https://www.fil.ion.ucl.ac.uk/spm/software/spm12
- AFNI https://afni.nimh.nih.gov
- FSL https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL
- FreeSurfer https://surfer.nmr.mgh.harvard.edu
- CONN https://web.conn-toolbox.org/home
- Nilearn https://nilearn.github.io/stable/index.html

### DTI Preprocessing Tools

- AFNI https://afni.nimh.nih.gov
- FSL https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FSL
- DSI Studio https://dsi-studio.labsolver.org
- MRtrix3 https://www.mrtrix.org/

----------

**Disclaimer**

If you have any inquiries or updates regarding brain graph learning with GNNs, please do not hesitate to contact us. We also extend an invitation to researchers interested in brain graph learning with GNNs to join this project as contributors and contribute to advancing research in this field.

Emails: xuexiong.luo@hdr.mq.edu.au, jia.wu@mq.edu.au.


 

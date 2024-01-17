# Awesome-Brain-Graph-Learning-with-Graph-Neural-Networks

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs) 
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs) 
![GitHub stars](https://img.shields.io/github/stars/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs?color=yellow&label=Stars)
![GitHub forks](https://img.shields.io/github/forks/XuexiongLuoMQ/Awesome-Brain-Graph-Learning-with-GNNs?color=blue&label=Forks) 
![](https://visitor-badge.glitch.me/badge?page_id=littleTreeme)

:fire::fire: This is a collection of awesome papers about graph neural networks for brain graph learning

## Contents
- [Surveys](#surveys)
- [Prediction-Based Static Brain Graph Learning](#Prediction-Based-Static-Brain-Graph-Learning)
- [Interpretation-Based Static Brain Graph Learning](#Interpretation-Based-Static-Brain-Graph-Learning)
- [Prediction-Based Dynamic Brain Graph Learning](#Prediction-Based-Dynamic-Brain-Graph-Learning)
- [Interpretation-Based Dynamic Brain Graph Learning](#Interpretation-Based-Dynamic-Brain-Graph-Learning)
- [Prediction-Based Multi-Modal Brain Graph Learning](#Prediction-Based-Multi-Modal-Brain-Graph-Learning)
- [Interpretation-Based Multi-Modal Brain Graph Learning](#Interpretation-Based-Multi-Modal-Brain-Graph-Learning)
- [Brain Datasets](#Brain-Datasets)
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
| [Contrastive Graph Pooling for Explainable Classification of Brain Networks]( https://arxiv.org/pdf/2307.11133.pdf) | _ Arxiv_ | 2023 | ContrastPool | - |
| [Brain Networks and Intelligence: A Graph Neural Network Based Approach to Resting State fMRI Data](https://arxiv.org/pdf/2311.03520.pdf ) | _Arxiv_ | 2023 | BrainRGIN | [[Code]](https://github.com/bishalth01/Brain-ROI-Aware-Graph-Isomorphism-NetworksBrainRGIN-)   |
| [ Classification of Brain Disorders in rs-fMRI via Local-to-Global Graph Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9936686&casa_token=08WIe6MyOYAAAAAA:KJD6n3VVd3Vs05A0fKPtElfGWRTz93VW_96KIQ-UF-fDx8CniPvxu2yqorLH18mr5uL9fA) | _TMI_ | 2023 | LG-GNN | [[Code]](https://github.com/cnuzh/LG-GNN)  |
| [Dementia analysis from functional connectivity network with graph neural networks]( https://www.sciencedirect.com/science/article/pii/S0306457322000309?casa_token=WiLyJQu02M0AAAAA:lc32wQxTCKDbeNtzNXA5YVtEBvm4aiJjznwq8E_xDZ_x2Zs6zqXxsqRG-pnTvOqfRO4rPA) | _IPM_ | 2022 | - |- |
| [ Graph Neural Network for Interpreting Task-fMRI Biomarkers]( https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7519579/) | _MICCAI_ | 2019 | t-fMRI | - |
| [ Community-Aware Transformer for Autism Prediction in fMRI Connectome ](https://arxiv.org/pdf/2307.10181.pdf) | _MICCAI_ | 2023 | Com-BrainTF | [[Code]](https://github.com/ubc-tea/Com-BrainTF.) |
| [FC–HAT: Hypergraph attention network for functional brain network classification](https://www.sciencedirect.com/science/article/pii/S0020025522007307?casa_token=stTW8Oy-au4AAAAA:0XJtoDfU1_mvPHLhXBkmTT114ihccpUiT7i5L6G1PsJNKnk_vxNpa95WvqqjDGZSjwCxUw) | _Information Sciences_ | 2022 |  FC–HAT | [[Code]](https://github.com/uuup123/FC–HAT)  |
| [ BrainGNN: Interpretable Brain Graph Neural Network for fMRI Analysis]( https://www.sciencedirect.com/science/article/pii/S1361841521002784?casa_token=tesOeiHg9n4AAAAA:4_A6aBwjG0FOY_Rfu7cenN4RZSFtfAr50gxdcxRnO2tsjKa1JaAjOdqKPztSlXIu7IITMw) | _ Med. Image Anal.	_ | 2021 | BrainGNN | [[Code]](https://github.com/xxlya/BrainGNN_Pytorch)   |
| [BrainIB: Interpretable Brain Network-based Psychiatric Diagnosis with Graph Information Bottleneck](https://arxiv.org/pdf/2205.03612.pdf) | _Arxiv_ | 2023 | BrainIB | - |
| [FBNetGen: Task-aware GNN-based fMRI Analysis via Functional Brain Network Generation](https://proceedings.mlr.press/v172/kan22a/kan22a.pdf) | _MIDL_ | 2022 | FBNetGen | [[Code]]( https://github.com/Wayfear/FBNETGEN.) |
| [ BRAINNPT: PRE-TRAINING TRANSFORMER NETWORKS FOR BRAIN FUNCTIONAL NETWORK CLASSIFICATION](https://arxiv.org/pdf/2305.01666.pdf) | _Arxiv_ | 2023 |  BrainNPT | -|

----------

## Prediction-Based Dynamic Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 |  | - |

----------

## Interpretation-Based Dynamic Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 |  | - |

----------

## Prediction-Based Multi-Modal Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 |  | - |

----------

## Interpretation-Based Multi-Modal Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 |  | - |

----------

## Datasets

| **Dataset** | **Data Source** | **Modality Type** | **Code** |
| ---- | :-----------: | :----: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | 
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | 
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 | - |

----------

## Tools

----------

**Disclaimer**



 

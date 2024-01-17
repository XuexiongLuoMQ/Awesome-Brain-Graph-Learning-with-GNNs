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
| [Hi-GCN: A hierarchical graph convolution network for graph embedding learning of brain network and brain disorders prediction]( https://www.sciencedirect.com/science/article/pii/S0010482520304273?casa_token=zTi-i1OA8R4AAAAA:GgqPf28cPE-sAAuxvaqpcEl-kIY84r7hUWyKGvD61KN8QAzpRqzo3don4iXIGKdhX4FljQ) | _Comput. Biol. Med._ | 2020 | Hi-GCN | [[Code]](https://github.com/hao jiang1/hi-GCN) |
| [A Graph Attention Neural Network for Diagnosing ASD with fMRI Data](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9669849&casa_token=MTyuvlZTI3QAAAAA:exXxjVImpiT7KFE2gS_F00YxSkVSVvzVLoICM9SoEctDdDNblIQ53pedt2hxWLsHl93mIg ) | _BIBM_ | 2021 | - |- |
| [BrainMixup: Data Augmentation for GNN-based Functional Brain Network Analysis ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10020662&casa_token=4qOSUY3BVcQAAAAA:rygG3mzSWMsnFiNyyBYfaKUYZtRi15plVy6l1hYie2e5fLC6cJSo3C02SimfJhjUGmScJA) | _Big Data_ | 2022 | - | - |
| [ BRAIN NETWORK TRANSFORMER]( https://proceedings.neurips.cc/paper_files/paper/2022/file/a408234a9b80604a9cf6ca518e474550-Paper-Conference.pdf) | _NeurIPS_ | 2022 | BRAINNETTF | [Code]](https://github.com/Wayfear/BrainNetworkTransformer)  |
| [BrainVGAE: End-to-End Graph Neural Networks for Noisy fMRI Dataset](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9994963&casa_token=V00-89HzU_MAAAAA:2uBPUSubvtWPfBe-TtJAqooaqpIeHuMpVh6qspyWV_Pk0F14D0ZXnsjkhqYY3R2XpOIaNw) | _BIBM_ | 2022 | - | - |
| [Classification of First-Episode Schizophrenia, Chronic Schizophrenia and Healthy Control Based on Brain Network of Mismatch Negativity by Graph Neural Network](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9515994) | _TNSRE_ | 2021 | - | - |
| [ Deep reinforcement learning guided graph neural networks for brain network analysis](https://www.sciencedirect.com/science/article/pii/S0893608022002507?casa_token=KFewXixEefMAAAAA:fGzD8g8xtjcCFB0Bux2KO2j0yTuBXe98vpH98pZRg9IZo3yKCrhrx5USv9ATd9GtpfpIxg) | _Neural Networks_ | 2022 | BN-GNN |[Code]](https://github.com/RingBDStack/BNGNN)  |
| [EEG-GNN: Graph Neural Networks for Classification of Electroencephalogram (EEG) Signals](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9630194&casa_token=LKFHAvrzSRMAAAAA:a8LKc73XLvB4JN8LK9H6eMlC8wZWae14zEkY_HHBzevZ2W_uM5amllUFPA4JCpiW0mrZMw) | _EMBC_ | 2021 | - | - |
| [PTGB: Pre-Train Graph Neural Networks for Brain Network Analysis ](https://arxiv.org/pdf/2305.14376.pdf) | _CHIL_ | 2022 | PTGB | [Code]]( https://github.com/ Owen-Yang-18/BrainNN-PreTrain)  |
| [ Data-Efficient Brain Connectome Analysis via Multi-Task Meta-Learning](https://dl.acm.org/doi/pdf/10.1145/3534678.3542680) | _KDD_ | 2022 | MML | [Code]]( https://github.com/Owen-Yang-18/BrainNN-PreTrain)  |

----------

## Interpretation-Based Static Brain Graph Learning

| **Paper Title** | **Venue** | **Year** | **Model** | **Code** |
| ----------- | :---: | :--: | :--: | :--: |
| [EEG-Based Graph Neural Network Classification of Alzheimer’s Disease: An Empirical Evaluation of Functional Connectivity Methods](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9878348) | _IEEE TNSRE_ | 2022 | - | - |
| [Effective and Interpretable fMRI Analysis via Functional Brain Network Generation ](https://arxiv.org/pdf/2107.11247.pdf) | _ICML Workshop_ | 2021 | - | - |
| [ Multi-Level Graph Neural Network With Sparsity Pooling for Recognizing Parkinson’s Disease ](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10310009) | _IEEE TNSRE_ | 2023 | SparsityATopK | - |
| [Balanced Graph Structure Information for Brain Disease Detection ](https://arxiv.org/pdf/2401.00876.pdf) | _PKAW_ | 2023 | Bargrain |- |
| [Brain network classification based on dynamic graph attention information bottleneck]( https://www.sciencedirect.com/science/article/pii/S0169260723005795) | _Comput. Meth. Programs Biomed._ | 2024 |  | - |

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



 

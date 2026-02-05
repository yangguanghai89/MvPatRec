# MvPatRec

# Introduction
This repository contains the dataset for paper: MvPatRec: Viewpoint-aware Alternating Attention via Textual Prompt for Multi-view Patent Recognition.

# Abstract
Design patent recognition stands as a pivotal task in intellectual property management, where accurately categorizing product designs into thousands of fine-grained categories based on their visual appearance remains a persistent challenge. Existing methods predominantly represent a design patent using a single rendered image, which provides limited visual evidence and often leads to ambiguous classification results. In practice, a design patent is typically associated with multiple rendered images that jointly depict its structural and geometric details, motivating the adoption of multi-view modeling for more informative patent representations. In this paper, MvPatRec, a multi-view design patent classification framework, is designed to explicitly exploit complementary information across different views. Beyond visual cues, view-dependent textual descriptions are incorporated as auxiliary semantic guidance to enrich visual feature representations. To effectively aggregate information from multiple views, a viewpoint-aware alternating attention is designed to jointly model intra-view and inter-view dependencies, enabling the complete and discriminative multi-view representation learning for design patents. Experimental results on MvDeepPatent, a large-scale multi-view design patent dataset reorganized from DeepPatent2 with aligned view descriptions, demonstrate the effectiveness of MvPatRec, achieving more than 10\% performance improvement over the strong baseline methods in terms of accuracy and precision. Specifically, it exhibits robust performance as the number of categories increases dynamically, which convincingly proves the generalization and scalability. Ablation studies further validate the contribution of view-specific textual prompt and multi-view visual aggregation.

# Dataset
You can get patent evaluated corpus, MvDeepPatent, at <https://pan.baidu.com/s/1O58mwdE_bDEvaR4DOF2lFg?pwd=pp7p>




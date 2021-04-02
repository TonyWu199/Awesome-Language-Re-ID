# Awesome-Language-Re-ID
List of published papers for natural language based Re-ID

1. Person Search with Natural Language Description[[paper](https://arxiv.org/abs/1702.05729)]. CVPR' 2017

   > 挖坑之作，提出CUHK-PEDES数据集。

2. Identity-Aware Textual-Visual Matching with Latent Co-attention[[paper](https://arxiv.org/abs/1708.01988)]. ICCV'2017(Same authors above)

3. Improving Deep Visual Representation for Person Re-identification by Global and Local Image-language Association[[paper](https://arxiv.org/abs/1808.01571)]. ECCV'2018

   > 利用natural language作为辅助信息来提升传统Re-ID的性能。

4. Improving Text-based Person Search by Spatial Matching and Adaptive[[paper](https://www.computer.org/csdl/proceedings-article/wacv/2018/488601b879/12OmNwAbquV)]. WACV'2018

5. Deep Cross-Modal Projection Learning for Image-Text Matching[[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Ying_Zhang_Deep_Cross-Modal_Projection_ECCV_2018_paper.pdf)]. ECCV'2018

   > 这篇文章的loss有被用于一些后续方法的baseline中，有一定效果。

6. Deep Adversarial Graph Attention Convolution Network for Text-Based Person Search[[paper](https://dl.acm.org/citation.cfm?id=3350991)]. MM'19

7. Language Person Search with Mutually Connected Classification Loss[[paper](https://ieeexplore.ieee.org/document/8682456)]. ICASSP' 2019

8. Adversarial Representation Learning for Text-to-Image Matching[[paper](https://arxiv.org/abs/1908.10534)]. ICCV'2019

   > 利用对抗模型来消除modality gap。

9. Dual-Path Convolutional Image-Text Embedding with Instance Loss[[paper](https://arxiv.org/abs/1711.05535)]. TOMM'2020

   > 针对cross-modal retrieval任务，先用instance loss预训练模型，为ranking loss创造一个好的初始化参数。

10. Pose-Guided Multi-Granularity Attention Network for Text-Based Person Search[[paper](https://arxiv.org/abs/1809.08440)]. AAAI' 2020

    > 对image提取key points，由此实现细粒度对齐。

11. Improving Description-based Person Re-identification by Multi-granularity Image-text Alignments[[paper](https://arxiv.org/abs/1906.09610)].  TIP'2020

    > 多粒度的对齐，和cross-modal retrieval任务中的Stacked Cross Attention for Image-Text Matching[[paper]()]这篇文章的方法很像。训练起来很复杂。

12. Text-based Person Search via Attribute-aided Matching[[paper](https://ieeexplore.ieee.org/document/9093640)]. WACV'2020

    > 通过增加attribute classification的任务来提升特征表达能力，其中attributes从sentence中提取。貌似又从natural language倒退回attribute了:sweat_smile:。

13. ViTAA: Visual-Textual Attributes Alignment in Person Search by Natural Language[[paper](https://arxiv.org/abs/2005.07327)]. ECCV'2020

    > 增加了一个轻量级的segment模型来对image进行语义分割，由此实现属性对齐。

14. Hierarchical Gumbel Attention Network for Text-based Person Search[[paper](https://dl.acm.org/doi/10.1145/3394171.3413864)]（Best current）. MM'2020

    > 将Gumbel Attention(hard attention mechanism)应用到Language Re-ID任务中。


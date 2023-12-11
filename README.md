# DEBT: Enhancing Entity Alignment in Knowledge Graphs through Description Enrichment and Bootstrap Training

PyTorch code for paper, which has been submitted to NAACL:

![The framework of DEBT model](https://github.com/TXiang-code/DEBT/blob/main/pipeline.png)

## Abstract
Entity alignment has emerged as a powerful technique for integrating knowledge graphs, facilitating the fusion of heterogeneous knowledge into a unified graph. The state-of-the-art methods combine both graph structures and side information for effective entity alignment. However, they neglect low-quality issues in data. The emerging knowledge graphs in diverse fields amass a wealth of entities that not only lack adequate descriptions but also annotated alignments. These two limitations lead to the overfitting problem and degrade the alignment performance. To tackle this, we propose DEBT. It first enriches the descriptions of entities by aggregating their neighbors and attributes. A bootstrap strategy is then utilized to expand the training set by incorporating entity pairs with similarity scores exceeding a dynamically decreasing threshold. Experimental results demonstrate that our method achieves the state-of-the-art accuracy. 

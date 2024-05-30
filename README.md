
# Neural Inverted Index for Fast and Effective Information Retrieval

## Introduction
This work introduces an innovative method in information retrieval (IR) that differs from traditional index-then-retrieve systems. The Differentiable Search Index (DSI) idea entails the integration of indexing and retrieval functions inside a single Transformer language model. This model has undergone training using the MS MARCO dataset and is dependent on the Pyserini library. The goal is to enhance the effectiveness of information retrieval by automatically generating appropriate document identifiers (docids).

## Task
- Develop an integrated sequence-to-sequence model ('f') for optimizing information retrieval.
- Investigate different training methodologies, such as auto-regressive and teacher-forcing techniques.
- Improve the effectiveness of retrieving information by prioritizing indicators such as Mean Average Precision (MAP), Precision@10, and Recall@1000.

## Useful Links
- **Dataset**: We utilize the MS MARCO dataset for this task. Detailed instructions on how to access and use the dataset with the Pyserini library are included.
- **Project Repository**
  - [Transformer Memory as a Differentiable Search Index](https://github.com/Saad-data/neural_inverted_index_dsi)
  - [Pyserini: An Easy-to-use Python Toolkit to Support Replicable IR Research with Sparse and Dense Representations](https://github.com/castorini/pyserini)
  - [Understanding Differential Search Index for Text Retrieval](https://arxiv.org/abs/2202.06991)

## Installation
To set up your environment to use the DSI model, follow these steps:
1. Clone the repository with our personal source files:
   \`\`\`bash
   git clone https://github.com/Saad-data/neural_inverted_index_dsi
   \`\`\`

## Authors
**Syed Saad Hasan**  
Email: [hasan.2106512@studenti.uniroma1.it](mailto:hasan.2106512@studenti.uniroma1.it)

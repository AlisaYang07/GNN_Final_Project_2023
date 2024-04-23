# Exploring Deep Learning Methods on the Analyst Coverage Network

## Abstract 
Graph datasets can be a rich source of information in fields such as Finance, since they can capture relationships that may not be evident in traditional tabular datasets. The Analyst Coverage Network (ACN) is a graph dataset where each node corresponds to a company, and edges between two nodes/companies represent the number of equity analysts covering both companies. We believe the ACN contains useful information on company similarity because analysts possess domain expertise and therefore are more likely to cover companies that are related in some dimension. Being able to group similar companies is an important task in Finance, as they often exhibit correlated returns. Graph Neural Networks (GNNs) are popular models used to extract information from graphs and both supervised (Graph Convolutional Network) and unsupervised (node2vec) techniques have demonstrated strong performance for many deep learning tasks. Applying both techniques to the ACN dataset gives us a broader understanding of their individual strengths and weaknesses. We demonstrate that GNNs can effectively extract meaningful features from the ACN graph. Specifically, we observe that the node2vec algorithm, which is an unsupervised technique, is simpler to train and produces embeddings that encode similar information to the Global Industry Classification Standard (GICS). These embeddings can then be used for a variety of downstream forecasting tasks. In contrast, the supervised technique is target-specific and can generate predictions directly, but it is harder to train and does not perform well with limited number of input features. 
 
![image](https://github.com/AlisaYang07/GNN_Final_Project_2023/assets/61921004/6513a2c1-719f-48a4-baa2-5cf102cf14f2)

Note: This paper resulted from research conducted at my internship at CPP Investment and is presented to partially fullfil the graduating conditions of Masters of Applied Computing (2023) program.

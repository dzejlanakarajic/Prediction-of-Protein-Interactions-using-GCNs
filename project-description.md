# Predicting of Protein Interactions using GCNs

Protein-protein interactions (PPIs) are essential to almost every process in a cell. Exploring PPIs is
crucial for understanding cell physiology in normal and disease states. The knowledge of PPIs can be
used for drug development and to assign roles (i.e., protein functions) to uncharacterized proteins. In
this project, we investigate the utility of Graph Convolutional Networks (GCNs) for the problem
of predicting protein-protein interactions (PPIs). The totality of PPIs is presented in the form of an
undirected network, we thus formulate the problem as a link prediction task by GCN. Your task is
to implement GCN for link prediction in PyTorch. The following steps should be undertaken and
documented:

1. Problem Definition
   1. Introduction to GCNs
   2. A short review on state-of-the-art for PPIs
   3. Formal definition of the problem (with mathematical notations)
   
2. Data Preprocessing
   1. Download the dataset (edgelist):
      1. Yeast
   2. Describe the dataset
   
3. Implementation
   1. Use GCNs in PyTorch and implement the link prediction problem
   
4. Empirical Evaluations and Discussion
   1. Link prediction Performance:
      1. Area Under the ROC Curve (AUC)
      2. Average Precision (AP)
   2. Hyperparameter study:
      1. Tune number of units in hidden layer 1: 256, 128, 64, 32.
      2. Tune number of units in hidden layer 2: 64, 32, 16, 8.
      3. Tune number of training epochs from 5 to 20.
      4. Set initial learning rate to 0.001, 0.01, and 0.1.

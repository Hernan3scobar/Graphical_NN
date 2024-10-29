# Graph Embeddings and Graph Convolutional Network (GCN) Implementation
> Based on concepts from [Kipf & Welling, 2017](https://arxiv.org/pdf/1603.08861)

Graph embeddings provide a way to represent nodes, edges, or entire graphs as continuous vectors in a high-dimensional space, which enables more efficient application of machine learning algorithms to graph-structured data.

This implementation uses a **Graph Convolutional Network (GCN)** designed to work directly with graph data. The GCN model applies graph convolutional layers, allowing it to aggregate information from each node's neighbors to generate meaningful embeddings for each node. This approach follows the embedding methodology outlined in the referenced paper to enhance learning on graph-structured data.

### Model Performance and Metrics
The performance metrics for the model are as follows:

- **Test Accuracy**: **0.7710** — The model correctly classifies 77.10% of test samples, showing its general reliability.
- **Recall**: **0.7762** — The model effectively identifies true positives, indicating strong performance in detecting relevant instances.
- **F1 Score**: **0.7698** — Balances precision and recall, suggesting a well-rounded performance with minimal compromise on false positives or false negatives.
- **Multi-class ROC AUC**: **0.9109** — Indicates the model's high capability to distinguish between different classes, a crucial metric for multi-class tasks.

The **confusion matrix** shows consistent performance across all classes, though Class 1 exhibits a slightly higher rate of false positives.

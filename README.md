# Investigating GNN Convergence on Large Randomly Generated Graphs with Realistic Node Feature Correlations

We investigate the convergence behaviour of graph neural networks when applied to large randomly generated graphs. The node features will be sampled in such a manner to ensure correlation between neighbouring nodes. In sampling such features, we will appeal to properties exhibited by real-life graphs, particularly properties that are captured by the Barabási-Albert model.

The investigation includes an informal theoretical analysis, which indicates the possibility for divergence. Indeed, our experimental findings strongly validate that GNN classifiers may be able to produce divergent outputs on the resulting graphs, in the presence of realistic node correlations.

The original paper was written by myself as part of a mini-project in Graph Representation Learning during my Master's degree. Minor adaptations have since been made to the paper, which is available on arXiv at https://arxiv.org/abs/2602.16145. This repository includes the original Python code, presented as a Jupyter notebook, which was written in Google Colab.

Any comments or questions should be sent to me via email at mzain@live.co.uk.

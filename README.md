# Jet Flavor Classification

These notebooks are used to classify heavy-flavored jets at LHCb using graph neural networks (GNNs). Currently, there are four binary classifiers:
- b vs q
- c vs b
- c vs q
- b/c vs q
  
There is also a combined classifier, which performs the same binary classifications together.

## Setting Up Environment

Use Python version 3.9.0, since PyTorch Geometric is incompatable with the most recent versions. Conda environment, gnn_env.yml, is attached.

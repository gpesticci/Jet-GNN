* [Jet Flavour Classification](#jet-flavour-classification)
  * [Setting Up Environment](#setting-up-environment)
  * [Data Preparation](#data-preparataion)

# Jet Flavour Classification

The goal of this project is to develop a graph neural network to classify jets. Currently, the model can determine if a jet originated from a _b_-quark or not.
In the future, it will be extended to classify _c_-jets and fat jets.
The classifier performs with AUC = 0.9245, and has a working efficiency of 80% with 90% background rejection.


## Setting Up Environment

Use Python version 3.9.0, since PyTorch Geometric is incompatable with the most recent versions.
Install the following packages to your environment:

```
pip install pandas
pip install numpy
pip install matplotlib
pip install torch
pip install torchvision
pip install torchaudio
pip install torch-geometric
pip install networkx
pip install scikit-learn
pip install seaborn
```
## Data Preparation

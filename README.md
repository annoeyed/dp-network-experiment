# DP Network Experiment

This repository contains an experiment using Differential Privacy (DP) with the Opacus library on the UNSW-NB15 network security dataset.

This notebook compares the performance of a baseline model and a differentially private model using PyTorch.

## Contents

- Data preprocessing (SMOTE, normalization)
- Model training (Baseline and DP)
- Evaluation (Accuracy, Confusion Matrix)
- Epsilon (ε) calculation using Opacus

## Run on Google Colab

[Open in Colab](https://colab.research.google.com/github/annoeyed/dp-network-experiment/blob/main/dp_network.ipynb)

### Installing dependencies in Colab

After opening in Colab, run the following command in the first code cell to install required packages:

```python
!pip install torch torchvision opacus scikit-learn imbalanced-learn
```

## Additional Information
The UNSW-NB15 dataset is not included in this repository. Please upload it manually when using Colab.

The notebook includes both baseline and differentially private model evaluation using ε metrics.

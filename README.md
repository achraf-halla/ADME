# ADME
Predicting ADME Properties of Molecules Using Graph Neural Networks (GNNs)

# Overview
This project aims to predict ADME (Absorption, Distribution, Metabolism, and Excretion) properties of small molecules using Graph Neural Networks. Initially, the focus is on a single ADME property: solubility, using the Therapeutics Data Commons (TDC) dataset.

# Short term Project Steps
1. Data Acquisition
Load the Solubility_AqSolDB dataset via TDC.

Each sample includes a SMILES string and a corresponding aqueous solubility value.

2. Data Exploration
Analyze the distribution of solubility values (e.g., histogram, boxplot).

Check for data imbalance or outliers.

Visualize example molecules.

Compute basic molecular descriptors (e.g., MolWt, LogP) and explore correlations with solubility.

Investigate potential patterns in high vs. low solubility compounds.

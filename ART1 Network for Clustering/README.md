# ART1 Network for Clustering

This repository contains a Python implementation of the ART1 (Adaptive Resonance Theory 1) network for clustering purposes, along with PCA (Principal Component Analysis) and Q-Matrix computation for feature extraction and dimensionality reduction.

## Overview

The provided Python script performs the following tasks:

1. **ART1 Network**:
    - Implements the ART1 network for clustering unlabeled data.
    - Trains the ART1 network on the Iris dataset and predicts clusters.
    - Visualizes the clusters and prototypes in bottom-up and top-down space.

2. **PCA**:
    - Computes Principal Component Analysis (PCA) for dimensionality reduction.
    - Reconstructs the data based on the selected principal components.
    - Visualizes the transformed data in a scatter plot.

3. **Q-Matrix Computation**:
    - Computes the Q-Matrix for feature extraction.
    - Determines the best number of principal components and associated Q-Matrix using an iterative approach.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- NumPy
- Matplotlib
- scikit-learn

### Usage

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the repository directory:

    ```bash
    cd <repository_directory>
    ```

3. Run the Python script:

    ```bash
    python art1_network.py
    ```

4. View the output:

    - The script will display the clusters and prototypes of the ART1 network.
    - It will also visualize the transformed data after PCA and display the computed covariance matrix.



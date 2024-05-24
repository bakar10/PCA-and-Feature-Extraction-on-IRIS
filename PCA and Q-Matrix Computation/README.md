# PCA and Q-Matrix Computation

This repository contains Python scripts for computing Principal Component Analysis (PCA) and Q-Matrix for dimensionality reduction and feature extraction tasks on IRIS dataset

## Overview

The provided Python script performs the following tasks:

1. **Load Iris Dataset**:
    - Load the Iris dataset from the scikit-learn library.

2. **Compute PCA**:
    - Implement PCA (Principal Component Analysis) to reduce the dimensionality of the Iris dataset.
    - Visualize the transformed data in a scatter plot.

3. **Compute Q-Matrix**:
    - Implement the computation of the Q-Matrix for feature extraction.
    - Find the best number of principal components and associated Q-Matrix using an iterative approach.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- NumPy
- scikit-learn
- pandas
- matplotlib

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
    python pca_q_matrix.py
    ```

4. View the output:

    - The script will display the transformed data in a scatter plot for PCA.
    - It will also print the Q-Matrix computed along with the best number of principal components.


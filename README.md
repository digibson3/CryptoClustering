# CryptoClustering

## Overview

This project applies unsupervised machine learning techniques—specifically K-Means clustering and Principal Component Analysis (PCA)—to group cryptocurrencies based on their performance and market characteristics. By analyzing and reducing feature sets, the project demonstrates how clustering can help uncover patterns and group similar cryptocurrencies together for further analysis or investment strategy.

## Objectives

- Preprocess and normalize cryptocurrency market data.
- Apply K-Means clustering to group similar cryptocurrencies.
- Use PCA to reduce dimensionality while preserving variance.
- Visualize clustering results in 2D and 3D plots.
- Analyze the impact of using fewer features on clustering quality.

## Technologies Used

- Python 3.9+
- Pandas
- scikit-learn
- matplotlib
- plotly
- hvplot
- Jupyter Notebook

## Files

- `crypto_clustering.ipynb`: Main notebook with data preprocessing, clustering, PCA, and visualizations.
- `Resources/crypto_market_data.csv`: Cleaned and transformed crypto dataset.
- `README.md`: Project overview and usage instructions.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/digibson3/CryptoClustering.git
   cd CryptoClustering
Install dependencies (preferably in a virtual environment):

bash
Copy
Edit
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open crypto_clustering.ipynb and run the cells to perform clustering and PCA analysis.

Key Insights
Clustering with all features can result in overlapping or indistinct clusters due to high dimensionality.

Using PCA allows for effective clustering by reducing noise and focusing on the most significant components of the data.

Visualizations in 2D and 3D help interpret the cluster distribution more clearly.

Fewer features without PCA may simplify clustering but often reduce accuracy and insight.

# CryptoClustering
Module 19 - Unsupervised Learning


# Cryptocurrency Clustering with K-Means and PCA

This repository contains the code and resources for a cryptocurrency clustering project using K-Means and Principal Component Analysis (PCA). The objective of this project is to analyze and cluster various cryptocurrencies based on their price changes over different time frames. We used dimensionality reduction with PCA to enhance clustering visualization and interpretation.

## Project Overview

The project includes:
- **Data Loading and Preprocessing**: Loading cryptocurrency data from a CSV file and scaling it with `StandardScaler`.
- **Elbow Method**: Identifying the optimal number of clusters (`k`) using the Elbow method.
- **Clustering with K-Means**: Applying K-Means clustering to both the original scaled data and the PCA-reduced data.
- **PCA for Dimensionality Reduction**: Using PCA to reduce the dataset to three principal components.
- **Visualization**: Creating composite plots to compare clusters formed with the original and PCA-reduced data.

## File Structure

- **`Crypto_Clustering.ipynb`**: Jupyter Notebook containing the code for loading, preprocessing, clustering, PCA, and visualizing the data.
- **`Resources/crypto_market_data.csv`**: Source CSV file with cryptocurrency market data used in this project.

## Code Sources

The code in this project was developed as part of a structured assignment, with inspiration and guidance from project instructions. Specific portions of the code (e.g., Elbow method for optimal `k` determination and PCA implementation) are based on standard methods and libraries within Python’s `sklearn` and `pandas` libraries.

### Note on Code Source

All code for loading, transforming, and visualizing data can be found in the `Crypto_Clustering.ipynb` notebook within this repository. Please refer to this notebook for specific implementations and explanations.

## Getting Started

1. **Clone this repository**:
    ```bash
    git clone https://github.com/hamiltonbrba/CryptoClustering.git
    ```
2. **Install dependencies**:
    - This project requires Python 3 and the following libraries:
      - `pandas`
      - `scikit-learn`
      - `hvplot`
    - Install them using `pip install pandas scikit-learn hvplot`.

3. **Run the Notebook**:
    - Open `Crypto_Clustering.ipynb` in Jupyter Notebook or Jupyter Lab and follow the code cells to reproduce the analysis and visualizations.

## Results

The clustering analysis identified distinct groupings of cryptocurrencies based on their 24-hour and 7-day price change percentages, both in the original feature space and the reduced PCA space. The use of PCA simplified the data structure, resulting in clearer cluster separations.

## License

This project is for educational purposes. Please review and respect any data or library licenses when using this code.


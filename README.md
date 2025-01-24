# **Final Project: Dimensionality Reduction on High-Dimensional Data**
This project was conducted for COMS W4995: Geometric Data Analysis at Columbia University.

## **Overview**
This project evaluates the effectiveness of three dimensionality reduction techniques: Principal Component Analysis (PCA), t-Distributed Stochastic Neighbor Embedding (t-SNE), and Isometric Mapping (Isomap) using the MNIST dataset. By focusing on the challenging task of separating and visualizing the handwritten digits '1' and '7', the study provides insights into the strengths and limitations of these methods in clustering and visualization.

## **Objectives**
1. Assess the ability of PCA, t-SNE, and Isomap to uncover underlying patterns in high-dimensional data.
2. Compare their effectiveness in differentiating between visually similar handwritten digits ('1' and '7').
3. Highlight potential improvements and explore avenues for future research in dimensionality reduction techniques.

## **Key Takeaways**
- PCA is computationally efficient but limited in handling non-linear relationships.
- t-SNE excels at capturing local structures but is sensitive to hyperparameters.
- Isomap keeps the overall structure of the data intact but may not handle small-scale details as well.

## **Data**
- **Dataset**: MNIST (Modified National Institute of Standards and Technology)
  - **Images**: 70,000 grayscale images of handwritten digits, each 28x28 pixels.
  - **Focus**: Digits '1' and '7', chosen for their structural similarities and classification challenges.

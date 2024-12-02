# **Advanced Dimensionality Reduction Techniques**

This repository demonstrates the implementation and comparison of various dimensionality reduction techniques on different datasets, including **image datasets** (e.g., Digits, Faces) and **tabular datasets** (e.g., Iris). It covers both linear and non-linear methods, providing interactive visualizations and detailed results.

## **Techniques Demonstrated**

The following dimensionality reduction techniques are included:

- **Linear Techniques**:
  - PCA (Principal Component Analysis)
  - Randomized PCA
  - Incremental PCA
  - Kernel PCA
  - Factor Analysis
- **Manifold Learning Techniques**:
  - t-SNE (t-Distributed Stochastic Neighbor Embedding)
  - UMAP (Uniform Manifold Approximation and Projection)
  - ISOMAP
  - MDS (Multidimensional Scaling)
  - LLE (Locally Linear Embedding)
- **Non-linear Techniques**:
  - Autoencoders (using TensorFlow/Keras)

## **Links to Demonstrations**

1. **Dimensionality Reduction - Google Colab**  
   This notebook explores various dimensionality reduction techniques with interactive visualizations.  
   [Colab Link](https://colab.research.google.com/drive/1asPrSLU3-4yWnICUbCmKy5Di4LnUDaUl?usp=sharing)

2. **Dimensionality Reduction - Databricks**  
   Scalable implementation of dimensionality reduction on Databricks for large datasets.  
   [Databricks Link](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3433607511868086/2570502538451909/2517534166151825/latest.html)

3. **Dimensionality Reduction for Images and Tabular Data**  
   Includes techniques applied on both image and tabular datasets, including medical datasets.  
   [Colab Link](https://colab.research.google.com/drive/1nZWFoVYl4rFF9pt_q-p7G7YI8ZeaptY7?usp=sharing)

Video [link](https://www.youtube.com/watch?v=QIQZEQ6eVLo&list=PLGHkLcp2I_S99VL95LxofYaOPgjBVpJc_)

## **Datasets Used**

- **Image Datasets**:
  - Digits Dataset: Handwritten digits (8x8 grayscale images).
  - Faces Dataset: Human face images for non-linear dimensionality reduction.
  
- **Tabular Datasets**:
  - Iris Dataset: Classic dataset with sepal/petal measurements of flowers.
  - Medical Datasets: Real-world datasets sourced from research papers.

## **Results Summary**

### **Key Observations**

1. **Linear Techniques**:
   - **PCA**: Retains maximum variance in a linear projection, ideal for datasets with linear structures.
   - **Randomized PCA**: Efficient for large datasets, provides comparable results to standard PCA.
   - **Incremental PCA**: Processes data in batches, useful for memory-constrained environments.
   - **Kernel PCA**: Handles non-linear relationships using RBF and Polynomial kernels.
   - **Factor Analysis**: Identifies underlying latent variables in the data.

2. **Manifold Learning Techniques**:
   - **t-SNE**: Excellent for visualizing clusters; preserves local relationships effectively.
   - **UMAP**: Faster than t-SNE with similar visualization quality and better preservation of global structure.
   - **ISOMAP**: Projects data by preserving geodesic distances, ideal for curved manifolds.
   - **MDS**: Preserves pairwise distances in projections, slower for large datasets.
   - **LLE**: Retains local neighborhood structures, suited for non-linear manifolds.

3. **Non-linear Techniques**:
   - **Autoencoders**: Neural networks learn compressed latent representations, scalable for large datasets.

### **Performance Comparison**

- **Best for Visualization**: t-SNE and UMAP offer interpretable visualizations with meaningful clusters.
- **Fastest Techniques**: Randomized PCA and Incremental PCA are efficient for large-scale datasets.
- **Handling Non-Linearity**: Kernel PCA, ISOMAP, and Autoencoders perform well for complex patterns.
- **Memory-Constrained Environments**: Incremental PCA processes data in chunks without loading it entirely into memory.

## **Visualizations**

- **Interactive Visualizations**:
  - t-SNE and UMAP provide interactive 2D scatter plots using Plotly.
  - Explore UMAP interactive demos at [UMAP Visualization](https://pair-code.github.io/understanding-umap/).

- **Comparison Plots**:
  - Computation time, reconstruction error, and explained variance are visualized as bar plots for easy comparison.

## **How to Use**

### **Google Colab**
- Open the provided Colab links.
- Run the cells sequentially to view results and visualizations.

### **Databricks**
- Import the Databricks notebook into your workspace.
- Attach it to a cluster and execute the cells for scalability demonstrations.

## **References**

- [Analytics Vidhya: Dimensionality Reduction Techniques](https://www.analyticsvidhya.com/)  
- [Pair-Code UMAP Visualization](https://pair-code.github.io/understanding-umap/)

---

## **Acknowledgments**

- Thanks to the authors of the referenced resources for their valuable insights.
- All datasets are publicly available or sourced from academic research.

---

## **Contact**

For feedback or questions, open an issue in the repository or contact the maintainers.

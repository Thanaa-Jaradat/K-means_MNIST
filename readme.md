#  MNIST Clustering Analysis

### **Description**
This project explores clustering on the MNIST handwritten digits dataset using K-Means. It evaluates clustering performance, visualizes results, and experiments with different initialization methods and the Elbow Method to estimate the optimal number of clusters.

---

## 🚀 Overview
The project demonstrates unsupervised learning on image data with the following steps:

1. **Data Preparation:** Loads MNIST dataset and selects a subset for faster processing.  
2. **K-Means Clustering:** Performs clustering with standard k-means++ initialization, random initialization, and custom initialization using one image per true digit.  
3. **Evaluation Metrics:** Computes **Purity**, **Adjusted Rand Index (ARI)**, **Normalized Mutual Information (NMI)**, and **Accuracy after aligning cluster labels**.  
4. **Visualization:**  
   - Displays 10×10 grids of sample images per cluster (cluster ID / true digit).  
   - Shows corresponding ground truth grids for comparison.  
5. **Elbow Method:** Tests various K values to estimate the optimal number of clusters using WCSS and the KneeLocator method.

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:**  
  - `numpy`, `matplotlib`, `tensorflow` (data & preprocessing)  
  - `scikit-learn` (K-Means, metrics)  
  - `kneed` (KneeLocator for Elbow Method)  

---

## 📁 Project Structure
| Section | Description |
|---------|-------------|
| Data Loading | Loads MNIST dataset and flattens images for clustering |
| Clustering | Applies K-Means with different initializations (k-means++, random, custom centroids) |
| Evaluation | Calculates Purity, ARI, NMI, and Accuracy after alignment of clusters |
| Visualization | Plots cluster results and ground truth for visual comparison |
| Elbow Method | Tests K values (2–16) to ident

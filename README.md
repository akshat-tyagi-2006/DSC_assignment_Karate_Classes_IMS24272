# DSC-212 Assignment — Karate Club Community Structure and Centrality Exploration

## Recursive Modularity-Based Partitioning and Network Role Analysis

This repository contains an implementation of **recursive spectral modularity partitioning** applied to the classic Zachary Karate Club network, along with an examination of how important **centrality measures** behave as the graph undergoes successive splits.

## ✍️ Author

* **Name:** Akshat Tyagi  
* **Roll No.:** IMS24272  
* **Batch:** BS–MS 2024  
* **Instructor:** Dr. Saptarshi Bej  
* **Course:** DSC212 – *Mathematical Foundations to Data Science, Varsha 2025*

---

## 🔍 Project Overview

The major steps in this assignment include:

### 1. Graph Construction
   - The Karate Club social network is loaded using NetworkX.  
   - This dataset is widely used as a model example for community detection studies.

### 2. Recursive Spectral Community Detection
   - Newman's spectral modularity method is used to inspect the modularity matrix.  
   - Nodes are split according to the sign of the principal eigenvector components.  
   - The recursive division stops once further splitting would not improve modularity.

### 3. Centrality Metrics Tracked Across Splits
   - **Degree centrality**  
   - **Betweenness centrality**  
   - **Closeness centrality**  
   - **Clustering coefficient**  
   Tracking these at each stage shows how node roles evolve as groups separate.

### 4. Visual Outputs
   - The graph is displayed with a fixed layout to ensure meaningful comparison.  
   - Colors highlight community membership across iterations.  
   - Heatmaps illustrate how each centrality value changes for all nodes.

---

## 📁 Repository Contents

The repository includes:

1. A Jupyter Notebook with source code and intermediate outputs  
2. A PDF containing assignment instructions  
3. A PDF containing the analytical write-up  
4. Eight PNG images generated during execution  

---

## 🛠️ Dependencies

- Python 3.7 or newer  
- `networkx`  
- `numpy`  
- `matplotlib`

To install:
```bash
pip install networkx numpy matplotlib
```

---

## 📚 Reference Material

This implementation is based on:

* Newman's literature on modularity and spectral clustering  
* The original Karate Club dataset, a standard benchmark in social network analysis  

---

## 📎 Notes

This project is intended strictly for academic use and submission.  
It should not be redistributed or posted online without permission.  
Repository access is available until **04 January 2026**.

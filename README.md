# ColorCluster: K-Means Image Compression

**ColorCluster** demonstrates the power of **unsupervised learning** through K-Means clustering. It compresses images by grouping similar colors into clusters, replacing millions of individual pixels with a smaller palette of representative colors — all without using any labeled data.

---
As is was an assigment for one of my courses some plotting functions were already given for better visual representation. 

##  Overview

This project implements the **K-Means algorithm** from scratch to perform color compression and clustering visualization. By learning the underlying structure of data, it can summarize complex patterns — like the color distribution of an image — into a few simple, interpretable centroids.

The notebook walks through:

* Implementing the K-Means steps (`find_closest_centroids`, `compute_centroids`, and initialization)
* Visualizing how centroids move as the algorithm converges
* Applying K-Means to compress an image by reducing color diversity

---

## 🧠 How Unsupervised Learning Is Used

K-Means is an **unsupervised** algorithm — it doesn’t need target labels or predefined categories. Instead, it discovers natural groupings in the data by minimizing the distance between points and their assigned centroids. Here, each pixel’s RGB values are treated as data points, and the algorithm automatically groups similar colors together.

---

## 🌟 Why It’s Cool

What makes this project exciting is that it reveals structure hidden inside raw data — without any supervision. You can literally *see* the algorithm learning, as color regions tighten and converge. The final compressed image keeps the essential visual features but uses only a fraction of the original colors — proof of how unsupervised learning can simplify complexity in a meaningful way.



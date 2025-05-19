# 📦 SVD-Based Image Compression in R

This repository demonstrates how to perform **image compression using Singular Value Decomposition (SVD)** in **R**, based on the tutorial by me [Riki Matsumoto](https://medium.com/@rikimatsumoto/tutorial-singular-vector-decomposition-based-image-compression-in-r-4974d88d1407).

> **Goal**: Compress an image by retaining only the top `k` singular values from its matrix representation. This illustrates dimensionality reduction via SVD in image processing.

---

## 🧠 What You’ll Learn

- How grayscale images can be represented as numeric matrices.
- Basics of Singular Value Decomposition (SVD).
- How to reconstruct images using reduced-rank approximations.
- How compression quality varies by number of singular values retained.

---

## 🖼️ Original Article

📖 [Read the full tutorial here](https://medium.com/@rikimatsumoto/tutorial-singular-vector-decomposition-based-image-compression-in-r-4974d88d1407)

---


## 📦 Requirements

Install the following R packages:

```r
install.packages(c("jpeg", "ggplot2", "gridExtra"))
```



This project is for educational purposes. Use and modify freely under the MIT License.


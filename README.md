# Linear Algebra Projects

This repository contains my practical assignments for the **Linear Algebra** course at **Sharif University of Technology**.

The projects focus on applying linear algebra concepts to practical computational problems using **Python, NumPy, and Jupyter Notebooks**.

## Projects

### 1. PageRank Using the Power Iteration Method

The first project implements the **PageRank algorithm**, which ranks web pages according to the importance of their incoming links.

The project models the web as a directed graph and constructs a link matrix representing the relationships between pages. The PageRank vector is then computed iteratively using the **power iteration method** until the values converge.

The implementation covers several important linear algebra concepts:

* Vector and matrix representations of graphs
* Construction and normalization of a link matrix
* Stochastic matrices
* Eigenvectors and eigenvalues
* Power iteration
* Convergence of iterative numerical methods

The project also uses **NetworkX** to represent and visualize the graph structure.

### 2. Movie Recommendation Using SVD

The second project explores the use of **Singular Value Decomposition (SVD)** for discovering hidden patterns in user–movie rating data.

A user–movie matrix is constructed from the available ratings. SVD is then applied to decompose the matrix into lower-dimensional components, allowing the underlying relationships between users and movies to be analyzed.

The project demonstrates concepts including:

* Matrix factorization
* Singular Value Decomposition
* Dimensionality reduction
* Low-rank approximations
* User–item matrices
* Latent features and hidden patterns
* Reconstruction of matrix data

The resulting decomposition can be used to identify similarities between users and movies and form the basis of a simple recommendation system.

## Technologies

* **Python**
* **NumPy**
* **Matplotlib**
* **NetworkX**
* **Jupyter Notebook**

## Repository Structure

```text
Linear-Algebra-Projects/
│
├── README.md
│
├── Project-1/
│   └── PageRank.ipynb
│
└── Project-2/
    └── SVD-Recommender.ipynb
    └── compressed_output.jpg
    └── gray-nature.png
```

## Purpose

These projects were developed to gain practical experience with linear algebra by implementing mathematical concepts computationally rather than treating them only as theoretical tools.

They demonstrate how techniques such as **eigenvector computation, iterative methods, matrix factorization, and SVD** can be applied to real-world problems such as web-page ranking and recommendation systems.

## Author

**Reza Golbahar**

Sharif University of Technology

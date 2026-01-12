# Linear Algebra for Machine Learning

## Why this matters
Linear algebra is the language of machine learning.  
Every dataset is a matrix.  
Every model is a function that transforms vectors.  
Every neural network is a stack of linear transformations plus non-linearities.

This file documents how I am learning and understanding linear algebra from an ML and data perspective.

---

## Core Objects

### Vectors
A vector is an ordered list of numbers that represents a point or direction in space.

In machine learning, vectors usually represent:
- a data sample (e.g. one person, one image, one row of a dataset)
- a set of model parameters

Key operations:
- addition
- scalar multiplication
- dot product (measures similarity and projection)

---

### Matrices
A matrix is a rectangular grid of numbers.

In ML, matrices are used to:
- store datasets (rows = samples, columns = features)
- represent weights in models
- apply linear transformations to vectors

Important operations:
- matrix multiplication
- transpose
- inverse (when it exists)

---

## Systems of Linear Equations
Many ML problems can be written as systems of equations.

Example:
Finding model weights that best fit data  
→ becomes solving a system of equations  
→ which is done using matrix methods.

Gaussian elimination and matrix factorisation are tools for solving these efficiently.

---

## Key Ideas I’m Learning

| Concept | Why it matters in ML |
|--------|---------------------|
| Determinant | Tells whether a matrix transformation is reversible |
| Eigenvalues & Eigenvectors | Show the main directions a transformation stretches or compresses data |
| Vector spaces | Define what kinds of data representations are possible |
| Linear independence | Prevents redundant or useless features |
| Rank | Tells how much real information a matrix contains |

---

## How this shows up in AI
- Training a model = solving a big optimisation problem over matrices
- PCA and dimensionality reduction rely on eigenvectors
- Neural networks are stacked matrix multiplications
- Data preprocessing uses linear transformations

---

## Learning Sources
- Engineering Mathematics – Dexter J. Booth  
- Online ML and linear algebra resources (to be expanded)

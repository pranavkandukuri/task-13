# task-13
AI & ML Internship – Task 13
PCA – Dimensionality Reduction
1. Introduction

In machine learning, datasets often contain many features, which increases:

computation time

storage cost

risk of overfitting

Principal Component Analysis (PCA) is a dimensionality reduction technique that reduces the number of features while preserving maximum information (variance).

2. Tools Used

Python

Scikit-learn

Matplotlib

3. Dataset

Primary Dataset: MNIST Dataset

Alternative Dataset: Sklearn Digits Dataset

Each image is converted into a feature vector before applying PCA.

4. Problem PCA Solves

Reduces high-dimensional data

Removes redundant features

Improves model speed

Helps in visualization

Reduces overfitting

5. Data Preparation

Load digits / MNIST dataset

Flatten image data into feature vectors

Separate features (X) and labels (y)

6. Feature Scaling

Before applying PCA, features are scaled using StandardScaler.

Reason:
PCA is based on variance, and unscaled features can dominate principal components.

7. Applying PCA

PCA is applied with different numbers of components such as:

2

10

30

50

Each setting captures a different amount of variance.

8. Explained Variance

Explained Variance Ratio tells how much information (variance) is retained by each principal component.

High variance → more information

Low variance → less information

9. Cumulative Variance Plot

Cumulative variance is plotted

Helps decide the optimal number of components

Choose minimum components that retain maximum variance (e.g., 90–95%)

10. Dimensionality Reduction

Original dataset is transformed into lower-dimensional dataset

Number of features reduces significantly

Information loss is minimized

11. Model Training

Logistic Regression is trained on:

Original dataset

PCA-reduced dataset

12. Accuracy Comparison

Accuracy of original vs reduced dataset is compared

Slight accuracy drop is acceptable due to:

faster computation

reduced complexity

13. PCA 2D Visualization

PCA with 2 components is used

Scatter plot shows class separation

Helps visually understand data distribution

14. Deliverables

Explained variance plot

Reduced dataset

Accuracy comparison report

15. Final Outcome

Understood feature compression

Learned variance trade-off

Applied PCA practically before modeling

Improved understanding of dimensionality reduction

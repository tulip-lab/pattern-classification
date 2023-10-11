[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Pattern--Classification-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Nonparametric--Estimation-orange)](README.md)

# Nonparametric estimation

Nonparametric estimation is a statistical approach that does not rely on specific assumptions about the underlying probability distribution or functional form of the data. It aims to estimate unknown quantities directly from the data itself, using flexible and data-driven techniques.
    - `Histogram`: A histogram is a simple nonparametric estimation technique that divides the data into equal-width bins or intervals and counts the number of data points falling into each bin. It provides an estimate of the probability distribution by approximating the underlying density function. The height of each bin represents the frequency or probability density of the data within that interval.
    - `Parzen Window`: The Parzen window, or kernel density estimation, is a nonparametric technique that estimates the probability density function of a random variable by placing a window or kernel function on each data point and summing them up. The kernel function determines the shape and width of the window. The Parzen window method provides a smooth estimate of the density function and allows for flexibility in capturing complex data patterns.
    - `K-Nearest Neighbors` (KNN): KNN is a nonparametric algorithm used for both classification and regression tasks. In KNN, the estimated value of a target variable for a new data point is obtained by averaging or voting the values of its k nearest neighbors in the feature space. KNN does not assume any specific functional form and can capture nonlinear relationships in the data. The choice of k affects the smoothness of the estimate, with larger k resulting in smoother estimates but potentially losing fine-grained details.

These nonparametric estimation techniques, including histograms, Parzen window, and KNN, provide flexible and data-driven approaches to estimate probability distributions, density functions, or regression functions directly from the data. They are particularly useful when the underlying distribution or relationship is unknown, complex, or difficult to specify parametrically. These techniques have applications in various fields, including data analysis, pattern recognition, machine learning, and exploratory data analysis.

## Lecture Slides Handouts

- [Lecture A: Nonparametric estimation (1)](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S05A.pdf)
- [Lecture B: Nonparametric estimation (2)](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S05B.pdf) 



# Gaussian Mixture Models

This repository explores Gaussian distributions and Gaussian Mixture Models (GMMs), with a focus on how they work, how they are trained, and where they can be applied in real-world data analysis problems.

A Gaussian Mixture Model is a probabilistic model that represents a dataset as a combination of multiple Gaussian distributions. Each component has its own mean and covariance, and the overall distribution is a weighted sum of these components. This makes GMMs useful for clustering, density estimation, and identifying unusual observations.

## Why this repository exists

The goal of this project is to provide a clear, practical understanding of GMMs and their relationship to statistical learning. The code and examples are intended to help illustrate:

- how Gaussian distributions are parameterized
- how mixture models combine multiple distributions
- how the Expectation-Maximization (EM) algorithm fits the model
- how GMMs can be used for clustering and anomaly detection

## Key concepts

### Gaussian distributions
A Gaussian distribution is defined by a mean and variance (or covariance in multi-dimensional settings). It describes data that tends to cluster around a central value with some variability.

### Mixture models
A mixture model assumes that the data come from multiple underlying subpopulations, each represented by its own Gaussian distribution. Instead of assuming one single distribution for all observations, the model allows several local patterns to coexist.

### EM algorithm
The EM algorithm is commonly used to estimate the parameters of a GMM. It alternates between:

1. assigning data points to clusters probabilistically
2. updating the cluster parameters based on those assignments
3. repeating until convergence

## Applications

Gaussian Mixture Models are useful in a wide range of scenarios, including:

- clustering data with overlapping groups
- modeling multimodal distributions
- detecting anomalies by identifying low-density regions
- segmenting data in image processing and signal analysis
- constructing flexible generative models for unsupervised learning

## Repository focus

This project is centered on understanding the theory and intuition behind GMMs, especially in the context of anomaly detection. It provides a foundation for exploring how statistical models can be used to describe complex data distributions without requiring labels for every observation.

## Typical workflow

A standard GMM workflow usually involves:

- preparing the dataset
- choosing the number of mixture components
- initializing the parameters
- fitting the model with EM
- evaluating the fit and interpreting the resulting clusters
- using the learned density model to detect anomalies or group similar observations

## Summary

Gaussian Mixture Models are a powerful and interpretable tool in machine learning and statistical modeling. They are especially valuable when data is not well described by a single Gaussian distribution and when structure may exist in multiple overlapping groups. This repository is intended as an educational and exploratory resource for learning those ideas in practice.

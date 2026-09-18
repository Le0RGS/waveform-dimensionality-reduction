# Waveform Feature Extraction and Dimensionality Reduction

## Overview

This project investigates feature extraction and dimensionality reduction for music waveform time-series data.

The aim is to transform high-dimensional waveform data into a lower-dimensional representation while retaining information useful for distinguishing between different types of music.

## Method

The project follows two main stages:

1. **Feature extraction** — extracting informative features from the original music waveform time-series data.
2. **Dimensionality reduction** — reducing the resulting feature space using multiple dimensionality reduction techniques.

The dimensionality reduction methods investigated include:

- Principal Component Analysis (PCA)
- Autoencoders
- Locally Linear Embedding (LLE)

The resulting representations are analysed and compared using visualisation and classification performance.

## Results

The different dimensionality reduction methods produce lower-dimensional representations of the extracted music features while retaining useful information from the original data.

The project also investigates the effect of dimensionality reduction on K-nearest-neighbour (KNN) classification, including the computational cost of classification.

## Report

The full mathematical methodology, results and discussion are available in the project report:

[Project Report](waveform-dimensionality-reduction-report.pdf)

# Resting-State fMRI Brain Connectivity Analysis

This project explores resting-state fMRI brain activity using dimensionality reduction, clustering, and dynamic brain state analysis techniques.

The objective was to analyze functional connectivity patterns across 90 subjects and 100 brain regions (ROIs) in order to identify recurring brain activation structures and investigate differences across individuals.

The project was completed as part of a multivariate statistics and machine learning research project.

## Full Interactive Report

👉 https://rieille9.github.io/fmri-brain-connectivity-analysis/
---

## Project Objectives

The project focused on several key questions:

* How can high-dimensional fMRI data be represented efficiently?
* Can functional connectivity patterns reveal meaningful brain structures?
* Are there recurring dynamic brain activation states?
* Can subjects or brain regions be grouped using unsupervised learning techniques?

---

## Dataset

The dataset contains resting-state fMRI recordings for:

* 90 subjects
* 100 brain regions (ROIs)
* ~1000 time points per subject

Each subject is represented by a matrix of brain activation signals over time.

Due to dataset restrictions, the raw data is not publicly available in this repository.

---

## Methods Used

### Exploratory Data Analysis

* Time-series visualization
* Distribution analysis
* Stationarity analysis
* Normality testing (Shapiro-Wilk)

### Dimensionality Reduction

* Principal Component Analysis (PCA)
* Covariance-based PCA
* Correlation-based PCA

### Functional Connectivity Analysis

* ROI correlation matrices
* Connectivity feature extraction
* Brain network analysis

### Time-Series Modeling

* VAR(1) modeling
* Dynamic interaction analysis between ROIs

### Clustering

* K-means clustering
* Hierarchical clustering
* Subject clustering
* ROI clustering

### Dynamic Brain State Analysis

* Co-Activation Patterns (CAPs)
* PCC seed-based analysis
* Temporal fraction analysis
* Frequency of alternation
* Permutation testing

---

## Technologies Used

* R
* tidyverse
* ggplot2
* pheatmap
* GGally
* ggseg
* Statistical modeling
* Multivariate analysis

---

## Key Results

* Identified dominant functional connectivity structures using PCA
* Detected meaningful ROI clusters linked to known brain networks
* Extracted recurring co-activation patterns (CAPs)
* Analyzed temporal dynamics of resting-state brain activity
* Explored demographic differences through permutation testing

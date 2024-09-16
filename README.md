![Machine Learning Project](./MLProject.webp)

---

# Machine Learning Project

This repository contains the work and exercises for a Machine Learning course, focusing on analyzing health-related data to predict smoking habits using various machine learning models.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Part A: Data Analysis and Preparation](#part-a-data-analysis-and-preparation)
- [Part B: Machine Learning Models](#part-b-machine-learning-models)
  - [Decision Tree](#decision-tree)
  - [Neural Networks](#neural-networks)
  - [K-Means Clustering](#k-means-clustering)
  - [Hierarchical Clustering](#hierarchical-clustering)
- [Results](#results)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Contact](#contact)

## Project Overview

This project focuses on exploring a health dataset to predict whether individuals are smokers based on various biological and personal characteristics. The project is split into two parts: data analysis and preparation (Part A) and the application of different machine learning models (Part B).

## Project Structure

- **Part A:** Data understanding, exploratory analysis, and preparation for modeling.
- **Part B:** Building and evaluating different machine learning models to predict smoking.

## Part A: Data Analysis and Preparation

The first part of the project involves an in-depth exploration of the dataset, which includes personal information and basic biological signals. Steps in this phase include:

1. **Defining the Problem:** Predicting smoking habits using health indicators.
2. **Data Understanding:** Detailed analysis of the data's features, including demographics, health measurements, and lifestyle-related attributes.
3. **Exploratory Analysis:** Visualizing data distributions, investigating correlations, and identifying expected and unexpected relationships between features.
4. **Data Cleaning:** Handling missing values, outlier treatment, and discretization of continuous variables.

## Part B: Machine Learning Models

The second part of the project involves the implementation and evaluation of several machine learning models using the prepared data from Part A. The models used include:

### Decision Tree

- **Objective:** Build a decision tree model to classify individuals as smokers or non-smokers.
- **Key Steps:**
  - Training the decision tree with 80% of the data.
  - Hyperparameter tuning using grid search to maximize accuracy.
  - Evaluating the model's performance on the test set.
- **Results:** The best model achieved an accuracy of around 76.89% on the test set.

### Neural Networks

- **Objective:** Use a neural network model to predict smoking habits.
- **Key Steps:**
  - Normalizing the data using a standard scaler.
  - Implementing the neural network with different configurations and tuning hyperparameters.
  - Using grid search to find the optimal parameters.
- **Results:** The neural network achieved an accuracy of 78.36% on the test set after tuning.

### K-Means Clustering

- **Objective:** Apply K-Means clustering to explore potential groupings within the dataset.
- **Key Steps:**
  - Using the K-Means algorithm to identify clusters based on the data's features.
  - Evaluating the clusters using inertia, silhouette score, and Davies-Bouldin index.
- **Results:** Analyzed the clusters to find groupings of individuals with similar characteristics.

### Hierarchical Clustering

- **Objective:** Explore the data using hierarchical clustering.
- **Key Steps:**
  - Applying the hierarchical clustering algorithm to the dataset.
  - Comparing the results with those from K-Means clustering.
- **Results:** Chose the number of clusters based on various evaluation metrics.

## Results

After evaluating all models, the neural network was selected as the final model due to its higher accuracy in predicting smoking habits compared to other models.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/RoiAzrai/Machine-Learning-Project.git
    cd Machine-Learning-Project
    ```

2. The project is split into parts; each part contains Jupyter notebooks that can be run for different analyses and model building.
3. Open the relevant notebook in Jupyter to explore the data analysis (Part A) or the model implementations (Part B).

## Contact

For any questions or further information, please contact the author:

- **Name:** Roi Azrai
- **GitHub:** [RoiAzrai](https://github.com/RoiAzrai)

---

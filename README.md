# NEO Hazard Analysis

A machine learning project that predicts whether a **Near-Earth Object (NEO)** is potentially hazardous using orbital characteristics obtained from NASA's NeoWs dataset. The project compares multiple classification algorithms and includes a real-time prediction pipeline for analyzing newly discovered asteroids.

## Overview

Near-Earth Objects (NEOs) are asteroids and comets whose orbits bring them close to Earth. While most pose no threat, a small percentage are classified as **Potentially Hazardous Asteroids (PHAs)** based on their orbit and proximity.

This project leverages machine learning to classify NEOs as hazardous or non-hazardous using orbital parameters and historical observations.

## Features

* Hazardous vs Non-Hazardous NEO Classification
* Dataset containing **35,000+ asteroid records**
* Feature engineering using **16 orbital features**
* Comparison of multiple machine learning models
* Real-time prediction pipeline using NASA NeoWs data
* Performance evaluation using ROC-AUC and confusion matrices
* End-to-end machine learning workflow

## Dataset

### Source

NASA NeoWs (Near Earth Object Web Service)

### Dataset Statistics

* 35,000+ asteroid records
* 16 orbital and physical features
* Binary classification target (Hazardous / Non-Hazardous)

### Features Used

* Absolute Magnitude
* Estimated Diameter
* Relative Velocity
* Miss Distance
* Eccentricity
* Semi-Major Axis
* Inclination
* Perihelion Distance
* Aphelion Distance
* Orbital Period
* Earth MOID
* Additional orbital parameters

## Machine Learning Pipeline

### Data Preprocessing

* Missing value handling
* Feature selection
* Numerical scaling
* Train-test split
* Class imbalance handling

### Models Evaluated

#### Logistic Regression

A fast and interpretable baseline model for hazard prediction.

#### Support Vector Machine (SVM)

Used to capture complex decision boundaries within orbital feature space.

#### Random Forest

An ensemble-based approach capable of modeling non-linear relationships and feature interactions.

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

## Results

### Key Achievements

* Processed **35,000+ Near-Earth Object records**
* Trained on **16 orbital features**
* Compared Logistic Regression, SVM, and Random Forest models
* Built a real-time hazard prediction pipeline
* Integrated live asteroid data from NASA APIs
* Evaluated model performance using ROC-AUC and confusion matrices

## Technologies Used

### Machine Learning

* Python
* Scikit-learn
* Pandas
* NumPy

### Visualization

* Matplotlib

### Data Source

* NASA NeoWs API

## Workflow

1. Collect asteroid data from NASA NeoWs.
2. Preprocess and engineer orbital features.
3. Train multiple classification models.
4. Evaluate performance using standard ML metrics.
5. Deploy a real-time prediction pipeline.
6. Analyze newly discovered asteroids for potential hazards.

## Learning Outcomes

Through this project, I gained experience in:

* Supervised Machine Learning
* Classification Problems
* Feature Engineering
* Model Evaluation
* Scientific Data Analysis
* API Integration
* End-to-End ML Pipelines

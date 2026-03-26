VinGuard - ML-Based Wine Quality Classifier

This project implements a supervised machine learning system to classify wine quality. It analyzes physicochemical metadata in real time to distinguish between high-quality premium wines and standard varieties.

Machine Learning Quality Classification in Python

Overview
This project demonstrates how machine learning can be used in the food and beverage industry to automate quality assurance. It utilizes K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) classifiers to analyze wine features and predict whether a sample meets the "Good Quality" threshold (Quality ≥ 7).

The system includes a data visualization suite that displays confusion matrices, feature correlations, and model performance metrics.

Features

Dual-Model Classification: Compares KNN and SVM performance for optimal accuracy.

Automated Data Preprocessing: Includes feature scaling and handling of multi-dimensional chemical data.

Quality Thresholding: Binary classification logic to identify premium wine samples.

Performance Analytics: Generates heatmaps and confusion matrices for model validation.

Feature Engineering: Extracts critical acidity and alcohol metrics for classification.

Robust Evaluation: Achieves up to 90% accuracy with optimized SVM hyperplanes.

How It Works

The system loads wine chemical data from a structured CSV dataset.

Data is cleaned and labeled, defining "Good Quality" as any wine scoring 7 or higher.

Features are normalized using a standard scaler to ensure geometric model accuracy.

The KNN model classifies samples based on their proximity to known quality clusters.

The SVM model identifies the optimal hyperplane to separate quality classes.

Accuracy and performance logs are generated to compare the two approaches.

Results are visualized through Seaborn heatmaps to show true vs. false positives.

Prerequisites

Python 3.x

Required libraries: pandas, scikit-learn, matplotlib, seaborn

# VinAnalytics - Integrated Machine Learning for Wine Analysis

This project implements a multi-model machine learning system to analyze wine quality and composition. It uses both supervised and unsupervised learning to classify quality levels, predict chemical properties, and discover hidden patterns in physicochemical data.

Machine Learning Quality Analysis in Python

## Overview
This project demonstrates how various machine learning paradigms can be integrated to provide a 360-degree view of laboratory data. It uses KNN and SVM for classification, Linear Regression for continuous value forecasting, and K-Means clustering for grouping similar wine profiles.

The system includes a full data processing pipeline and a performance evaluation suite that tracks accuracy, Mean Squared Error (MSE), and Silhouette scores.

## Features
- **Multi-Model Classification:** Uses KNN and SVM to identify high-quality wine samples
- **Continuous Property Prediction:** Implements Linear Regression to forecast alcohol content
- **Unsupervised Data Clustering:** Uses K-Means to discover natural groupings in wine chemistry
- **Advanced Data Preprocessing:** Includes feature scaling and automated handling of the WineQT dataset
- **Comprehensive Metrics:** Tracks performance via accuracy scores, MSE, and Silhouette validation
- **Statistical Visualization:** Generates confusion matrices and heatmaps for data-driven insights

## How It Works
- The system ingests chemical telemetry from a wine dataset using Pandas
- Data is normalized using a StandardScaler to ensure consistency across different chemical units
- Supervised models (KNN & SVM) are trained to classify wine as "Good" or "Bad" quality
- A regression engine analyzes the relationship between features to predict continuous variables
- The K-Means algorithm identifies geometric clusters to group similar wine varieties
- Silhouette scores are calculated to validate the structural integrity of the clusters
- The final output provides a comparison of model performance and statistical visualizations

## Prerequisites
- Python 3.x
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

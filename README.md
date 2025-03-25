# Spam Email Classification and Anomaly Detection

## Overview
This project classifies emails as spam or not spam using the Spambase dataset (`spambase_csv.csv`). It employs Logistic Regression, Random Forest, SVM, and Neural Network models, analyzes feature importance, performs K-Means clustering with PCA, and uses an autoencoder for anomaly detection. Comprehensive visualizations provide insights into model performance and data patterns.

## Functionality
1. **Preprocessing**:
   - Loads `spambase_csv.csv`, scales 57 features with `StandardScaler`.
   - Splits data (80% train, 20% test).

2. **Classification**:
   - Trains Logistic Regression, Random Forest, SVM, and Neural Network (MLP).
   - Evaluates with accuracy, precision, recall, and F1-score.

3. **Feature Importance**:
   - Uses Random Forest to rank feature importance.

4. **Clustering**:
   - Applies PCA (2D) and K-Means (2 clusters) for visualization.

5. **Anomaly Detection**:
   - Trains an autoencoder to detect anomalies via reconstruction error.

6. **Visualization**:
   - Model accuracy bar plot, feature importance, PCA clustering, autoencoder loss, and error distribution.

## Frameworks and Libraries
- **Python**: Core.
- **Pandas**: Data handling (`pd`).
- **NumPy**: Numerical ops (`np`).
- **Matplotlib**: Plots (`plt`).
- **Seaborn**: Visualizations (`sns`).
- **Scikit-learn**: Modeling, clustering (`RandomForestClassifier`, etc.).
- **TensorFlow/Keras**: Autoencoder (`keras`).

## Dataset
- Source: `spambase_csv.csv` (UCI Spambase).
- Rows: 4,601 (3,680 train, 921 test).
- Columns: 58 (57 features + `class`).
- Features: Word/char frequencies, capital run lengths.
- Target: `class` (0 = not spam, 1 = spam).

## Key Features
- **Multi-Model**: Compares four classifiers for spam detection.
- **Insights**: Identifies top spam predictors.
- **Clustering**: Visualizes data in 2D PCA space.
- **Anomaly Detection**: Flags unusual emails with autoencoder.
- **Visuals**: Detailed plots for analysis.

## Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow



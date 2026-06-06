 🌸 Iris Flower Classification Dashboard

An interactive machine learning dashboard that classifies Iris flower species using morphological measurements and visualizes the complete workflow of data exploration, model training, evaluation, and prediction. The project demonstrates how supervised learning algorithms can accurately distinguish between Iris Setosa, Versicolor, and Virginica using flower characteristics.



📊 Overview

This project uses the famous Iris Dataset to train and evaluate classification models, including Logistic Regression and Decision Tree classifiers. The dashboard provides interactive visualizations, confusion matrix analysis, feature importance insights, and a live species prediction tool.

Users can:

* Explore feature distributions across species
* Visualize feature correlations and class separation
* Compare machine learning model performance
* Analyze confusion matrices and misclassifications
* Predict species from custom flower measurements



 ✨ Features

 📈 Exploratory Data Analysis Dashboard

* Dataset statistics
* Species distribution analysis
* Feature histograms
* Statistical summaries
* Box plot visualizations
* Missing value analysis

 📉 Feature Relationship Analysis

* Pairwise scatter plots
* Correlation visualization
* Species clustering patterns
* Morphological comparisons

 🤖 Model Performance Comparison

* Logistic Regression Evaluation
* Decision Tree Evaluation
* Accuracy Comparison
* Precision, Recall, and F1 Score
* Best Model Recommendation

 🔍 Confusion Matrix Analysis

Visual representation of model predictions showing:

* Correct classifications
* Misclassified samples
* Species overlap regions
* Classification boundaries

 🌸 Live Species Predictor

Enter flower measurements and instantly receive:

* Predicted Species
* Confidence Score
* Class Probabilities
* Species Comparison



 🧠 Machine Learning Pipeline

 Dataset

Iris Dataset

* 150 Flower Samples
* 4 Features
* 3 Species

 Data Preprocessing

* Data validation
* Feature analysis
* Train-Test Split (80/20)
* Feature scaling (if applicable)

 Models

 Logistic Regression

A linear classification algorithm used to create decision boundaries between species.

 Decision Tree Classifier

A tree-based model that classifies flowers based on feature splits.

 Evaluation Metrics

| Metric    | Logistic Regression | Decision Tree |
| --------- | ------------------- | ------------- |
| Accuracy  | 97.3%               | 96.0%         |
| Precision | 97.4%               | 96.2%         |
| Recall    | 97.3%               | 96.0%         |
| F1 Score  | 97.3%               | 96.0%         |

🏆 Best Performing Model: Logistic Regression



 📋 Features Used

| Feature      | Description              |
| ------------ | ------------------------ |
| Sepal Length | Length of the sepal (cm) |
| Sepal Width  | Width of the sepal (cm)  |
| Petal Length | Length of the petal (cm) |
| Petal Width  | Width of the petal (cm)  |

 Target Classes

* Iris Setosa
* Iris Versicolor
* Iris Virginica


 🛠️ Technologies Used

 Machine Learning

* Python
* Scikit-learn
* NumPy
* Pandas

 Frontend

* HTML5
* CSS3
* JavaScript

 Visualization

* Chart.js



📸 Dashboard Preview

Morphology Dashboard

* Feature Distributions
* Histograms
* Box Plots
* Species Statistics

 Correlation Analysis

* Scatter Plot Matrix
* Feature Relationships
* Species Clustering

 Model Evaluation

* Accuracy Comparison
* Performance Metrics
* Confusion Matrices
* Feature Importance

 Live Predictor

Users can adjust flower measurements and generate species predictions in real time.



 🚀 Getting Started

 Clone the Repository

```bash
git clone https://github.com/yourusername/iris-flower-classification-dashboard.git

cd iris-flower-classification-dashboard
```

 Open the Dashboard

Simply open:

```text
iris_botanical_dashboard.html
```

in your browser.

No additional setup is required.



📊 Model Interpretation

Most Important Features

✅ Petal Width
✅ Petal Length

These features provide the clearest separation between flower species and contribute most to classification accuracy.

Less Influential Features

* Sepal Length
* Sepal Width

While useful, they show greater overlap among species.

### Misclassification Analysis

Most classification errors occur between:

* Versicolor
* Virginica

These species share similar petal dimensions, making them harder to distinguish than Setosa.



📈 Sample Results

| Metric                       | Value               |
| ---------------------------- | ------------------- |
| Dataset Size                 | 150 Samples         |
| Features                     | 4                   |
| Species                      | 3                   |
| Missing Values               | 0                   |
| Logistic Regression Accuracy | 97.3%               |
| Decision Tree Accuracy       | 96.0%               |
| Best Model                   | Logistic Regression |



 🎯 Learning Objectives

This project demonstrates:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering Concepts
* Classification Algorithms
* Model Evaluation
* Confusion Matrix Interpretation
* Interactive Machine Learning Dashboards
* Real-Time Prediction Systems



🔮 Future Improvements

* Add Random Forest Classifier
* Add Support Vector Machine (SVM)
* Hyperparameter Tuning
* Cross-Validation Analysis
* Feature Selection Techniques
* Model Explainability with SHAP
* Flask/Web Deployment
* Real Dataset Upload Support


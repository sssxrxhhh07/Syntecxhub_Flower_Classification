🌸 Iris Flower Classification
An end-to-end Machine Learning project that classifies Iris flower species using the famous Iris dataset. The project includes Exploratory Data Analysis (EDA), data visualization, model training, performance evaluation, confusion matrix analysis, and an interactive prediction system for classifying new flower samples.
📌 Project Overview
The Iris dataset is one of the most widely used datasets in Machine Learning. It contains measurements of iris flowers from three species:
   Iris Setosa
   Iris Versicolor
   Iris Virginica
Using sepal and petal measurements, this project trains classification models to accurately predict the species of a flower.
🎯 Objectives
   Perform Exploratory Data Analysis (EDA) on the Iris dataset.
   Visualize relationships between flower features.
   Train and compare multiple classification models.
   Evaluate model performance using accuracy scores.
   Generate and analyze confusion matrices.
   Predict flower species for new user-provided inputs.
   Create an interactive dashboard/CLI prediction tool.
📊 Dataset Information
   Feature	Description
    Sepal Length	Length of the sepal (cm)
    Sepal Width	Width of the sepal (cm)
    Petal Length	Length of the petal (cm)
    Petal Width	Width of the petal (cm)
   Target Classes
    Setosa
    Versicolor
    Virginica
   Dataset Size:
    150 samples
    4 features
    3 classes
🔍 Exploratory Data Analysis
   The project includes:
     Distribution analysis of all features
     Histograms and statistical summaries
     Feature correlation analysis
     Pairwise scatter plots
     Species-wise comparisons
     Feature importance visualization
   Key Findings
     Petal Length and Petal Width are the most informative features.
     Setosa is easily separable from the other species.
     Most classification errors occur between Versicolor and Virginica due to overlapping feature values.
🤖 Machine Learning Models
   Logistic Regression
   Accuracy: 97.3%
   Precision: 97.4%
   Recall: 97.3%
   F1 Score: 97.3%
   Decision Tree
   Accuracy: 96.0%
   Precision: 96.2%
   Recall: 96.0%
   F1 Score: 96.0%
   K-Nearest Neighbors (Optional Comparison)
   Accuracy: 96.7%
   Precision: 96.8%
   Recall: 96.7%
   F1 Score: 96.7%
🏆 Best Performing Model: Logistic Regression
   📈 Confusion Matrix Analysis
   The confusion matrix reveals:
   Setosa is classified perfectly.
   A few Versicolor samples are misclassified as Virginica.
   Virginica and Versicolor exhibit slight overlap due to similar petal dimensions.
   This analysis helps understand model weaknesses and class boundaries.
🖥️ Interactive Predictor
Users can input:
   Sepal Length
   Sepal Width
   Petal Length
   Petal Width
   The system predicts:
   Flower Species
   Prediction Confidence
   Class Probabilities
Example:
   Enter Sepal Length: 5.1
   Enter Sepal Width: 3.5
   Enter Petal Length: 1.4
   Enter Petal Width: 0.2
   Predicted Species: Setosa
   Confidence: 99.8%
🛠️ Technologies Used
   Python
   NumPy
   Pandas
   Matplotlib
   Seaborn
   Scikit-Learn
   HTML/CSS/JavaScript (Dashboard)
   Chart.js
📂 Project Structure
iris-flower-classification/
│
├── data/
│   └── iris.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── scripts/
│   ├── train.py
│   ├── predict.py
│   └── evaluate.py
│
├── dashboard/
│   └── iris_botanical_dashboard.html
│
├── requirements.txt
├── README.md
└── LICENSE
🚀 How to Run
  Clone Repository
   git clone https://github.com/yourusername/iris-flower-classification.git
   cd iris-flower-classification
  Install Dependencies
   pip install -r requirements.txt
  Train Model
   python train.py
  Run Prediction Script
   python predict.py
  Open Dashboard
   open iris_botanical_dashboard.html
or simply open the HTML file in your browser.
📸 Features
   ✅ Exploratory Data Analysis
   ✅ Data Visualization
   ✅ Logistic Regression Model
   ✅ Decision Tree Model
   ✅ Confusion Matrix Analysis
   ✅ Interactive Prediction Tool
   ✅ Beautiful Botanical Dashboard
   ✅ Real-time Species Prediction
📚 Learning Outcomes
This project demonstrates:
Data preprocessing
   Exploratory Data Analysis
   Classification algorithms
   Model evaluation
   Feature importance interpretation
   Interactive machine learning applications
   Scientific data visualization

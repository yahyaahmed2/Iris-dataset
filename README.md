🧠 Iris Flower Classification using ML
This project is a machine learning workflow built on the famous Iris dataset. The goal is to classify iris flowers into three species: Setosa, Versicolor, and Virginica based on the features of their petals and sepals.

📁 Dataset
Source: Kaggle (https://www.kaggle.com/datasets/uciml/iris)

Features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species (Target variable)

📊 Exploratory Data Analysis (EDA)
Checked for missing values and duplicates

Summary statistics (df.describe())

Histograms and boxplots for feature distribution

Correlation heatmap

🛠️ Preprocessing
Encoded target labels with LabelEncoder
Standardized features using StandardScaler
Dropped irrelevant columns like Id

🤖 Models Trained
1. Logistic Regression
Used as a baseline classifier

Achieved 100% accuracy

2. K-Nearest Neighbors (KNN)
Trained with k=3
Also achieved 100% accuracy
Visualized decision boundaries using mlxtend

3. Decision Tree
Used sklearn.tree.DecisionTreeClassifier
Evaluated with accuracy and classification report

📈 Results
Model	Accuracy
Logistic Regression	100%
KNN (k=3)	100%
Decision Tree	~100%

Note: The Iris dataset is small and well-separated, so it's common for basic models to achieve perfect accuracy.

📚 Libraries Used
-pandas, numpy
-matplotlib, seaborn
-scikit-learn
-mlxtend (for visualization)

📌 How to Run
-Clone the repo or copy the notebook
-Install requirements (if needed)
-Run cells in order using Jupyter Notebook or Google Colab

🧠 What I Learned
-Hands-on EDA and feature exploration
-Data preprocessing pipeline
-Training and evaluating ML models
-Visualizing decision boundaries

🔗 Future Improvements
-Use cross-validation for better generalization
-Try ensemble methods (Random Forest, Gradient Boosting)
-Deploy using FastAPI


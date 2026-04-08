Breast Cancer Tumor Prediction 🎗️
This project utilizes Machine Learning to classify breast cancer tumors as either Malignant (cancerous) or Benign (non-cancerous). By analyzing various features of cell nuclei, the model provides a highly accurate diagnostic tool to assist medical professionals.

📊 Project Overview
Early detection is critical in breast cancer treatment. This project implements a data-driven approach to automate the classification process using the Wisconsin Breast Cancer (Diagnostic) Dataset.

🛠️ Tech Stack
Language: Python

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn

Environment: Jupyter Notebook / Google Colab

🧬 Dataset Features
The model analyzes 30 different features extracted from digitized images of fine needle aspirates (FNA) of breast masses, including:

Radius (mean of distances from center to points on the perimeter)

Texture (standard deviation of gray-scale values)

Perimeter

Area

Smoothness (local variation in radius lengths)

🚀 Workflow
Exploratory Data Analysis (EDA): Visualizing data distribution and feature correlations.

Data Cleaning: Handling missing values and encoding categorical labels (M=1, B=0).

Feature Scaling: Standardizing data to improve model convergence.

Model Training: Evaluating multiple algorithms including Logistic Regression and Random Forest.

Evaluation: Measuring performance using Accuracy, Precision, Recall, and the Confusion Matrix.

💻 How to Use
Clone the repo:

Bash
git clone https://github.com/kripasekar187-bit/BreastCancerTumorPrediction.git
Install dependencies:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
Run the analysis:
Open the .ipynb file in Jupyter Notebook or run the Python script.

📈 Results
The model achieves high accuracy on the test set, demonstrating the effectiveness of machine learning in identifying patterns within clinical data.

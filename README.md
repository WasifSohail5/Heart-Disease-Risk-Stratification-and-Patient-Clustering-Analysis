# 🫀 Heart Disease Risk Stratification & Patient Clustering

Welcome to a real-world data science and machine learning project focused on improving healthcare outcomes! This repository provides a full workflow for predicting heart disease risk and uncovering patient subgroups using the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease).

---

## 🚀 Project Goals

1. **Risk Stratification:**  
   Build robust machine learning models to classify patients as high or low risk for heart disease.
2. **Patient Clustering:**  
   Discover clinically meaningful patient clusters to inform personalized treatment strategies.

---

## 📦 Dataset

- **Source:** UCI Machine Learning Repository  
- **Features:** Age, sex, blood pressure, cholesterol, ECG results, and more  
- **Target:** Heart disease diagnosis (converted to binary: 0 = no disease, 1 = disease)

---

## 🛠️ Workflow Overview

### 1. Data Preparation & Exploration
- Handle missing values and outliers
- Feature scaling and normalization
- Visual exploratory data analysis (EDA)

### 2. Supervised Learning (Classification)
- Algorithms: Decision Tree, Logistic Regression, SVM, Neural Network, Random Forest, Gradient Boosting
- Metrics: Accuracy, Precision, Recall, F1-Score, Cross-Validation
- Model comparison and selection

### 3. Unsupervised Learning (Clustering)
- Optimal number of clusters selected via the Elbow Method  
  ![Elbow Method For Optimal k](elbow_method.png)
- K-Means clustering (Optimal **k = 4**)
- Visualization with PCA

### 4. Insights & Recommendations
- Feature importance analysis
- Cluster profiling: disease prevalence, top risk factors, actionable group insights
- Clinical suggestions for resource allocation and treatment focus

---

## 📊 Key Visualizations

- Feature distributions & correlations
- Confusion matrices for each model
- Model performance comparison
- PCA cluster map
- Cluster-wise heart disease prevalence

All visualizations are automatically saved as PNG files for easy reporting and presentation.

---

## 🏁 Getting Started

### 1. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn ucimlrepo
```

### 2. Run the main analysis

```bash
python heart_disease_full_solution.py
```

### 3. Review Results

- Performance metrics and insights will be displayed in the terminal.
- Visualizations will be saved as `.png` files.
- Use the findings to inform medical decisions or academic research.

---

## 🧩 Project Structure

```
heart_disease_full_solution.py
feature_distributions.png
feature_correlations.png
class_distribution.png
model_comparison.png
confusion_matrix_<model>.png
elbow_method.png
cluster_visualization.png
cluster_disease_analysis.png
feature_importance.png
README.md
```

---

## 💡 Why This Project Matters

Heart disease remains a leading cause of mortality worldwide. By combining supervised and unsupervised learning, this project helps:

- Detect high-risk individuals early
- Personalize interventions and follow-ups
- Allocate healthcare resources more effectively
- Foster data-driven clinical decision-making

---

## 👨‍💻 Author

- **Wasif-Sohail55**  
  [GitHub Profile](https://github.com/Wasif-Sohail55)

---

## 📄 License

For educational and research purposes. Dataset provided by [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php).

---

**Ready to make an impact?**  
Clone, run, and explore — contribute your findings or fork for your next healthcare data science adventure!

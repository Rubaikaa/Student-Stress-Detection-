# Student-Stress-Detection
# 🎓 Predictive Modeling and Clustering of Student Stress Using Machine Learning

This project leverages machine learning techniques to analyze, predict, and cluster stress levels in students based on various psychological, environmental, and academic factors. The primary aim is to assist educators, counselors, and institutions in identifying at-risk students and recommending proactive interventions.

## 📊 Dataset

**Source**: [Kaggle - Student Stress Factors: A Comprehensive Analysis](https://www.kaggle.com/datasets/whenamancodes/student-stress-factors-a-comprehensive-analysis)

- Records: 1100 students
- Features: 20 predictors (e.g., anxiety level, self-esteem, sleep quality, bullying)
- Target: `stress_level` (ordinal classes)

## 🧠 Project Objectives

- Identify key features influencing student stress.
- Predict student stress levels using supervised learning models.
- Cluster students based on stress-related attributes.
- Apply dimensionality reduction (PCA) for visualization.
- Generate insights and practical recommendations for stress management.

## 🧰 Tools & Libraries

- Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly
- Scikit-learn (RandomForestClassifier, KMeans, PCA)
- Google Colab (for execution)
- Report generated using Jupyter and exported as PDF

## 🔍 Key Steps

### 1. Data Preprocessing
- Checked data types and null values
- Normalized data using `MinMaxScaler`

### 2. Exploratory Data Analysis (EDA)
- KDE plots and heatmaps to understand feature distributions and correlations
- Identified most influential features on stress levels

### 3. Model Building
- Used `RandomForestClassifier` for classification
- Achieved ~88% accuracy on test data
- Calculated feature importances

### 4. Clustering with KMeans
- Optimal clusters determined using Elbow Method
- Clustered both original and PCA-reduced data
- Added cluster labels for further analysis

### 5. Dimensionality Reduction
- Applied PCA to reduce data to 8 principal components
- Visualized clusters in 2D (PC1 vs PC2)

## 📈 Insights

- **Top stress predictors**: blood pressure, sleep quality, self-esteem, extracurricular load
- **Stress levels correlated** with academic performance, teacher-student relationships, bullying
- **Distinct clusters** revealed behavioral patterns and subgroups needing tailored support

## ✅ Recommendations

- Promote emotional well-being programs and self-esteem workshops
- Regular health screenings to monitor physical symptoms like blood pressure
- Foster better teacher-student communication
- Strengthen social support networks and reduce bullying
- Introduce stress-management and time-management sessions

## 📁 Files in this Repo

| File | Description |
|------|-------------|
| `[StressLevelDataset.csv](https://github.com/Rubaikaa/Student-Stress-Detection-/blob/main/StressLevelDataset.csv)` | Dataset used in the project |
| `Student_Stress_Analysis.ipynb` | Full step-by-step Colab notebook |
| `Student_Stress_Report_Final.pdf` | Final report with analysis, insights, and recommendations |
| `README.md` | This file |

## 🚀 Future Work

- Fine-tune model using hyperparameter optimization (GridSearchCV)
- Try other classifiers (XGBoost, SVM, Neural Networks)
- Deploy as a web-based dashboard for real-time prediction
- Incorporate text-based features from student feedback

## 🙋‍♀️ Maintainer

**Rubaika Zohaib**  
📍 Dubai | 🧠 Psychology + 🧪 Data Science  
PGD in Data Science with AI  
*Loves uncovering patterns in student behavior using data!*  

---

**Feel free to fork, use, or contribute to this project!** 🌟

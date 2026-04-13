# PCA-Based User Classification Analysis

A machine learning and statistical analysis project on gym member behavioral data.  
This project applies Principal Component Analysis (PCA) and classification models to predict user experience levels and identify key behavioral patterns.

---

## 📊 Project Highlights

- Dataset: 973 gym members with 5 key features  
- Applied PCA to reduce dimensionality to 3 components  
- Explained 92.7% of total variance  
- Built multiple classification models using PyCaret  
- Best model: Random Forest  
- Achieved 79.6% accuracy and 0.775 F1-score  

---

## 🧠 Problem Statement

The goal of this project is to classify gym users into three experience levels (Beginner, Intermediate, Expert) based on physiological and behavioral features, and to understand the key factors influencing user progression.

---

## ⚙️ Methods

- Data preprocessing and feature selection  
- Exploratory Data Analysis (EDA)  
- Principal Component Analysis (PCA)  
- Model comparison using PyCaret  
- Hyperparameter tuning (Random Forest)  
- Visualization of feature relationships and classification results  

---

## 📈 Key Findings

- Higher experience levels are associated with:
  - Lower body fat percentage  
  - Longer training session duration  

- PCA successfully reduced dimensionality while preserving most information  

- Expert users are more separable, while Beginner and Intermediate show overlap  

---

## 🖼️ Visualizations

### PCA Projection
![PCA Plot](images/pca_plot.png)

### Model Performance Comparison
![Model Comparison](images/model_comparison.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

---

## 📁 Project Structure
gym-pca-user-classification/
│
├── notebooks/
│ └── gym_pca_classification.ipynb
│
├── data/
│ └── gym_members_exercise_tracking.csv
│
├── reports/
│ └── final_report.pdf
│
├── images/
│ ├── pca_plot.png
│ ├── model_comparison.png
│ └── confusion_matrix.png
│
├── requirements.txt


---

## ▶️ How to Run

1. Clone the repository:git clone https://github.com/yourusername/gym-pca-user-classification.git
2. Install dependencies:pip install -r requirements.txt
3. Open the notebook:jupyter notebook notebooks/gym_pca_classification.ipynb

---

## 🛠️ Tools & Technologies

- Python  
- pandas, numpy  
- scikit-learn  
- PyCaret  
- matplotlib / seaborn  

---

## 📌 Author

Yinpeng Su  

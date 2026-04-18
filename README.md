# CancerdiagnosisusinglogiacalregressionKNNCrossValidation**
# 🧠 Breast Cancer Detection using Logistic Regression, KNN & Cross Validation

## 📌 Overview

This project predicts whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** using machine learning models.
We use the **Breast Cancer Wisconsin Dataset** and implement multiple classification algorithms with **cross-validation** to ensure reliable and generalized performance.

---

## 🎯 Objectives

* Preprocess and clean real-world medical data
* Apply **Logistic Regression** and **K-Nearest Neighbors (KNN)**
* Use **Cross Validation** for robust model evaluation
* Compare model performance using metrics and graphs
* Improve prediction reliability

---

## 📂 Dataset

* **Name:** Breast Cancer Wisconsin Dataset
* **Samples:** 569
* **Features:** 30 numerical features
* **Target Variable:**

  * Malignant (M) → 1
  * Benign (B) → 0

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 🔹 Step 1: Data Preprocessing

* Loaded dataset using Pandas
* Removed unnecessary columns (`id`, `Unnamed: 32`)
* Converted categorical labels to binary values
* Applied **StandardScaler** for normalization
* Split dataset into training and testing sets

---

### 🔹 Step 2: Model Building

#### ✔ Logistic Regression

* Linear model for binary classification
* Provides probability-based predictions

#### ✔ K-Nearest Neighbors (KNN)

* Distance-based algorithm
* Sensitive to feature scaling
* Performance depends on value of **K**

---

### 🔹 Step 3: Model Evaluation

#### ✅ Cross Validation (Key Feature of This Project)

* Applied **10-fold cross-validation**
* Ensures model is not overfitting
* Provides more reliable accuracy than a single train-test split

#### ✅ Evaluation Metrics

* Accuracy (Train & Test)
* Cross-validation accuracy
* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve & AUC

---

## 📊 Visualizations

* Confusion Matrix Heatmaps
* ROC Curve Comparison
* K vs Accuracy Graph (to find optimal K in KNN)

---

## 📈 Results

* Logistic Regression showed **stable and consistent performance**
* KNN achieved **high accuracy after tuning K**
* Cross-validation confirmed that both models generalize well
* Minimal overfitting observed

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/breast-cancer-ml.git
```

2. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Run the project:

```bash
python main.py
```

---

## 📌 Future Enhancements

* Add advanced models (SVM, Random Forest)
* Deploy as a web application
* Integrate real-time prediction interface
* Use deep learning models

## 📜 License

This project is for educational purposes.

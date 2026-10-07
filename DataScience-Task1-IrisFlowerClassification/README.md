# 🌸 **Iris Flower Classification**

## **Oasis Infobyte Data Science Internship – Task 1**

---

## 📌 **Project Overview**

This project focuses on building a **Machine Learning Classification Model** to classify Iris flowers into three different species:

- 🌱 **Setosa**
- 🌸 **Versicolor**
- 🌺 **Virginica**

The project includes **Exploratory Data Analysis (EDA)**, **Data Visualization**, **Feature Selection**, **Model Training**, **Model Evaluation**, and **Model Comparison**.

---

## 🎯 **Objectives**

The main objectives of this project are:

- **Explore and understand the Iris dataset**
- **Check the dataset for missing values**
- **Perform Exploratory Data Analysis (EDA)**
- **Visualize relationships between different features**
- **Select suitable features for classification**
- **Train multiple Machine Learning classification models**
- **Evaluate model performance**
- **Compare the performance of different models**
- **Select the best-performing model**

---

## 🛠️ **Technologies Used**

| **Technology / Library** | **Purpose** |
|---|---|
| **Python** | Programming Language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **Scikit-learn** | Machine Learning |
| **Jupyter Notebook** | Development environment |

---

## 📊 **Dataset**

The **Iris dataset** is a built-in dataset available in **Scikit-learn**.

It contains **150 flower samples** belonging to **3 different species**.

### **Features**

| **Feature** | **Description** |
|---|---|
| **Sepal Length** | Length of the sepal |
| **Sepal Width** | Width of the sepal |
| **Petal Length** | Length of the petal |
| **Petal Width** | Width of the petal |

### **Target Classes**

The target variable contains three Iris species:

- **Setosa**
- **Versicolor**
- **Virginica**

Each species contains **50 samples**.

---

## 🔍 **Exploratory Data Analysis**

Several EDA techniques were performed to understand the dataset.

### **Dataset Inspection**

The following checks were performed:

- **Dataset shape**
- **Data types**
- **Missing values**
- **Descriptive statistics**
- **Class distribution**

The dataset contains **150 rows and 5 columns**.

There were **no missing values** in the dataset.

---

## 📈 **Data Visualization**

### **1. Pairplot**

A **pairplot** was created to visualize the relationships between the numerical features and observe the separation between different Iris species.

### **Observation**

The pairplot shows that the Iris species can be separated reasonably well based on their measurements.

**Petal length** and **petal width** show particularly strong separation between the different species.

---

### **2. Box Plot**

Box plots were created for the numerical features to understand their distributions and differences between the species.

### **Observation**

The box plots show noticeable differences in the distributions of the Iris features.

The **petal-related features** show stronger differences between species, while some overlap can be observed in the **sepal-related features**.

---

## 🧩 **Feature Selection**

The following four numerical features were selected as input variables:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

The **species** column was used as the target variable.

All four numerical features were retained so that the classification models could use the complete available feature information.

---

## ✂️ **Train-Test Split**

The dataset was divided into **training and testing datasets**.

- **80%** of the data was used for training.
- **20%** of the data was used for testing.

The training dataset was used to train the Machine Learning models, while the testing dataset was used to evaluate their performance on unseen data.

---

# 🤖 **Machine Learning Models**

Two classification algorithms were implemented and compared.

## **1. Logistic Regression**

**Logistic Regression** was used as the first classification algorithm.

The model was trained using the training dataset and then used to predict the Iris species in the testing dataset.

### **Evaluation Metrics**

The model was evaluated using:

- **Accuracy**
- **Classification Report**
- **Confusion Matrix**

### **Result**

**Logistic Regression achieved 100% accuracy** on the test dataset.

The confusion matrix showed that all test samples were correctly classified.

---

## **2. K-Nearest Neighbors (KNN)**

**K-Nearest Neighbors (KNN)** was used as the second classification algorithm.

KNN classifies a new sample based on the classes of its nearest neighboring training samples.

### **Evaluation Metrics**

The model was evaluated using:

- **Accuracy**
- **Classification Report**
- **Confusion Matrix**

### **Result**

**KNN also achieved 100% accuracy** on the test dataset.

The confusion matrix showed that all test samples were correctly classified.

---

# 📊 **Model Comparison**

The performance of both classification models was compared using their test accuracy.

| **Model** | **Accuracy** |
|---|---:|
| **Logistic Regression** | **100%** |
| **K-Nearest Neighbors (KNN)** | **100%** |

### 🏆 **Best Model**

Both models achieved the **same accuracy of 100%** on the test dataset.

Therefore, **Logistic Regression** was selected as the final model because it provides a **simple and interpretable classification approach**.

---

# 📌 **Key Findings**

- The dataset contains **150 Iris flower samples**.
- There are **3 target classes**: Setosa, Versicolor, and Virginica.
- The dataset contains **no missing values**.
- **Petal length and petal width** provide strong separation between the Iris species.
- Both **Logistic Regression** and **KNN** performed very well.
- Both models achieved **100% test accuracy**.
- **Logistic Regression** was selected as the final model because of its simplicity and interpretability.

---

# 💡 **Key Learnings**

Through this project, the following concepts were practiced:

- **Python programming**
- **Data loading and preprocessing**
- **Exploratory Data Analysis**
- **Data visualization**
- **Feature selection**
- **Train-test splitting**
- **Classification algorithms**
- **Model training**
- **Model evaluation**
- **Confusion matrix analysis**
- **Classification reports**
- **Model comparison**

---

# 📁 **Project Structure**

```text
DataScience-Task1-IrisFlowerClassification/
│
├── 📓 Iris_Flower_Classification.ipynb
├── 📄 README.md
│
└── 📁 screenshots/
    ├── pairplot.png
    ├── boxplot.png
    ├── confusion_matrix_logistic.png
    ├── confusion_matrix_knn.png
    └── model_comparison.png

```
---

## **Key Learnings**

### Through this project, the following concepts were practiced:

- Exploratory Data Analysis
- Data visualization
- Feature selection
- Train-test splitting
- Classification algorithms
- Model evaluation
- Confusion matrix interpretation
- Model comparison


## **Conclusion**

The project successfully developed a machine learning solution for Iris flower classification. Both Logistic Regression and KNN performed very well on the test dataset, achieving 100% accuracy. The analysis also demonstrated that petal measurements are particularly useful for distinguishing between the three Iris species.

## Internship Details

# Oasis Infobyte – Data Science Internship

This project was completed as part of the **Oasis Infobyte Data Science Internship Program**.

**Internship Track:** Data Science  
**Task:** Task 1 – Iris Flower Classification  
**Project Type:** Machine Learning Classification  
**Tools:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

### Skills Demonstrated

- Python programming
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization
- Feature selection
- Classification algorithms
- Model training and testing
- Model evaluation
- Confusion matrix analysis
- Model comparison
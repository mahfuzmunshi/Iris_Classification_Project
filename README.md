# 🌸 Iris Flower Species Classification Project 🤖

### Project Status: COMPLETE

This is my first end-to-end Data Analysis and Machine Learning project, focusing on the classic Iris dataset. The goal of this project was to apply fundamental data analysis, visualization, and classification techniques to accurately predict the species of Iris flower based on its physical measurements.

---

## 🎯 Objective & Goal

The primary objective was to build a robust model capable of classifying the Iris flower into one of three species: *Iris-setosa*, *Iris-versicolor*, or *Iris-virginica*.

This project demonstrates proficiency in the following key data analysis and machine learning stages:
* **Data Ingestion & Cleaning**
* **Exploratory Data Analysis (EDA) & Visualization**
* **Feature Engineering & Model Preparation**
* **Model Training and Evaluation (Classification)**

---

## 🛠️ Technology Stack & Libraries

* **Language:** Python
* **Environment:** Jupyter Notebook (via VS Code)
* **Core Libraries:**
    * **Pandas:** For data manipulation and cleaning.
    * **NumPy:** For numerical operations.
    * **Matplotlib / Seaborn:** For data visualization (e.g., Count Plot, Pair Plot).
    * **Scikit-learn:** For machine learning utilities (Data Splitting, Label Encoding) and the classification model.

---

---

## 💡 Learning Context & Assistance

This project was completed as a core part of a **60-day accelerated learning path** guided by an AI coding assistant (Gemini). The use of the AI assistant was strictly limited to **structural guidance, conceptual explanation, and error resolution** (e.g., fixing syntax, explaining library functions) to ensure rapid, hands-on learning of the entire data science workflow. All code execution, data analysis interpretation, and result reporting were performed by the user.


## 📊 Dataset Overview

The dataset consists of 150 samples of Iris flowers, with 50 samples from each of the three species. It includes the following features (characteristics):

| Feature Name | Description | Data Type |
| :--- | :--- | :--- |
| **Sepal Length (Cm)** | Length of the sepal. | Float |
| **Sepal Width (Cm)** | Width of the sepal. | Float |
| **Petal Length (Cm)** | Length of the petal. | Float |
| **Petal Width (Cm)** | Width of the petal. | Float |
| **Species** | The target species name (Categorical). | Object (Encoded to Integer) |

**Key Findings during EDA:**
* The dataset is **perfectly balanced** (50 instances per species).
* No **missing values** were found.
* The **Pair Plot** confirmed a strong correlation between **Petal Length** and **Petal Width**, suggesting these are the most critical features for species separation.

---

## 🧠 Model & Results

### Model Used: K-Nearest Neighbors (KNN) Classifier

KNN is a simple, non-parametric classification algorithm that classifies a data point based on how its neighbors are classified.

### 🏆 Final Evaluation

The model was trained on 80% of the data and tested on the remaining 20% (30 samples).

| Metric | Score | Comment |
| :--- | :--- | :--- |
| **Accuracy Score** | **100.00%** | The model correctly predicted all 30 samples in the test set. |
| **Precision, Recall, F1-Score**| **1.00 (Perfect)**| The classification report confirms flawless performance across all three species. |

**Conclusion:** The KNN model achieved perfect classification accuracy on the test set, demonstrating that the Iris species can be reliably distinguished using these four physical measurements.

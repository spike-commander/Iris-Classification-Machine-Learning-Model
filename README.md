# Iris Classification Machine Learning Model

A machine learning project that classifies Iris flower species using **Logistic Regression**. This serves as my second machine learning model, built to demonstrate the foundational concepts of data preprocessing, feature utilization, and categorical classification.

## 📌 Project Overview
The goal of this project is to accurately predict the specific species of an Iris flower based on its structural dimensions. Since Logistic Regression is highly effective for linearly separable categorical outcomes, it is implemented here to classify flowers into one of three species.

## 📊 Dataset Detail
This project utilizes the classic **Iris Dataset**, a staple benchmark in machine learning. The dataset contains 150 instances evenly balanced across three classes (50 samples each):
*   **Iris-setosa**
*   **Iris-versicolor**
*   **Iris-virginica**

### Features (Predictor Variables)
The model trains on four numeric structural attributes (measured in centimeters):
1.  **Sepal Length**
2.  **Sepal Width**
3.  **Petal Length**
4.  **Petal Width**

## 🛠️ Tech Stack & Libraries
*   **Python** (Core language)
*   **NumPy & Pandas** (Data manipulation and cleaning)
*   **Matplotlib & Seaborn** (Exploratory data analysis and data visualization)
*   **Scikit-Learn** (Model training, data splitting, scaling, and evaluation)

## ⚙️ Workflow & Implementation
1.  **Data Exploration:** Analyzing feature distributions and plotting pair-plots to visualize the natural clustering and boundaries between species.
2.  **Preprocessing:** Scaling features using standard normalization and encoding categorical target labels into numerical formats.
3.  **Data Splitting:** Partitioning data into dedicated training and testing sets to evaluate unseen performance fairly.
4.  **Model Training:** Training a Multi-class Logistic Regression algorithm on the processed training set.
5.  **Evaluation:** Calculating performance metrics using a Confusion Matrix, Precision, Recall, and overall Classification Accuracy.

## 🚀 How to Run the Notebook
To interact with the code, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com
   ```
2. Open the notebook file `iris-classification-machine-learning-model.ipynb` in your preferred environment:
   *   [Google Colab](https://google.com)
   *   Jupyter Notebook / JupyterLab
   *   VS Code (with Jupyter Extension)
3. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
4. Run the code cells sequentially from top to bottom.

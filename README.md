# APR_assignment_1_Logistic_regression

# Logistic Regression Model for Social Network Ads

This project builds a logistic regression model to predict whether a user will purchase a product based on their **Age**, **Estimated Salary**, and **Gender**, using the `Social_Network_Ads.csv` dataset.  

---

## 📌 Project Steps

1. **Load the Data**  
   - The `Social_Network_Ads.csv` file was loaded into a Pandas DataFrame.

2. **Preprocess the Data**  
   - Checked for missing values (none found).  
   - One-hot encoded the `Gender` column.  
   - Scaled `Age` and `EstimatedSalary` using `StandardScaler`.

3. **Split the Data**  
   - Training set: 75%  
   - Testing set: 25%

4. **Build the Logistic Regression Model**  
   - Trained a Logistic Regression classifier on the training data.

5. **Evaluate the Model**  
   - **Accuracy:** `0.8800`  
   - **Precision:** `0.9310`  
   - **Recall:** `0.7297`  
   - **F1-score:** `0.8182`

6. **Visualize the Results**  
   - Plotted decision boundaries for both training and test sets to show how the model classifies users based on `Age` and `EstimatedSalary`.

---

## 📊 Key Findings

- The model achieved **good accuracy and precision** in predicting purchases.  
- The recall shows the model successfully identified a significant portion of actual purchases, though there is **room for improvement**.  

---

## 🚀 Next Steps

- Compare performance with other classification models (e.g., SVM, Random Forest, KNN).  
- Tune hyperparameters of the Logistic Regression model to improve recall.  
- Investigate **misclassified instances** to understand model limitations.  

---

## 📂 Dataset

The dataset used in this project is **`Social_Network_Ads.csv`**.  

---

## ⚙️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

✅ This project demonstrates a complete ML pipeline: data preprocessing, model building, evaluation, and visualization.  

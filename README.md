# -Iris-Flower-Classification-

---

## Task Description

- Goal:The task is to build a machine learning model that can classify iris flowers into one of three species — Setosa, Versicolor, or Virginica — based on the length and width of sepals and petals.
- Dataset: IRIS.csv (Iris flower dataset)
- Target: Species (Setosa, Versicolor, Virginica)


## Tools & Libraries

•	Python
•	pandas, seaborn, matplotlib
•	scikit-learn
•	Gradio

## Steps Performed

## 1. Define the Problem
•	Multi-class classification problem.

## 2. Collect and Prepare Data
•	Loaded CSV, checked for nulls, and encoded labels.

## 3. Exploratory Data Analysis (EDA)
•	Pairplots and correlation heatmap to visualize feature relationships.
•	Found that petal length and petal width are strong predictors.

## 4. Feature Engineering
•	No derived features were needed; used original four features.

## 5. Split Data
•	Used train_test_split (80% training, 20% testing).

## 6. Choose and Train Models
•	Logistic Regression
•	Decision Tree

## 7. Evaluate the Models
•	Used Accuracy Score and Confusion Matrix
•	Both models achieved ~97-100% accuracy

## Evaluation Metrics
•	Accuracy Score: Proportion of correct predictions.
•	Confusion Matrix: Breakdown of predictions by class.

## Conclusion
•	Both models perform excellently on this dataset.
•	Petal features are most significant in determining flower species.
•	The app allows real-time, user-friendly predictions using either algorithm.

##  How to Run Locally

### 1. Clone the repository:
```bash
https://github.com/Waseem-23/-Iris-Flower-Classification-

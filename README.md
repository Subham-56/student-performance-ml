# Student Performance Prediction

Predicting student performance using **Linear Regression**.  
This is a beginner-level Machine Learning project based on **Andrew Ng’s Machine Learning course (Part 1)**.

---

## Dataset
The dataset is from Kaggle: [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  

It contains the following columns:

- `gender` – Male/Female  
- `race/ethnicity` – Student group  
- `parental level of education` – Parent's education level  
- `lunch` – Standard or free/reduced  
- `test preparation course` – Completed or none  
- `math score`, `reading score`, `writing score` – Individual exam scores  

We calculate an **average score** from math, reading, and writing to use as the prediction target.

---

## Project Steps

1. **Load Dataset**  
   Load CSV data using pandas.

2. **Exploratory Data Analysis (EDA)**  
   - Check for missing values  
   - Visualize average scores by gender  

3. **Preprocessing**  
   - Encode categorical features to numeric values  
   - Select features (`gender`, `lunch`, `test preparation course`) and target (`average_score`)

4. **Train-Test Split**  
   Split data into 80% training and 20% testing sets.

5. **Train Linear Regression Model**  
   Predict average student scores based on selected features.

6. **Model Evaluation**  
   Evaluate predictions using **Mean Squared Error (MSE)** and **R² Score**.

7. **Predictions**  
   Show sample predictions and compare with actual scores.

---

## Visualizations

- **Average Scores by Gender**  
- **Actual vs Predicted Scores Scatter Plot**

These visualizations help understand the data and model performance.

---

## Tools & Libraries

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Key Learnings

- Implemented **Linear Regression** from sklearn.  
- Performed **basic preprocessing** of categorical data.  
- Split data into **training/testing sets** for evaluation.  
- Evaluated model with **MSE** and **R² metrics**.  
- Visualized relationships in the dataset for better understanding.

---

## How to Run

1. Clone the repository.  
2. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn

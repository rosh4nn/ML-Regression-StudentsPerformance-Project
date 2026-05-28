# Students Performance Analysis & Prediction Project 🎓

This project applies exploratory data analysis and machine learning to understand the factors affecting student academic performance and predict final exam outcomes. It is built and executed entirely within Google Colab.

[![Open In Colab](https://google.com)](https://google.com)

## 📌 Project Overview
* **Dataset:** Student Performance Dataset (features include: study time, parental education, attendance, internet access, free time, and past grades).
* **Goal:** Identify key elements influencing student grades and build a predictive model
* **Libraries Used:** Python, Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.

## 📊 Data Visualization & Insights (EDA)
To understand trends in the dataset, linear regressions were evaluated using Seaborn `lmplot` functions. Key trends identified from the **lmplots** include:
* **Study Time vs. Final Grades:** A clear positive linear trend, showing that increased study hours correlate with higher final scores.

## ⚙️ Workflow
1. **Data Loading & Cleaning:** Importing the student data structure.
2. **Exploratory Analysis:** Using `lmplots` to reveal linear relationships and find data distributions.
3. **Preprocessing:** Removed weak related features and splitting data into train/test sets.
4. **Model Training:** Training regression or classification models to predict performance scores.
5. **Evaluation:** Assessing performance using baseline accuracy or error metrics.

## 🚀 How to Run the Project
1. Click the **Open in Colab** badge at the top of this file.
2. Once the notebook opens in Google Colab, click **Runtime** in the top menu.
3. Select **Run all** to execute all code cells sequentially.

## 📈 Key Findings
* **Model Performance:** ["R2_score: 0.988713724754468" / mean_absolute_error: 1.6274712206280653]

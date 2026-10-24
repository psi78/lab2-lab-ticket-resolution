# Lab 2: Software Support Ticket Resolution Time Estimation

**Author:** Israel Shimeles  
**ID:** UGR/7570/16  
**Institution: Addis Ababa University / Addis Ababa Institute of Technology  
**Repository:** [lab2-lab-ticket-resolution](https://github.com/psi78/lab2-lab-ticket-resolution)

---

## 📌 Project Overview

This lab focuses on building, evaluating, and comparing machine learning regression pipelines to estimate and predict resolution times for software support tickets. Utilizing real-world exploratory data analysis (EDA), data preprocessing pipelines, feature engineering, and regularized regression algorithms, this project analyzes key ticket features to deliver accurate resolution time estimations.

---

## 🛠️ Key Tasks & Workflow

1. **Exploratory Data Analysis (EDA):**
   * Loaded and inspected dataset features from `lab_ticket_resolution.csv`.
   * Checked for missing values, feature distributions, and correlations.

2. **Data Preprocessing & Pipeline Construction:**
   * Scaled numerical features using standard scaling techniques within scikit-learn pipelines to prevent data leakage.
   * Split data into training and test datasets.

3. **Model Training & Comparison:**
   * **Baseline Model:** Dummy Regressor (mean/median strategy).
   * **Multiple Linear Regression:** Evaluated baseline predictive performance.
   * **Polynomial Regression:** Modeled non-linear feature interactions.
   * **Regularized Models:** Implemented Ridge ($L_2$) and Lasso ($L_1$) regressions to reduce overfitting and improve model generalization.

4. **Model Evaluation & Residual Analysis:**
   * Calculated evaluation metrics including Root Mean Squared Error (RMSE) and $R^2$ score (achieving $R^2 \approx 0.91$).
   * Performed residual analysis and plotted diagnostic graphs saved as `task8_plots.png` to check homoscedasticity and detect potential outliers.

---

## 📂 Project Structure

```text
├── lab_ticket_resolution.ipynb   # Main Jupyter Notebook containing code, analysis, and answers
├── lab_ticket_resolution.csv     # Support ticket dataset
├── task8_plots.png               # Diagnostic and residual evaluation plots
└── README.md                     # Project documentation# Lab 3: Software Support Ticket Resolution Time Estimation

**Author:** Israel Shimeles  
**ID:** UGR/7570/16  
**Institution:** Addis Ababa University / Addis Ababa Institute of Technology  
**Repository:** [lab2-lab-ticket-resolution](https://github.com/psi78/lab2-lab-ticket-resolution)

---

## 📌 Project Overview

This lab focuses on building, evaluating, and comparing machine learning regression pipelines to estimate and predict resolution times for software support tickets. Utilizing real-world exploratory data analysis (EDA), data preprocessing pipelines, feature engineering, and regularized regression algorithms, this project analyzes key ticket features to deliver accurate resolution time estimations.

---

## 🛠️ Key Tasks & Workflow

1. **Exploratory Data Analysis (EDA):**
   * Loaded and inspected dataset features from `lab_ticket_resolution.csv`.
   * Checked for missing values, feature distributions, and correlations.

2. **Data Preprocessing & Pipeline Construction:**
   * Scaled numerical features using standard scaling techniques within scikit-learn pipelines to prevent data leakage.
   * Split data into training and test datasets.

3. **Model Training & Comparison:**
   * **Baseline Model:** Dummy Regressor (mean/median strategy).
   * **Multiple Linear Regression:** Evaluated baseline predictive performance.
   * **Polynomial Regression:** Modeled non-linear feature interactions.
   * **Regularized Models:** Implemented Ridge ($L_2$) and Lasso ($L_1$) regressions to reduce overfitting and improve model generalization.

4. **Model Evaluation & Residual Analysis:**
   * Calculated evaluation metrics including Root Mean Squared Error (RMSE) and $R^2$ score (achieving $R^2 \approx 0.91$).
   * Performed residual analysis and plotted diagnostic graphs saved as `task8_plots.png` to check homoscedasticity and detect potential outliers.

---

## 📂 Project Structure

```text
├── lab_ticket_resolution.ipynb   # Main Jupyter Notebook containing code, analysis, and answers
├── lab_ticket_resolution.csv     # Support ticket dataset
├── task8_plots.png               # Diagnostic and residual evaluation plots
└── README.md                     # Project documentation

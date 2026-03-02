# DHC-INTERNSHIP
DHC DATA ANALYSIS INTERNSHIP PROJECT

# Task 1: Exploring and Visualizing the Iris Dataset

## 📌 Objective
The goal of this task is to explore and visualize the Iris dataset using Python libraries such as **pandas**, **seaborn**, and **matplotlib**.  
This helps in understanding dataset structure, relationships between variables, and data distribution.

---

## 📂 Dataset
- **Name:** Iris Dataset  
- **Source:** Available via seaborn (`sns.load_dataset('iris')`)  
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Approach
1. **Data Loading**  
   - Loaded dataset using seaborn and pandas.
2. **Data Exploration**  
   - Checked dataset shape, column names, and first few rows.
3. **Visualizations**  
   - **Scatter Plot:** Sepal Length vs Sepal Width (colored by species).  
   - **Histogram:** Distribution of Petal Length.  
   - **Box Plot:** Spread of Sepal Length across species.

---

## 📊 Results & Insights
- Scatter plot shows clear separation between species based on sepal dimensions.  
- Histogram reveals distinct distribution patterns of petal length.  
- Box plot highlights differences in sepal length spread across species, with Setosa having the smallest range.

---

## ✅ Conclusion
The Iris dataset demonstrates clear species‑level differences in flower dimensions.  
Exploratory Data Analysis (EDA) confirms that simple visualizations can effectively distinguish between species.

---

## 🛠️ Tools & Libraries
- Python 3.x  
- pandas  
- seaborn  
- matplotlib  

---


# Task 2: Credit Risk Prediction

## 📌 Objective
Predict whether a loan applicant is likely to default based on personal and financial data.

## 📊 Dataset
Loan Prediction Dataset  
Features include:
- `ApplicantIncome`: Income of the applicant  
- `CoapplicantIncome`: Income of co-applicant  
- `LoanAmount`: Loan amount requested  
- `Loan_Amount_Term`: Duration of loan  
- `Credit_History`: Credit history record  
- `Education`: Applicant’s education level  
- `Property_Area`: Applicant’s residential area  
- `Loan_Status`: Target variable (Y = approved, N = rejected)  

## ⚙️ Approach
1. Data Cleaning
   - Handled missing values using median for numeric features and `"Unknown"` for categorical features.
   - Encoded categorical variables using one-hot encoding.

2. Exploratory Data Analysis (EDA)
   - Distribution of loan amounts.
   - Relationship between applicant income and loan default.
   - Education vs loan default visualization.

3. Model Training
   - **Logistic Regression** for baseline classification.
   - **Decision Tree Classifier** for non-linear relationships.

4. Model Evaluation
   - Accuracy score comparison.
   - Confusion matrix visualization for both models.

## 📈 Results
- Logistic Regression provides a strong baseline with interpretable coefficients.
- Decision Tree captures non-linear patterns but may risk overfitting.
- Key insights:
  - **Income** influences loan approval likelihood.
  - **Education** and **credit history** are strong predictors of loan default.

## ✅ Key Insights
- Applicants with higher income are less likely to default.  
- Education level shows correlation with loan approval.  
- Credit history is a critical factor in predicting loan risk.  


# Task 3: Predicting Insurance Claim Amounts

## 📌 Objective
Estimate medical insurance claim amounts based on personal data using regression modeling.

## 📊 Dataset
**Medical Cost Personal Dataset**  
Features include:
- `age`: Age of the insured person  
- `sex`: Gender  
- `bmi`: Body Mass Index  
- `children`: Number of dependents  
- `smoker`: Smoking status  
- `region`: Residential area  
- `charges`: Medical insurance cost (target variable)  

## ⚙️ Approach
1. Data Preparation
   - Encoded categorical variables (`sex`, `smoker`, `region`).
   - Split dataset into training and testing sets.

2. Exploratory Data Analysis (EDA)
   - Correlation heatmap to identify feature relationships.
   - Scatter plots for `BMI vs Charges` and `Age vs Charges`.
   - Boxplot for `Smoking Status vs Charges`.

3. Model Training
   - Applied Linear Regression.
   - Trained on 80% of the dataset, tested on 20%.

4. Model Evaluation
   - Metrics used:
     - MAE (Mean Absolute Error)
     - RMSE (Root Mean Squared Error)

## 📈 Results
- **BMI, age, and smoking status** strongly influence insurance charges.
- Smokers have significantly higher predicted charges.
- Linear Regression provides a baseline model with reasonable accuracy.

## ✅ Key Insights
- Age: Older individuals tend to have higher charges.  
- BMI: Higher BMI correlates with increased charges.  
- Smoking: Smoking status is the most impactful feature.  

#






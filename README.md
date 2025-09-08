# 📊 Data-Analytics-for-Insurance-Cost-Dataset-using-Python
This project analyzes the Insurance Cost dataset (commonly containing features like age, sex, bmi, children, smoker, region, and charges) to explore factors influencing medical insurance costs and build predictive models.
## 🔹 Project Overview
The main goals of this project are:

- Perform Exploratory Data Analysis (EDA) to understand data distribution and relationships.

- Investigate how demographics and lifestyle factors affect insurance costs.

- Build machine learning models to predict insurance charges.

- Evaluate feature importance to identify key cost drivers.
## 🔹 Dataset

Typical dataset columns:
 | Column       | Description                                                     |
| ------------ | --------------------------------------------------------------- |
| **age**      | Age of the individual                                           |
| **sex**      | Gender (male/female)                                            |
| **bmi**      | Body Mass Index                                                 |
| **children** | Number of children/dependents                                   |
| **smoker**   | Smoking status (yes/no)                                         |
| **region**   | Residential region (northeast, northwest, southeast, southwest) |
| **charges**  | Individual medical insurance costs                              |

## 🔹 Tools & Libraries

- **Python** 🐍

- **Pandas, NumPy** → Data manipulation

- **Matplotlib, Seaborn** → Data visualization

- **Scikit-learn** → Machine learning models & evaluation
## 🔹 Project Workflow
**1. Data Loading & Cleaning**

- Load dataset with Pandas.

- Handle missing values & categorical encoding.

- Prepare data for analysis.

**2. Exploratory Data Analysis (EDA)**

- Distribution of insurance charges.

- Relationship between smoker status, BMI, age, and costs.

- Correlation heatmap.

**3. Modeling**

- Train-test split.

- Linear Regression for baseline model.

- Random Forest Regressor for feature importance & improved performance.

**4. Evaluation**

- R² Score, MAE, RMSE.

- Compare actual vs predicted charges.
## 🔹 Key Insights

- Smoking significantly increases insurance charges.

- BMI and age also strongly influence costs.

- Random Forest identifies smoker, bmi, and age as top predictive features.

## 🔹 Example Visualizations

📌 Charges Distribution
<br />  📌 BMI vs Charges (colored by smoker status)
<br />  📌 Boxplot of Charges by Smoker Status
<br /> 📌 Feature Importance from Random Forest
## 🔹 Future Work

- Try advanced models (XGBoost, Gradient Boosting).

- Hyperparameter tuning for better predictions.

- Deploy as an interactive dashboard (Streamlit/Flask).
## 🔹 Author

👤 Bahre Hailemariam <br /> 
📧 bahre.hail@gmail.com

🌐 https://www.linkedin.com/in/bahre-hailemariam/

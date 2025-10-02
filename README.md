# Sales--BlackFriday

### 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on the Black Friday Sales dataset to understand customer purchasing patterns, product preferences, and demographic influences. The analysis includes data cleaning, feature encoding, visualization, and correlation analysis to uncover insights that can guide business decisions or predictive modeling.

### 📂 Dataset Features
- **User_ID, Product_ID** – Unique identifiers
- **Gender** – Customer gender (Male/Female)
- **Age** – Age groups (0-17, 18-25, …, 55+)
- **Occupation** – Occupation code
- **City_Category** – City type (A, B, C)
- **Stay_In_Current_City_Years** – Years stayed in current city
- **Marital_Status** – Married/Unmarried
- **Product_Category_1** – Primary product category
- **Purchase** – Purchase amount

### 🔎 Key Measures Taken
1. **Data Cleaning & Preprocessing**
   - Dropped irrelevant identifiers (`User_ID`, `Product_ID`)
   - Encoded categorical variables (`Gender`, `Age`, `City_Category`, `Stay_In_Current_City_Years`)

2. **Exploratory Data Analysis**
   - Countplots and bar charts for categorical features
   - Analysis of purchase distribution across age, gender, and city categories

3. **Feature Engineering**
   - Combined features like Age + Marital Status for deeper insights

4. **Correlation Analysis**
   - Generated correlation matrix of numeric features vs. `Purchase`
   - Visualized correlations with heatmaps

### 📊 Key Insights
- Age group 26–35 contributes the highest purchases
- Males purchase more frequently than females
- City Category B shows higher purchase activity
- Occupation and Product_Category_1 moderately influence purchase amounts

### 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook / Google Colab

### 🚀 Future Scope
- Build predictive models to estimate purchase amounts
- Apply clustering to segment customers
- Perform feature selection and model evaluation
"""

# Fuel Economy Analysis (2008–2018)

A data science project analyzing fuel economy trends in U.S. vehicles from 2008 to 2018 using Python. This project involves data cleaning, visualization, classification, regression, and clustering to extract insights from EPA SmartWay data.

## Dataset
The data was collected from Excel files named:
```
SmartWay Vehicle List MY {YEAR}.xlsx
SmartWay Vehicle List for MY {YEAR}.xlsx
```
Years covered: **2008 to 2018**

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for ML models)
- Jupyter Notebook

## Project Steps

1. **Data Loading & Cleaning**
   - Loaded yearly datasets from 2008–2018.
   - Cleaned and standardized columns across files.
   - Handled missing values and type conversions.

2. **Exploratory Data Analysis (EDA)**
   - Count plots by year.
   - Fuel type vs MPG comparison.
   - SmartWay classification trends.
   - Scatter plots of City vs Highway MPG.

3. **Classification Models**
   - Logistic Regression
   - Decision Tree Classifier  
   Predicted whether a vehicle qualifies for SmartWay status based on MPG.

4. **Regression Model**
   - Predicted **City MPG** using **Highway MPG**.
   - Used Linear Regression with high R² score.

5. **Clustering (KMeans)**
   - Clustered vehicles based on MPG performance.

## Results

| Model              | Performance Metric | Value        |
|--------------------|--------------------|--------------|
| Logistic Regression | Accuracy           | ~69%         |
| Decision Tree      | Accuracy           | ~82%         |
| Linear Regression  | R² Score           | ~0.94        |
|                    | RMSE               | ~5.04 MPG     |

## What I Learned
As a student, I learned how to:
- Clean and merge real-world multi-year data.
- Visualize trends to gain insights.
- Build predictive models for classification and regression.
- Apply clustering for pattern discovery.

## How to Run

```bash
git clone https://github.com/Sanjureddy-17/fuel_economy_analysis.git
cd fuel_economy_analysis
# Open the .ipynb notebook in Jupyter or VS Code
```

## Author

**Muvva Sanjeeva Reddy**  
Data Science Enthusiast | Python | SQL | Power BI  
[LinkedIn](https://www.linkedin.com/in/sanjureddy-17/) | [GitHub](https://github.com/Sanjureddy-17)


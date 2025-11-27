# Telco Customer Churn Analysis

## Project Overview
This project conducts an in-depth analysis of a telco customer dataset to understand the factors that influence customer churn. The goal is to derive actionable insights that can help reduce customer attrition rates.

The analysis follows a standard data science workflow:
*   **Data Loading & Inspection**
*   **Data Cleaning & Preprocessing**
*   **Exploratory Data Analysis (EDA) & Visualization**
*   **Correlation Analysis**

## Dataset
The dataset used is the `Telco-Customer-Churn.csv`, a common dataset for churn prediction modeling. It contains information about:
*   Customer demographics (gender, senior citizen status, dependents)
*   Services subscribed (phone, internet, online security, etc.)
*   Account information (tenure, contract type, payment method, monthly charges)
*   **Target Variable:** `Churn` - Whether the customer left the service in the last month.

## Key Steps & Insights
1.  **Data Cleaning:** Handled missing values and incorrect data types in the `TotalCharges` column.
2.  **Exploratory Data Analysis (EDA):**
    *   Visualized the overall churn distribution.
    *   Analyzed the relationship between `tenure` and churn rate, revealing that newer customers are significantly more likely to churn.
    *   Identified key categorical features for further analysis (e.g., `Contract`, `InternetService`, `PaymentMethod`).
3.  **Correlation Analysis:** Examined relationships between numerical features (`tenure`, `MonthlyCharges`, `TotalCharges`).

## Technologies Used
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook

## How to Run
1.  Clone this repository.
2.  Ensure you have Jupyter Notebook and the required Python libraries installed.
3.  Open the `project_8.ipynb` notebook.
4.  Run the cells sequentially to reproduce the analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
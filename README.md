# Black Friday Sales Analysis

![Black Friday Sales](https://img.shields.io/badge/Black%20Friday%20Sales-Analysis-blue)

## 📊 Project Overview

The **Black Friday Sales Analysis** project aims to explore and analyze Black Friday sales data to understand customer purchasing behavior, product preferences, and sales trends. The insights derived from this analysis can help businesses make data-driven decisions in marketing, inventory management, and sales optimization.

## 🗂️ Dataset Overview

- **Source**: The dataset is sourced from [Kaggle's Black Friday dataset](https://www.kaggle.com/sdolezel/black-friday).
- **Description**: The dataset contains detailed records of customer transactions during Black Friday, including demographic information, product details, and purchase amounts.

### Key Features:

1. **User_ID**: Unique identifier assigned to each customer.
2. **Product_ID**: Unique identifier assigned to each product purchased.
3. **Gender**: Gender of the customer (`Male`/`Female`).
4. **Age**: Age group of the customer (e.g., `0-17`, `18-25`, `26-35`).
5. **Occupation**: Code representing the customer's occupation.
6. **City_Category**: Category of the city where the customer resides (`A`, `B`, `C`).
7. **Stay_In_Current_City_Years**: Number of years the customer has lived in the current city.
8. **Marital_Status**: Marital status of the customer (`0` = Single, `1` = Married).
9. **Product_Category_1**: Primary category of the purchased product.
10. **Product_Category_2**: Secondary category of the purchased product (may contain missing values).
11. **Product_Category_3**: Tertiary category of the purchased product (may contain missing values).
12. **Purchase**: Purchase amount spent by the customer on the transaction.

## 🛠️ Tools and Technologies

- **Python**: Main programming language used for data analysis.
- **Pandas**: For data cleaning, manipulation, and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For creating insightful visualizations.
- **Scikit-Learn**: For predictive modeling and machine learning.

## 📈 Analysis Workflow

1. **Data Cleaning**: Handling missing values in product categories, adjusting data types, and preparing data for analysis.
2. **Exploratory Data Analysis (EDA)**: 
   - Analyzing customer demographics (gender, age, occupation).
   - Identifying top-selling products and popular product categories.
   - Examining purchasing patterns based on age groups, gender, and city categories.
3. **Data Visualization**: Using plots to visualize purchase trends, product popularity, and demographic spending behavior.
4. **Predictive Modeling**: Building basic models to predict purchase amounts based on customer demographics and product categories.

## 📊 Key Insights

- **Top Age Group**: Customers aged 26-35 are the most active shoppers.
- **Popular Product Categories**: Electronics and fashion items dominate sales.
- **Gender Spending**: Male customers generally spend more on average compared to female customers.
- **City Trends**: City category B shows higher sales volumes compared to other categories.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook (optional but recommended for interactive analysis)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/black-friday-sales-analysis.git
cd black-friday-sales-analysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Running the Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook Black_Friday_Sales_Analysis.ipynb
```

Run each cell in the notebook to perform the data cleaning, analysis, and visualization steps.

## 🤝 Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## 📬 Contact

For questions, feedback, or collaboration, reach out at achyuthags755@gmail.com.

---

⭐ If you find this project helpful, please give it a star!

```

This README provides a comprehensive overview of your project and highlights the key features of the dataset. Feel free to adjust the text to better fit your specific analysis and findings!

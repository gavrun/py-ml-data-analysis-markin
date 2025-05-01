# Online Sales Analysis Project

This study project presents a complete data analysis workflow for an e-commerce electronics store. The analysis focuses on customer behavior, product performance, revenue trends, and regional patterns over the past year. 

The goal is to demonstrate the full lifecycle of a data analysis project in Python using Jupyter Notebook.

## Project Structure

```
online-sales-analysis/
├── data/
│   ├── online_sales.csv
│   └── customers.csv
├── notebooks/
│   └── analysis.ipynb  # Jupyter Notebooks
└── README.md
```

## Objectives

- Analyze sales data of an online electronics store
- Identify popular product categories and top-selling items
- Explore seasonal trends and regional differences
- Understand customer behavior using demographic information
- Visualize key insights through graphs and charts

## Data set

online_sales.csv: transaction data (date, product, category, quantity, price, region, customer)

customers.csv: customer profile data (age, gender, registration date, premium status)

## Tools & Libraries

- Python 3.x
- Pandas
- Matplotlib
- NumPy
- Jupyter Notebook

## How to Run

1. Clone repository:

```
git clone https://github.com/USERNAME/REPO_NAME.git
cd project 
```

2. Create and activate a virtual environment:

```
python -m venv .venv
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.venv\Scripts\Activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Register a Jupyter kernel:

```
python -m ipykernel install --user --name=K_NAME --display-name "Python (K_NAME)"
```

5. Launch the notebook:

```
jupyter notebook notebooks/B_NAME.ipynb
```

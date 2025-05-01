# US Store Sales Analysis

## Description

This project performs a rigorous exploratory data analysis (EDA) on sales data from a US store using Python. It leverages libraries like Pandas for in-depth data manipulation and Plotly for creating interactive visualizations to uncover key insights into sales trends, profitability across different segments, and customer behavior patterns.

## Data Source

The dataset used for this analysis is `us-store.xls`, located within the `data/` directory.

## Key Analyses Performed

*   **Data Loading and Initial Inspection:** Loaded data from an Excel file (`.xls`) and performed initial checks (shape, data types, missing values).
*   **Data Cleaning:** Handled missing values (if any were found), found none.
*   **Time Series Analysis:**
    *   Extracted month and year from order dates.
    *   Aggregated sales data on a monthly basis.
    *   Visualized monthly sales trends using line charts to identify seasonality or growth patterns.
*   **Profitability Analysis:**
    *   Calculated total sales and profit for different customer segments.
    *   Computed the Sales-to-Profit ratio for each segment.
    *   Visualized segment-wise sales and profitability using bar charts.
*   **Customer Segmentation:** Analyzed sales and profit distribution across customer segments (e.g., Consumer, Corporate, Home Office).
*   **Interactive Visualizations:** Utilized Plotly to create dynamic and interactive charts for better data exploration.

## Setup

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  **Install dependencies:**
    ```bash
    pip install pandas plotly openpyxl xlrd nbformat
    ```
    *   `pandas`: For data manipulation and analysis.
    *   `plotly`: For interactive plotting.
    *   `openpyxl`, `xlrd`: Required by Pandas to read Excel files (`.xlsx`, `.xls`).
    *   `nbformat`: Required for rendering Plotly figures correctly in notebooks.

## Usage

The main analysis is contained within the `main.ipynb` Jupyter Notebook. Open this file using Visual Studio Code, Jupyter Lab, or Jupyter Notebook and run the cells sequentially to perform the analysis and view the visualizations.

## Project Structure

```
.
├── data/
│   └── us-store.xls      # Raw data file
├── venv/                 # Python virtual environment (ignored by git)
├── .gitignore            # Specifies intentionally untracked files that Git should ignore
├── main.ipynb            # Jupyter Notebook with the analysis code
└── README.md             # This file
```

## Libraries Used

*   Pandas
*   Plotly
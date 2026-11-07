
# Customer Churn Analysis & Customer Intelligence

An end-to-end Python data analysis project focused on understanding
customer churn, exploring customer and subscription behaviour, and
identifying factors associated with customer cancellations.

## Project Overview

Customer churn is an important business metric because losing existing
customers can affect recurring revenue and long-term customer
relationships. This project analyses customer, subscription, and
customer-support information to understand churn patterns and explore
how subscription details and support-related factors relate to customer
retention.

The analysis is performed in Python using data preparation, feature
engineering, exploratory analysis, and visualisation techniques.

## Objectives

-   Prepare and clean customer, subscription, and support data.
-   Create useful analytical features from existing fields.
-   Calculate the overall customer churn rate.
-   Explore churn across different plan types.
-   Examine the relationship between customer-support escalations and
    churn.
-   Present patterns through clear, interpretable visualisations.

## Tools & Technologies

  Tool / Library     Purpose
  ------------------ -------------------------------------------
  Python             Data analysis and processing
  Pandas             Data manipulation and cleaning
  NumPy              Numerical operations and feature creation
  Matplotlib         Data visualisation
  Seaborn            Statistical visualisation
  Jupyter Notebook   Interactive analysis environment

## Dataset & Key Fields

The notebook works with customer, subscription, and support-related
data. Fields used in the analysis include:

-   **Customer information:** `customerid`, `customer_name`, `country`,
    `state`, `gender`, `dob`
-   **Subscription information:** `subscription_start_date`,
    `subscription_type`, `renewal_date`, `plan_type`, `contract_type`
-   **Cancellation and billing-related indicators:**
    `cancellation_date`, `cancellation_reason`, `monthly_charges`,
    `cltv`
-   **Support information:** `complaint_date`, `escalations`,
    `csat_score`, `complaint_count`

The notebook creates additional analytical fields such as `churn_flag`,
`tenure_days`, `churn_risk`, and `cancellation_month`.

> Note: The README describes the fields and workflow visible in the
> analysis notebook. Add the dataset source, record count, and data
> licence here if those details are available and permitted to be
> shared.

## Project Workflow

1.  **Data loading and inspection** -- inspect the available customer,
    subscription, and support data.
2.  **Data cleaning** -- review data types, missing values, and data
    consistency before analysis.
3.  **Feature engineering** -- derive churn indicators and additional
    fields for analysis.
4.  **Exploratory data analysis** -- calculate churn metrics and compare
    churn patterns across customer and subscription attributes.
5.  **Visualisation** -- use Matplotlib and Seaborn to communicate
    patterns and relationships.
6.  **Export** -- export the prepared analysis dataframe to CSV for
    further use.

## Key Analysis & Findings

The notebook includes the following analysis:

-   **Overall churn rate:** The calculated churn rate in the notebook is
    **28.57%**.
-   **Churn by plan type:** Compares churn rates across different plan
    types.
-   **Support escalations and churn:** The notebook reports a
    correlation of **0.77** between support escalations and the churn
    indicator in the analysed data.

The correlation is an association in this dataset; it does not by itself
establish that escalations cause customers to churn.

## Visualisation

The analysis uses:

-   Matplotlib charts for churn comparisons and other analytical views.
-   Seaborn visualisations, including pairwise relationship exploration.

## How to Run the Project

1.  Clone this repository:

    ``` bash
    git clone https://github.com/NehaKumari990/Churn-Data-Analysis.git
    ```

2.  Move into the project directory:

    ``` bash
    cd Churn-Data-Analysis
    ```

3.  Install the required libraries:

    ``` bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

4.  Start Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

5.  Open the project notebook and run the cells in sequence.

## Repository Structure

``` text
Customer-Churn-Analysis/
│
├── Churn_Analysis.ipynb       # Main analysis notebook (add this if available)
├── Churn_Analysis.html        # Exported notebook (if included)
├── data/                      # Dataset files (add if permitted)
└── README.md
```

Update this structure to match the files actually uploaded to your
GitHub repository.

## Skills Demonstrated

-   Data cleaning and preprocessing
-   Exploratory Data Analysis (EDA)
-   Feature engineering
-   Customer churn metrics
-   Correlation analysis
-   Data visualisation
-   Python data analysis

## Future Improvements

-   Build an interactive dashboard for exploring churn metrics.
-   Add a predictive machine learning model to estimate customer churn
    risk.
-   Evaluate model performance using suitable classification metrics.
-   Develop actionable customer-retention recommendations based on
    validated findings.

## Author

**Neha Kumari**

-   GitHub: [NehaKumari990](https://github.com/NehaKumari990)
-   LinkedIn:
    [nehakumari1110](https://www.linkedin.com/in/nehakumari1110)

------------------------------------------------------------------------

If you find this project useful, feel free to ⭐ the repository.

# Supply Chain Business Analytics and Disruption Risk Analysis

## <u><strong>1. Project Overview</strong></u>

Supply chains involve multiple suppliers, purchase orders, quality checks, and delivery activities. Any delay, quality issue, or unreliable supplier can affect business operations, increase costs, and create supply chain disruptions.

This project focuses on analyzing supply chain data to identify supplier risks, operational issues, purchase order problems, and potential disruption-prone areas.

The project uses Python-based data analysis and visualization techniques to convert raw supply chain data into meaningful business insights. The processed results are then presented through an interactive Tableau dashboard to support data-driven decision-making.

## <u><strong>2. Problem Statement</strong></u>

Organizations often have large amounts of supply chain data, but raw data alone does not clearly show:

* Which suppliers are performing poorly.
* Which suppliers have a high risk of disruption.
* Which purchase orders are delayed or problematic.
* Which suppliers are associated with quality incidents.
* Which operational areas require management attention.
* What actions can be taken to reduce supply chain risks.

Without proper analysis, management may find it difficult to identify risks early and take corrective action.

Therefore, this project aims to build a data-driven supply chain analytics solution that analyzes supplier performance, purchase orders, quality incidents, and disruption-related information to identify risks and provide actionable recommendations.

## <u><strong>3. Project Objectives</strong></u>

The main objectives of this project are:

* Analyze raw supply chain datasets.
* Clean and preprocess the available data.
* Evaluate supplier performance and reliability.
* Analyze purchase order-related information.
* Identify quality incidents and recurring quality problems.
* Assess supplier-level disruption risk.
* Generate important executive-level KPIs.
* Identify suppliers requiring management attention.
* Generate business recommendations.
* Present the findings through a Tableau dashboard.

## <u><strong>4. Tools and Technologies Used</strong></u>

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Tableau
* CSV datasets
* GitHub

## <u><strong>5. Dataset Description</strong></u>

The project uses multiple supply chain datasets.

### Raw Datasets

* `parts_master.csv`
* `purchase_orders.csv`
* `quality_incidents.csv`
* `supply_chain_history.csv`

### Processed Datasets

* `disruption_scenario_analysis.csv`
* `executive_kpi_summary.csv`
* `management_actions.csv`
* `purchase_orders_processed.csv`
* `quality_incidents_processed.csv`
* `supplier_features.csv`
* `supplier_master.csv`
* `supplier_recommendations.csv`
* `supplier_risk_assessment.csv`
* `top_disruption_suppliers.csv`

The raw datasets were cleaned, transformed, and processed to generate analytical datasets that could be used for supplier risk analysis, KPI generation, and dashboard creation.

## <u><strong>6. Proposed Solution</strong></u>

The problem was solved through a complete data analytics workflow.

### Step 1: Data Collection

The available supply chain datasets were collected in CSV format. These datasets contained information related to suppliers, parts, purchase orders, quality incidents, and supply chain activities.

### Step 2: Data Cleaning and Preprocessing

The raw data was cleaned and prepared for analysis.

The preprocessing activities included:

* Checking missing values.
* Checking duplicate records.
* Correcting data types.
* Standardizing column names.
* Handling inconsistent values.
* Preparing date-related columns.
* Combining relevant datasets.
* Creating analysis-ready datasets.

### Step 3: Feature Engineering

Relevant features were created from the available data to evaluate supplier and operational performance.

These features were used to analyze:

* Supplier reliability.
* Purchase order performance.
* Quality incident frequency.
* Delivery-related issues.
* Supplier risk.
* Disruption-related indicators.

### Step 4: Supplier Risk Analysis

Supplier-level information was analyzed to identify suppliers with higher operational risk.

The supplier risk assessment considered available indicators such as:

* Delivery performance.
* Purchase order issues.
* Quality incidents.
* Supplier reliability.
* Disruption-related factors.

### Step 5: KPI Generation

Important executive-level KPIs were generated to provide a summarized view of supply chain performance.

These KPIs help management understand the current condition of suppliers, purchase orders, quality incidents, and disruption risk.

### Step 6: Management Recommendations

Based on the analysis, supplier recommendations and management actions were generated.

These recommendations help identify:

* Suppliers requiring closer monitoring.
* Suppliers with recurring issues.
* Areas where corrective action may be needed.
* Possible actions for reducing disruption risk.

### Step 7: Tableau Dashboard

The processed datasets were connected to Tableau to create an interactive dashboard.

The dashboard presents the major findings in a visual and management-friendly format.

## <u><strong>7. Analysis Performed</strong></u>

### 7.1 Supplier Performance Analysis

This analysis evaluates supplier-level performance and helps identify reliable and unreliable suppliers.

The analysis focuses on:

* Supplier performance comparison.
* Supplier reliability.
* Purchase order-related performance.
* Quality-related issues.
* Supplier risk levels.

### 7.2 Purchase Order Analysis

Purchase order data was analyzed to understand order-related performance and possible operational issues.

The analysis focuses on:

* Purchase order status.
* Delayed or problematic orders.
* Supplier-wise order performance.
* Order-related disruption indicators.

### 7.3 Quality Incident Analysis

Quality incident data was analyzed to identify recurring quality problems and suppliers associated with those problems.

The analysis focuses on:

* Number of quality incidents.
* Supplier-wise quality issues.
* Frequently occurring problems.
* Quality-related operational risks.

### 7.4 Supplier Risk Assessment

A supplier risk assessment was created to classify and compare suppliers based on available risk indicators.

This analysis helps answer:

* Which suppliers have the highest risk?
* Which suppliers require management attention?
* Which suppliers may affect supply chain continuity?
* Which suppliers should be monitored more closely?

### 7.5 Supply Chain Disruption Analysis

The project analyzes disruption-related indicators to identify suppliers and operational areas that may contribute to supply chain disruptions.

This analysis supports early risk identification and better supplier management.

### 7.6 Executive KPI Analysis

An executive KPI summary was generated to provide a high-level overview of supply chain performance.

The KPIs help management monitor:

* Supplier performance.
* Purchase order activity.
* Quality incidents.
* Disruption risk.
* Operational performance.

## <u><strong>8. Key Findings</strong></u>

The final findings should be updated based on the actual results generated from the notebooks and processed datasets.

The analysis is intended to identify:

* The suppliers with the highest disruption risk.
* Suppliers with frequent quality incidents.
* Suppliers with poor purchase order performance.
* Operational areas requiring improvement.
* The most important supply chain risk indicators.
* Suppliers requiring corrective action or closer monitoring.

### Important Findings from the Analysis

1. **Highest-risk suppliers:**
   Add the names of the highest-risk suppliers identified in `supplier_risk_assessment.csv`.

2. **Top disruption-prone suppliers:**
   Add the suppliers identified in `top_disruption_suppliers.csv`.

3. **Quality-related findings:**
   Add the major quality issues and the suppliers associated with them.

4. **Purchase order findings:**
   Add the important purchase order-related patterns discovered during analysis.

5. **Executive KPI findings:**
   Add the major KPIs from `executive_kpi_summary.csv`.

6. **Management actions:**
   Add the most important recommendations from `management_actions.csv`.

## <u><strong>9. Business Impact</strong></u>

This project can support supply chain management in the following ways:

* Helps identify high-risk suppliers.
* Supports early identification of potential disruptions.
* Improves supplier monitoring.
* Helps management understand quality-related problems.
* Supports better purchase order management.
* Makes supply chain KPIs easier to understand.
* Helps prioritize corrective actions.
* Supports data-driven supplier selection and evaluation.
* Improves visibility into supply chain performance.

The main impact of the project is that it converts raw operational data into useful insights that can support better planning, risk management, and business decisions.

## <u><strong>10. Tableau Dashboard</strong></u>

The Tableau dashboard provides an interactive view of the project findings.

The dashboard includes analysis related to:

* Executive-level KPIs.
* Supplier risk assessment.
* Top disruption-prone suppliers.
* Purchase order performance.
* Quality incidents.
* Supplier recommendations.
* Management actions.

The dashboard is designed to help users quickly identify important supply chain issues and focus on areas requiring attention.

## <u><strong>11. Project Workflow</strong></u>

```text
Raw Supply Chain Data
        |
        v
Data Cleaning and Preprocessing
        |
        v
Feature Engineering
        |
        v
Supplier Performance Analysis
        |
        v
Purchase Order and Quality Analysis
        |
        v
Supplier Risk and Disruption Assessment
        |
        v
KPI Generation
        |
        v
Management Recommendations
        |
        v
Tableau Dashboard
```

## <u><strong>12. Project Structure</strong></u>

```text
business_analytics_project1/
│
├── data/
│   ├── raw/
│   │   ├── parts_master.csv
│   │   ├── purchase_orders.csv
│   │   ├── quality_incidents.csv
│   │   └── supply_chain_history.csv
│   │
│   └── processed/
│       ├── disruption_scenario_analysis.csv
│       ├── executive_kpi_summary.csv
│       ├── management_actions.csv
│       ├── purchase_orders_processed.csv
│       ├── quality_incidents_processed.csv
│       ├── supplier_features.csv
│       ├── supplier_master.csv
│       ├── supplier_recommendations.csv
│       ├── supplier_risk_assessment.csv
│       └── top_disruption_suppliers.csv
│
├── notebooks/
│   └── Data analysis and preprocessing notebooks
│
├── tableau/
│   └── Tableau dashboard files
│
├── docs/
│   └── Project documentation
│
└── README.md
```

## <u><strong>13. How to Run the Project</strong></u>

### Clone the Repository

```bash
git clone https://github.com/vatsalagrawal08/Supplier-Risk-Disruption-Analytics
```

### Open the Project Folder

```bash
cd Supplier-Risk-Disruption-Analytics
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Start Jupyter Notebook

```bash
jupyter notebook
```

Run the notebooks available inside the `notebooks/` folder.

### Open the Tableau Dashboard

Open the Tableau workbook available inside the `tableau/` folder.

## <u><strong>14. Project Author</strong></u>

**Vatsal Agrawal**

## <u><strong>15. Project Status</strong></u>

**Status:** Completed

## <u><strong>16. License</strong></u>

This project was created for academic and educational purposes.


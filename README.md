# PLP Data Analytics Assignment 3
## Duka Sales Analysis and Mobile Money Agent Data Cleaning

This repository contains two data analytics engagements completed as part of the PLP Data Analytics programme.

## Engagement 1: Duka Electronics Sales Analysis

The first engagement explores sales transactions from Duka Electronics between January and June 2026.

The analysis covers:
- Initial data inspection and quality assessment.
- Revenue calculation and derived variables.
- Branch performance and ranking.
- Product performance by revenue and units sold.
- Weekday versus weekend sales comparisons.
- Monthly revenue trends.
- Filtering Premium Online orders from Nairobi and Mombasa.
- Excel analysis using SUMIFS, XLOOKUP and PivotTables.

### Key deliverables
- `duka_sales_exploration.ipynb`: Python sales analysis.
- `excel/duka_branch_summary.xlsx`: Excel workbook containing branch summaries and a PivotTable.
- `outputs/premium_online_coast_capital.csv`: Filtered Premium Online orders from Nairobi and Mombasa.

## Engagement 2: Mobile Money Agent Data Cleaning

The second engagement focuses on auditing and cleaning a mobile money agent transaction dataset.

It includes data quality assessment, transaction standardisation, duplicate handling, missing-value treatment, outlier identification, agent information merging and summary reporting.

### Planned deliverables
- `cleaning_pipeline.py`
- `agent_cleanup.ipynb`
- `outputs/agent_transactions_clean.csv`

## Repository Structure

```text
plp-da-a3-duka-sales-and-agent-cleanup/
│
├── README.md
├── requirements.txt
├── generate_data.py
├── duka_sales_exploration.ipynb
├── excel/
│   └── duka_branch_summary.xlsx
├── outputs/
│   └── premium_online_coast_capital.csv
│
└── .gitignore
```

Additional files for the second engagement will be added as the project progresses.

## Data Generation

The datasets are generated using `generate_data.py`.

Run:

```bash
python generate_data.py
```

This generates the source CSV datasets required for both engagements.

The generated raw datasets are excluded from version control. Run the generator locally to recreate them.

## Installation

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Google Sheets
- Microsoft Excel-compatible `.xlsx` files

## Data Handling

Raw generated datasets and temporary working files are excluded from the GitHub repository. Processed outputs required by the assignment are stored in the `outputs/` directory.

# Customer Behavior Analysis

### 🐍 Python | 🐘 PostgreSQL | 📊 Power BI

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="60"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="60"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" width="60"/>
</p>

**SQL • Python • Power BI**

---

## Project snapshot

A modular data analysis project that explores customer behaviour across transactions, cohorts, and product interactions. This repository contains SQL objects (schema & queries), Python notebooks/scripts for data transformation and modeling, and Power BI reports for interactive visual exploration and dashboards.

> **Goal:** Turn raw transaction and engagement data into actionable insights for marketing, product, and retention teams.

---

## Tech stack ⚙️

* **SQL**: ETL queries, staging, aggregation, cohort analysis.
* **Python**: data cleaning, feature engineering, EDA, simple predictive models, notebooks (Jupyter / .py scripts).
* **Power BI**: polished dashboards for stakeholders (KPI, funnel, retention, segment explorer).

---

## Quick start

1. Clone the repo:

```bash
git clone https://github.com/Orange5994/Customer_Shopping_Behaviour_analysis.git
cd Customer_Shopping_Behaviour_analysis
```

2. Create a Python virtual environment and install dependencies (example):

```bash
python -m venv venv
source venv/bin/activate   # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
# Or install manually
pip install numpy pandas
```

3. Load sample data / connect to your database following `docs/CONNECTIONS.md`.
4. Run the example notebook `notebooks/01-explore-customers.ipynb` or the SQL scripts in `sql/` to build the analytical tables.

---

## How to run the pieces

### SQL

* `sql/01_staging.sql` — creates staging tables.
* `sql/02_aggregations.sql` — builds aggregated customer-level tables used by notebooks and Power BI.

Run via your SQL client or command line (psql / sqlcmd) per `docs/CONNECTIONS.md`.

### Python

* Notebooks are ordered numerically (01, 02, ...).
* `notebooks/01-explore-customers.ipynb` — exploratory data analysis with visualizations and summary statistics.
* `scripts/data_pipeline.py` — example script to extract from DB and save cleaned CSVs.

### Power BI

* Power BI Desktop file(s) live in `powerbi/`. See `powerbi/README.md` for instructions to point visuals at local CSVs or direct DB.

---

## Key deliverables / example analyses

* RFM segmentation and segment-level revenue trends.
* Churn & retention curves (cohort analysis).
* Product funnels and conversion rates across customer journeys.
* Top drivers of customer spending (feature importance from simple models).

---

## Contributing

1. Fork the repo and open a feature branch.
2. Add tests or a notebook demonstrating your change when appropriate.
3. Open a pull request describing the change and linking any associated issue.

See `CONTRIBUTING.md` for more details.

---

## License

This repository is released under the MIT License. See `LICENSE`.

---

## Contact

Project owner: Your Name — replace with your email or GitHub handle.

---

**Want it trimmed or expanded?** I can make a shorter landing page or add sections (badges, screenshot placeholders, sample queries) — tell me which and I’ll update the README.

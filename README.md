# 💍 World Marriage Statistics Analysis

This project explores global patterns in marriage data based on gender, age group, country, and time. The dataset includes observations from dozens of countries over multiple decades and allows for deep demographic insights.

## 📌 Objectives

Analyze how marriage trends vary across:
- Different age groups
- Genders
- Countries and regions
- Time periods

This project uses a complete modern data stack:

- **Python** for data cleaning
- **PostgreSQL** for structured storage
- **dbt** for modeling and transformation
- **Tableau** for data visualization
- **GitHub + VSCode** for version control and collaboration

## 📁 Project Structure

```
world-marriage-analysis/
│
├── data/                      # Cleaned and raw datasets
├── notebooks/                 # Jupyter Notebooks for exploration and EDA
├── sql/                       # SQL queries for PostgreSQL
├── dbt_project/               # dbt models and configs
├── tableau/                   # Tableau workbooks/screenshots
├── scripts/                   # Python scripts for cleaning and loading
├── README.md
└── .gitignore
```

## ⚙️ Workflow

1. **Clean and prepare the dataset** using Python (pandas)
2. **Import cleaned data** into PostgreSQL
3. **Build dbt models** for transforming the data into insights (e.g. summary tables)
4. **Create Tableau dashboards** visualizing patterns by country, gender, age
5. **Version control** the entire project with Git and GitHub

## 💡 Sample Questions

- At what age do most people get married across different countries?
- Which gender has a higher marriage rate in each country?
- How have marriage and divorce rates changed over time?
- Which regions have the highest proportion of never-married individuals?

## 📊 Tools Used

| Tool       | Purpose                    |
|------------|----------------------------|
| Python     | Data cleaning and export   |
| PostgreSQL | Data storage and queries   |
| dbt        | Data modeling and logic    |
| Tableau    | Data visualization         |
| GitHub     | Collaboration & versioning |
| VSCode     | Code development           |

---


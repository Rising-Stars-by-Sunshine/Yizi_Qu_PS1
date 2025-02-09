# Data Overview

## 1. Data Source
This study utilizes data from the **China Family Panel Studies (CFPS)** for the years **2010, 2012, and 2014**. CFPS is a **longitudinal survey** that collects rich information on **child development, family structure, and socio-economic conditions** in China. The dataset includes key indicators for **psychological well-being, physical health, and cognitive development**, allowing for an in-depth analysis of the effects of **parental absence on child outcomes**.

---

## 2. Data Dictionary

| Variable Name         | Description                                      | Type     |
|----------------------|------------------------------------------------|---------|
| `id`                 | Unique identifier for each child               | Integer |
| `year`               | Survey year (2010, 2012, 2014)                 | Integer |
| `happiness_score`    | Self-reported happiness level (1-10)           | Integer |
| `sickness`          | Whether the child was sick in the past month (Yes/No) | Categorical |
| `math_score`         | Standardized math test score                   | Float   |
| `word_score`         | Standardized word test score                   | Float   |
| `parental_absence`   | Parent status (Both present, Father absent, Mother absent, Both absent) | Categorical |
| `age`               | Child’s age in years                            | Integer |
| `gender`            | Child’s gender (Male/Female)                   | Categorical |
| `ethnicity`         | Ethnic group of the child                      | Categorical |
| `economic_status`   | Household economic level (Low/Middle/High)     | Categorical |
| `community_type`    | Rural or urban classification                   | Categorical |

---

## 3. File Information
- **File Format**: `.dta` (Stata)
- **Size**: ~50MB per year
- **Missing Data Handling**: Standard imputation techniques applied
- **Confidentiality**: Personally identifiable information (PII) removed

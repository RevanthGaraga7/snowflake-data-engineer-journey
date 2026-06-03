# ❄️ Snowflake Data Engineer Journey

<div align="center">

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

![Certification](https://img.shields.io/badge/SnowPro%20Associate-Platform%20Certified-brightgreen?style=flat-square)
![Labs](https://img.shields.io/badge/Labs%20Completed-9%20%2F%209-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

</div>

---

## 👋 About This Repository

This repository documents my complete journey through **Snowflake Ascent: Platform Training** — from zero to certified.

I completed **9 hands-on labs**, attended virtual workshops, and earned two official Snowflake credentials:

- 🏅 **SnowPro Associate: Platform** — Snowflake's industry-recognized certification
- 🎓 **Ascent: Snowflake Platform Training** — Official training completion certificate

Everything here reflects real, working code written and tested inside Snowflake Notebooks.

---

## 🎓 Certifications Earned

| Certification | Issuing Body | Date | Valid Until |
|---|---|---|---|
| SnowPro Associate: Platform | Snowflake | May 2026 | May 2028 |
| Ascent: Snowflake Platform Training | Snowflake | May 2026 | No Expiry |

> 📄 Certificate PDFs are available in the [`/certificates`](./certificates/) folder.

---

## 📚 Labs Completed (9 / 9)

| # | Lab Title | Key Concepts |
|---|---|---|
| 01 | Interacting with Snowflake | Snowsight UI, Notebooks, SQL & Python cells |
| 02 | Identity and Access | Roles, privileges, database creation, ownership |
| 03 | Database Object Hierarchy | SHOW commands, INFORMATION_SCHEMA |
| 04 | Tables, Data Types & Loading | CREATE TABLE, INSERT, RENAME, ILIKE, LIMIT |
| 05 | Warehouses and Context | Virtual warehouses, auto-suspend, scaling |
| 06 | Load Wizard & Marketplace | COPY INTO, zero-copy cloning, data sharing |
| 07 | Check Your Code | Query history, Time Travel, metadata queries |
| 08 | Stages & Semi-Structured Data | Stages, VARIANT type, JSON parsing with `:` |
| 09 | Unstructured Data & Cortex LLM | PARSE_DOCUMENT, CLASSIFY_TEXT, TRANSLATE, SUMMARIZE, COMPLETE |

---

## 🛠️ Technical Skills Demonstrated

### ❄️ Snowflake Core
- Virtual Warehouses (XSMALL → 4XLARGE), auto-suspend & resume
- **Time Travel** — query historical data using `BEFORE(STATEMENT => $query_id)`
- **Zero-copy cloning** — instant table/schema backups
- External stages pointing to S3 (`s3://uni-lab-files`)
- Directory tables for file-level metadata

### 📦 Data Loading
- `COPY INTO` for bulk data ingestion
- File formats: CSV, TSV, JSON, Parquet
- Internal and external stage management

### 🗂️ Semi-Structured Data
- `VARIANT` data type for storing raw JSON
- JSON key extraction: `column:key::datatype` syntax
- Flattening nested JSON structures

### 🤖 Snowflake Cortex AI
| Function | Purpose |
|---|---|
| `PARSE_DOCUMENT()` | Extract text from PDFs using OCR |
| `CLASSIFY_TEXT()` | Auto-categorize text into labels |
| `TRANSLATE()` | Translate between languages (e.g., EN ↔ ES) |
| `SUMMARIZE()` | Generate summaries from long text |
| `COMPLETE()` | Run LLM prompts / build RAG pipelines |

---

## 📂 Repository Structure

```
snowflake-data-engineer-journey/
│
├── README.md
│
├── labs/
│   ├── ob_lab_1_interacting_with_snowflake.ipynb
│   ├── ob_lab_2_identity_and_access.ipynb
│   ├── ob_lab_3_database_object_hierarchy.ipynb
│   ├── ob_lab_4_tables_datatypes_loading_data.ipynb
│   ├── ob_lab_5_warehouses_and_context.ipynb
│   ├── ob_lab_6_load_wizard_marketplace.ipynb
│   ├── ob_lab_7_check_your_code.ipynb
│   ├── ob_lab_8_stages_and_semi_structured_data.ipynb
│   └── ob_lab_9_unstructured_data_cortex_llm_functions.ipynb
│
├── certificates/
│   ├── clmsCertificate.pdf
│   └── SnowPro_Associate_Platform.pdf
│
└── Screenshots/
    
```

---

## 🚀 How to Explore

1. **Browse the labs** — Each `.ipynb` file has completed SQL/Python code with markdown explanations
2. **Check the certificates** — `/certificates` folder holds both official PDFs

---

## 📅 Timeline

| Milestone | Date |
|---|---|
| Snowflake Account Created | April 7, 2026 |
| Completed All 9 Labs | April 2026 |
| Earned Ascent Certificate | April 2026 |
| Passed SnowPro Associate Exam | May 2026 |

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/garagasravanrevanth)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RevanthGaraga7)

---

<div align="center">
  <sub>⭐ If this helped you, consider giving the repo a star!</sub>
</div>


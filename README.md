# Supabase Challenge – Resale Pipeline

This repository contains my resale data pipeline using:

- Meltano (ELT)
- dbt (Transformation)
- Dagster (Orchestration)

---

## ✅ Before You Start (Important)

Please create both Conda environments first.

### 1️⃣ Create ELT Environment (eltn)

```bash
conda env create -f eltn_environment.yml
conda activate eltn

conda env create -f dagstern_environment.yml
conda activate dagstern

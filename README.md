# Digital-Twin

# Genomic, Demographic & Survival Data for Digital Twin Analysis

This repository contains **example input files** and **format guidelines** for running the Digital Twin–based genomic, demographic, and survival analysis pipeline.

Please carefully follow the instructions below before uploading data into the Shiny application.

---

## 📁 Files in This Repository

The repository includes example CSV files corresponding to each required data component:

1. `1.genomic_database.csv`  
2. `2.genomic_new_patients.csv`  
3. `3.demographic_part_database.csv`  
4. `4.demographic_new_patients.csv`  
5. `5.outcome_data_database.csv`  
6. `6.medication_database.csv`  

These files serve as **templates** demonstrating the required structure and naming conventions.

---

## ❗ Mandatory Data Format Requirements

### 1️⃣ Patient Identifier Column (Required)

- **The FIRST column of every file must be named exactly:**

```text
Patient.ID

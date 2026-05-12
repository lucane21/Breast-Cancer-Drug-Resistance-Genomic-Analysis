Translational Oncology Cohort Analysis — Breast Cancer (BRCA)

Project overview

This project looks at breast cancer data to understand patterns across cohorts by exploring how patients differ in terms of molecular subtype, clinical characteristics, and treatment response.
I used public datasets from TCGA-BRCA (via cBioPortal).

Data source

The dataset comes from TCGA-BRCA (The Cancer Genome Atlas), accessed through cBioPortal.

It includes:

clinical information (age, stage, survival)
genomic data (mutations like TP53, BRCA1/2, HER2)
molecular subtypes
treatment and outcome-related variables (where available)

How I approached it

I structured the analysis around cohorts and looked for patterns across these groups.

Project structure
1. Cohort definition

First step is defining meaningful patient groups based on:

molecular subtype
mutation status (TP53, BRCA1/2, HER2)
clinical outcomes
2. Data preparation (SQL)

I used SQL to:

combine clinical and genomic data
build unified patient-level tables
define cohorts for analysis
3. Exploratory analysis (Python)

Then I explored:

distributions of clinical variables
differences between cohorts
basic relationships between mutations and outcomes
4. Dashboard (Power BI)

Finally, I built a simple dashboard to visualize:

cohort composition
subtype distribution
treatment response patterns
outcome differences across groups

🔍 Key questions I looked at
Do different molecular subtypes behave differently in terms of outcomes?
Are certain mutations associated with worse clinical progression?
How do response patterns vary across patient groups?
Can we observe consistent trends across cohorts?
🧬 What this project is meant to reflect

This is not a machine learning project.

It’s closer to how data is actually explored in translational oncology environments:

clinical interpretation first
structured cohorts
descriptive + comparative analysis
focus on biological meaning rather than model accuracy
💼 Skills used
SQL for cohort building and data integration
Python for exploratory analysis
Power BI for visualization
Clinical data understanding (oncology context)
Translational thinking (clinical ↔ data bridge)
📌 Relevant roles

This project is aligned with roles like:

Healthcare Data Analyst
Clinical Data Analyst
Oncology Data Analyst
Real World Evidence Analyst (junior)
Clinical Analytics Associate
👩‍🔬 About me

Lucía Cané, PhD
Translational Oncology & Healthcare Data Analytics
Barcelona, Spain

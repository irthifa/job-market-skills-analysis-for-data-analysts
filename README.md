# Job-Market Skills Analysis for Data Analyst Role

Analysis of real Data Analyst job postings to identify the most in-demand tools and skills, and how they cluster together. Built to guide my own skill-building priorities for data analyst roles.

## What this project does
- Cleans and validates ~19,039 real job postings from Luke Barousse's Data Analyst Job Postings dataset (Kaggle)
- Extracts and standardises mentioned skills (Python, SQL, Power BI, Excel, Tableau, etc.)
- Identifies top skills by frequency and which skills tend to be required together
- Visualises findings in an interactive Tableau Public dashboard

## Tools used
- Python (pandas, matplotlib)
- Tableau Public
- Kaggle dataset

## Data source
[Data Analyst Job Postings (Google Search)](https://www.kaggle.com/datasets/lukebarousse/data-analyst-job-postings-google-search) — Kaggle

## Data quality steps taken
- Removed exact duplicate postings
- Filtered to relevant job titles
- Standardised inconsistent skill naming (e.g. "power_bi" → "Power BI")
- Dropped postings with missing/unparseable skill data

## Key findings
- SQL is the single most in-demand skill, appearing in 67.6% of all postings analysed
- 107 distinct skills/tools were identified across the dataset
- Python and SQL are the strongest skill pairing overall, co-occurring in 6,031 postings.
- SQL and Tableau form the next-closest pairing, behind only Python and SQL pair.
- Skill demand also shifts noticeably by location. Filtering to Washington, DC postings, the top skills become Excel, PowerPoint, Word, and Tableau. SQL and Python don't appear at all, a sharp contrast to the overall ranking. This suggests DC's "data analyst" postings lean more toward reporting/presentation and BI tools than general-purpose programming. 

## Dashboard
- ![dashboard screenshot](/Dashboard.png)
- [Live dashboard link](https://public.tableau.com/shared/DYN5XK3WN)

## Author 
irthifa ikram

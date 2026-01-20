# CFPB Data Insights
## Goal-
Analyze CFPB (Consumer Financial Protection Bureau) consumer complaint data to identify trends, recurring issues, and potential risk signals across products, companies, and time.

## Scope
### In scope
Exploratory data analysis (EDA): volumes, trends, distributions
Data cleaning/standardization (dates, product/issue labels, company names)
Aggregations and benchmarking (by product, issue, company, geography)
Optional text analysis on narratives (topic themes, keywords)
### Out of scope (for now)
Causal claims about company behavior
Linking to internal/third-party customer data
Automated regulatory conclusions (this is an analytics project)

## Dataset
Source: CFPB Consumer Complaint Database (public)
Typical fields: received date, product/issue, company, state/ZIP (partial), submission channel, company response, timeliness, consumer dispute, narrative text (if provided).

## Current Status

[x] Ingest raw dataset
[ ] Data profiling + quality checks
[ ] Cleaning + standardization
[ ] EDA visuals and summary tables
[ ] (Optional) Narrative NLP
[ ] Findings summary

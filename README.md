# Loan Risk Analysis- Overview

## Goal
Enable end-to-end development and evaluation of predictive models for lending decisions by providing a synthetic, privacy-safe dataset that supports:
Risk score regression (predict a continuous risk score)
Loan approval classification (predict approve/deny outcome)

## Scope
### In Scope
Building and comparing models for: 
Continuous risk scoring (regression)
Loan approval prediction (binary classification)
Feature engineering and selection using provided attributes (e.g., income-to-debt proxies)
Model evaluation (e.g., RMSE/MAE for regression; accuracy/precision/recall/AUC for classification)
Testing workflows: data prep, train/validation splits, bias/robustness checks (within synthetic limits)
Communicating insights: drivers of risk/approval using explainability methods (e.g., feature importance)

### Out of scope (for now)
Making real underwriting decisions or production credit policy from this dataset alone
Claiming regulatory, compliance, or fairness conclusions applicable to real populations
Calibrating models to real default rates, loss given default, or portfolio economics without real data
Any assertion that patterns reflect actual consumer behavior (synthetic data may embed artifacts)
Identity resolution, fraud verification, KYC/AML, or linking to external consumer files without explicit fields and governance

## About the Dataset
This is a synthetic dataset of 20,000 applicant records containing representative personal and financial attributes commonly used in credit and underwriting analytics. It includes features spanning demographics, credit history, employment status, income, existing debt, and related financial metrics, designed to simulate real-world lending signals for modeling, experimentation, and benchmarking—without using real consumer data.

## Current Status
### Ingest raw dataset [x]
### Data profiling + quality checks [x]
### Cleaning + standardization [x]
### 

## Findings and Summary (Updates going forward)


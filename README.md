# Cotiviti Practicum – CMS Medicare IRF Data Analysis

## Project Overview

This repository contains work completed as part of my Fall 2026 Biomedical Informatics practicum with Cotiviti.

The project focuses on exploring publicly available CMS Medicare data to identify meaningful patterns in healthcare utilization, provider characteristics, patient populations, and Medicare payments.

The initial phase of the project is exploratory. Findings from this analysis will be used to develop and refine a focused research question for subsequent analysis.

## Dataset

**CMS Medicare Post Acute Care Utilization – Inpatient Rehabilitation Facility (IRF) by Geography and Provider**

Current analysis uses the **2024 provider level dataset**.

The dataset contains information related to:

- Inpatient rehabilitation facility utilization
- Medicare beneficiaries
- Episode/stay counts
- Service days
- Medicare charges and payments
- Beneficiary demographics
- Beneficiary risk scores
- Chronic health conditions
- Primary diagnosis categories
- Physical therapy (PT)
- Occupational therapy (OT)
- Speech/language pathology (SLP)

## Phase 1 – Exploratory Data Analysis

**Timeline:** August 24 – September 11, 2026

The purpose of Phase 1 is to understand the structure, quality, and characteristics of the CMS IRF dataset before developing a formal research question.

### Current Analysis

Initial exploratory analysis includes:

- Reviewing dataset structure and variables
- Separating national, state, and provider level records
- Identifying CMS suppressed values
- Evaluating data types and data quality
- Examining provider level utilization
- Calculating average days per stay
- Calculating Medicare payment per stay
- Comparing beneficiary risk scores with Medicare payment
- Comparing length of stay with Medicare payment
- Examining variation and potential outliers across providers

## Preliminary Observations

Early exploration shows substantial variation in Medicare payment per stay among IRF providers.

Initial analysis also suggests that:

- Length of stay has a moderate positive relationship with Medicare payment per stay.
- Beneficiary average risk score has little apparent linear relationship with Medicare payment per stay.
- Medicare payment per stay is right-skewed, with a relatively small number of providers showing substantially higher payments.
- CMS data suppression is common in several demographic, diagnosis, and chronic condition variables and will need to be considered in future analyses.

These findings are preliminary and are being used to guide further investigation rather than represent final conclusions.

## Phase 2 – Data Preparation and Analysis

**Timeline:** September 14 – October 9, 2026

Phase 2 builds on the exploratory analysis completed during Phase 1. The focus of this phase is to prepare the data for formal analysis, further investigate the patterns identified during exploration, and refine the project research question.

### Current Goals

Phase 2 analysis will include:

- Cleaning and preparing the provider-level dataset for analysis
- Further evaluating CMS suppressed and missing values
- Identifying variables most relevant to Medicare payment and utilization
- Investigating variation and potential outliers in Medicare payment per stay
- Examining provider-level characteristics associated with payment variation
- Considering geographic, beneficiary risk, length of stay, diagnosis, and utilization factors
- Adding or merging additional datasets where needed
- Developing initial visualizations to examine important relationships and patterns
- Using findings to refine and finalize the research question

### Current Research Direction

Phase 1 identified substantial variation in Medicare payment per stay among IRF providers. Phase 2 will further investigate this variation and explore which provider, utilization, beneficiary, or geographic characteristics may help explain these differences.

Particular attention will be given to distinguishing variation that may be related to Medicare payment methodology from variation occurring at the provider level.

### Cotiviti Feedback

Feedback from the Cotiviti practicum team will be used throughout Phase 2 to evaluate:

- Whether the findings support the developing research question
- Whether important variables, comparisons, or datasets are missing
- Alternative approaches that may be useful for investigating the observed patterns
- Which findings should be prioritized for further analysis

### Phase 2 Milestone

By the end of Phase 2, the goal is to have an **analysis ready dataset, a finalized research question, and initial visualizations and analyses that provide direction for the next phase.**

## Potential Research Directions

Future analysis may investigate whether variation in Medicare utilization or payment is associated with:

- Geographic location
- Length of stay
- Beneficiary risk
- Patient demographics
- Chronic health conditions
- Primary diagnosis categories
- Therapy utilization
- Provider level characteristics

The potential research directions identified during Phase 1 will be further evaluated and refined into a final research question during Phase 2.

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- GitHub
- Claude/VS Code 

## Project Status

**Academic Term:** Fall 2026

**Program:** University of Utah – Biomedical Informatics MS

**Practicum Partner:** Cotiviti

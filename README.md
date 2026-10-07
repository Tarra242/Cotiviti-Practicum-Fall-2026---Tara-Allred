# Cotiviti Practicum – Fall 2026

## Medicare IRF Temporal Payment and Anomaly Analysis

This practicum uses publicly available CMS Medicare Post Acute Care Utilization data for Inpatient Rehabilitation Facilities (IRFs) to explore provider level payment patterns over time.

The project focuses on using temporal analysis and provider peer comparisons to identify unusual payment patterns that may warrant further investigation within a Fraud, Waste, and Abuse (FWA) framework.

**Important:** Statistical anomalies identified in this project are screening signals and are not evidence of fraud.

---

## Data

CMS Medicare Post Acute Care Utilization – Inpatient Rehabilitation Facility by Geography and Provider

Years included:
- 2022
- 2023
- 2024

The original 2024 dataset was expanded to include 2022 and 2023 to support longitudinal analysis.

---

## Phase 1 – Dataset Exploration ✅

- Explored CMS IRF dataset structure and variables
- Examined provider, payment, utilization, diagnosis, beneficiary, and therapy variables
- Evaluated initial payment patterns and potential outliers
- Used Cotiviti and Jorie Butler feedback to guide project direction

---

## Phase 2 – Data Cleaning and Preparation ✅

- Audited missingness and CMS suppression
- Developed KEEP / REVIEW / EXCLUDE framework
- Converted and validated numeric variables
- Performed family level quality checks
- Engineered per-stay payment and utilization measures
- Created consistent cleaning methodology across annual datasets
- Preserved suppressed values as missing rather than imputing values

Final annual datasets contain the original CMS variables plus engineered features for analysis.

---

## Phase 3 – Temporal and Anomaly Analysis ✅

Three year analysis was performed using 2022–2024 provider data.

### Provider Coverage

- 1,217 unique providers appeared across the three years
- 1,069 providers were present in all three years
- 3,207 provider year observations were included in the matched three year dataset

### Analysis

- Evaluated year to year payment changes
- Used robust modified Z-scores for anomaly screening
- Evaluated provider volume as a potential source of bias
- Developed volume based provider peer groups
- Compared global and peer adjusted anomaly detection
- Identified unusual provider payment trajectories
- Examined three year patterns including continued changes and reversals
- Evaluated volume, beneficiary risk, and therapy utilization as possible explanations

The peer adjusted payment screen identified 40 candidate providers with unusual changes across multiple payment measures.

Thirty of these providers had complete 2022–2024 histories and were included in the three year trajectory analysis.

### Three-Year Standardized Payment Trajectories

- Reversal Up: 11
- Continued Increase: 11
- Reversal Down: 7
- Continued Decrease: 1

Changes in provider volume showed little relationship with changes in standardized payment per stay among the 30 candidates.

These findings support using longitudinal patterns and peer comparisons to prioritize providers for additional investigation rather than interpreting a single unusual payment value as evidence of FWA.

---

## Phase 4 – Candidate Investigation

Next steps:

- Conduct a targeted literature review on Medicare FWA and healthcare anomaly detection
- Identify common analytical approaches and gaps in existing work
- Investigate selected candidate providers
- Explore potential explanations for unusual payment trajectories
- Determine what cannot be explained using provider level CMS data
- Identify where claims level data would be required for deeper FWA investigation

---

## Phase 5 – Final Project

- Refine and validate findings
- Compare results with relevant literature
- Develop Tableau visualizations
- Evaluate limitations and potential bias
- Finalize interpretation and conclusions
- Complete final paper and presentation

---

## Project Direction

The purpose of this project is not to determine whether a provider has committed fraud.

Instead, the project explores whether longitudinal provider payment patterns and peer adjusted anomaly detection can be used as a screening method to identify providers that may warrant more detailed review.

Provider level CMS data can help answer:

**Where should we look more closely?**

Claims level investigation would then be necessary to understand why an unusual payment pattern occurred and whether it has a legitimate explanation or represents potential FWA.

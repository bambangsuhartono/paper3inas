# PRASASTI IT Strategic Planning – Reproducibility Materials

This repository provides the reproducibility and calculation materials
supporting the validation of the PRASASTI framework proposed in the study.

The repository is intended to improve transparency by documenting the
data structure, calculation procedures, validation methods, expert
evaluation, Delphi consensus analysis, applicability assessment, and
gap analysis used in the research.

## 1. Research Context

PRASASTI is an integrated IT strategic planning framework combining
strategic planning, enterprise architecture, and IT governance concepts.

The validation procedure evaluates the framework using expert assessment
and does not represent a direct measurement of organizational maturity.
The resulting applicability index therefore represents expert-assessed
applicability and perceived implementation feasibility of the framework.

## 2. Data and Expert Evaluation

The validation dataset contains responses from 19 experts.

The expert assessment covers seven framework validation items:

1. Clarity of the framework concept
2. Completeness of framework components
3. Suitability of framework integration
4. Relevance of indicators
5. Process-flow integration
6. Organizational applicability
7. Clarity of framework outputs

The expert responses are used for content validation, agreement analysis,
reliability testing, Delphi consensus assessment, and applicability
evaluation.

## 3. Calculation Workbook

The main calculation file is:

2026-DSR kertas kerja Data & perhitungan - V 1.1.xlsx

The workbook contains the following calculation modules:

### Sheet Olah Data -Form Responses
This sheet is data quesioner form 19  expert

### Sheet 00 – Guide

This sheet documents the calculation logic and formulas used throughout
the analysis.

The main calculations include:

- Content Validity Ratio (CVR)
- Scale-level Content Validity Index, Average (S-CVI/Ave)
- Aiken's V
- Cronbach's Alpha
- Kendall's W
- Delphi IQR
- Applicability Gap
- Applicability Level

### Sheet 01 – Respondent Profile

This sheet summarizes the expert respondents according to their expertise
and professional background.

The percentage of each respondent category is calculated as:

Percentage = Number of respondents in category / Total respondents

### Sheet 02 – CVR and S-CVI/Ave

Content validity is evaluated using the Content Validity Ratio (CVR)
and item-level Content Validity Index (I-CVI).

The CVR formula is:

CVR = (Ne - N/2) / (N/2)

where:

Ne = number of experts identifying an item as relevant

N = total number of experts

The I-CVI is calculated as:

I-CVI = Ne / N

The scale-level content validity is summarized using:

S-CVI/Ave = Average(I-CVI)

### Sheet 03 – Aiken's V

Aiken's V is used to assess the degree of expert agreement regarding
the relevance and adequacy of each framework item.

The calculation is:

V = Σs / [n(c - 1)]

where:

s = r - lo

r = rating assigned by an expert

lo = lowest possible rating

n = number of experts

c = number of response categories

### Sheet 04 – Reliability and Consensus

Three complementary analyses are provided.

#### Cronbach's Alpha

Cronbach's Alpha evaluates internal consistency of the seven-item
assessment instrument.

The calculation follows:

α = k/(k-1) × [1 - Σσ²_item / σ²_total]

where:

k = number of items

σ²_item = variance of each item

σ²_total = total-score variance

#### Kendall's W

Kendall's coefficient of concordance is used to evaluate agreement
among the participating experts.

The calculation follows:

W = S / [m²(n³-n)/12]

where:

m = number of experts

n = number of items

S = sum of squared deviations of item ranks

#### Delphi IQR

The Delphi consensus measure is calculated as:

IQR = Q3 - Q1

Consensus is considered achieved when:

IQR ≤ 1

### Sheet 05 – Validation Summary

This sheet consolidates the principal validation results from the
previous calculation sheets.

The reported indicators include:

- CVR
- S-CVI/Ave
- Aiken's V
- Cronbach's Alpha
- Kendall's W
- Delphi IQR

Each result is linked to its corresponding source calculation sheet.

### Sheet 06 – Applicability Index and Gap Analysis

The applicability assessment consists of eight dimensions:

1. Strategic alignment
2. IS/IT portfolio planning
3. Enterprise architecture blueprint
4. Governance objective mapping
5. Risk and control integration
6. Capability assessment
7. Performance measurement
8. Implementation roadmap

The applicability gap is calculated as:

Gap = Target - Current

The current assessment values are compared with a target value of 85%.

The resulting gaps are used to identify dimensions requiring further
improvement.

### Sheet 07 – Dashboard

This sheet provides a consolidated view of:

- Number of experts
- CVR
- S-CVI/Ave
- Aiken's V
- Cronbach's Alpha
- Kendall's W
- Delphi IQR
- Average applicability
- Average target
- Average gap

## 4. Reproduction Procedure

To reproduce the reported calculations:

1. Open the calculation workbook.
2. Review the respondent data in the respondent-data sheet.
3. Verify the number of valid expert responses.
4. Review the seven validation items.
5. Recalculate CVR and I-CVI.
6. Calculate S-CVI/Ave from the item-level I-CVI values.
7. Calculate Aiken's V using the expert rating matrix.
8. Calculate Cronbach's Alpha from item-level variance and total-score
   variance.
9. Calculate Kendall's W using the expert ranking data.
10. Calculate Delphi IQR from Q1 and Q3.
11. Calculate the applicability index for each framework dimension.
12. Calculate the gap using Target - Current.
13. Review the consolidated results in the summary and dashboard sheets.

## 5. Reproducibility Principle

All reported statistics should be calculated from the original numerical
responses rather than from rounded presentation values.

For presentation purposes, numerical results may be rounded to two
decimal places. The underlying calculations retain the original numerical
precision.

## 6. Data Integrity

The repository preserves the calculation logic and data-processing
structure used in the study. Before reproduction, users should verify
that the number of relevant responses does not exceed the number of valid
expert responses and that all formulas reference the intended response
range.

## 7. Scope and Interpretation

The expert-validation results represent expert-assessed applicability
and perceived implementation feasibility of PRASASTI. They should not be
interpreted as direct evidence of organizational maturity, organizational
readiness, or post-implementation performance.

A real organizational implementation would be required to evaluate
actual implementation outcomes, resource requirements, decision changes,
and longitudinal performance.

## 8. License and Citation

Please cite the associated research article when using these materials.

The repository is intended solely to support transparency,
reproducibility, and verification of the reported calculations.

# BRCA1/2 Variant Analysis in Breast Cancer

## Overview
Analysed somatic variants in BRCA1 and BRCA2 genes using 
publicly available TCGA breast cancer WES data. Variants 
classified using ACMG/AMP criteria via Ensembl VEP.

## Objective
Identify pathogenic and likely pathogenic variants in a 
cohort of 50 breast cancer samples and generate a 
clinical-style variant report.

## Methods
- Data source: TCGA-BRCA (GDC portal, public access)
- Tools: Ensembl VEP, R (VariantAnnotation, ggplot2)
- Classification: ACMG/AMP 2015 criteria
- Databases used: ClinVar, gnomAD, COSMIC

## Key findings
- 12 pathogenic variants identified in BRCA1
- 7 likely pathogenic variants in BRCA2
- 3 variants of uncertain significance (VUS)

## Files
- analysis/variant_annotation.R — full annotated R script
- results/variant_report.pdf — clinical-style report
- results/plots/ — lollipop plots, frequency charts

## Skills demonstrated
R · VEP · ClinVar · ACMG classification · VCF analysis

## How to reproduce
1. Download data from GDC portal (link below)
2. Run analysis/variant_annotation.R in RStudio
3. Output saved to results/

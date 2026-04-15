# TP53-mutation-analysis
Reproducible analysis of TP53 mutation frequency and type distribution in breast cancer using TCGA-BRCA data.
# TP53 Mutation Analysis in Breast Cancer

## Data Source
- **Study:** TCGA Breast Invasive Carcinoma (BRCA)
- **Source:** [cBioPortal](https://www.cbioportal.org/study/summary?id=brca_tcga)
- **Patients:** 1,084

## Methodology
1. Downloaded mutation (MAF) and clinical data from cBioPortal.
2. Filtered mutations where Hugo_Symbol == "TP53".
3. Grouped by Variant_Classification to count mutation types.
4. Generated a bar chart of mutation type distribution.

## Results
![TP53 Mutation Types](figures/tp53_mutation_types.png)

TP53 mutations were found in XX% of patients. Missense mutations 
were the most common type, consistent with TP53's role as a 
tumour suppressor in breast cancer.

## Repository Structure
- `data/raw/` — Original downloaded files
- `data/processed/` — Filtered TP53 mutation table
- `scripts/` — Analysis scripts
- `figures/` — Output visualizations

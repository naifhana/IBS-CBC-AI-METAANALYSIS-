# Meta-Analysis of CBC Markers for IBS Diagnosis

## Data
- `data/aggregated_meta_data.csv`: 110 studies for meta-analysis.
- `data/yemen_cohort_raw.csv`: 142 Yemeni IBS patients (supplementary).

## How to run
1. Install R packages:
   ```r
   install.packages(c("metafor", "ggplot2"))
   ```
2. Run the analysis:
   ```bash
   Rscript code/meta_analysis/random_effects_model.R
   ```

## Output
The script will generate forest plots in the `results` directory.

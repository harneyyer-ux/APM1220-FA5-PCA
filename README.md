# APM1220 FA5 — Principal Component Analysis

- **Name:** Harneyyer Clores
- **Section:** Section 2
- **Assessment title:** Formative Assessment 5 — Principal Component Analysis (PCA)
- **Dataset source:** World Happiness Report 2021, accessed via the Hugging Face dataset mirror: https://huggingface.co/datasets/jason1966/ajaypalsinghlo_world-happiness-report-2021

## Description

This analysis uses the 2021 World Happiness Report dataset. It selects seven quantitative variables: Ladder score, Logged GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, and Perceptions of corruption. Country name and Regional indicator are excluded from the PCA.

The selected variables are standardized and PCA is performed using the correlation matrix. The analysis reports descriptive statistics, correlations, eigenvalues, proportions and cumulative proportions of variance, eigenvectors/component coefficients, and a scree plot. Component retention is considered using the scree plot, the Kaiser criterion, cumulative variance, and subject-matter interpretation.

The uploaded dataset contains 149 observations and 20 original columns. The seven selected variables have no missing values.

## Files

- `APM1220_FA5_PCA.pdf` — organized assessment report with results, graphs, and interpretations.
- `world-happiness-report-2021.csv` — dataset used in the analysis.
- `PCA_analysis.py` — Python script to reproduce the analysis.
- `scree_plot.png` — scree plot.
- `descriptive_statistics.csv` — descriptive statistics.
- `correlation_matrix.csv` — correlation matrix.
- `pca_variance_summary.csv` — PCA eigenvalues and variance proportions.
- `pca_eigenvectors.csv` — eigenvectors/component coefficients.

## How to run

Place `PCA_analysis.py` and `world-happiness-report-2021.csv` in the same folder. Run:

```bash
python PCA_analysis.py
```

Required Python packages: `pandas`, `numpy`, `matplotlib`, and `scikit-learn`.

## Source citation

World Happiness Report. (2021). *World Happiness Report 2021*. Dataset copy accessed through Hugging Face: https://huggingface.co/datasets/jason1966/ajaypalsinghlo_world-happiness-report-2021

This dataset mirror identifies the original source as the World Happiness Report. Cite the original report as required by the assessment instructions.

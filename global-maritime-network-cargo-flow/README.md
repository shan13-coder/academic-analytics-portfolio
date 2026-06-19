# Global Maritime Network & Cargo Flow Analysis

## Summary

Analysed global maritime connectivity, container throughput, and seaborne cargo roles using UNCTAD data and Tableau dashboards.

## What This Project Shows

- Built a UNCTAD data pipeline covering 182 connectivity economies, 95 throughput economies, and 1,785 economy-cargo records.
- Modelled the 2023 relationship between liner shipping connectivity and container throughput.
- Tested model robustness using bootstrap and top-economy exclusion sensitivity.
- Developed maritime hub typology, rank-gap, residual, cargo concentration, and trade-role analyses.

## Key Results

- Pearson correlation = 0.792.
- Spearman rank correlation = 0.971.
- Log-linear model R-squared = 0.682.
- Bootstrap 95% correlation interval = 0.791-0.882.
- R-squared remained within 0.682-0.739 after excluding up to the top 10 throughput economies.

## Limitations

The connectivity-throughput model is an association analysis and does not establish causality.


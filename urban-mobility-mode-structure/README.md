# Urban Mobility & Mode Structure Analysis

## Summary

Built a source-traceable official mobility panel and used PCA and K-means++ to identify descriptive urban mobility-structure segments.

## What This Project Shows

- Built a 242-record city-year panel covering 22 cities/counties and 11 official survey years.
- Audited user-provided mobility data against official values.
- Analysed Taipei public-transport decline and partial recovery.
- Applied PCA, K-means++, silhouette scoring, random-seed stability testing, and leave-one-feature-out sensitivity testing.

## Key Results

- Taipei public transport share recovered from 37.2% in 2022 to 38.3% in 2024.
- PCA first two components explained 96.90% of standardized variance.
- Best-performing k = 2-6 clustering solution had silhouette = 0.727.
- Mean ARI across 100 random-seed runs = 0.951.

## Limitations

Clusters are descriptive. They should not be interpreted as causal or permanent city classifications.


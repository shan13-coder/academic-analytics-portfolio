# Academic Projects Round 2 Extension Summary

Target applications: Data Science and Supply Chain Management

## 1. QGIS Public Transport Accessibility

Added a sequence-aware route-direction model using 2,624 route-stop records, 163 route-direction groups, 104,728 households, and 20 attractions.

- 500 m route-aware estimated access: 103,554 households (98.88%)
- Original buffer-only estimated access: 51,306 households (48.99%)
- Active route directions linked to attractions: 141

Use with caution: this model excludes timetables, frequency, transfers, travel time, and pedestrian-network distance.

Output: `projects/03_qgis_accessibility/outputs/qgis_route_aware_extension.xlsx`

## 2. Freeway VD & ETC Traffic Flow

Added five-threshold congestion-classifier sensitivity testing and directional ETC summaries.

- Tested thresholds: P60, P70, P75, P80, P90
- Global agreement range: 79.17%-88.89%
- Cohen's kappa range: 0.405-0.611
- Directional ETC links summarized: 6
- Northbound weighted mean speed: 59.95 km/h
- Southbound weighted mean speed: 78.17 km/h

Output: `projects/01_freeway_vd_etc/outputs/vd_etc_threshold_sensitivity_extension.xlsx`

## 3. Global Maritime Network & Cargo Flow

Added model uncertainty, outlier sensitivity, and a four-segment maritime hub typology.

- Model sample: 95 economies
- Bootstrap samples: 5,000
- LSCI-log throughput correlation 95% interval: 0.791-0.882
- R-squared after excluding up to top 10 throughput economies: 0.682-0.739
- Typology: 46 established hubs, 45 lower-scale networks, 2 connectivity-leveraged, 2 volume-intensive

Output: `projects/02_global_maritime/outputs/global_maritime_robustness_typology_extension.xlsx`

## 4. Red Sea Port Resilience Analysis

Reconstructed a before/after port-impact dataset using only values explicitly stated or labelled in the supplied peer-reviewed paper.

- Comparison periods: October 2023 and February 2024
- Services rerouted via Cape Route: 25 of 26 (96.15%)
- Additional vessels: 53
- Additional capacity: approximately 1.0 million TEU
- Reconstructed observations: 27 port-route impacts across 22 ports
- Asia-Mediterranean weekly call reduction: 13.5%
- Asia-Europe weekly call reduction: 8.4%
- Transshipment share of gross labelled capacity impacts: 85.24%

Output: `projects/05_red_sea/outputs/red_sea_port_resilience_extension.xlsx`

## 5. Urban Mobility & Mode Structure

Built a source-traceable official panel from MOTC survey tables and audited the user-provided working workbook.

- Panel: 242 city-year records, 22 cities/counties, 11 survey years
- Taipei public-transport share: 42.8% in 2016, 37.2% in 2022, and 38.3% in 2024
- Recovered share of the 2016-to-2022 decline: 19.6%
- Taipei 2024 public-transport rank: first
- Taipei 2024 private-motorized rank: lowest
- Mean absolute error in comparable user-provided public-transport values: 5.02 percentage points

Output: `projects/06_urban_mobility/outputs/urban_mobility_official_panel_extension.xlsx`

### PCA and clustering extension

- Clustered 22 city/county longitudinal profiles using six standardized mode-structure features.
- Compared k = 2-6; selected k = 2 with mean silhouette = 0.727.
- Identified three transit-oriented metropolitan jurisdictions and 19 private-motorized-dominant jurisdictions.
- PCA first two components explained 96.90% of standardized variance.
- Mean adjusted Rand index across 100 random-seed tests: 0.951.
- Leave-one-feature-out minimum adjusted Rand index: 1.000.

Output: `projects/06_urban_mobility/outputs/urban_mobility_pca_clustering_extension.xlsx`

# Academic Analytics Portfolio

**Description:** Academic portfolio of data science, supply chain analytics, and transportation analytics projects using Python, GIS, Tableau, and reproducible analytical workflows.

This repository contains selected academic and self-extended analytics projects focused on data science, supply-chain analytics, transportation analytics, and logistics strategy.

The repository is intentionally curated for public review. It includes project summaries, reproducible scripts, selected summary tables, and CV-ready evidence. Large raw datasets, copyrighted PDFs, original presentations, GIS archives, downloaded XML snapshots, and generated workbooks are excluded.

## Featured Projects

| Project | Focus | Methods |
|---|---|---|
| [E-Commerce GMV Growth Analysis](ecommerce-gmv-growth-analysis/) | Business analytics, customer analytics | Data quality checks, relational joins, GMV decomposition, RFM-style segmentation, PSI, cohort analysis |
| [Global Maritime Network & Cargo Flow Analysis](global-maritime-network-cargo-flow/) | Supply-chain and maritime analytics | UNCTAD data pipeline, Tableau dashboards, correlation, log-linear modelling, bootstrap, hub typology |
| [Urban Mobility & Mode Structure Analysis](urban-mobility-mode-structure/) | Transportation data science | Official mobility panel, PCA, K-means++, silhouette scoring, ARI stability testing |
| [Red Sea Shipping Disruption Analysis](red-sea-shipping-disruption/) | Supply-chain disruption and resilience | Before/after reconstruction, route-impact dataset, port winner/loser ranking, transshipment exposure |
| [Freeway VD & ETC Traffic Flow Analysis](freeway-vd-etc-traffic-flow/) | Transportation operations analytics | XML/CSV processing, cross-source consistency checks, congestion classification, threshold sensitivity |
| [Freeway Speed-Flow Relationship Analysis](freeway-speed-flow-relationship/) | Traffic-flow modelling | XML.GZ parsing, weighted minute-level aggregation, period comparison, speed-flow model testing |
| [Public Transport Accessibility with QGIS](public-transport-accessibility-qgis/) | GIS and accessibility analysis | Household coverage, buffer sensitivity, route-aware accessibility screening |
| [DHL Supply Chain Digital Transformation](dhl-supply-chain-digital-transformation/) | Logistics strategy | Source-KPI matrix, distribution-network scenario modelling, sensitivity analysis |

## Repository Structure

```text
ecommerce-gmv-growth-analysis/
global-maritime-network-cargo-flow/
urban-mobility-mode-structure/
red-sea-shipping-disruption/
freeway-vd-etc-traffic-flow/
freeway-speed-flow-relationship/
public-transport-accessibility-qgis/
dhl-supply-chain-digital-transformation/
assets/
  portfolio-level summaries and CV project selection notes
```

Each project folder generally contains:

- `docs/`: project status, reports, and CV-ready bullets.
- `scripts/`: reproducible analysis or workbook-building scripts.
- `analysis/`: selected summary outputs used to support reported metrics.
- `outputs/`: compact JSON headline metrics where available.

## Main Evidence Highlights

- Processed 543,533 e-commerce source records across 7 relational tables and built an order-level GMV analysis pipeline.
- Built a UNCTAD maritime pipeline covering 182 connectivity economies, 95 throughput economies, and 1,785 economy-cargo records.
- Built an official urban mobility panel covering 22 cities/counties, 11 survey years, and 242 city-year records.
- Reconstructed 27 labelled Red Sea crisis port-route impact records across 22 ports from a peer-reviewed study.
- Integrated 720 VD minute records and 1,440 ETC vehicle-type records into 144 segment-period observations.

## Data and Reproducibility Notes

Raw data is not fully included when it is large, copyrighted, classroom-provided, or better accessed from official sources. Scripts and selected outputs are included to document the analytical workflow and support the claims made in CV bullets.

See `DATA_NOTES.md` for details.

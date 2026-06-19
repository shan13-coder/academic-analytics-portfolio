# Project Interview Guide

## Global Maritime Network

**Story:** I wanted to test whether liner connectivity is associated with realized container throughput and whether the result survives skew and outliers. I merged official UNCTAD datasets, used log transformation and rank correlation, then added bootstrap and top-volume exclusion tests.

**Limitation:** Economy-level association does not establish causality.

## Red Sea Port Resilience

**Story:** I reconstructed a port-impact dataset from values explicitly reported in a peer-reviewed study, then compared route disruption, port winners and losers, and transshipment exposure.

**Limitation:** The 27 observations are labelled paper values, not a complete AIS or port-call census.

## Urban Mobility Panel & Clustering

**Story:** I replaced an unsourced working table with an official 242-record panel, measured Taipei's COVID recovery, then built city profiles and compared K-means solutions using silhouette and stability tests.

**Limitation:** Only 22 profiles are available, and mode shares are compositional. Clusters are descriptive.

## Freeway VD & ETC

**Story:** I aligned two traffic data sources with different spatial definitions, verified data completeness, compared cross-source correlations, and tested whether congestion labels were sensitive to threshold choice.

**Limitation:** VD occupancy and ETC counts measure different concepts; neither is ground truth.

## Speed-Flow Relationship

**Story:** I downloaded official detector snapshots, created weighted minute-level flow observations, compared morning and afternoon conditions, and evaluated alternative speed-flow models.

**Limitation:** The dataset covers one detector and two one-hour periods, so model generalization is limited.

## Answer Structure

For each project, answer in this order:

1. Decision question
2. Data source and scale
3. Cleaning or integration challenge
4. Model or analytical method
5. Quantitative result
6. Limitation and next data needed

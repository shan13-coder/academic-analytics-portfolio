# Freeway VD & ETC Traffic Flow Analysis

## Summary

Integrated VD and ETC traffic indicators to compare cross-source traffic-flow consistency and congestion classification behaviour.

## What This Project Shows

- Processed 720 VD minute records and 1,440 ETC vehicle-type records.
- Built 144 segment-period observations with 100% merge completeness.
- Quantified cross-source consistency across speed, occupancy, and vehicle-count indicators.
- Tested congestion classification sensitivity across multiple percentile thresholds.

## Key Results

- Segment-level speed correlations up to 0.619.
- Occupancy-volume correlations up to 0.515.
- P75 classification agreement = 80.56%.
- Cohen's kappa = 0.481 under the P75 rule.
- Threshold sensitivity agreement range = 79.17%-88.89%.

## Limitations

Classification agreement is not ground-truth accuracy; it measures consistency between VD- and ETC-derived classifications.


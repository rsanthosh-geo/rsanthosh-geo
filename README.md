# Santhosh Kumar R

**Geospatial Analyst · AI Data Operations · Remote Sensing, GIS & Applied Machine Learning**

[Mail](mailto:rsanthosh.geo@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rsanthoshgeo)

Solving geospatial, remote sensing, and environmental-intelligence problems for teams building satellite-driven infrastructure, climate, and biodiversity intelligence.

---

## About

3 years in AI Data Operations at AiDash, building ML pipelines on satellite
and aerial imagery for electrical T&D vegetation risk, biodiversity
assessment, and climate-risk intelligence.

## Highlights

- **94% field-validated accuracy** manually identifying tree-hazard threats
  (dead/declining trees threatening electrical T&D corridors, storm-driven
  fire and fall-risk) for UK/US utility clients via visual interpretation
  of multi-resolution satellite/aerial imagery — matched against
  independent client field verification, the highest field-validated
  result recorded within the AI Data Operations team. Separately validated
  model-based tree-health outputs, driving a **~30% reduction in false
  positives** through iterative review.
- Architected **Code4Habitat** (2025 internal hackathon) — an AI
  habitat-classification model exceeding **60% accuracy** against the UK
  Defra Biodiversity Metric / UKHab standards, cutting assessment cycles
  from days to hours.
- Built a checklist-driven, multi-resolution tree-species classification
  methodology — **30+ species**, **60% exact-match ground-truth
  confidence**, delivered across **14,600+ line miles** on two utility
  contracts.

## What I've built

Open-source geospatial tools, generalized from real production
workflows. Every one ships with a standalone mode, a synthetic/
reproducible demo, and an honest README about what's illustrative versus
measured — not just a description of what the code is claimed to do.

| Tool | What it does |
|---|---|
| [raster-nodata-cleanup](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/raster-nodata-cleanup) | Batch NoData/white-patch removal from satellite, aerial, and drone imagery — QGIS and standalone modes |
| [vegetation-extraction](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/vegetation-extraction) | Excess Green Index vegetation-polygon extraction from RGB imagery |
| [spatial-feature-snapping](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/spatial-feature-snapping) | Point-to-line-vertex snapping with a strict 1:1 constraint |
| [linear-network-delivery-estimator](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/linear-network-delivery-estimator) | Network length aggregation with recency-based delivery-time estimation |
| [polygon-delta-qc-engine](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/polygon-delta-qc-engine) | Shapefile delta QC — dependency-free DBF parsing, ground-truth-verified |
| [spatial-dataset-splitter](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/spatial-dataset-splitter) | Splits a merged spatial dataset into one file per group, any geometry type |
| [geometry-validator-repair](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/geometry-validator-repair) | Detects and repairs invalid polygon geometry — self-intersections, slivers, duplicate vertices |
| [imagery-tile-prioritizer](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/imagery-tile-prioritizer) | Tile footprint indexing with overlap-priority ranking (recency or vendor order) |
| [geometric-drift-qc](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/geometric-drift-qc) | Flags features with significant positional/angular drift between raw and corrected versions |

## Tech stack

Python · PyQGIS · GDAL / rasterio · GeoPandas / Shapely · Google Earth
Engine · SAM (applied segmentation/annotation use) · pandas / openpyxl · PyQt5

## Education

M.Sc. Geology — University of Madras *(RUSA Project Fellow)*
B.Sc. Geology — National College

## Certifications

IIRS & ISRO — Geospatial Technology (FOSS4G) · IIT Bombay — FOSSEE
Mapathon · NIDM — RS & GIS in Meteorological Hazards · NIDM —
Nature-Based Solutions

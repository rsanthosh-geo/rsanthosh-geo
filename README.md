# Santhosh Kumar R

**Geospatial AI | Training Data Quality & Model Validation | Powerline Analytics | Vegetation AI • Tree Intelligence • LiDAR • Drones • Satellite**
Geospatial Analyst, AI Data Operations at AiDash · Utility Vegetation Management · Bengaluru

[Mail](mailto:rsanthosh.geo@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rsanthoshgeo)

I improve AI models by improving the data they learn from. I work on satellite, aerial, drone and LiDAR-derived data for utility vegetation management, powerline analytics and biodiversity net gain.

My work covers the full data-to-model loop: imagery specification and vendor acceptance, ground truth and labeling rules, human-in-the-loop correction, model validation, and delivery. Imagery, vendors and the modelling team: one quality loop.

---

## Selected results

- **94% field-validated accuracy** on tree-hazard identification along multi-geography utility corridors, confirmed by independent client field verification. The highest in the AI Data Ops team.
- **A 7-day commitment shipped in 5:** 4,600+ line miles delivered two days early, then scaled to 14,600+ line miles in the next phase.
- **Human-in-the-loop correction loop** that feeds model fine-tuning. Corrected polygons lifted modelling-team throughput from 1–4k to 20k polygons per day.
- **~30% fewer false positives** by defining where expert review must override model output.
- **Tree-species classification from 60% to 80%+ accuracy** across 30+ species for a UK utility.
- **Months to weeks (60% faster):** a spatial-network point-data workflow automated in Python with LiDAR-derived ground truth, now in production.
- **Code4Habitat** (solo, 2025 internal hackathon): habitat classification at 60%+ accuracy against the UK Defra Biodiversity Metric/UKHab, assessment time from days to hours. Presented to executive leadership.

## How I work

- Set the modelling team's data priorities: which error types and classes to fix first, labeling rules and quality thresholds.
- Write imagery specifications for providers and set vendor acceptance criteria (acceptance rate up by 25%).
- Set a daily output benchmark for each new task type and plan weekly deliverables across concurrent projects.
- Run user acceptance testing on new tools and train colleagues.

## Open-source toolkit

Quality-control and automation tools generalized from production workflows. Each ships with a standalone mode, a reproducible demo, and a README that separates what is illustrative from what is measured. → [geospatial-toolkit](https://github.com/rsanthosh-geo/geospatial-toolkit)

**Model-output QC and ground truth**
- [`polygon-delta-qc-engine`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/polygon-delta-qc-engine): quantifies correction volume between model output and human-corrected polygons, per feeder and feature ID.
- [`geometric-drift-qc`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/geometric-drift-qc): flags positional and angular displacement between raw and corrected geometries.
- [`geometry-validator-repair`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/geometry-validator-repair): topology validation and repair; unfixable features are reported, never dropped.

**Imagery preparation**
- [`raster-nodata-cleanup`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/raster-nodata-cleanup): batch NoData-mask removal on satellite, aerial and drone rasters.
- [`imagery-tile-prioritizer`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/imagery-tile-prioritizer): footprint indexing and overlap ranking across multi-vendor tiles.
- [`vegetation-extraction`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/vegetation-extraction): Excess Green Index vegetation polygons from RGB imagery.

**Network and delivery operations**
- [`spatial-feature-snapping`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/spatial-feature-snapping): 1:1 point-to-vertex conflation onto line networks.
- [`spatial-dataset-splitter`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/spatial-dataset-splitter): splits merged datasets into per-group deliverables.
- [`linear-network-delivery-estimator`](https://github.com/rsanthosh-geo/geospatial-toolkit/tree/main/linear-network-delivery-estimator): per-feeder line-mile aggregation with a planning-level time estimate.

## Tech stack

Python · GeoPandas · Rasterio · GDAL · Shapely · Google Earth Engine · SAM · pandas / openpyxl

## Education

M.Sc. Geology — University of Madras *(RUSA Project Fellow)*
B.Sc. Geology — National College

## Certifications

IIRS & ISRO — Geospatial Technology (FOSS4G) · IIT Bombay — FOSSEE
Mapathon · NIDM — RS & GIS in Meteorological Hazards · NIDM —
Nature-Based Solutions

## Core expertise

Geospatial AI · Remote Sensing · Utility Vegetation Management · Tree Species Classification · Tree Health Analytics · Powerline Analytics · LiDAR · Drones · Satellite & Aerial Imagery · Training Data Quality · Model Validation · Imagery Specification · Vendor Management · Workflow Automation

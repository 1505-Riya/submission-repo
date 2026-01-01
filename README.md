# Vegetation Change Detection Using Multi-Temporal Sentinel-2 NDVI

## Project Overview
This repository contains the submission for the Imagery Analyst assignment.  
The project demonstrates an end-to-end Earth Observation (EO) workflow for vegetation change detection using multi-temporal Sentinel-2 optical imagery.

The analysis focuses on seasonal vegetation change over the Punjab–Haryana agricultural region using NDVI differencing, with emphasis on automation, preprocessing, interpretation, and clean deliverables.

---

## Region of Interest (ROI)
The selected ROI covers cropland-dominated areas across Punjab, Haryana, and western Delhi NCR.  
This region experiences strong seasonal crop cycles (primarily rabi crops such as wheat), making it suitable for NDVI-based change analysis.

ROI geometry is provided in GeoJSON format in the `roi/` directory.

---

## Data Used
### Optical Imagery
- Satellite: Sentinel-2 Level-2A
- Spatial Resolution: 10 m (Red, NIR)
- Acquisition Dates:
  - 23 February 2023 – Peak vegetation stage
  - 22 April 2023 – Crop maturity / harvest stage
- Bands Used:
  - Red (B04)
  - Near Infrared (B08)
  - Scene

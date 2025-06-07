# Flood Risk Assessment for Bartholomew County, Indiana

## Overview

This project evaluates the flood risk and potential socio-economic impact of a 100-year return period flood event in Bartholomew County, Indiana. Using FEMA’s Hazus software integrated with ArcGIS Pro, the analysis estimates damages to buildings, infrastructure, and essential facilities, as well as the projected need for shelter and economic losses.

---

## Data Description

The dataset includes:

- **Hazus Model Outputs**: Auto-generated summaries of building damages, exposure, debris, essential facility damage, and economic loss.
- **Final Report** (`Bartholomew_County_Flood_Report.pdf`): A detailed narrative interpreting the Hazus outputs and maps.
- **Log Files**:
  - `flAnalysisLog.txt`: Documents preprocessing steps and hazard data import.
  - `FlHazardLog.txt`: Contains parameters and event-specific metadata used during simulation.
- **Hazus Report** (`Hazus_Report.pdf`): FEMA-modeled risk report showing exposure, population, damages, and infrastructure risk maps.

---

## Methodology

The following steps were used in the project:
1. **Region Definition**: Selected Bartholomew County in ArcGIS using census tracts.
2. **Hazard Setup**: Simulated a 100-year flood scenario using depth grids and riverine input data.
3. **Exposure Analysis**: Evaluated building types, population distribution, and critical infrastructure.
4. **Damage Estimation**: Used Hazus modeling to assess:
   - Structural damage (residential, commercial, industrial)
   - Economic losses
   - Debris generation
   - Social impacts like displaced population
5. **Report Generation**: Compiled outputs into maps and logs for analysis and documentation.

---

## Tools Used

- ArcGIS Pro
- FEMA Hazus-MH (2023)
- Microsoft Excel
- U.S. Census CRE, FEMA NRI
- NLCD Land Cover Viewer
- STATS Indiana (Demographic data)

## Files Included

- `AggregationLog.txt` – Log of spatial data merging operations
- `FlHazardLog.txt` – Hazard model processing log
- `flAnalysisLog.txt` – Final analysis script or steps log
- `hzflcr_gsr.pdf` – Generated summary report of the risk assessment
- `Kunchala_Final.docx` – Final project write-up with maps, graphs, and interpretations

## Acknowledgments

This project was developed as part of INFO-P502: Modeling Crisis, guided by Prof. Kevin Mickey at Indiana University.



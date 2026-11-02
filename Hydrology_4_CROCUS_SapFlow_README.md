# Sap Velocity Data for Urban Trees in Chicago, Illinois (2024–2025)

**Metadata page:** https://www.osti.gov/biblio/3013822 (DOE ESS-DIVE / LBNL data repository record)  
**DOI:** https://doi.org/10.15485/3013822

## Overview
Uncorrected sap velocity measurements made with the heat ratio method (HRM) using ICT International SFM1x sensors on urban trees at five sites in Chicago, Illinois, as part of the DOE CROCUS (Community Research on Climate and Urban Science) project. Includes street trees and trees in urban park locations. Data were transmitted over LoRaWAN and collected by Sage Network (https://sagecontinuum.org/) nodes.

## Key contents
- Sensor ID, GPS coordinates, tree ID, tree species (common and scientific names), diameter at breast height (DBH, cm)
- Uncorrected sap velocity (cm/hr) from inner and outer probes
- Sage Node identifiers, so sap data can be linked to air quality and wind data from the same nodes
- 3-bit quality-control flags: physical range (< -10 or > 60 cm/hr), step spikes (> 36 cm/hr change), stuck sensor (> 10 identical values in a row)
- Species: sugar, silver and red maple; swamp white oak; American elm; honey locust; cottonwood; tree of heaven
- CSV format; timestamps in local Chicago time (CDT/CST); 15–20 minute intervals depending on sensor
- Raw data, not corrected for wood anatomy or species-specific characteristics

## Temporal & spatial coverage
- **Time:** 2024–2025 (per dataset title)
- **Location:** Chicago, Illinois, USA: Chicago State University (CSU), Northeastern Illinois University (NEIU), Northwestern University (NU), University of Illinois Chicago (UIC), and West Woodlawn "Blacks in Green" (BIG)

## Citation
Berkelhammer, M., Kaludi, B., Lee, J., Negri, C., Collis, S., Muradyan, P., et al. (2026). Sap Velocity Data for Urban Trees in Chicago, Illinois (2024–2025). https://doi.org/10.15485/3013822

## Why this dataset is useful for final projects
Students can study how urban trees use water across species, sites and seasons, examine daily cycles of sap flow, and link tree water use to weather and air quality measured on the same Sage nodes.

## Suggested analyses
- Daily (diurnal) and seasonal cycles of sap velocity
- Comparison among species, tree sizes (DBH) or sites
- Inner vs. outer probe differences
- Effect of quality-control flags on summary statistics
- Linking sap velocity to weather (linked CROCUS WXT/AQT datasets)

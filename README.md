# Climate Hazard Risk Exposure Analysis

Author: Ava Robillard

This repository contains two visualizations based on [FEMA (Federal Emergency Management Agency)](https://www.fema.gov/about) [National Risk Index (NRI)](https://www.fema.gov/flood-maps/products-tools/national-risk-index) scores and the US Census Bureau's [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs/about.html). The two key questions explored are how risk scores for counties in California compare to those in other states, and how climate hazard risk exposure varies across racial and ethnic groups in California. These visualizations were created in R using the {ggplot2} package.

## Repository Structure

```         
eds240-nri-acs-viz
├── data                        
│ └── National_Risk_Index_Counties_807384124455672111.csv
│ └── ACS-1yr-2023-county-race-ethnicity.csv
├── eds240-nri-acs-viz.Rproj
├── HW2.qmd                     # risk exposure across states- NRI data
├── HW3.qmd                     # risk exposure across racial and ethnic groups- NRI + ACS data
└── README.md
```

## Data

The National Risk Index dataset provides information for communities most at risk to 18 different natural hazards. It offers a baseline risk measurement for expected annual loss, social vulnerability and community resilience at the Census tract or county level (FEMA, 2025).

The US Census Bureau's American Community Survey (ACS) is a nationwide survey of social, economic, housing, and demographic data. This data is collected for a small subset of the population at 1 and 5 year intervals, making it more timely for data analysis.

All data is stored locally, but can be accessed using the US Census Bureau API and the [RAPT](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/page/RAPT-2025?dlg=dialog_1) tool NRI Counties layer.

## References

This assignment was created as a part of EDS 240: Data Visualization & Communication, taught by Sam Shanny-Csik.

Data: Federal Emergency Management Agency. (2025). National Risk Index. Retrieved January 29, 2025, from <https://www.fema.gov/flood-maps/products-tools/national-risk-index>

U.S. Census Bureau. (2023). American Community Survey 1-year estimates: Race and ethnicity data [Data set]. Retrieved February 7, 2025, from <https://api.census.gov/data/2023/acs/acs1>

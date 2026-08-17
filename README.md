[README.md](https://github.com/user-attachments/files/31135147/README.md)
# Water_Level_Thames
DataCamp guided project: Analysis of the historical water levels on the River Thames at high and low tides
# Analyzing River Thames Water Levels

Time-series analysis of ~115,000 tidal water-level readings at London Bridge, 1911–1995: typical high- and low-tide levels, and whether very high tides have become more common.

## Questions
- What are the typical high- and low-tide levels at London Bridge?
- Has the share of "very high" tide readings changed over the 85-year record?

## Data
Tidal readings (date/time, water level in metres ODN, high/low-tide flag) for station 10-11, London Bridge, provided with the DataCamp project.

## Method
Parsed ~115,000 timestamped readings with pandas, separated high- and low-tide observations, computed summary statistics (mean, median, IQR), and calculated the annual share of readings beyond the 90th/10th percentile thresholds. Visualized annual trends with matplotlib.

## Key findings
- High tides averaged 3.32 m ODN (median 3.35, IQR 0.74); low tides −2.38 m ODN (median −2.41, IQR 0.54).
- The share of "very high" readings (above 3.96 m) roughly doubled across the record: about 6% of readings in the first decade versus about 13% in the last.
- Annual mean high tides trend upward while low tides fall — the tidal range at London Bridge widened over the century.

## Possible extensions
The full dataset covers 13 stations along the Thames; repeating the analysis across stations would show how these trends vary from the estuary to upstream. The same approach could also be applied to Danish water-level data from DMI's open data API.

## Tools
Python · pandas · matplotlib

## Origin
Based on a DataCamp guided project ("Analyzing River Thames Water"). Code tidied and visualizations added.

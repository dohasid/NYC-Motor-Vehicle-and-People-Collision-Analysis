# NYC-Motor-Vehicle-and-People-Collision-Analysis

This project analyzes vehicle collision data in New York City to uncover patterns in timing, location, cause, and injury severity. The goal is to explore how public data can inform safer, more equitable urban planning and transportation policy.

## Files
- `New York City Motor Vehicle and People Collision Analysis.Rmd` – Full analysis code and insights
- `New York City Motor Vehicle and People Collision Analysis.html` – Rendered output for easy viewing
- Motor_Vehicle_Collisions_-_Crashes.csv – Dataset containing details about the crash event
- Motor_Vehicle_Collisions_-_Person.csv Dataset containing details about people involved in the crash.

## Key Findings
- **Brooklyn** had the highest number of collisions; **Staten Island** had the fewest.
- Collision counts appear to correlate with **borough population**.
- Most frequent crash times and causes were identified.
- NA values were cleaned to improve graph accuracy, though some data was lost.

## Tools
- R
- ggplot2
- dplyr
- tidyr
- coord_map

## Data Sources
Due to file size limits, the raw datasets are not included in this repository.

You can download them here:
- NYC Open Data: [Crash Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
- NYC Open Data: [Person Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Person/f55k-p6yu/about_data)

## Why This Matters
This analysis supports public safety initiatives, equitable traffic policy, and smart urban planning. Understanding when and where crashes occur helps direct city efforts and resources to the areas and times they’re needed most.

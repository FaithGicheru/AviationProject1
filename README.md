# AviationProject1
## Overview
This project involves analyzing accident data from the aviation industry to identify the aircraft with the lowest operational risk for both private and commercial operations.
### Business Understanding
The company wants to delve into aviation and seeks to minimize operational risks. This analysis will assist the Head of the Aviation Division in making an informed decision regarding the purchase of aircraft with the lowest operational risk.
## Stakeholder
Head of Aviation Division
## Key question
Which airplane has the least operational risk overall?
What is the effect of weather conditions on airplane operations?
Which aircraft has the lowest rate of fatal injuries?
## Data understanding
## Data source
This publicly available dataset contains historical aviation accident data. It includes details on aircraft, weather conditions, and injuries recorded in the past, among others.
### Data Description
The dataset contains 90,348 reported accident records and 31 variables. 
Key variables include:
- Aircraft manufacturer and model
- Weather conditions at the time of the accident
- Aircraft damage level
- Number of fatal, serious, and minor injuries
A weighted severity score  was created using injury outcomes to measure risk 

## Visualizations

### 1. Lowest Risk Aircraft Make
This visualization shows aircraft manufacturers with the lowest average accident severity scores, highlighting safer aircraft make for both private and commercial operations.

### 2. Fatal Injuries by Aircraft Damage Level
This barplot illustrates that the greater the aircraft damage, the higher the number of fatal injuries.

### 3. Average Accident Severity by Weather Condition
This visualization shows that poor weather conditions are associated with higher accident severity, indicating increased operational risk.

## Conclusion

### Key Findings
1. Certain aircraft Makes are associated with lower average accident severity, making them suitable for aircraft operations.
2. The higher the level of aircraft damage, the higher the number of fatal injuries.
3. Adverse weather conditions result in more severe outcomes.

### Recommendations
- Certain aircraft makes should be considered for purchase due to their low accident severity score.
- Aircraft operational limits should be put in place during adverse weather conditions.
- Aircraft models with strong structural resilience should be considered as they are less damaged during accidents, which in turn  reduces injury severity.

## Repository Structure
- `notebooks/` – Jupyter Notebook containing analysis
- `data/` – Aviation accident dataset
- `presentation/` – Non-technical presentation slides
- `dashboard/` – Interactive dashboard
- `.gitignore` – Files excluded from version control

---

## Links
- [Final Jupyter Notebook](notebooks/final_notebook.ipynb)
- Interactive dashboard[https://public.tableau.com/authoring/Aircraftoperationalriskanalysis/Dashboard1#1]
- [Presentation](presentation.pdf/)

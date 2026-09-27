# India Crime Dataset — Exploratory Analysis

Exploratory data analysis of crime records across Indian cities — crime types, weapons used, victim demographics, and time-based trends, with a focused deep-dive on Delhi.

## Dataset
`data/crime_dataset_india.csv` — crime records with fields: City, Date of Occurrence, Time of Occurrence, Crime Description, Victim Age, Victim Gender, Weapon Used, Case Closed.

## Approach
1. Data cleaning — null checks, duplicate checks, date/time parsing
2. Feature engineering — extracted Year, Month, and formatted Time from raw date/time fields
3. City-wise crime distribution
4. Crime type trends by month and year (top crime types)
5. City x Year x Crime Type pivot analysis
6. Weapon-used analysis across cities
7. Victim demographics — gender and age breakdown
8. Delhi case study — gender split, weapon type, robbery cases, case closure rate

## Key Findings
*(Fill in after running — e.g. "Delhi had the highest crime volume with X cases", "Theft was the most common crime type", "Case closure rate in Delhi was X%")*

## How to Run
```bash
pip install pandas seaborn matplotlib
jupyter notebook india_crime_dataset_analysis.ipynb
```

## Next Steps
- Build a classification model to predict case closure likelihood
- Add a choropleth/geo map of crime density by state
- Time-of-day heatmap (hour vs crime type)

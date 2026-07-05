# World Happiness Report — Exploratory Data Analysis

## Dataset
153 countries · 12 columns · Source: World Happiness Report 2017

## Key Questions Explored
- Which countries and regions are happiest?
- Which factors most strongly predict happiness?
- How does happiness vary within regions?

## Key Findings
- Top 5 happiest: Norway, Denmark, Iceland, Switzerland, Finland (all Scandinavian)
- Bottom 5: Central African Republic, Burundi, Tanzania, Syria, Rwanda
- Economy (0.81) and Job Satisfaction (0.81) are the strongest predictors of happiness
- Generosity is the weakest predictor (0.16) — counterintuitive finding
- Freedom (0.58) does not separate happy from unhappy countries as much as assumed
- Central African Republic scores 0 on both Economy and Family — complete societal breakdown
- North America least variation in happiness · Africa highest variation
- Europe anomaly: unusually low Freedom score — likely a data grouping artifact

## Techniques Used
Pandas, SQL (GROUP BY, HAVING, subqueries), Matplotlib, Seaborn
Bar chart, heatmap, regplot, boxplot, horizontal bar chart

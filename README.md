# Predicting-economic-damage-from-natural-disasters

## Overview
This project analyzes global natural disaster data to identify which types of disasters cause the greatest economic damage. Using approximately 3,000 recorded disaster events, the study examines whether disaster type, severity, or duration best predicts economic loss.

The analysis is motivated by real-world exposure to disaster-prone regions and focuses on understanding economic risk rather than forecasting individual events.

## Data
- Source: Kaggle – Global Climate Events and Economic Impact Dataset  
- Each observation represents a natural disaster event with an estimated economic loss (in million USD)
- Key variables include disaster type, severity, duration, and economic impact

## Methodology
Disaster events are grouped into five categories: Heat Events, Water Events, Earth Movement Events, Cold Events, and Storm Events. Severity levels are classified from Minor to Catastrophic.

Exploratory data analysis and visualizations are used to compare economic impacts across groups. A linear regression model evaluates the relationship between economic damage, disaster type, severity level, and duration.

## Key Findings
- Disaster duration is the only statistically significant predictor of economic damage. 
- Disaster type and severity do not significantly explain economic losses once duration is controlled. 
- Longer-lasting disasters consistently lead to higher economic impact across all categories. 

## Conclusion
The results suggest that the persistence of a disaster plays a more critical role in determining economic damage than its classification or severity. These findings highlight the importance of focusing on disaster duration when assessing economic risk and planning mitigation strategies. 







## Link to Trello:https://trello.com/b/RVXsQKDG/project-1111-official
##Link to pre: https://docs.google.com/presentation/d/1gzvWhwsQcSck8CpwpDsI4gODmoo4M4bSJI2bfFA2Qlc/edit?usp=sharing
## Main Project-1111
# Project-1111
# Apple Stock & GDP: Unveiling the Economic Connection

## Project Overview
This project analyzes the relationship between **Apple's stock price (1980–2022)** and the **US GDP growth rate** over the same period. The goal is to determine whether macroeconomic data influences Apple’s stock price, providing valuable insights for investors. If a significant relationship is found, investors could leverage economic forecasts to make informed decisions regarding Apple stock investments.

## Research Question
**Is there a relationship between US macroeconomic data (GDP growth rate) and Apple’s stock price?**

## Data Sources
- **GDP Growth Rate** – World Bank Group
- **Apple Stock Prices** – Kaggle

## Hypothesis
- **H₀ (Null Hypothesis):** There is no significant relationship between the US GDP growth rate and Apple’s stock price.
- **H₁ (Alternative Hypothesis):** There is a significantly positive relationship between the US GDP growth rate and Apple’s stock price.

## Data Cleaning Process
### GDP Data:
- Removed all countries except the **USA**
- Dropped irrelevant columns to retain only necessary data
- Filled missing values (`NA`) to ensure completeness
- Transformed the dataset from a **horizontal** to a **vertical** format
- Filtered data to include only years **from 1980 onwards**

### Apple Stock Price Data:
- Aggregated stock prices by **year** instead of daily records
- Calculated the **mean stock price** for each year
- Reset the index to align the dataset with the **Years column**

### Unique Method Used:
- Utilized **`pd.melt`** to efficiently convert the GDP dataset from a **wide (horizontal)** to a **long (vertical)** format, making it easier to analyze trends over time.

## Challenges & Solutions
### Major Obstacle:
Initially, we selected a **European Apple dataset**, but we discovered that it contained mixed data from other regions, making it unsuitable for analysis. To ensure accuracy, we shifted our focus to the **US Apple dataset**, providing a more reliable and region-specific foundation for our study.

### Risk Management:
- Identified challenges early and collaborated as a team to find solutions.
- Adapted to obstacles efficiently to ensure smooth project progression.

## Exploratory Data Analysis
- **Scatterplots** and **correlation analysis** were conducted to visualize the relationship between Apple stock prices and GDP growth.
- Key insights and interesting patterns were identified.

## Teamwork & Project Management
### Workflow & Collaboration:
- Organized the project workflow using **Trello** before starting.
- Assigned tasks strategically among team members to maximize efficiency.
- Adhered to the initial plan but remained flexible, making adjustments when necessary.

## Conclusion & Insights
- Our analysis evaluated whether there is a statistically significant relationship between **US GDP growth** and **Apple stock prices**.
- **Findings**:
    1- It would be difficult to predict stock prices of a single company simply based on GDP growth rate as GDP covers wider perspective of the entire economy. 
    2- US Economy has gone through multiple economic cycles with recessions, stable growths and boomings;
    3- Apple’s stock prices have grown exponentially in the past decades which infers that the company has excellent performance in revenues, profits and cash 
      flows. 

- **Implications**: If a relationship exists, it can help investors align stock investments with economic trends.
- **Open Questions**: Are there other macroeconomic variables that might have influenced Apple’s stock price more directly?

## Acknowledgments
Project by **Hilena & Rao**

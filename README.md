# Household Travel Survey Analysis

> What the Ministry of Transportation's household travel survey reveals about who holds a driving licence in the Tel Aviv metro area.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![seaborn](https://img.shields.io/badge/seaborn-4C72B0) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Highlights

- Real public-sector microdata: household and member tables covering about 39,000 people.
- Question-driven analysis across education, employment, gender and religious sector.
- Clear finding: licence gaps between groups are large, widest among ultra-Orthodox respondents.

## Questions

1. How does education level relate to the driver-profile field in the survey?
2. Is employment status related to holding a car or motorcycle licence?
3. How do gender and religious sector relate to holding a car licence?

## Approach

Fixed mixed data types, recoded survey codes into labels, handled missing household fields (about 45% of cells), removed age outliers with the IQR rule, then used pivot tables, cross-tabulations, dummy variables and a correlation heatmap.

## Key finding

Car-licence holding by gender and sector:

| Sector | Women | Men |
|---|---|---|
| Secular | 74.4% | 87.4% |
| Arab | 70.7% | 87.5% |
| Orthodox | 59.5% | 78.4% |
| Ultra-Orthodox | 33.0% | 63.4% |

## Repository structure

| Path | Description |
|---|---|
| `Travel Habit Survey Analysis-23.ipynb` | The analysis |
| `תכנון הצגת הפרויקט – קבוצה 23.pdf` | Presentation plan and recommendations (Hebrew) |

## Context

University group project (Group 23) by Amit Stein and Nadav Mashiach.

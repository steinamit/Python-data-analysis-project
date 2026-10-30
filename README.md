# Household Travel Survey Analysis

Exploratory analysis of the Israeli Ministry of Transportation's household travel survey for the Tel Aviv metro area.

**Context:** university group project (Group 23) · **Team:** Amit Stein, Nadav Mashiach

## Questions
1. How does education level relate to the driver-profile field in the survey?
2. Is employment status related to holding a car or motorcycle licence?
3. How do gender and religious sector relate to holding a car licence?

## Data
Two survey tables: households and household members (about 39,000 people).

## Approach
- Fixed mixed data types and recoded numeric survey codes into readable labels.
- Handled missing household fields (about 45% of cells) and removed age outliers with the IQR rule.
- Pivot tables, cross-tabulations, dummy variables and a correlation heatmap.
- Charts: box plots, bar, pie and count plots.

## Selected findings
Car-licence rates differ sharply by gender and sector:

| Sector | Women | Men |
|---|---|---|
| Secular | 74.4% | 87.4% |
| Arab | 70.7% | 87.5% |
| Orthodox | 59.5% | 78.4% |
| Ultra-Orthodox | 33.0% | 63.4% |

## Files
- `Travel Habit Survey Analysis-23.ipynb`: the analysis
- `תכנון הצגת הפרויקט – קבוצה 23.pdf`: presentation plan with recommendations

**Tools:** Python · pandas · NumPy · seaborn · matplotlib

# Aircraft-Accident-Risk-Analysis

## 🚀 Project Objective
The objective of this project is to assist the company in identifying the safest and lowest-risk aircraft for commercial and private aviation business expansion. This analysis leverages aircraft accident data to uncover patterns, risks, and actionable insights for informed decision-making.
We will achieve this by analyzing potential risk of accidents by:
### Risk Analysis by Aircraft Model and Manufacturer
### Mechanical failure by aircraft type
### Accidents Hotspot by location
### Broad phase of aircraft.

##Data overview
The dataset used is:https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses
- **Total Records:** 88,889
-  **Key Columns:** Make, Model, Total Fatal Injuries, Total Serious Injuries, Total Minor Injuries, Total Uninjured, Country, Latitude, Longitude, etc.
   
### Tools Used:
- **Programming Language:** Python, Jupyter Notebook
- **Libraries:** Pandas, NumPy, matplotlib, Seaborn

## Project steps
### Data cleaning
Handled missing data by filling or dropping.
saved new file as df_clean

## Data Analysis and Visualization:

### Evaluating Aircraft Safety Based on Make and Model
**Find below Visualization and Comments**
![image](https://github.com/user-attachments/assets/035817d9-e191-44f7-9819-fe4ce7876eac)

 **Comments**:
 1.Boeing 747-168 leads the chat at 349 fatalities recoerded making them unsafe choice for travelling.
 2.Second place is Tupolev Tu-154
 3.Third place is Boeing 767-366 ER with 217 deaths recorded.
 
### Assessing Accident Risk by Mechanical Failure by Aircraft type

**Find below Visualization and Comments**
![image](https://github.com/user-attachments/assets/ae0f8c9c-dd66-4f88-8221-0dafbb14f90f)

**Comments**:
 1. Single engine flight have more accidents compared to multi-engine flight.
 2. Amateur Built flights despite having few records in the dataset seems to record most fatalities.
  
### Accidents Hotspots by Location
**Find below Visualization and Comments**
![image](https://github.com/user-attachments/assets/650d37f2-04e5-47fb-86c4-9e9a90df1610)


**Comments**:
1. Most aviation accidents occur in the Usa and appears to be on the top 10 list of countries that record the most accidents according to our dataset.

### Accidents by broad Phase of flight*
- **Find below Visualization and Comments**
![image](https://github.com/user-attachments/assets/08be27c1-9acd-4e40-b0be-6673799cafa3)

**Comments**:
1. From our analysis we can see that most accidents occur during landing with 15428 fatalities recorded.
   
## Key Insights & Recommendations:**  
   - invest in aircrafts with low accident rates.
   - conduct additional checkups of aircraft used during landing and takeoff phase
   - Avoid single engine aircraft for commercial purposes
   - Caution to be taken while flying to Usa, this can be done through proper training of pilots,routine maintenance of 
     aircrafts.

### conclusion
This analysis provides valuable insights into aviation risk.Future work can include more granular analysis by aircraft age,maintenance records and weather conditions

# Summary-:
## Interactive Dashboard "Tableau- Find below link"
https://public.tableau.com/views/AviationAccidentAnalysis-PresentationTN/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# Phase-1-Project_Lydia
#Readme file
#project title:Evaluating Low-Risk Aircraft Models for Commercial and Private Operations

#Overview and Goal
This project evaluates aviation accident data to identify low-risk aircraft models suitable for commercial and private operations. The study examines accident frequencies by aircraft type and model, the influence of engine configurations on safety performance, and historical trends in aviation incidents. The objective is to provide actionable insights to guide fleet expansion and operational safety strategies.

# **Stakeholders**

-Head of Aviation Division: Decision-maker for aircraft purchases.

-Leadership Team: Interested in financial viability and risk minimization.

# **Key Business Questions**

1. Which aircraft models demonstrate the lowest accident rates historically?

2. How does the number of engines impact safety performance and fatality rates?

3. What trends in accident data can inform the selection of low-risk aircraft models?

4. How can weather-related factors be considered in fleet and operational decision-making?

# **Source of Data**

The dataset is sourced from the Kaggle Aviation Accident Database Synopses, which includes historical aviation accident data.

# Data Overview
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 88889 entries, 0 to 88888
Data columns (total 31 columns):
 #   Column                  Non-Null Count  Dtype  
---  ------                  --------------  -----  
 0   Event.Id                88889 non-null  object 
 1   Investigation.Type      88889 non-null  object 
 2   Accident.Number         88889 non-null  object 
 3   Event.Date              88889 non-null  object 
 4   Location                88837 non-null  object 
 5   Country                 88663 non-null  object 
 6   Latitude                34382 non-null  object 
 7   Longitude               34373 non-null  object 
 8   Airport.Code            50132 non-null  object 
 9   Airport.Name            52704 non-null  object 
 10  Injury.Severity         87889 non-null  object 
 11  Aircraft.damage         85695 non-null  object 
 12  Aircraft.Category       32287 non-null  object 
 13  Registration.Number     87507 non-null  object 
 14  Make                    88826 non-null  object 
 15  Model                   88797 non-null  object 
 16  Amateur.Built           88787 non-null  object 
 17  Number.of.Engines       82805 non-null  float64
 18  Engine.Type             81793 non-null  object 
 19  FAR.Description         32023 non-null  object 
 20  Schedule                12582 non-null  object 
 21  Purpose.of.flight       82697 non-null  object 
 22  Air.carrier             16648 non-null  object 
 23  Total.Fatal.Injuries    77488 non-null  float64
 24  Total.Serious.Injuries  76379 non-null  float64
 25  Total.Minor.Injuries    76956 non-null  float64
 26  Total.Uninjured         82977 non-null  float64
 27  Weather.Condition       84397 non-null  object 
 28  Broad.phase.of.flight   61724 non-null  object 
 29  Report.Status           82505 non-null  object 
 30  Publication.Date        75118 non-null  object 
dtypes: float64(5), object(26)
memory usage: 21.0+ MB

# Data analysis approach
Top 10 Aircraft Makes by Accident Count
Top 10 Aircraft Models by Accident Count
Yearly Trend in Accidents
Count of accidents by weather conditions
single-engine vs multi-engine accidents
accidents by flight phase

# Key findings
-Aircraft Safety: Certain models (e.g., Cessna and piper) have a higher number of accidents but could reflect higher usage rather than risk.

-Trends Over Time: Accident frequencies have declined over the years, indicating advancements in technology and improved safety regulations.

-Engine Configuration and Safety: Aircraft with multiple engines generally show lower average fatality rates compared to single-engine aircraft. This suggests that redundancy in engines enhances safety, potentially offering more options in emergencies, such as engine failure.

-Flight Phases: Takeoff and landing are the most accident-prone phases, while cruise is generally stable, this therefore shows where safety improvements should focus.

-Weather Conditions: Most accidents occur under unknown or visual weather conditions, suggesting data gaps and the need for better weather-specific operational strategies.

# Recommendations
1. Aircraft Selection
-Prioritize Multi-Engine Models: Choose multi-engine aircraft for commercial and high-stakes operations due to their lower fatality rates and enhanced safety in emergencies.
-Focus on Modern Designs: Invest in aircraft that are equipped with advanced navigation, safety systems, and redundancy mechanisms to reduce operational risks
-Comprehensive Audits: Conduct safety and maintenance audits for frequently used models, particularly those with high accident counts, to identify and address vulnerabilities.


2. Safety Enhancements
-Training Programs: Tailor training for high-risk flight phases, such as takeoff and landing, and improve pilot readiness for weather-specific challenges.
-Flight Phase Mitigations: Implement automation technologies, such as advanced landing systems, to reduce risks during critical phases.
-Weather-Resilient Operations: Equip aircraft with state-of-the-art weather detection systems and develop detailed weather-specific operational strategies.

3. Strategic Investments
-Leverage Historical Trends: Utilize the declining accident trend to benchmark best practices and implement modern safety protocols for newly acquired fleets.
-Data-Driven Decisions: Fill data gaps, especially in weather reporting and accident causes, to improve safety assessments and operational decision-making.
-Fleet Modernization: Align fleet acquisitions with safety records, focusing on reliable models that balance operational efficiency with strong safety performance.

# Next steps
Assess High-Usage Models: Conduct safety and reliability assessments for frequently used aircraft models.
Pilot Program for Multi-Engine Aircraft: Test the operational and financial performance of multi-engine aircraft in select routes.
Improve Safety Culture: Enhance training programs and maintenance schedules for high-usage aircraft and highrisk phases like takeoff and landing.
Address Data Gaps: Collaborate with aviation authorities to improve weather and accident reporting standards.

# Interactive Dashboard
For the interactive dashboard, it can be accessed via [tableau link](https://public.tableau.com/app/profile/vxp.red/viz/firstinteractiveboard/Dashboard1?publish=yes)

# Jupyter notebook link
For further reference, the jupyter notebook can be accessed here:
 https://github.com/Lydia-byte-rgb/Phase-1-Project_Lydia/blob/main/phase_1_project_main.ipynb

# Contact information
For any clarification reach out to me on: lydiamangoa10@gmail.com

# Repository structure
README.md
phase_1_project_main.ipynb
requirements.txt



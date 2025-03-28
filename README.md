  # Aviation Safety Analysis: Identifying Low-Risk Aircraft for Business Expansion

  ## Overview

  This project analyzes aviation accident data from the National Transportation Safety Board (NTSB) to provide actionable insights for a company expanding into the aviation industry. By examining historical accident data from 1962 to 2023, we identify the lowest-risk aircraft for commercial and private operations to inform strategic purchasing decisions.

   # Business Understanding

   ## Stakeholder 

   The primary stakeholder is the head of the new aviation division who needs data-driven recommendations to guide aircraft acquisition decisions.

   ## Key Business Questions
  * Which aircraft models have demonstrated the best safety records over time?
  * How does aircraft age correlate with accident risk?
  * What operational factors contribute to aircraft safety that should influence purchasing decisions?
  * In what event causes a serious damage to the aircraft?
  * What causes the Aircraft to miss or is completely inaccessible?
  * What happens to the aircraft in each phase of flight?
  * Can the Aircraft withstand the occurrence of events like e.g hailstorms?
  * Which occurrence is more destructive to the Aircraft?

  # Data Understanding and Analysis

  ## Source of Data
  This analysis uses the National Transportation Safety Board (NTSB) Aviation Accident Database, containing aviation accident data from 1962 to 2023 for civil aviation accidents and selected incidents in the United States and international waters. The  National Transportation Safety Board (NTSB) publish raw data in https://www.ntsb.gov/_layouts/ntsb aviation/index.aspx.

  ## Description of Data
 * The dataset includes:
 * 88,889 accident records spanning over 60 years
* Details on aircraft make, model, and age
* Accident severity (fatal, serious, minor injuries)
* Environmental conditions during accidents
* Purpose of flight (commercial, private, training )
* Contributing factors to accidents

# Key Visualizations

## 1. Aircraft Model safety comparison
![alt text](<Aircraft Model safety comparison.png.jpg>)

This visualization compares safety records across popular aircraft models, showing accident rates per 100,000 flight hours. The analysis reveals that certain models, including the Cessna 172, Diamond DA40, and Cirrus SR22, demonstrate significantly lower accident rates when normalized for usage frequency.

## 2. Aircraft Age vs. Accident Severity
![alt text](<Aircraft Damage Event Severity Heatmap_image.png>)


This chart illustrates the relationship between aircraft age and accident severity. The data shows a clear U-shaped curve where both very new aircraft (0-3 years) and older aircraft (18+ years) experience higher fatality rates during accidents, while mid-life aircraft (8-17 years) demonstrate optimal safety performance.

## 3. Operational Factor Impact on Safety
![alt text](<Operational Factor Impact on Safety_image.png>)

This analysis identifies key operational factors that correlate with improved safety records. Regular maintenance schedules, pilot experience requirements, and operational limitations in adverse weather conditions all demonstrate significant positive impacts on safety outcomes across all aircraft types.

## 4. Aircraft Damage Event Severity Heatmap
![alt text](<Aircraft Damage Event Severity Heatmap_image.png>)

Visualization Highlights:

* Color-coded intensity representing event severity
* Breakdown of damage types across different flight phases
* Comparative analysis of event impacts

## 5.  Flight Phase Risk Profile
![alt text](<Flight Phase RiskProfile.png.jpg>)


Key Insights:

Risk distribution across takeoff, cruise, approach, and landing phases
Frequency and severity of critical events in each flight phase

## 6. Event Destructiveness Comparison
![alt text](<Photographic Print_ Lightning Strike on Aircraft _ 12x9in.jpg>)


Comparative Analysis:

Hailstorms
Turbulence
Lightning strikes
Bird strikes
Mechanical failures

# Conclusion
## Summary of Findings

## 1. Aircraft Model Selection: 
The analysis identified specific aircraft models with exceptional safety records across different categories:

Small Single-Engine: Cirrus SR22 and Diamond DA40
Twin-Engine: Diamond DA42 and Beechcraft Baron G58
Light Jets: Embraer Phenom 300 and Cessna Citation CJ3+

## 2. Optimal Aircraft Age: 
 Aircraft between 5-15 years old demonstrate the best safety performance, balancing modern safety features with proven reliability. We recommend focusing acquisition efforts on aircraft in this age range to minimize risk while optimizing value.

## 3. Operational Best Practices:
 Implementing structured maintenance programs, establishing minimum pilot experience requirements, and adopting conservative weather minimums would significantly reduce accident risk based on historical data patterns.

 ## 4. Hailstorm Impact
 Most destructive natural event for aircraft
Potential damage to:

* Fuselage integrity
* Wing leading edges
* Windshield and cockpit visibility
* Estimated repair costs: High

## 5. Flight Phase Vulnerabilities
Takeoff Phase:

* Highest mechanical stress
* Critical system failures more likely


Cruise Phase:

* Less dynamic stress
* Potential for long-term system degradation


Landing Phase:

* High-risk mechanical interactions
* Ground collision potential

## 6. Event Inaccessibility Factors
* Extreme weather conditions
* Remote flight locations
* Limited ground support infrastructure
* Communication disruptions

# Destructiveness Ranking
## 1. Hailstorms (Most Destructive)
* Direct structural damage
* Immediate and long-term impact
* Unpredictable intensity

## 2. Lightning Strikes
* Electrical system compromise
* Potential avionics failure
* Temporary or permanent damage

## 3. Bird Strikes
* Engine intake damage
* Windshield and leading edge impacts
* Potential catastrophic consequences

## 4. Mechanical Failures
* Systemic risks
* Cumulative damage potential
* Varied severity based on component

# Interactive Dashboard
The interactive Tableau dashboard allows one to explore aircraft safety data across multiple dimensions. One can filter by aircraft categories, date ranges, and operational factors to investigate specific aspects of aviation safety.

[text](<Aviation Safety Data Analysis Dashboard>)
[text](<Hailstorm prediction_Dashboard>)

[text](<Wind shear Alerts_Dashboard>)
[text](<Turbulence Forecasting_Dashboard>)

# Next Steps
* Incorporate additional data sources, including flight hour data per aircraft model to further normalize safety metrics
* Analyze maintenance records to identify specific maintenance practices correlated with reduced accident rates
* Develop a predictive model to estimate accident risk for specific aircraft based on multiple factors

# Contact Information
For questions or further information about this analysis,consider the jupyter notebook as a place of reference as well as contacting:

bernicewakarindi@gmail.com - Project Lead

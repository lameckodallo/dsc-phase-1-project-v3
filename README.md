# Aviation Safety Risk Analysis

## Project Overview
This project analyzes flight safety using historical aviation incident data to determine whether our company should invest in aircraft — both for commercial and personal use.

We assess risks across aircraft makes, flight purposes, and operational contexts, with the goal of guiding a data-driven market entry strategy into the aviation sector.

---

## Business Questions
1. Should we even be investing in aircraft at all?  
   We explore long-term trends in aviation safety to assess whether the industry presents acceptable risk levels for new entrants.

2. If yes, how should we enter?  
   Our analysis suggests beginning with a “pilot” phase focused on executive and business travel, where historical risk is lowest. This phased approach helps us gain experience while minimizing early exposure to high-risk scenarios.

3. What types of aircraft should we consider?  
   We evaluate injury risk by aircraft make and recommend safe-performing models — particularly Beech and Bellanca, which rank among the safest within the most commonly used aircraft.

---

## Data Understanding

**Source**:  
The dataset comes from the [National Transportation Safety Board (NTSB)](https://www.ntsb.gov/) and is located in the `data/` folder. It covers civil aviation accidents and selected incidents from 1962 to 2023, including those in U.S. and international waters.

**Content Summary**:
- Over 90,000 records with 30+ variables
- Mix of textual and numerical data
- Some variables (like injury counts, severity, and aircraft make) are well-populated and reliable
- Others have missing data and were selectively excluded from analysis
- Post-1980 data shows more variation and reliability, and was used for risk trend modeling

---

## Conclusions

### 1. Modern aviation is far safer than in the past  
Injury severity has declined over time due to improvements in aircraft design, pilot training, and regulatory oversight. For our business, this translates into:
- Lower liability exposure
- Fewer safety-related service interruptions
- Stronger reputational positioning

![Total Injuries Over Time](images/total_injuries_over_time.png)

---

### 2. Start slow: Launch a risk-aware pilot phase focused on executive travel  
We recommend a deliberate rollout:
- Begin with executive and business segments, where risk is lowest
- Avoid early entry into higher-risk personal aviation
- Use the pilot to build internal capacity and safety culture

![Heatmap: Risk by Flight Purpose](images/heat_map_for_risk_by_flight_purpose.png)

---

### 3. Choose safe, proven aircraft brands  
Among the most commonly used aircraft, Beech and Bellanca consistently show lower injury risk per incident. These are the optimal starting points for procurement — blending safety with operational familiarity.

![Total Fatalities by Aircraft Make](images/total_fatalities_by_make.png)

---

## Next Steps

- Validate Tableau dashboard insights with domain experts and operations teams  
- Engage with aircraft procurement consultants to assess availability and cost of Beech/Bellanca models  
- Design pilot protocols for executive travel: routes, crews, maintenance standards  
- Build a flight risk scoring tool using this framework to assess new aircraft makes as data evolves  
- Monitor ongoing incident data to update risk trends and adjust strategy  

For an interactive dashboard, visit the  
[Tableau Public Dashboard](https://public.tableau.com/app/profile/lameck.odallo3896/viz/phaseoneproject_17536380409370/Dashboard1)

Access the full codebase and project files in the  
[GitHub Repository](https://github.com/lameckodallo/dsc-phase-1-project-v3)


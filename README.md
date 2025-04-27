# Electric Vehicle (EV) Analysis
## Problem Statement
With the rapid adoption of electric vehicles (EVs), stakeholders in the automotive industry, including policymakers, manufacturers, and infrastructure planners, require actionable insights into the EV ecosystem. The goal is to analyze registration trends, vehicle types, manufacturer shares, and regional adoption to drive future planning and policy decisions.

# Objective
To develop a dynamic, interactive Tableau dashboard that provides deep insights into:
- Total EV registrations across years and states
- Distribution of vehicle types (BEV vs PHEV)
- Popular manufacturers and models
- Average electric range of vehicles
- Clean Alternative Fuel Vehicle (CAFV) eligibility
- Patterns in EV adoption by geography and model year

# Steps Followed
1. Data Collection & Understanding
- Acquired dataset comprising 1,50,422 electric vehicle records.
- Key attributes identified: Make, Model, Model Year, EV Type (BEV/PHEV), State, Electric Range, CAFV Eligibility.

2. Data Cleaning
  - Removed null or inconsistent records.
  - Standardized EV types and state names.
  - Verified data types for Tableau compatibility.

3. Data Transformation
  - Categorized data by EV Type and CAFV eligibility.
  - Derived fields such as average electric range.
  - Aggregated counts by model, make, year, and state.

4. Data Visualization (in Tableau)
- KPIs Panel:
    - Total Vehicles: 1,50,422
    - Average Electric Range: 67.83 miles
    - BEV Share: 77.6% (1,16,750 vehicles)
    - PHEV Share: 22.4% (33,672 vehicles)
- Bar Charts:
    - Vehicles by Model Year
    - Top 10 Vehicle Models and Makes
    - CAFV Eligibility Breakdown
- Map View:
    - Total Vehicles by State
- Filter Panels:
    - By EV Type
    - By CAFV Eligibility
    - By State

## Insights & Findings
- Tesla leads the market with over 52.7% of total EVs.
- Nissan and Chevrolet follow as top competitors.
- The most popular EV models include Tesla Model S, 3, X, Y and Nissan Leaf.
- Over 41.8% of vehicles are CAFV eligible, aiding clean fuel incentives.
- EV adoption is highest in states like California and other western states.
- The average electric range across all EVs is 67.83 miles, though newer models often exceed this.
- The trend shows a rise in BEV registrations over recent years.

## Conclusion
The EV dashboard provides a clear snapshot of electric vehicle adoption across the United States. Tesla dominates the landscape, both in terms of make and models. BEVs form the majority of EVs, reflecting a strong market preference over PHEVs. CAFV eligibility is significant and could impact buyer incentives and infrastructure planning.

## Recommendations
1. Policy Focus: Increase awareness and eligibility for CAFV to boost clean energy vehicle adoption.
2. Infrastructure Investment: Prioritize charging stations in states with lower adoption to stimulate growth.
3. Manufacturer Strategy: Non-Tesla brands should focus on improving vehicle range and cost-effectiveness.
4. Incentivize BEVs: Promote BEVs through tax benefits or rebates as they form the majority and align with long-term sustainability goals.
5. Year-over-Year Monitoring: Maintain dashboards to track emerging trends and make real-time data-driven decisions.

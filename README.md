# Hospital_Dashboard
HOSPITAL EMERGENCY ROOM DASHBOARD - PROJECT DOCUMENTATION

OVERVIEW
Developed a comprehensive Power BI reporting solution to monitor and analyze Emergency Room (ER) performance. The dashboard provides real-time insights into patient flow, wait times, and satisfaction levels, enabling hospital administrators to identify bottlenecks and optimize staffing.

KEY PERFORMANCE INDICATORS (KPIs)
- Total Patient Volume: 9,216 visits
- Average Wait Time: 35.3 minutes
- Patient Satisfaction Score: 4.99 / 10
- Admission Rate: 50.04%
- Total Referrals: 579

TECHNICAL IMPLEMENTATION
- Tools: Power BI Desktop, DAX, Power Query (M), Data Modeling.
- Data Architecture: Built a star schema connecting patient demographics, referral departments, and arrival timestamps.
- Advanced DAX: Authored measures for rolling averages, target achievement percentages, and dynamic time-period filtering.
- Visualizations: 
    * Temporal Heatmaps (Arrival patterns by Hour/Day)
    * Demographic Donut Charts (Gender, Race)
    * Age Group Distribution Bar Charts
    * Departmental Referral Flow Diagrams

BUSINESS IMPACT & INSIGHTS
- Staffing Optimization: Identified peak surge periods (e.g., Saturdays 15:00-16:00), supporting data-driven physician scheduling.
- Operational Efficiency: Highlighted that 40.68% of patients missed wait-time targets, pinpointing specific hours for process re-engineering.
- Referral Tracking: Analyzed secondary load on General Practice and Orthopedics to improve inter-departmental transitions.

DASHBOARD STRUCTURE
1. Consolidated View: High-level executive overview of all-time metrics.
2. Monthly View: Deep-dive performance trends filtered by specific months.
3. Patient Details: Granular table for individual case auditing and tracking.

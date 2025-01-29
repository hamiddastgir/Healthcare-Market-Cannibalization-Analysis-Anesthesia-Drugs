Market Dynamics & Strategic Revitalization for an Injectable Anesthesia Drug

BIA-810D Final Project – Market Cannibalization Analysis

Date: November 27, 2023
Presented by: Group 3
Sponsor: Sanjiv Koshal

Problem Statement
	•	Product 1 (J1885 - Ketorolac Tromethamine): Market leader, experiencing consistent decline in sales.
	•	Product 2 (J2250 - Midazolam Hydrochloride): A new variant intended to absorb Product 1’s market share, but instead losing traction.
	•	Product 3 (J3010 - Fentanyl Citrate): A primary competitor that is rapidly gaining market share at the expense of both Product 1 and Product 2.
	•	Product 4 (J2704 - Propofol): An emerging competitor, showing signs of future growth.

The objective of this analysis is to evaluate the market dynamics and recommend strategies to address Product 2’s market erosion.

Data Sources & Preprocessing

The project utilizes multiple datasets to build an analysis-ready dataset for actionable insights.

Dataset Name	Description
Medicare Claims Data	Contains ~1 million claims, including procedure codes, diagnosis codes, and provider details.
HCP Demographics Data	Contains physician details, including specialty and region.
Patient Demographics Data	Contains patient age group distribution and demographic characteristics.
Zip-to-Territory Mapping Data	Maps HCP zip codes to sales territories.
Diagnosis Code Mapping Data	Maps ICD-10 diagnosis codes to medical specialties.
Procedure Code Mapping Data	Links HCPCS procedure codes to corresponding products.

Data Preparation Process
	•	Merged all claims datasets into a single structured dataframe (~28,368 records after filtering).
	•	Filtered for Procedure Codes (J1885, J2250, J3010, J2704) to focus on anesthesia products.
	•	Mapped diagnosis codes to specialties to identify treatment trends.
	•	Standardized zip codes and joined them with territory mapping data.
	•	Enriched claims data with HCP and patient demographic information.

 Analysis & Key Insights

1. Market Dynamics & Competitive Landscape
	•	Product 3 (J3010) is outperforming Product 2 due to strong HCP engagement and prescriber confidence.
	•	Product 1 (J1885) is steadily losing market share, signaling market saturation.
	•	Product 2 (J2250) is underperforming, struggling to differentiate itself against both Product 3 and Product 4.

Actionable Recommendations:
	•	Leverage Product 1’s legacy to increase Product 2’s credibility.
	•	Strengthen prescriber engagement through education and incentives.
	•	Improve targeting strategies in underperforming territories.

2. Key Market Drivers

HCP & Patient Behavior Analysis
	•	Anesthesiologists and Cardiologists are the primary prescribers. Product 3 dominates these groups.
	•	Patients aged 61-70 represent the highest claim volume, and Product 3 is capturing most of this group.

Actionable Recommendations:
	•	Increase engagement with Anesthesiologists and Cardiologists to boost Product 2’s adoption.
	•	Target older patient demographics with customized awareness campaigns.

3. Geographic Market Trends
	•	New York, NY & LA-San Diego, CA are experiencing sharp Product 2 declines, while Product 3 is growing rapidly.
	•	Less populated territories like Phoenix & Minneapolis show moderate declines.

Actionable Recommendations:
	•	Focus on high-population areas for aggressive re-engagement.
	•	Implement region-specific promotional strategies to counter Product 3’s dominance.


 Strategies to Revitalize Product 2’s Market Share
	1.	Territory Interventions: Deploy additional field force in top 5 underperforming territories.
	2.	Co-pay & Payer Assistance: Reduce financial barriers to enhance patient adoption.
	3.	Targeted Digital Promotions: Use webinars and direct HCP engagement to boost awareness.
	4.	Brand Repositioning: Align Product 2 with Product 1’s trusted reputation.
	5.	AI/ML Integration: Use predictive modeling to optimize marketing and prescriber targeting.


 Deliverables
	•	Jupyter Notebook (.ipynb) – Contains all Python code, data cleaning, EDA, and visualizations.
	•	PowerPoint Presentation (.pptx) – Summarizes key insights and strategic recommendations.


 Future Enhancements
	•	Expand Data Sources: Incorporate private insurance claims to improve accuracy.
	•	Predictive Modeling: Use machine learning models to optimize prescriber targeting.
	•	Competitor Analysis: Conduct deeper pricing & adoption analysis.


 Contact Information

For further inquiries or discussions, feel free to reach out to Group 3.
GitHub Profile: [Your GitHub Profile]
Email: [Your Email]

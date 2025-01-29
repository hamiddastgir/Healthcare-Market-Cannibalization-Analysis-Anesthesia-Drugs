# Market Dynamics & Strategic Revitalization for an Injectable Anesthesia Drug
**BIA-810D Final Project – Market Cannibalization Analysis**  
**Date: December 16, 2024**  
**Presented by:** **Group 3**  
**Sponsor:** _Sanjiv Koshal_

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Problem Statement](#problem-statement)  
3. [Data Sources & Preprocessing](#data-sources--preprocessing)  
4. [Analysis & Key Insights](#analysis--key-insights)  
    - [1. Market Dynamics & Competitive Landscape](#1-market-dynamics--competitive-landscape)  
    - [2. Key Market Drivers](#2-key-market-drivers)  
    - [3. Geographic Market Trends](#3-geographic-market-trends)  
5. [Strategies to Revitalize Product 2’s Market Share](#strategies-to-revitalize-product-2s-market-share)  
6. [Project Deliverables](#project-deliverables)  
7. [Future Enhancements](#future-enhancements)  
8. [Repository Structure](#repository-structure)  
9. [Contact Information](#contact-information)  

---

## Project Overview
This project provides a comprehensive market cannibalization analysis in the injectable anesthesia drug market. We specifically investigate why **Product 2 (Midazolam Hydrochloride)** has been unable to capitalize on the declining market share of **Product 1 (Ketorolac Tromethamine)** and is, instead, losing ground to **Product 3 (Fentanyl Citrate)**. Our team analyzes market trends, competitive forces, and emerging market drivers to recommend actionable strategies aimed at revitalizing Product 2’s market performance.

---

## Problem Statement
- **Product 1 (J1885 – Ketorolac Tromethamine)**  
  - Market leader with consistent decline in sales.
- **Product 2 (J2250 – Midazolam Hydrochloride)**  
  - Newly introduced variant intended to absorb Product 1’s market share; currently losing traction.
- **Product 3 (J3010 – Fentanyl Citrate)**  
  - Rapidly gaining market share at the expense of both Product 1 and Product 2.
- **Product 4 (J2704 – Propofol)**  
  - Emerging competitor, showing early signs of growth.

**Objective:** Evaluate the market dynamics and recommend data-driven strategies to address Product 2’s market erosion.

---

## Data Sources & Preprocessing
Below is an overview of the datasets used, as well as the cleaning and merging steps taken to create an analysis-ready dataset:

| **Dataset Name**                | **Description**                                                                                   |
|---------------------------------|---------------------------------------------------------------------------------------------------|
| **Medicare Claims Data**        | \~1 million claims, including procedure codes, diagnosis codes, and provider details.             |
| **HCP Demographics Data**       | Physician details, including specialty and region.                                                |
| **Patient Demographics Data**   | Patient age group distribution and demographic characteristics.                                   |
| **Zip-to-Territory Mapping**    | Maps HCP zip codes to sales territories.                                                          |
| **Diagnosis Code Mapping**      | Maps ICD-10 diagnosis codes to medical specialties.                                               |
| **Procedure Code Mapping**      | Links HCPCS procedure codes to corresponding products.                                            |

**Data Preparation Process:**
1. Merged the various claims data sources into a single structured DataFrame (~28,368 records after filtering).  
2. Filtered for relevant **Procedure Codes (J1885, J2250, J3010, J2704)** to focus on the four anesthesia products.  
3. Mapped ICD-10 diagnosis codes to specialties to identify usage trends across different HCP types.  
4. Standardized zip codes and joined with territory mapping to analyze geographic distribution.  
5. Enriched the claims data with HCP and patient demographic information for granular insights.

---

## Analysis & Key Insights

### 1. Market Dynamics & Competitive Landscape
- **Product 3 (J3010)** is outperforming **Product 2**, backed by strong HCP engagement and prescriber trust.  
- **Product 1 (J1885)** is steadily losing market share, indicating saturation and diminishing returns.  
- **Product 2 (J2250)** fails to differentiate effectively against both **Product 3** and the emerging **Product 4**.

**Actionable Recommendations:**
- Leverage Product 1’s legacy and brand recognition to boost Product 2’s credibility.  
- Strengthen HCP engagement via educational programs and incentive structures.  
- Refine targeting strategies in underperforming territories based on key demographic and utilization patterns.

### 2. Key Market Drivers
- **HCP & Patient Behavior Analysis**  
  - Anesthesiologists and Cardiologists account for the majority of prescriptions. Product 3 dominates within these prescriber groups.  
  - Patients aged 61–70 represent the highest claim volume, with Product 3 capturing most of that demographic.

**Actionable Recommendations:**
- Enhance educational outreach and partnerships with Anesthesiologists and Cardiologists to drive Product 2 adoption.  
- Tailor marketing campaigns to address the unique needs and concerns of older patient demographics.

### 3. Geographic Market Trends
- **High-density regions** (e.g., New York, NY & LA-San Diego, CA) show sharp declines for Product 2, while Product 3 enjoys significant growth.  
- **Less populated territories** (e.g., Phoenix & Minneapolis) exhibit moderate declines but may respond favorably to targeted interventions.

**Actionable Recommendations:**
- Intensify promotional efforts in top high-population cities to reclaim market share from Product 3.  
- Develop localized, region-specific strategies in moderate territories to prevent further erosion.

---

## Strategies to Revitalize Product 2’s Market Share
1. **Territory Interventions**: Allocate additional field resources to the top 5 underperforming territories to rebuild market presence.  
2. **Co-pay & Payer Assistance**: Lower financial barriers to adoption through patient-focused assistance and reduced co-pays.  
3. **Targeted Digital Promotions**: Leverage webinars, digital ads, and direct HCP engagement to improve brand awareness.  
4. **Brand Repositioning**: Align Product 2 with Product 1’s well-established reputation to reinforce trust.  
5. **AI/ML Integration**: Utilize predictive modeling for precision targeting, optimizing marketing spend and prescriber outreach.

---

## Project Deliverables
- **Jupyter Notebook** (`810 Final Python File.ipynb`):  
  Contains Python code for data preprocessing, exploratory data analysis (EDA), visualizations, and preliminary modeling.
- **PowerPoint Presentation** (`BIA 810-D Final Presentation Group 3.pptx`):  
  Summarizes the key findings, visual insights, and strategic recommendations for stakeholders.
- **Original Data Files** (CSV folder):  
  Source datasets used in the analysis. Note that certain files may be subject to privacy and compliance constraints.

---

## Future Enhancements
- **Expand Data Sources**: Incorporate private insurance claims to provide a more holistic view of the anesthesia drug market.  
- **Predictive Modeling**: Build advanced machine learning models to accurately forecast prescribing patterns and optimize targeting.  
- **Deeper Competitor Analysis**: Investigate pricing strategies, promotional activities, and adoption rates of competitor products.

---

## Repository Structure

Repository_Structure/
├── Original Data Files CSV/
│   ├── Medicare_Claims_data_part_1.csv
│   ├── Medicare_Claims_data_part_2.csv
│   ├── Medicare_Claims_data_part_3.csv
│   ├── Medicare_Claims_data_part_4.csv
│   ├── Medicare_Claims_data_part_5.csv
│   ├── HCP_demographics_data.csv
│   ├── Patient_demographics_data.csv
│   ├── Diagnosis_Code_Mapping.csv
│   ├── Procedure_Code_Mapping.csv
│   └── Zip_to_Territory_Mapping.csv
├── 810 Final Python File.ipynb
├── BIA 810-D Final Presentation Group 3.pptx
└── README.md

---

## Contact Information
For questions, feedback, or collaboration opportunities, feel free to reach out:

- **Group 3 – BIA-810D**  
- **GitHub Profile**: https://github.com/hamiddastgir
- **Email**: [mdastgir@stevens.edu](mailto:mdastgir@stevens.edu)

---

### Suggestions / Next Steps
- If you have any additional files or analyses, consider adding a `docs/` folder for more detailed documentation.  
- Provide a brief overview of your environment or requirements for running the Jupyter Notebook (e.g., Python version, libraries) in a `requirements.txt` or within the notebook header.  
- Encourage collaboration by including guidelines for contributions, issues, and pull requests.

**Thank you for exploring our market cannibalization analysis. We look forward to your feedback and continued collaboration!**

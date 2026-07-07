# ECOWAS Language & Digital Identity Inclusion Dashboard

## Women Techsters Bootcamp 5.1 Capstone Project

### Group 14 – FEMME FOUNDATION
**Women Techsters Hackathon  Group 14 (Femme Foundation)**
Category 3: Data Analysts & Technical Project Managers

## Project Overview

This project examines language exclusion in African digital identity systems across the 12 current ECOWAS member states. It combines language mapping, a custom Language Exclusion Risk Score, literacy and gender inclusion analysis, and a government digital ID portal accessibility audit into one Power BI dashboard.

Aligned with:
- SDG 9  Industry, Innovation and Infrastructure
- SDG 10  Reduced Inequalities
- SDG 16  Peace, Justice and Strong Institutions
---

## Key Finding

Across 8 audited government digital identity portals, 0 currently offer any indigenous African language option — despite most ECOWAS countries having official languages (English, French, Portuguese) spoken fluently by only a minority of the population.
---

## Team & Roles

| Name | Role | Responsibility |
|---|---|---|
| Lilian Kanu | Technical Project Manager / Group Rep | Overall coordination, schedule, Demo Day, final submission |
| Shammah Ogbodo-Benson | Team Lead – Data Strategy, Sourcing & Cleaning | Collect, clean, and standardize source datasets |
| Naimat Ayomide Daud | Lead Analyst – Language Mapping & Risk Score | Language mapping, Risk Score methodology, GitHub management |
| Bernice Makata | Lead Analyst – Literacy & Gender Data | Literacy, female literacy, internet access, gender trends |
| Matamela Zwothe | Lead Analyst – Portal Audit & AI Translation | Digital ID portal audit, AI translation demo, documentation validation |
| Blessing Bukola Ademola | Data Analyst – DAX & Calculations | All Power BI DAX measures, calculated columns, KPIs |
| Jemima Abah | Data Analyst – Dashboard Visualization | Charts, maps, slicers, presentation design |
| Gift Ikechukwu | Data Analyst – Documentation & Reporting | Team register, report writing, final QA |

----
## Repository Structure

- data/  Cleaned datasets (Excel/CSV) used across the dashboard
- methodology/ Written methodology docs: Risk Score formula, audit methods, gap logic
- dashboard/  Power BI (.pbix) files
- docs/ Project documentation, proposal, final report, presentation materials
- README.md This file
---

## Language Exclusion Risk Score  Summary

Risk Score = Literacy Risk + Fluency Risk + Internet Risk + Fragmentation Risk (0–100 scale)

- Literacy Risk  based on Adult Literacy %
- Fluency Risk  based on % of population fluent in the official language
- Internet Risk  based on Internet Users %
- Fragmentation Risk  based on number of indigenous languages with no official digital recognition

Risk Tiers: 0–33 Low · 34–66 Medium · 67–100 High

Full formula, weighting rationale, and data sources are documented in /methodology.
----

## Data Sources

- Ethnologue (language mapping)
- UNESCO World Atlas of Languages / UNESCO Institute for Statistics
- World Bank Open Data (literacy, internet access, financial inclusion)
- Direct audit of national digital ID portal websites (see /methodology for audit log)

  ---
## Status

In progress  Women Techsters Hackathon submission

---
## Contact

For questions about this repository, contact the team via the Women Techsters Category 3 hackathon channel.

---






# Language & Digital Inclusion Dashboard

## Women Techsters Bootcamp 5.1 Capstone Project

### Group 14 – FEMME FOUNDATION

---

# Project Overview

This project investigates how language barriers contribute to digital exclusion in ECOWAS digital identity systems.

Across many ECOWAS countries, government digital identity services are available only in English, French, or Portuguese despite most citizens speaking indigenous languages.

The dashboard visualizes where language, literacy, gender, and digital access intersect to create barriers to essential services.

---

# Problem Statement

Millions of ECOWAS citizens cannot independently access digital identity systems because government portals rarely support indigenous languages. This disproportionately affects women, rural populations, and individuals with lower literacy levels.

---

# Objectives

- Measure language exclusion across ECOWAS.
- Create a Language Exclusion Risk Score.
- Compare literacy and digital access.
- Evaluate multilingual support on government portals.
- Demonstrate how AI can improve language accessibility.

---

# Tools Used

- Power BI
- Microsoft Excel
- Claude AI / ChatGPT
- DAX
- Power Query

---

# Dashboard Features

- ECOWAS country map
- Language Exclusion Risk Score
- Literacy comparison
- Female literacy analysis
- Internet access comparison
- Government portal language audit
- AI-generated insights
- Key Influencers
- Decomposition Tree

---

# AI Component

The project incorporates AI in three ways:

1. AI-assisted translation into indigenous languages.
2. AI-generated executive summaries.
3. Power BI AI visuals for identifying key drivers of exclusion.

---

# Dataset Sources

- World Bank
- UNESCO
- GSMA
- National Statistics Offices
- Government Digital Identity Portals

---

# Repository Structure

```
├── Data
│   ├── ECOWAS_Data.xlsx
│
├── Dashboard
│   ├── Language_Digital_Inclusion.pbix
│
├── Images
│
├── AI_PROMPTS.md
│
├── README.md
│
└── Presentation.pdf
```

---

# Key Insights

- Language exclusion remains a significant barrier to digital identity access.
- Women experience higher exclusion due to lower literacy levels.
- Indigenous language support is limited across government portals.
- Countries with lower official-language reach generally have higher exclusion risk.



---

# Future Improvements

- Add more indigenous languages.
- Integrate live government portal monitoring.
- Develop an AI chatbot for multilingual digital identity assistance.
- Expand analysis beyond ECOWAS.

---

## Team & Roles

| Name | Role | Responsibility |
|---|---|---|
| Lilian Kanu | Technical Project Manager / Group Rep | Overall coordination, schedule, Demo Day, final submission |
| Shammah Ogbodo-Benson | Team Lead – Data Strategy, Sourcing & Cleaning | Collect, clean, and standardize source datasets |
| Naimat Ayomide Daud | Lead Analyst – Language Mapping & Risk Score | Language mapping, Risk Score methodology, GitHub management |
| Bernice Makata | Lead Analyst – Literacy & Gender Data | Literacy, female literacy, internet access, gender trends |
| Matamela Zwothe | Lead Analyst – Portal Audit & AI Translation | Digital ID portal audit, AI translation demo, documentation validation |
| Blessing Bukola Ademola | Data Analyst – DAX & Calculations | All Power BI DAX measures, calculated columns, KPIs |
| Jemima Abah | Data Analyst – Dashboard Visualization | Charts, maps, slicers, presentation design |
| Gift Ikechukwu | Data Analyst – Documentation & Reporting | Team register, report writing, final QA |

Group 14 – FEMME FOUNDATION

Women Techsters Bootcamp 5.1

---

# License

Educational Project

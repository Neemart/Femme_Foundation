
# Language & Digital Inclusion Dashboard

## Women Techsters Bootcamp 5.1 Capstone Project

### Group 14 – FEMME FOUNDATION

---

# Project Overview

Digital identity systems across Africa—specifically within ECOWAS member states—are primarily built using official/colonial languages (English, French, or Portuguese). However, with over 2,000 living African languages, millions of citizens, particularly women and rural populations, are excluded due to language and literacy barriers. 

Rather than building an unverified solution, Group 14 built a proof-first evidence dashboard in Power BI across 12 ECOWAS states to evaluate the severity of digital exclusion, map high-risk areas, and justify the deployment of AfriID AI—a voice-first multilingual assistant.

---

# Sustainable Development Goals (SDG) Alignment
SDG 05 (Gender Equality): Measures how language exclusion impacts women more severely than men due to existing literacy gaps.  SDG 09 (Industry, Innovation & Infrastructure): Builds a data-backed evidence base for inclusive identity tools.  SDG 10 (Reduced Inequalities): Pinpoints precise geographic and linguistic exclusion points in public services.  SDG 16 (Peace, Justice & Strong Institutions): Highlights systemic barriers preventing citizens from accessing legal identity.

---

# Dashboard Architecture & Views
# The Power BI evidence dashboard comprises 4 core interactive pages covering all 12 ECOWAS states:  

1. Exclusion Overview (Problem Statement)File Reference:
  Key Visuals & Metrics:Headline KPIs: 12 Countries Covered, 56.83 Average Risk Score, 20% Portals Non-Functional.  Risk Score Bar Chart: Guinea (70) and Guinea-Bissau (70) represent the highest exclusion risk, whereas Ghana (27) scores lowest.  Indigenous Languages Table: Highlights primary languages per country (e.g., Fon, Yoruba, Hausa, Wolof, Krio).  Multilingual Coverage Gap: Official vs. Indigenous percentage coverage breakdown.

![image alt](https://github.com/Neemart/Femme_Foundation/blob/79f93ea2f21595fce312e3180d0d9460620d9d5d/Screenshot%20(318).png)

 
 3. Access Evaluation (Evidence of Barriers)File Reference:
    Key Visuals & Metrics:Literacy Trends & Gender Gap: Line chart comparing female vs. male literacy (highlights gaps exceeding 20 points in 5 countries, peaking at 29 points in Guinea).  Effective Access Breakdown: Evaluates true access based on literacy and official language reach.  Portal Audit Breakdown: Analysis of 15 national government portals—0 out of 15 offer any indigenous African language support.

![image alt](https://github.com/Neemart/Femme_Foundation/blob/d3a4cb368bed4bd8b6e3536d51231b3b6c2065e1/Screenshot%20(319).png)

 
 4. AI-Assisted Insights (Drivers of Exclusion)File Reference:
 Key Visuals & Analytics:Key Influencers & Decomposition Tree: Machine-learning visuals breaking down primary drivers of Severe Risk Tiers by country and language group.  Scatter Plot: Average Risk Score vs. Effective Access % (validating that higher risk directly tracks with lower effective access).  Priority Deployment Ranking: Prioritizes regions for immediate intervention.

![image alt](https://github.com/Neemart/Femme_Foundation/blob/6f1771e284218f54685a80a95523cd2a37edde22/Screenshot%20(320).png)

 
5. Summary & Recommendations (Solutions & Policy)File Reference:
    Key Visuals & Metrics:Deployment Needs: Evaluates offline vs. cloud mode requirements across 12 countries (9 require offline capabilities).  Smart Narrative Box: Auto-generated summaries dynamically updating based on slicers and filters.  Policy Guidance: Directs decision-makers toward priority regions (Guinea, Guinea-Bissau, Sierra Leone, Liberia).

![image alt](https://github.com/Neemart/Femme_Foundation/blob/62174170d212aeb471fd29835e83fba18d35f820/Screenshot%20(321).png)

---

# Data Sources

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
| Shammah Ogbodo-Benson | Data Strategy, Sourcing & Cleaning | Collect, clean, and standardize source datasets |
| Naimat Ayomide Daud | Data Analyst – Language Mapping & Risk Score | Language mapping, Risk Score methodology, GitHub management |
| Bernice Makata | Data Analyst – Literacy & Gender Data | Literacy, female literacy, internet access, gender trends |
| Zwothe Matamela | Data Analyst – Portal Audit & Github Documentation | Digital ID portal audit, AI translation demo, documentation validation |
| Blessing Bukola Ademola | Data Analyst | AI Prompt Translation 
| Jemima Abah | Data Analyst – Dashboard Visualization | Charts, maps, slicers, presentation design |
| Gift Ikechukwu | Data Analyst – Documentation & Reporting | Team register, report writing, final QA |



---



# ECOWAS Language & Digital Identity Inclusion Dashboard

**Women Techsters Hackathon — Group 14 (Femme Foundation)**
Category 3: Data Analysts & Technical Project Managers

## Project Overview

This project examines language exclusion in African digital identity systems across the 12 current ECOWAS member states. It combines language mapping, a custom Language Exclusion Risk Score, literacy and gender inclusion analysis, and a government digital ID portal accessibility audit into one Power BI dashboard.

Aligned with:
- SDG 9 — Industry, Innovation and Infrastructure
- SDG 10 — Reduced Inequalities
- SDG 16 — Peace, Justice and Strong Institutions

## Key Finding

Across 8 audited government digital identity portals, 0 currently offer any indigenous African language option — despite most ECOWAS countries having official languages (English, French, Portuguese) spoken fluently by only a minority of the population.

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

## Repository Structure

- data/ — Cleaned datasets (Excel/CSV) used across the dashboard
- methodology/ — Written methodology docs: Risk Score formula, audit methods, gap logic
- dashboard/ — Power BI (.pbix) files
- docs/ — Project documentation, proposal, final report, presentation materials
- README.md — This file

## Language Exclusion Risk Score — Summary

Risk Score = Literacy Risk + Fluency Risk + Internet Risk + Fragmentation Risk (0–100 scale)

- Literacy Risk — based on Adult Literacy %
- Fluency Risk — based on % of population fluent in the official language
- Internet Risk — based on Internet Users %
- Fragmentation Risk — based on number of indigenous languages with no official digital recognition

Risk Tiers: 0–33 Low · 34–66 Medium · 67–100 High

Full formula, weighting rationale, and data sources are documented in /methodology.

## Data Sources

- Ethnologue (language mapping)
- UNESCO World Atlas of Languages / UNESCO Institute for Statistics
- World Bank Open Data (literacy, internet access, financial inclusion)
- Direct audit of national digital ID portal websites (see /methodology for audit log)

## Status

In progress — Women Techsters Hackathon submission

## Contact

For questions about this repository, contact the team via the Women Techsters Category 3 hackathon channel.

# Omnichannel Operations: Field Force Analytics Dashboard

## Project Overview
During the pandemic, traditional face-to-face interactions between pharmaceutical field representatives (reps) and healthcare providers (HCPs) became challenging. The shift toward digital strategies such as emails, texts, and remote calls created a fragmented data landscape, with interactions captured across multiple systems and no single source of truth.  

This project aimed to consolidate these interactions into a centralized, actionable platform, providing insights and metrics to support field reps, mid-level managers, and executives in optimizing their strategies and maximizing HCP engagement.

---

## Client
Top Pharmaceutical Company – partnered directly with two Director-level stakeholders.

---

## Challenge
- Existing reporting was **Excel-based**, requiring manual formatting and ~2 hours/week of operational effort.  
- Large files were difficult to interpret and often caused application crashes.  
- Pandemic-induced communication methods (emails, remote calls, texts) were **outside the scope** of legacy reports, requiring aggregation from multiple vendors.

---

## Business Goals
Enable medical representatives to transition to remote engagement while maximizing reach and awareness of new developments.

---

## User Needs
1. **Field reps & mid-level managers**: Track performance through metrics like HCP Reach % and Engagement Rate.  
2. **Executives**: Make informed strategic decisions to refine field force execution.

---

## User Research
- Conducted **interviews with 5 users** across different teams and levels.  
- Key findings:  
  - Users needed a **centralized, usable solution** for tracking activity and measuring performance.  
  - Executives required a **high-level view** to identify trends and guide strategic decisions.

---

## Solution
Developed a **consolidated analytics platform** integrating seven interaction types and providing critical insights and trends.

### Metric Definitions
To standardize calculations and reduce ambiguity, metrics such as **Engagements Per Week (EPW)** were defined collaboratively with stakeholders. Example:

| Option | Logic | Strategic Trade-off |
|--------|-------|-------------------|
| EPW (days on territory) | (Total Engagements / Days on Territory) * 5 | Pro: Consistent with legacy 'Calls Per Day'<br>Con: Inflated values |
| EPW per rep | Avg(Total Engagements / Count(Active Reps)) | Pro: Mathematically precise<br>Con: Hard for reps to validate |
| **EPW (weeks on territory)** | Total Engagements / Weeks on Territory | **Pro: Simple, easy to understand and validate by reps**<br>Con: Includes partially active reps |

> Chosen approach prioritized **clarity and user trust**.

---

## Design & Usability Testing
- Conducted **remote moderated usability tests with 10 users**.  
- Initially used radar charts for engagement split, but users found them overwhelming.  
- Pivoted to **simple bar charts** with color coding and text for storytelling to reduce cognitive load.  

### Final Views
| View | Target Users | Features |
|------|--------------|---------|
| Summary View | Field Users | Numeric grid at geo levels, deep-dive analysis |
| Trended View | Field Users | Charts for 13-week and 12-month trends, Engagements per Week, Segmented Customer Reach |
| Executive Summary | Executives | KPIs, nation-level distributions, insights, recommendations, channel contribution, call type split |

> Representative visualizations included due to client confidentiality.

<img width="2702" height="1598" alt="Group 20" src="https://github.com/user-attachments/assets/b208a829-deb9-4cf6-9ae3-43eb93064434" />

---

## Impact & Results
- **100% adoption** during pilot release.  
- Successfully rolled out to **12 sales teams across North America**.  
- Insights led to data-driven decisions:  
  - Identified HCP Reach % drop for High Priority Targets in Q3  
  - Highlighted 60% of these HCPs as Low Access  
  - Noted ineffective email engagement (72% unopened)  
  - Recommended pivoting to remote calls in Q4  

> Contributed positively to the healthcare industry during a global crisis.

---

## Learnings
- Engage **field users from the beginning**; management’s perspective may differ.  
- Prioritize **simple, clear visuals and text** over sophisticated but complex designs.  
- Metric clarity and trust are critical for adoption.

---

## Technology & Tools
- Excel / Data aggregation pipelines  
- Visualization: Bar charts, trend charts, KPI summaries  
- Usability Testing: Remote moderated sessions  

---

## Acknowledgements
> "There were a lot of variables at play on this one, but you handled it well. Prajakta deserves a raise for this delivery."  
> — Associate Director, Reporting Strategy

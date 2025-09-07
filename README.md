# 📊 Customer Voice Insight & Service Analytics – Home Office Portfolio Project

## Project Title
Customer Insight Analytics for Visa, Passport, and Immigration Services

## My Role
Business & Data Analyst / Tableau Developer / Automation Specialist

- Designed and implemented SQL queries (20+) to analyze satisfaction, escalations, and service timeliness.  
- Built interactive Tableau dashboards for executives and operational teams.  
- Automated reporting and SLA alerts using Power Automate flows.  
- Applied Agile Mini-Sprint methodology to deliver the project in a 10-day timeline.  
- Managed project tasks end-to-end using Trello boards for visibility and accountability.  

---

## Project Overview
This project simulates the role of a **Customer Voice Analyst** at the UK Home Office.  
The **Customer Voice team** focuses on ensuring customers are at the heart of decision-making for services like **Visas, Passports, Immigration, and Citizenship**.  

My task was to create an end-to-end analytics solution that:  
- Analyzes **customer satisfaction, escalations, and service efficiency**  
- Provides **Tableau dashboards** for stakeholders at multiple levels  
- Automates **monthly reporting and SLA breach alerts** using Power Automate  

This reflects real-world responsibilities from the job description, including delivering insight products, supporting evidence-based decisions, and ensuring the customer voice drives strategy.

---

## Problem Statement
The Home Office needed to understand:

- Which services are delivering **poor customer satisfaction**?  
- Where are **delays or SLA breaches** happening most often?  
- What are the **common escalation reasons** and how quickly are they resolved?  
- How can we **automate reporting** and ensure insights are delivered on time to directors and managers?  

---

## Stakeholder Engagement

### Target Stakeholders
- **Customer Voice Team Lead** – ensure insight aligns with business needs.  
- **Operational Managers** – use dashboards to address performance issues.  
- **Directors of Customer Services** – strategic decision-making.  
- **Analysts & Customer Experience Specialists** – day-to-day monitoring.  

---

## Use Cases
- Monthly **NPS monitoring** for each service line (Visa, Passport, Immigration, Citizenship).  
- Automated **email alerts** for SLA breaches (pending > 30 days).  
- Escalation analysis by **issue type, resolution time, and team**.  
- **Sentiment tracking** from customer comments and feedback surveys.  
- Regional dashboards for **location-based performance monitoring**.  

---

## Stakeholder Stories
- *“As a Director, I want a monthly dashboard with KPIs so I can make evidence-based decisions.”*  
- *“As a Customer Voice Manager, I want alerts when satisfaction drops below 60%, so I can intervene quickly.”*  
- *“As an Operations Team Lead, I need to know which escalation types are increasing to allocate resources effectively.”*  

---

## Acceptance Criteria
- 20+ SQL queries answering satisfaction, timeliness, escalation, and survey insights.  
- At least **3 Tableau dashboards** (Executive Overview, Voice of Customer, Escalations).  
- **2 Power Automate workflows**: SLA breach alert + monthly insight email.  
- Clear documentation in GitHub with methodology, Trello workflow, and insights.  

---

## Success Criteria
✅ Business questions answered with real insight.  
✅ Dashboards interactive, filterable, and usable by multiple teams.  
✅ Automated reporting workflows operational.  
✅ GitHub repository with version control and documentation.  

---

## Data Source
A **simulated dataset** was generated for 2024–2025 including:  

1. **Customer_Profile** – demographics, region, vulnerability.  
2. **Service_Requests** – submission/completion dates, status, location.  
3. **Customer_Feedback** – sentiment, ratings, comments.  
4. **Monthly_Satisfaction_Survey** – NPS-style surveys.  
5. **Escalations_Log** – issue type, resolution time, teams involved.  

---

## Dataset Example

**Service_Requests Table**  

| RequestID | CustomerID | ServiceType | SubmissionDate | CompletionDate | Status      | Location           |  
|-----------|------------|-------------|----------------|----------------|-------------|-------------------|  
| REQ00001  | CUST0231   | Visa        | 2024-03-15     | 2024-04-12     | Completed   | London Office      |  
| REQ00002  | CUST0450   | Passport    | 2025-06-07     | NULL           | Pending     | Manchester Centre  |  

---

## Data Model Structure
- **Fact Tables**: `Service_Requests`, `Customer_Feedback`, `Monthly_Satisfaction_Survey`, `Escalations_Log`  
- **Dimension Table**: `Customer_Profile`  
- Model structured as a **star schema** with CustomerID linking all datasets.  

---

## Methodology

### Chosen Approach: **Agile Mini-Sprint (7th – 17th Sept 2025)**  

I selected this methodology because:  
- The project had a **tight 10-day deadline** before and after my wedding.  
- Agile mini-sprints are **time-boxed**, ensuring I could deliver an MVP first, then polish later.  
- It fits the Home Office role expectation of **fast-paced, iterative insight delivery**.  

---

## Trello Project Execution

### Why Trello?  
- Visual Kanban workflow for transparency.  
- Easy to break tasks into **To Do → In Progress → Done**.  
- Enabled me to stay focused despite external time constraints (wedding/honeymoon).  

### Trello Columns  
1. **Backlog** – all tasks & ideas.  
2. **To Do (Today)** – daily focus.  
3. **In Progress** – active work.  
4. **Blocked** – dependencies or issues.  
5. **Done ✅** – completed work.  

### Daily Task Scheduling (Sept 7–17)  
- **Day 1–2**: Project planning, data cleaning, staging views.  
- **Day 3–4**: SQL query development (20+).  
- **Day 5–6**: Tableau dashboards.  
- **Day 7–8**: Power Automate workflows.  
- **Day 9–10**: Documentation, GitHub publishing, iteration.  

---

## Tools Used
- **SQL Server / PostgreSQL** – data extraction, transformation, queries.  
- **Tableau Public** – interactive dashboards & visualization.  
- **Power Automate** – automation (alerts, scheduled emails).  
- **Excel** – dataset storage, pre-processing.  
- **Trello** – Agile project management.  
- **GitHub** – documentation & version control.  

---

## Development Steps

1. **Project Planning & Requirement Gathering**  
   - Defined business questions and stakeholder needs.  
   - Designed folder structure and Trello board.  

2. **Data Exploration & Profiling**  
   - Checked nulls, duplicates, dirty values.  
   - Built staging views in SQL.  

3. **SQL Insights Development**  
   - 20+ queries covering Satisfaction, Timeliness, Escalations, Surveys.  
   - Categorized into logical folders.  

4. **Tableau Dashboard Design**  
   - Executive Overview  
   - Voice of Customer  
   - Escalation & Timeliness  

5. **Automation Flows**  
   - SLA Breach Alert (pending > 30 days).  
   - Monthly Insight Email with dashboard attachments.  

6. **Documentation & Version Control**  
   - README.md with insights, methodology, Trello workflow.  
   - Uploaded repo to GitHub.  

---

## Review & Iteration
- Initial MVP (SQL + Tableau) delivered by Day 6.  
- Polished dashboards and Power Automate flows after wedding break.  
- Iterated on documentation based on feedback.  

---

## Detailed Insights & Recommendations (Examples)

### Dashboard 1: CEO Executive Summary
- **Customer Satisfaction (NPS)** by service type.  
- **SLA Breach Rate** by month.  
- **Escalation Trends** by region.  

📌 **Insight**: Passport services had highest satisfaction (72%) while Visa applications had SLA breach rates exceeding 30% in Q2 2025.  

---

### Dashboard 2: Voice of Customer
- Sentiment analysis of feedback comments.  
- Word cloud of common complaints (“slow”, “unclear”, “delayed”).  
- Satisfaction trendlines over 2024–2025.  

📌 **Insight**: Negative sentiment peaked in June 2025 due to backlog in Immigration cases.  

---

### Dashboard 3: Escalation Monitoring
- Escalation volume by issue type.  
- Avg. resolution time by team.  
- Regional escalation hotspots.  

📌 **Insight**: “Lost Documents” and “Delays” accounted for 60% of escalations, with the longest resolution times at Edinburgh Centre.  

---

## Executive Summary
- This project demonstrates the ability to **analyze customer experience**, build **executive-level dashboards**, and implement **automation for real-time monitoring**.  
- By using **SQL, Tableau, Power Automate**, and an **Agile Trello workflow**, I replicated the working environment of a Home Office Customer Voice Analyst.  
- The solution ensures that the **voice of the customer** is embedded in operational and strategic decision-making.  

---

## Link to Tableau Dashboards
*(Insert Tableau Public link once published)*  

---

## Link to GitHub Repository
*(Insert GitHub repo link)*  

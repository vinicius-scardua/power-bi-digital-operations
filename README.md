# Digital Operations BI – Portfolio

**A Business Intelligence project focused on digital operations, performance monitoring, and data-driven decision support.**

## Project Overview

This project demonstrates how operational data can be transformed into meaningful business insights through data modeling, KPI development, and interactive data visualization.

The dashboard was developed using **Microsoft Power BI**, with a fictional dataset representing the operations of a digital education business. It brings together information about enrollments, students, revenue, community engagement, customer support, and mentorship sessions.

The goal is to demonstrate practical Business Intelligence skills and the ability to organize operational information into a clear, interactive report that supports performance monitoring and business analysis.

> **Data disclaimer:** All data used in this project is fictional and was created exclusively for portfolio and learning purposes. It does not represent any real company, customer, or business operation.

## Dashboard Preview

![Digital Operations BI Dashboard](images/dashboard-overview.png)

## Business Questions

The dashboard was designed to help explore questions such as:

- Which products generate the highest number of enrollments and revenue?
- How are enrollments distributed across different statuses?
- Which regions have the largest number of enrolled students?
- Which acquisition channels bring in the most students?
- What are the most common customer support ticket categories?
- How active are students within digital communities?
- How are mentorship sessions distributed by status?
- What are the average support resolution time and satisfaction levels?

## Key Performance Indicators

The report includes six main KPIs:

- **Total Enrollments:** Overall number of recorded enrollments.
- **Enrolled Students:** Number of unique students with enrollments.
- **Total Revenue:** Revenue generated from enrollments.
- **Total Support Tickets:** Number of recorded support requests.
- **Average Resolution Time:** Average time required to resolve support tickets, in hours.
- **Average Satisfaction Score:** Average customer satisfaction rating on a 0–5 scale.

## Dashboard Visualizations

The dashboard contains eight visual analyses:

1. **Enrollments by Product** – Compares enrollment volume across products.
2. **Revenue by Product** – Identifies revenue distribution across the product portfolio.
3. **Enrollment Status Distribution** – Shows the proportion of enrollments by status.
4. **Support Tickets by Category** – Highlights the most frequent support topics.
5. **Community Activities by Type** – Analyzes engagement across different activity types.
6. **Mentorship Sessions by Status** – Shows the distribution of mentorship session outcomes.
7. **Students by Region** – Compares the geographic distribution of enrolled students.
8. **Students by Acquisition Channel** – Examines the channels associated with student acquisition.

## Technical Skills Demonstrated

### Data Preparation and Modeling
- Importing and organizing multiple CSV datasets.
- Using Power Query for data preparation and column header correction.
- Structuring data across dimension and fact tables.
- Creating and managing table relationships.
- Applying a date dimension to support time-based analysis.

### Business Intelligence and Data Analysis
- Developing KPI cards and operational performance indicators.
- Creating DAX measures, including distinct student counts.
- Using aggregation functions such as count, distinct count, sum, and average.
- Analyzing enrollment, revenue, engagement, support, and mentorship data.
- Applying product and date filters to enable interactive analysis.

### Data Visualization and Reporting
- Building interactive reports in Microsoft Power BI.
- Selecting appropriate visualizations for different business questions.
- Organizing dashboard layouts for readability and usability.
- Using slicers to explore data by product and date.
- Presenting operational metrics in a clear and structured format.

## Dataset Structure

The project uses seven fictional CSV files:

| File | Description |
|---|---|
| `dim_products.csv` | Product information and business units |
| `dim_students.csv` | Student profiles, regions, and acquisition channels |
| `dim_date.csv` | Calendar dimension for time-based analysis |
| `fact_enrollments.csv` | Enrollment records, status, revenue, and payment methods |
| `fact_community_activity.csv` | Student activity within digital communities |
| `fact_support_tickets.csv` | Support requests, response times, resolution times, and satisfaction |
| `fact_mentorship_sessions.csv` | Mentorship sessions, types, durations, and statuses |

## Tools and Technologies

- **Microsoft Power BI** – Dashboard development, data modeling, and visualization.
- **Power Query** – Data preparation and transformation.
- **DAX** – Measures and analytical calculations.
- **CSV** – Structured data sources.
- **GitHub** – Project documentation, versioning, and portfolio presentation.

## Project Structure

```text
power-bi-digital-operations/
│
├── data/
│   ├── dim_date.csv
│   ├── dim_products.csv
│   ├── dim_students.csv
│   ├── fact_community_activity.csv
│   ├── fact_enrollments.csv
│   ├── fact_mentorship_sessions.csv
│   └── fact_support_tickets.csv
│
├── images/
│   └── dashboard-overview.png
│
├── digital-operations-bi.pbix
└── README.md
```

## Business Value

This project demonstrates how Business Intelligence can support digital operations by consolidating information from different operational areas into a single analytical view.

By combining performance indicators, interactive filters, and complementary visualizations, the dashboard makes it easier to identify patterns, compare results, monitor operational performance, and explore potential areas for improvement.

It also reflects my interest in connecting **operations, processes, technology, and data analysis** to support better business decisions.

---

**Project developed for learning and professional portfolio purposes.**

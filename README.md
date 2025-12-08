#Project Summary

I designed and implemented an end-to-end Business Intelligence solution to analyze customer complaints extracted from the company’s Customer Management System (CMS). The project involved transforming raw complaint data into a structured and interactive analytical dashboard using Power BI. The system tracked complaint identifiers, customer contract numbers, service order numbers, complaint types, statuses, financial rectifications, creation and last update timestamps, and agency and divisional performance.

The objective of the project was to reduce complaint resolution time, improve operational transparency, and enable management to make data-driven decisions. Before this project, reporting was performed manually using disconnected Excel files, which caused delays, inconsistencies, and limited visibility across regions and agencies. My solution provided real-time performance metrics, trend analysis, aging analysis, and financial risk visibility.


---

##Business Problem

The organization experienced increasing customer complaints related to faulty meters, billing disputes, power outages, and equipment failures. Data was exported daily from CMS but remained underutilized because:

•	No centralized reporting model existed

•	Agency-level performance could not be compared

•	Complaint aging was not tracked

•	Financial exposure from disputed bills was poorly understood


Senior management required a single interactive reporting platform that could identify operational bottlenecks, prioritize high-risk complaints, and monitor performance by region, agency, and staff.

---



##Role and Responsibilities

I worked as the lead Data Analyst and Power BI Developer on this project. I was fully responsible for design, development, testing, and delivery.

My responsibilities included:

Analyzing CMS data structure and mapping business requirements

Designing the data model and star schema

Building data extraction and transformation rules

Developing DAX calculations and KPIs

Designing interactive dashboards

Testing accuracy of calculations and visuals


---

##Technical Environment

Power BI Desktop

Power Query (M Language)

DAX (Data Analysis Expressions)

Microsoft Excel (data source)

Windows Operating System


---

##System Design & Implementation

Data Extraction and Cleaning

I imported complaint data from CMS Excel exports into Power BI using Power Query. I applied multiple transformations, including:

Promoting header rows

Removing irrelevant columns

Cleaning text fields using Trim and Clean operations

Standardizing complaint status values

Converting financial fields from text to numeric data types

Parsing timestamp fields into standard date formats

Removing duplicate complaint IDs

---

##Data Modelling

I designed a star schema data model comprising:

A fact table containing complaint records

A date dimension table for time intelligence

Organizational dimensions including Division and Agency


I created explicit relationships between the date table and the complaint creation date field and disabled automatic date/time generation to maintain performance and accuracy.


---

##DAX Measures and Calculations

I developed advanced DAX measures, including:

Total Complaints

Open Complaints

Resolved Complaints

Resolution Rate

Average Resolution Time

Aging Buckets

Monthly Trend Metrics

Financial Rectification Sums


I also handled null and blank values in complaint statuses to ensure data completeness and reporting integrity.


---

##Dashboard Design

I designed an interactive, user-friendly dashboard that included:

KPI cards displaying total, open, and resolved complaints

A resolution rate gauge

A time-series line chart by month

A bar chart by agency and division

A complaint type distribution visualization

Aging bucket analysis

A detailed complaint-level table with drill-through navigation


The dashboard was optimized for management review and operational use.


---

##Testing and Validation

I performed extensive validation by:

Comparing dashboard totals with raw CMS exports

Testing filter and slicer functionality

Verifying date intelligence accuracy

Conducting scenario testing for blank and missing fields


User acceptance testing was conducted with operational managers.



---

##Outcomes and Benefits

The project delivered significant improvements, including:

Reduced report preparation time from several hours to minutes

Faster identification of high-risk complaints

Improved accountability across agencies

Better visibility of financial exposure from disputed billing

Improved management decision-making



---

##Challenges and Solutions

Challenges included inconsistent status labels, missing timestamps, and financial columns stored as text. I resolved these by implementing cleansing rules in Power Query, building validation logic, and introducing error-handling mechanisms in DAX.


---

##Conclusion

This project strengthened organizational control over customer complaint management. I successfully delivered a scalable, automated analytics solution that converted operational CMS data into actionable business insights, significantly improving response times and operational efficiency.

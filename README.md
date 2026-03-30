# Power BI Data Jobs Analysis 📊

An end-to-end Power BI project analyzing **479K real-world data job postings from 2024** — built across two reports covering an interactive dashboard with drill-through, and a comprehensive visualization library with 15+ chart types.

---


## 📁 Project Structure

```
powerbi-data-jobs-analysis/
├── 1_Data_Jobs_Dashboard.pbix      # Main dashboard + drill through
├── 2_visualizations.pbix           # Full visualization report
├── images/                         # Screenshots and GIFs
└── README.md
```

---

# Part 1 — Data Jobs Dashboard

A fully interactive Power BI dashboard designed to help **job seekers find their ideal data role** — whether you're a fresher exploring salaries, someone looking for remote-friendly jobs, or a professional comparing roles across locations and platforms. Built on 479K real job postings from 2024, this dashboard makes it easy to explore the data jobs market at a glance and drill deep into any specific role.

![Dashboard Demo](images/demo2.gif)

---

## 🎯 Purpose

Job hunting in data can be overwhelming — hundreds of roles, varying salaries, different locations, different requirements. This dashboard cuts through the noise and answers the questions that actually matter to a job seeker:

- Which data job pays the most?
- Is a degree actually required?
- Are remote (WFH) opportunities available?
- Which platform should I apply on?
- What is the salary range for my target role — minimum, median, maximum?
- Where in the world are most jobs posted?
- Is the job market growing or shrinking?

---

## 📊 Dashboard Pages

### Main Dashboard
![Main Dashboard](images/11_main_dashboard.png)

The main page gives a complete overview of the data jobs market in 2024. It is designed to be simple and intuitive — every visual answers a specific question so users can quickly get the information they need without any confusion.

**What you can see:**
- **479K job postings** analyzed with an overall **3.5 star salary rating**
- **Median yearly salary of $113K** and **median hourly salary of $47.62** across all data roles
- **Job trend line chart** — shows how job postings changed month by month throughout 2024, with a dashed trendline showing the overall direction
- **Hourly vs Yearly salary scatter plot** — compare all job titles at once to see which roles offer the best compensation on both hourly and yearly basis
- **Job counts bar chart** — instantly see which roles have the most openings (Data Engineer leads, followed by Data Analyst)
- **Summary table with sparklines** — a clean table showing every job title's median yearly salary, median hourly salary, job count, and a sparkline showing the hiring trend
- **Job title slicer** — filter the entire dashboard to focus on any specific role

---

### Job Title Drill Through
![Drill Through](images/12_drill_through.png)

The drill-through page is the most powerful feature of this dashboard. Select any job title from the main dashboard and drill through to get a **dedicated insights page** for that specific role — giving job seekers a complete picture before they apply.

**How to use it:** Right-click any job title on the main dashboard → select Drill Through → Job Title, or use the "Drill Through to Job Title" button after selecting a title from the slicer.

**What you can see for any selected role:**
- **Salary gauge charts** — median yearly and hourly salary with min/max range shown, so you know what to expect and what to negotiate
- **WFH%** — what percentage of postings for this role offer work from home
- **No Degree Mention%** — how many postings don't require a degree (great insight for non-traditional candidates)
- **Health Insurance%** — how many postings mention health insurance benefits
- **Global job map** — where in the world are jobs for this role posted, so you can target the right locations
- **Top hiring platforms** — LinkedIn, BeBee, Indeed, ZipRecruiter and more ranked by job count, so you know exactly where to apply
- **Job types breakdown** — full-time vs contract vs internship vs part-time split

---

## 🔍 Q&A Search Feature

The dashboard also includes a **Q&A search bar** — click it and type any question about the data in plain English to get instant visual answers. For example:
- *"median salary by job title"*
- *"count of jobs in United States"*
- *"top companies by job count"*

This makes the dashboard accessible even to users who don't know how to navigate Power BI visuals.

---

## 📌 Key Features — Dashboard

- **Drill-through** — click any job title for a full dedicated insights page
- **Q&A search bar** — ask questions in plain English and get instant visual answers
- **Job title slicer** — filter the entire dashboard to any specific role instantly
- **DAX measures** — median salary, job count, and salary star rating built using DAX
- **Sparklines** — mini trend charts inside the summary table showing hiring momentum per role
- **Gauge charts** — show salary with min/max context so you know the full range
- **Designed for simplicity** — clean layout with clear titles so anyone can understand the insights without a tutorial

---

---

# Part 2 — Data Jobs Visualization Report

A comprehensive Power BI report demonstrating 15+ visualization types applied to the same dataset, with an interactive home page navigation linking to each chart category.

![Visualization Demo](images/demo.gif)

---

## 📁 Project Structure

```
powerbi-visualizations-demo/
├── 2_visualizations.pbix       # Power BI report file
├── images/                     # Screenshots of all report pages
└── README.md
```

---

## 🗂️ Report Pages

### 🏠 Home — Navigation Page
![Home](images/01_home_navigation.png)

---

### 📊 Column & Bar Charts
Answers: *What is the highest paying job in data? Which jobs have the most postings without degree requirements?*

![Column & Bar](images/02_column_bar_charts.png)

---

### 📈 Line & Area Charts
Answers: *What is the trend of data jobs in 2024? What portion of jobs belong to each job title over time?*

![Line & Area](images/03_line_area_charts.png)

---

### 🥧 Common Charts
Answers: *What portion of postings don't mention a degree? What portion are WFH? What are the types of data jobs?*

![Common Charts](images/04_common_charts.png)

---

### 🗺️ Map Charts
Answers: *Where are job postings globally? Which countries don't mention degrees? Where are the highest paying jobs?*

![Map Charts](images/05_map_charts.png)

---

### 🌊 Uncommon Charts
Includes Ribbon chart, Waterfall chart, and Funnel chart applied to job market data.

![Uncommon Charts](images/06_uncommon_charts.png)

---

### 📋 Tables
Detailed tabular view of job postings with salary star ratings, company names, yearly salary, and job trends sparklines.

![Tables](images/07_tables.png)

---

### 🃏 Cards
KPI cards showing median yearly salary, median hourly salary, and job counts broken down by job title.

![Cards](images/08_cards.png)

---

### 🎛️ Slicers
Interactive filters for job title, posting date range, and salary range — all connected across the report.

![Slicers](images/09_slicers.png)

---

### 🔖 Buttons & Bookmarks
Bookmarks used to toggle between filtered/unfiltered states and show/hide slicers dynamically.

![Bookmarks](images/10_bookmarks.png)

---

## 📌 Key Features — Visualization Report

- **Interactive navigation** — home page with buttons linking to each chart section
- **15+ visualization types** — column, bar, line, area, pie, donut, scatter, map, filled map, ribbon, waterfall, funnel, table, card, slicer
- **Bookmarks & buttons** — toggle views, show/hide slicers, reset filters
- **Real questions answered** — every page answers a specific business question about the data jobs market


---

## 🗃️ Dataset

**Source:** Luke Barousse's Data Jobs Dataset  
**Size:** 479,000 job postings  
**Period:** January 2024 – December 2024  
**Fields include:** job title, company name, salary (yearly & hourly), location, job type, WFH status, degree requirement, health insurance, skills

---

## 🛠️ Tools Used

- **Power BI Desktop** — report building, visualizations, bookmarks, slicers, buttons, navigation, drill-through
- **DAX** — calculated measures for median salary, job count, salary star rating

---

## 📓 Notes

Detailed documentation on how each visualization was built, including design decisions and lessons learned.

👉 [View Notes on Google Colab](https://colab.research.google.com/drive/1l9vjSmjTugoo8AjMN7IMlOIiUhUHG57d)

---

## 🔗 Related Projects

- [SQL Data Jobs Analysis](https://github.com/arnav-is-op) — SQL-based analysis of the same dataset
- [Python Job Postings Analysis](https://github.com/arnav-is-op/python_project_for_job_analysis) — Python/Pandas analysis with Matplotlib & Seaborn visualizations


![image](https://github.com/user-attachments/assets/f31b743a-1eb1-4844-ac0a-f94311bd44e6)
# Excel Analysis Project

## Introduction

This is my second Excel-based data project, where I had the chance to apply more advanced tools and techniques than before. While my earlier work focused on the basics of data cleaning and visualization, this project allowed me to dive deeper into professional-level features within Excel.

## 🧰 Excel Tools & Features Used

Throughout the analysis, I used a range of built-in and advanced Excel functionalities:

- Pivot Tables to summarize and group data efficiently

- Pivot Charts for dynamic and clear visualizations

- Power Query for data transformation and cleanup

- Power Pivot to build relationships between tables

- Basic DAX formulas to create calculated columns and measures
  
## ❓ Project Goals & Analysis Scope

The purpose of this project is to explore the current state of the data job market and understand what makes certain roles more valuable than others. Using a dataset of real job listings from 2023, I set out to answer the following questions:

- Does having more technical skills lead to a higher salary?

- How do data job salaries vary by region?

- Which technical skills are most frequently required in the field?

- What are the average salaries associated with the top 10 in-demand skills?

By answering these questions, the goal is to identify patterns that can help job seekers — including myself — make informed decisions about skill development and career direction in the data industry.

## 1️⃣ Do More Skills Translate to Higher Salaries?

## 🔍 Skill: Power Query

#### Data Extraction

To kick things off, I used Power Query to pull in the original dataset (data_salary_all.xlsx) and built two distinct queries:

- First containing comprehensive job listing details
- Another capturing the skills associated with each job ID

### Data Transformation

Each query underwent several cleaning and restructuring steps — I adjusted data types, dropped irrelevant columns, removed unnecessary words from text fields, and cleaned up whitespace for consistency.

- data_jobs_all:

![001](https://github.com/user-attachments/assets/15c81e3f-5883-4045-8587-084019f14edc)

- data_jobs_skills:

![002](https://github.com/user-attachments/assets/9fd076aa-81d7-49dd-9f8e-1afe1fd4db04)

### 📊 Analysis

A clear trend emerged: job postings listing more required skills tended to offer higher median salaries — a pattern especially noticeable in roles like Senior Data Engineer and Data Scientist. 
On the flip side, positions such as Business Analyst, which often list fewer required skills, generally came with lower salary offerings. This indicates that specialized or broader technical skill sets may be more highly valued in the job market.

![image](https://github.com/user-attachments/assets/f8a93c52-c770-4ba6-acef-6970767ce3e7)

The analysis suggests that expanding your skillset — particularly with in-demand and relevant tools — can significantly enhance your earning potential, especially if you're targeting senior or technical roles.

## 2️⃣ How Do Data Job Salaries Vary by Region?

## Skill: PivotTables & DAX

### Pivot Table Creation

To explore regional salary differences, I used Power Pivot to build a data model and generated a PivotTable.
I placed job_title_short into the row labels and used salary_year_avg as the values field to summarize the data.

![image](https://github.com/user-attachments/assets/6da43e9d-3ab6-4e77-946f-c7f681a7b5db)

![image](https://github.com/user-attachments/assets/23b15f63-4af7-4861-bd23-037016517fe5)


### 📊 Analysis

Roles such as Senior Data Engineer and Data Scientist offer significantly higher median salaries both within the U.S. and abroad — a testament to the global demand for advanced data skills.
Notably, there's a considerable salary gap between U.S. and non-U.S. positions, particularly in tech-heavy roles. This likely reflects the concentration of high-paying tech industries within the U.S. market.

![image](https://github.com/user-attachments/assets/8b7d6392-8a40-4e58-b2c0-70a23fee4d41)

Understanding these geographic salary trends is crucial for both professionals and employers. It supports more informed decision-making around job location, remote opportunities, and compensation negotiations in a globally distributed job market.

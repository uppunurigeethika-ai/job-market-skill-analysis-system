# Job Market Skill Analysis System

##  Project Overview
The Job Market Skill Analysis System is a Python-based project that analyzes job-listing data to identify patterns in skills, job roles, locations, salaries, and experience levels. It converts raw job-market data into organized summaries, statistical insights, and graphs.

##  Objectives
- Analyze job-market data efficiently.
- Identify the most frequently mentioned skills and job roles.
- Explore salary trends across experience levels.
- Analyze job listings by location.
- Identify fresher-friendly job opportunities.
- Present insights through tables, statistics, and visualizations.

##  Technologies Used
- **Python** – Project implementation
- **Pandas** – Data processing, cleaning, grouping, and analysis
- **Matplotlib** – Data visualization
- **CSV** – Dataset format
- **Google Colab** – Notebook development and execution

##  Dataset
The project uses a synthetic job-market dataset prepared for academic purposes.

- **Records:** 2,500
- **Columns:** 14
- **Format:** CSV

### Key Attributes
- Job ID
- Job Title
- Company
- Location
- Posted Date
- Experience
- Minimum, maximum, and midpoint salary (LPA)
- Skills
- Education
- Employment Type
- Work Mode
- Fresher-Friendly status

##  Project Modules

### 1. Dataset Loading
Reads the CSV file using Pandas and handles a missing-file error.

### 2. Data Preprocessing and Cleaning
- Removes duplicate Job IDs.
- Trims extra spaces from text columns and fills empty text values.
- Converts posting dates into date format.
- Converts salary columns into numeric values.
- Identifies invalid salary ranges.
- Recalculates salary midpoint values.

### 3. Dataset Overview
Displays the dataset dimensions, column names, first five records, and missing-value counts.

### 4. Preprocessing Report
Displays the original record count, duplicate records removed, invalid salary records, remaining records, and missing values after preprocessing.

### 5. Skill Analysis
Counts skill mentions and identifies the top 10 in-demand skills.

### 6. Job Role Analysis
Analyzes the distribution of job listings across different job titles.

### 7. Location Analysis
Identifies the locations with the highest numbers of job listings.

### 8. Salary Analysis
Calculates average salary and job-listing counts for different experience levels.

### 9. Fresher Opportunity Analysis
Analyzes fresher-friendly job listings by job title and calculates their average salaries.

### 10. Skills for a Selected Role
Allows users to enter a job role and view the matching listing count and top skills associated with that role.

### 11. Data Visualization
Generates five Matplotlib graphs:
- Top 10 In-Demand Skills
- Job Role Distribution (Donut Chart)
- Top 10 Job Locations
- Average Salary by Experience Level
- Fresher-Friendly vs Other Listings

##  Menu-Driven Interface
The system provides the following main-menu options:

1. Dataset Overview
2. Preprocessing Report
3. Top Skills
4. Job Role Analysis
5. Location Analysis
6. Salary by Experience
7. Fresher-Friendly Jobs
8. Skills for a Selected Role
9. View Graphs
0. Exit

##  How to Run the Project
1. Open the project notebook in Google Colab.
2. Download the CSV dataset from this repository.
3. Upload the CSV file to the Colab session.
4. Ensure the notebook's dataset path matches the uploaded filename.
5. Run the notebook cells in order.
6. Use the main menu to explore the analyses and graphs.

##  Sample Results
The project presentation demonstrates the following results from the synthetic dataset:

- **Top skill:** Python, with 1,103 mentions.
- **Top job location:** Bengaluru, with 273 listings.
- **Average salary for freshers:** 6.57 LPA.
- **Average salary for 6–8 years of experience:** 26.88 LPA.
- **Preprocessing report:** 2,500 records remaining, with zero duplicate records removed and zero invalid salary records identified.

These results describe the supplied synthetic dataset and should not be interpreted as statistics for the entire real-world job market.

##  Intended Users
- Students
- Job seekers

##  Expected Benefits
- Easier understanding of job-market requirements.
- Faster analysis of job-related information.
- Structured insights into skills, salaries, experience, and employment opportunities.

##  Team Members
- T. Yashashwani
- U. Geethika
- P. Sashank
- V. Rishi Pradyun

##  License
No license has been specified for this project.

# NYC Job Posting Analysis - Streamlit Application

### Project Overview
This Streamlit application provides an interactive analysis of job postings in New York City. Users can explore key job metrics such as salary ranges, job categories, and positions available. The application also includes visualizations and filters to help users find specific job opportunities based on various attributes like agency, career level, and work location.

### Table of Contents
1. [Project Description](#project-description)
2. [Features](#features)
3. [Dataset Description](#dataset-description)
4. [Installation](#installation)
5. [How to Use the Application](#how-to-use-the-application)
6. [Visualizations and Analysis](#visualizations-and-analysis)
7. [Conclusion](#conclusion)
8. [References](#references)

---

### Project Description
The **NYC Job Posting Analysis** application is designed to provide insights into the job market in New York City. The dataset used for this analysis contains information on various job postings, including job titles, salary ranges, and required qualifications. The goal is to help users understand the job market better and filter out relevant job postings based on their needs.

### Features
- **Job Search Filter**: Users can filter jobs based on job category, career level, agency, and salary range.
- **Visualizations**: Various plots including histograms and bar charts for salary distribution, job categories, and agency-wise job listings.
- **Career Level Exploration**: Provides insights into the types of jobs available at different career levels (Entry, Mid, and Senior).
- **Detailed Job Information**: Displays information like job description, qualifications, and application process for each job.

---

### Dataset Description
The dataset used in this application consists of 4,421 job postings with the following key columns:
- **Job ID**: Unique identifier for each job posting.
- **Agency**: The agency offering the job.
- **Business Title**: Title of the job position.
- **Job Category**: Category of the job (e.g., Technology, Administration, Finance).
- **Full-Time/Part-Time**: Indicator for full-time or part-time positions.
- **Career Level**: Indicates the required experience level (e.g., Entry, Mid, Senior).
- **Salary Range**: The salary offered for the job.
- **Work Location**: The job's location.
- **Posting Date**: The date the job was posted.

---

### Installation
To run the Streamlit application locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/nyc-job-posting-app.git
   cd nyc-job-posting-app
   
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
    
3. Run the Streamlit application:
   ```bash
   streamlit run Streamlit_vizapp.py
   
4. Access the application in your web browser at:
   ```arduino
   http://localhost:8501

   ---
   
### How to Use the Application
- **Dataset Upload:** Upload the NYC job postings dataset to start using the app. The application will automatically parse and display key job metrics.
- **Job Search:** Use the filters on the sidebar to narrow down job postings by various criteria, such as job category, salary range, and career level.
- **Visualizations:** View visualizations like salary distributions and job availability across different agencies and locations.
- **Detailed View:** Click on individual job postings to view the full details, including qualifications, job descriptions, and application procedures.

---

### Visualizations and Analysis
- **Salary Distribution:** Explore the salary range across various job categories and career levels.
- **Job Availability by Agency:** A bar chart showing the number of job postings for each agency.
- **Career Level Analysis:** Provides insights into which career levels have the most job openings and the associated salary range.
- **Job Locations:** Explore the distribution of jobs across different NYC boroughs and work locations.

---
  
### Conclusion
This Streamlit application is a useful tool for exploring job opportunities in NYC. It allows users to filter jobs based on their preferences and gain insights into salary distributions and job availability across various agencies.

---

### References
[Streamlit App](https://8sqmkeqee57ufdylly2hdm.streamlit.app/)

# LinkedIn_JobPosting_Analysis

## Project Overview

This project aims to analyze LinkedIn job postings to uncover trends in hiring, job roles, required skills, and company demand. By leveraging data analysis and visualization techniques, the analysis extracts insights that can help job seekers, recruiters, and industry analysts make informed decisions.

### Data Sources

* linkedin_job_postings.csv - Contains job postings with details such as company name, job title, location, experience level, and more.
* job_skills.csv - Includes information on required skills for different job roles.

## Key Findings and Insights 

* The combined dataset contains 1,294,268 job postings with 15 columns, including job title, company, job location, job skills, and more.
* After data cleaning and handling missing values, the dataset is ready for further analysis.
* The top 10 job titles present in the dataset are:
     1. Account Executive
     2. Registered Nurse - RN Care Manager
     3. Restaurant Supervisor - The Forklift
     4. Independent Real Estate Agent
     5. Registered Nurse (RN)
     6. Lead Sales Associate-FT
     7. Group/Unit Supervisor (Systems Support Manager)
     8. Electrical Engineer
     9. Housekeeper
    10. School-Based Behavior Technician

## Tools and Technologies Used

* Programming Language: Python
* Libraries: NumPy, Pandas, Matplotlib, Seaborn

## Methodology

* Importing the necessary libraries.
* Loading the two datasets: 'job_skills.csv' and 'linkedin_job_postings.csv'.
*  Combining the two datasets using Pandas' 'merge()' function.
*  Performing data cleaning:
      - Handling missing values
      - Removing duplicates
      - Converting data types
 * Analyzing the top 10 job titles by counting the occurrences of each job title.
 * Visualizing the top 10 job titles using a bar chart.

## Conclusions

* The analysis provides a good overview of the job postings data from LinkedIn, including the most common job titles.
* The data cleaning and preparation steps ensure the dataset is ready for further analysis and modeling.
* The top 10 job titles identified can provide valuable insights into the most in-demand roles in the job market.
* To further enhance the analysis, the following suggestions can be considered:
     - Perform more in-depth analysis on the job skills, such as identifying the most common skills across different job titles.
     - Explore the relationship between job titles, job levels, job types, and other relevant features.
     - Investigate the geographical distribution of job postings and identify any regional trends.
     - Analyze the changes in job titles and skills over time to identify emerging trends in the job market.






























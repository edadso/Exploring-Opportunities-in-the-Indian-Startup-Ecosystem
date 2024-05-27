# Exploring-Opportunities-in-the-Indian-Startup-Ecosystem

## Table of Contents

1. [Description](#1-Description)<br>
2. [Business Understanding](#2-business-understanding)
   - 2.1. [Hypothesis](#21-hypothesis)
   - 2.2. [Analytical Questions](#22-analytical-questions)<br>
3. [Data Understanding](#3-data-understanding)
   - 3.1. [Data Collection](#31-data-collection)
   - 3.2. [Exploratory Data Analysis](#32-exploratory-data-analysis)
   - 3.3. [Issues with the Data](#33-issues-with-the-data)
   - 3.4. [Handling Identified Issues](#33-handling-identified-issues)


# 1. Description
Our team aims to strategically enter the Indian Startup Ecosystem by leveraging data-driven insights to identify high-potential opportunities. Through comprehensive research and analysis, we seek to gain insight into funding received by startups in India from 2018 to 2021.

The project followed the Cross Industry Standard Process for Data Mining (CRISP-DM) framework methodology to solve the problem at hand.


# 2. Business Understanding
By [THE TIMES OF INDIA](https://timesofindia.indiatimes.com/business/india-business/india-becomes-third-largest-startup-ecosystem-in-the-world/articleshow/85871428.cms), India has emerged as the third largest startup ecosystem in the world after US and China. Following this, our team aims to strategically enter the Indian Startup Ecosystem by leveraging data-driven insights to identify high-potential opportunities. Through comprehensive research and analysis, we seek to gain insight into funding received by startups in India from 2018 to 2021.

### 2.1. Hypothesis
**Null Hypothesis (Ho):** The sector of a startup has no significant influence on the funding it receives.<br>

**Alternative Hypothesis (Ha):** The sector of a startup has significant influence on the funding it receives.

### 2.2. Analytical Questions
1. How is funding spread across the years?
2. What are the dominant sectors within the Indian startup ecosystem across the years?
3. Are there any emerging sectors that have shown a significant increase in funding year over year?
4. Where in India could be considered the surviving grounds for startups?
5. How does the startup's location influence its funding and growth opportunities?
6. Is there a relationship between what a startup does and the funding it receives?
7. Is there a correlation between the year a startup received funding and the amount of funding it received?
8. Which cities or regions have the highest concentration of funded startups?


# 3. Data Understanding
This data provides information into amount of money startups received from 2018 to 2021, the sector of startups, headquaters, what a startup do, the year of establishment, startup name, investors, and stage.<br>

`Feature Description`:
- **Company_Brand:** Name of startup
- **Founded:** Year of establishment
- **HeadQuater:** Location of startup Headquater
- **Sector:** Sector or industry of startup
- **What_it_does:** what the startup does
- **Founders:** Name od founder
- **Investors:** Name of investor
- **Amount:** Amount of investment in USD and INR
- **Statge:** Funding stage/ Phase of development (eg. Ideation stage, Validation stage, Scaling stage (Series B, etc.))
- **Year:** Year startup received funding

### 3.1. Data Collection
The datasets for the analysis were retrieved from from different sources. The 2020 and 2021 datasets were retrieved from a remote database while, the 2018 and 2019 datasets in CSV file format were retrieved from a GtHub repository and OneDrive respectively. Eventually, merging these datasets would be essential at a point to consolidate the information for comprehensive analysis

### 3.2. Exploratory Data Analysis
The datasets were examined and explored to better understand the datasets and identify issues present. Also, the data quality was verified to understand how clean or dirty the datasets are.

### 3.3. Issues with the Data
- Missing values
- Amount and Founded columns not in the right data types
- Duplicated rows
- Some values not in their respective columns

### 3.3. Handling Identified Issues
- Filled missing values with percentage not more than 35%
    1. Numerical columns were filled with the median value of that column
    2. Categorical columns were filled with the most frequent values of that column
- Amount and Founded columns were converted to the right data types
- Duplicated rows were dropped based on the funding stage of startups
- Values not in their respective columns were put back in their respective columns.




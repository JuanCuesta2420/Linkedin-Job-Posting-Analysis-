# Linkedin-Job-Posting-Analysis-


Steps & Methodologies Used: 
  
    - 1. Data Collection
        - Web Scraping: Extracted job postings from LinkedIn using BeautifulSoup/Selenium.
        - Collected key job attributes, including:
        - Job Title
        - Industry
        - Location
        - Salary Range
        - Job Description
   
    -2. Data Processing & Cleaning
        - Removed duplicate listings and handled missing values.
        - Standardized job titles and salary information for consistency.
   
    -3. Exploratory Data Analysis (EDA)
        - Word Cloud Analysis: Identified common job titles and skills.
        - Industry Distribution: Determined which sectors have the highest job postings.
        - Geographical Breakdown: Mapped job availability across different locations.
   
    -4. Models Used
        ✅ Natural Language Processing (NLP)
          - TF-IDF (Term Frequency-Inverse Document Frequency): Analyzed job descriptions to extract most in-demand skills.
        ✅ Clustering (K-Means)
          -Grouped job postings into clusters based on skills and salary ranges.
          -Helped identify career paths within industries.
        ✅ Linear Regression
          -Predicted salary ranges based on:
          -Job title
          -Industry
          -Location
          -Required experience level
        ✅ Decision Trees
          -Used to model salary variations and determine which factors most influence compensation.
        ✅ Data Visualization
          -Sankey Diagram: Showcased job transitions between industries.
          -Choropleth Maps: Displayed job density by location.
          -Bar & Line Charts: Highlighted trends in hiring and salaries.


Results & Insights
   
    - Top-Paying Industries: Identified sectors with the highest salaries.
    - Most In-Demand Skills: Found which technical and soft skills were most frequently listed.
    - Location-Based Salary Trends: Provided geographical salary insights to help job seekers make informed decisions.

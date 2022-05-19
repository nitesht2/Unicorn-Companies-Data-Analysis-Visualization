
## Unicorn Companies Data Analysis

This data analysis is a part of Maven Unicorn Challange.
Detail of the challange can be found [here](<https://www.mavenanalytics.io/blog/maven-unicorn-challenge>)

A unicorn company is a private company with a valuation of more than $1 billion, and today there are over 1,000 unicorn companies around the world!

This dataset contains a csv table with 1,074 records, one for each company
Each record contains details on the company's current valuation, total funding, country of origin, industry, select investors, and the years they were founded and became unicorns.

------
## Data Wrangling
Here are the few steps for data wrangling and cleaning:

- Removed rows with missing values
- Cleaned Valuation and Funding columns and cast as float
- Exclude rows with "Unknown" Funding values
- Explode Select Investors column into individual rows for categorical analysis
## Tools

I used python in Google Collab to clean and analyzed the data.

:pushpin: [Clean data](https://github.com/nitesht2/Unicorn-Companies-Data-Analysis-Visualization/blob/main/clean_unicorn_companies.csv) 

:pushpin: [Notebook of the project](https://github.com/nitesht2/Unicorn-Companies-Data-Analysis-Visualization/blob/main/Unicorn_Companies.ipynb)

## Author
- [@nitesht2](https://github.com/nitesht2)

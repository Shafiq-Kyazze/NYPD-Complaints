
# NYPD Civilian Complaints: Project Overview
***
* Performed exploratory data analysis of NewYork Police Department(NYPD) complaints reviewed by the Civilian Complaint Review Board (CCRB)
* Analysis showed that Male officers are more aggressive than their female counterparts
* Abuse of Authority is the commonest misconduct in the NYPD
* Police precinct 75 in Brooklyn had the most complaints  
* Black New Yorkers are handled more aggressively than any other racial group

## Code and Resources used
***
**Python Version:** 3.7
**Packages:** pandas,numpy,seaborn,matplotlib.
**Markdown cheatsheet:** https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.
***
## Data Sources
* Data was obtained from [ProPublica](https://www.propublica.org/article/nypd-civilian-complaint-review-board-editors-note).
* 2 different datasets were used and a readme file from ProPublica giving a description of the data.
***
## Data Cleaning
***
The data was cleaned to make it more comprehensible and easier to use. I made the foloowing changes
* Removed rows without complainant ethnicity
* Joined the first and last name columns together and got rid of them
* Filled rows with missing complainant gender with the commonest gender
* Deleted rows with missing contact reason and precinct
* Filled rows with missing outcome description
***
## Exploratory Data Analysis
I looked at the data sets and their different various categorical variables.
Below are some of the insights I made

| Fado Type          | Female Officer(%) | Male (%) |
| ------------------ |:-----------------:| --------:|
| Abuse of Authority | 6.2               |   93.8   |
|        Discourtesy | 6.0               |   94.0   |
| Offensive Language | 5.6               |   94.4   |
|              Force | 3.8               |   96.2   |
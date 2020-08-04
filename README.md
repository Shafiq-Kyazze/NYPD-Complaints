
# NYPD Civilian Complaints: Project Overview
***
* Performed exploratory data analysis of NewYork Police Department(NYPD) complaints reviewed by the Civilian Complaint Review Board (CCRB)
* Analysis showed that Male officers are more aggressive than their female counterparts
* Abuse of Authority is the commonest misconduct in the NYPD
* Police precinct 75 in Brooklyn had the most complaints  
* Black New Yorkers are handled more aggressively than any other racial group

## Code and Resources used
***
- **Python Version:** 3.7
- **Packages:** pandas,numpy,seaborn,matplotlib.
- **Markdown cheatsheet:** https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.
***
## Data Sources
- Data was obtained from [ProPublica](https://www.propublica.org/article/nypd-civilian-complaint-review-board-editors-note).
- 2 different datasets were used and a readme file from ProPublica giving a description of the data.
***
## Data Cleaning
***
The data was cleaned to make it more comprehensible and easier to use. I made the foloowing changes:\
* Removed rows without complainant ethnicity.\
* Joined the first and last name columns together and got rid of them.\
* Filled rows with missing complainant gender with the commonest gender.\
* Deleted rows with missing contact reason and precinct.\
* Filled rows with missing outcome description.\
***
## Exploratory Data Analysis
I looked at the data sets and their different various categorical variables.\
Below are some of the insights I made:\

**1. Officers in their 20s and 30s are more likely to behave inappropriately than older officers.**
<img src="https://user-images.githubusercontent.com/58377262/89234537-23e9b500-d5e4-11ea-865b-a4d1376d2354.png" height=600 width=1200 align=left>
 

**2. Male NYPD Officers are more aggressive than female officers.**
| Fado Type          | Female Officer(%) | Male (%) |
| ------------------ |:-----------------:| --------:|
| Abuse of Authority | 6.2               |   93.8   |
|        Discourtesy | 6.0               |   94.0   |
| Offensive Language | 5.6               |   94.4   |
|              Force | 3.8               |   96.2   |

**3. NYPD officers are most likely to abuse their authority when misconducting themselves.** 
![fado_type, hue=officer gender](https://user-images.githubusercontent.com/58377262/89235674-8c399600-d5e6-11ea-960f-497f35463ee9.png)


**4. Black NewYorkers are more likely to face police brutality than any other racial group.**
![fado_type vs Race](https://user-images.githubusercontent.com/58377262/89235925-23065280-d5e7-11ea-8fc2-a239b3c978ca.png)\
**5.Officers  in their 60s and 50s are less likely to be exonerated than their young counterparts.**\
**6. NYPD pfficers from precint 75 in Brooklyn had the most complaints.**\
**7. Officers from precinct 77 in Brooklyn are more likely to be found in the wrong by the CCRB than officers from any other precinct.**\
**8. Officers with higher ranks are less likely to misconduct themselves.**\
**9. For every 1000 complaints, 8 are about sexism and transphobia.**\
**10.For every 1000 complaints, 13 are race related.**\
**11. Hispanic and Black New Yorkers are more likely to make a complaint about bring handled aggressively by the NYPD than any other racial group.**\
**12. White New Yorkers are more likely to make a complaint about offensive language and discourtesy than any other racial group.**


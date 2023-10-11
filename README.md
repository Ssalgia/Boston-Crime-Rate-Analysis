# Boston-Crime-Rate-Analysis

 ### INTRODUCTION
   Boston is Massachusetts capital and largest city. Founded in 1630.It was the scene of several key events of the American Revolution, such as the Boston Massacre, the Boston Tea Party, the Battle of Bunker Hill, and the Siege of Boston. Upon gaining U.S. independence from Great Britain, it continued to be an important port and manufacturing hub as well as a center for education and culture. Its rich history attracts many tourists, with Faneuil Hall alone drawing more than 20 million visitors per year. Hence the crime rate here has seen fluctuations throughout. A city’s crime rate has always been a factor. In Boston, where the violent crime rate is 70% higher than the national average, residents also must worry about hate crime. 

Introduction to Database System and Benefits:
      Today, we would like to propose a database system project that will create an easier and faster analysis method of Boston crimes. This database system consists of four different tables focusing on the different types of crimes that had took place in Boston with their percentage ratio at most. From tables that reviews the crimes characteristics to statistics of the Boston the system will allow us to quickly come up with analytics of the crimes. Our project is focused on crime data; thus, we intently search visualization projects of crime examination. 

### OBJECTIVES:
 Our project involves below objectives below:
 a. What’s the trend of total crime incidents happened in Boston neighbourhood from 2015 to         2018?
 b. Which district in Boston neighbourhoods is the most safe and unsafe? 
 c. Which Street across Boston and neighbourhoods is the safest? 
 d. What does the crime calendar look like (Month, Day, time) for each street? 
 e. What’s the detailed trend of crime incidents happened in different district, year, and month?
   From this undertaking, we need to show the information thoroughly. We will picture the information zeroed in on three distinct parts:
• In the first place, we will zero in on time pattern to show the wrongdoing recurrence.
• Second, we will zero in on the spot related wrongdoing recurrence.
• Keep going, we will zero in on weapon types utilized in wrongdoing occurrences. On the site, we will provide polices with a few unique factors of information that they might need to know.

### DATASET:
SOURCE:
https://www.kaggle.com/vitorgamalemos/visualization-boston-crimes/data
■	The data has main crimes.csv file containing the Boston Crime data from 2015 – 2018.
■	It has an approximate of 3,00,000 rows and 16 columns. 
■	The columns include Incident number, Offence Code group, Offence Description, District, Reporting, Date of Occurrence, Year, Month, Day_of_week, UCR_Part (there are 4 parts the crimes are divided in…Part One, Part two and so on), Hour, Street, Longitude and Latitude.


### PROCESS AND TOOLS USED:
•	The data was cleaned using Python (Jupyter Notebook) – NaN values were replaced, and column ‘Shooting’ was deleted because 90% of the entries were missing.
•	The crimes.csv file loaded in the AWS S3 Bucket (cloud storage).
•	Hosted the MySQL server on AWS RDS.
•	Query editor to create 4 tables (Date_Time.csv, Incident_occurred, Location.csv, Offence_info.csv).
•	Tableau for Visualization and Analysis.

### CONCLUSION:
Boston sees 655 violent crimes per 100,000, making the city less safe than 83 percent of US cities. The violent crime rate in Boston is nearly double the national violent crime rate. People in Boston have a 1 out of 153 chances of becoming a victim of crime, compared to a 1 in 296 in the state of Massachusetts. The Massachusetts murder/homicide rate for 2017 was 2.51 per 100,000 population, a 26.77% increase from 2016. The Massachusetts murder/homicide rate for 2016 was 1.98 per 100,000 population, a 2.59% increase from 2015. According to the WalletHub study, Boston is among the top six cities with the highest number of hate crimes per capita. Boston ranked No. 99.



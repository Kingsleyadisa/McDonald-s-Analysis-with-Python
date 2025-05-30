# McDonald-s-Analysis-with-Python
## Introduction
       This analysis is carried out to answer specific questions about bike buyers of different educational degree, age brackets income e.t.c in a specific region. The dataset used in this assessment is gotten from the Data Analytics/Science class by PSP Analytics.

## Data Analysis Process
To effectively analyze this data, we followed the following process:
1.	Data collection
2.	Data Cleaning and Formating
3.	Data Exploration
4.	Data Visualization
5.	Insights and Recommendation

## Data Collection
This data was collected from an email sent by Joseph Elijah. The mail contained two file, one which is the Assessment spreadsheet and the other which is the group assessment question. 
On opening the assessment spreadsheet using Microsoft excel, we discovered several data columns and rows containing various data elements. The given assessment questions guided us on how to analyze the data.
Given questions:
A. Data Cleansing
1. Remove **Duplicates**
2. Replace M and S in column 2 to Married and Single... And same for M and F using Male and Female in column 3
3. Make sure the income column has values with '0' decimal places.
4. Group the age into age brackets in a different column with adolescents (0-30), middle age (31-54), and old (55+). Tip: Use the 'IF' function.
B. Data Analysis/Visualization
5. Using PIVOT tables and charts, show the relationship between
a. The average income of each gender and their bike purchase history
b. Distance travelled by commuters and bike purchase
c. Age bracket and bike purchase.
d. From your analysis in c above, suggest which age bracket should be given less attention by the Bike Manufacturers.
C. Reporting
1. Create a mouth-watering dashboard with atleast three slicers.
2. With the slicer, explain the behavior of European Middle age singles on Bike purchase.
3. With the slicer, deduce which academic qualification earns more

Data Cleaning and Formatting
Before proceeding with exploration and visualization, we had to ensure that the data was clean and properly formatted. Here’s a screenshot of the original data

•	We removed duplicates by first highlighting and conditionally formatting the whole sheet to easily identify duplicated rows and blanks
•	We then used the Remove Duplicates in the Data tab to remove duplicates and get unique data. We noted that the ID is the primary key in the table while removing duplicates
•	We replaced M and S as well as M and F with Married and Single with Male and Female in the Marital status and Gender column respectively using the Find and Replace button in the HOME tab
•	The income column was formatted to 0 decimal place and the dollar currency ($) using the Number Format button in the Home tab
•	We then grouped the ages into three main age brackets using the IF function as the range was wide. Formula used is given as: 
=IF(L2<=30,"Adolescent",IF(L2<=54,"Middle Age",IF(L2>=55,"Old")))
How the dataset looked like after cleaning is given the Cleaned Data sheet in the worksheet
![image](https://github.com/user-attachments/assets/9264b0b5-750b-4b2c-b7b1-f3202257cdea)

Data Exploration
We made use of Pivot tables to explore the formatted data set and answer the given questions earlier outlined. 
From the analysis of Age bracket and bike purchase, we suggest that Middle age bracket should be given less attention by the Bike Manufacturers because it is discovered they usually buy more. More marketing focus should instead be on the adolescent and old age bracket because their count of bike purchase is relatively low
 
Data Visualization and Insights
 
For this datasheet, we made use of mainly bar charts and line charts in Microsoft excel to visualize the data and create the dashboards.
1.	With the slicer in the dashboard above, we can deduce the behavior of European Middle age singles on Bike purchase
2.	Using the slicer, it is deducted that the Graduate degree earns more with an average income of $70,000, as shown in the image below
 

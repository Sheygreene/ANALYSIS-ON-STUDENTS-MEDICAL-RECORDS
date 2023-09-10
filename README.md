# INTRODUCTION
This task focuses on creating a detailed visualization of medical students' records from the provided dataset using Pivot tables and their functions on an Excel spreadsheet.

# ACTIVITY
A dataset of students' medical records was used to generate pivot tables from the activity below and to show the insights gathered from the pivot tables developed.

1. The average values of males and females age, BMI, temperature, heart rate, blood pressure and cholesterol
2. The average height and weight for both genders, in two (2) decimal places
3. The total number of students across the different blood groups
4. The total number of students who smoke and those who do not smoke
5. The total number of students who have diabetes and those without diabetes

# SKILLS DEMONSTRATED
1. Data Cleaning
2. Creating Pivot Tables
3. Data Visualization using pivot charts from pivot tables

# DATA CLEANING
The raw dataset contained 13 columns of information, which included the Student ID, their age, and some health metrics. The rows contained 200,000 pieces of information corresponding to the respective columns as well as some blank spaces.
![RAW DATASET](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/RAW%20DATA%20SET.png)

The dataset was cleaned by filling up the blank spaces with the average values of each column. For the columns that contained gender, blood group, smoking, and diabetes, they were calculated by using COUNTIF to find out the highest occurring value, which was used to fill up the blank spaces in these columns. After that, I transformed the full data set into a table by highlighting the entire data set, pressing Control T, and adjusting the header to fit into the column accordingly.
![CLEANED DATA](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/CLEANED%20DATA.png)
![TABLE WITH THE DATA FOR THE BLANK SPACES](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/TABLE%20WITH%20THE%20DATA%20FOR%20BLANK%20SPACES.png)

# CREATING PIVOT TABLES

The first activity required me to create a pivot table in order to determine the average medical data. I first highlighted a cell in the cleaned data table, clicked INSERT TAB, picked 'Pivot Table,' and then selected a specific cell in the new worksheet where I wanted the pivot table to be shown. The pivot table fields box popped up containing all the headers on my table, then I dragged the GENDER to the ROWS section, and then the AGE, BMI, TEMPERATURE, HEART RATE, BLOOD PRESSURE, and CHOLESTEROL of males and females were dragged to the VALUES section of the pivot table section. This automatically developed a pivot table showing the summation of the data I dragged to the VALUE section into six columns. I right-clicked on the 'Sum of BMI' header and then summarized the numbers by AVERAGE across the new six columns formed, as seen in the pivot table below.
![PIVOT TABLE](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/PIVOT%20TABLE.png)

The second activity of this task was to create a pivot table showing the average weight and height of the male and female genders by highlighting a cell in the cleaned raw data table, then clicking on INSERT TAB, then selecting PIVOT TABLE, then clicking an empty cell in the worksheet where I displayed PIVOT TABLE. The pivot table fields box popped up, containing all of my table's headers, so I dragged the GENDER to the ROWS section, then the HEIGHT and WEIGHT to the VALUES section of the pivot Table section, which automatically created a pivot table showing the summation of the height and weight in columns, with their grand total, so I changed the SUM to AVERAGE by right-clicking to summarize the numbers to AVERAGE OF HEIGHT and AVERAGE OF WEIGHT, then right-clicking to remove the grand total. I highlighted the data and then clicked on the LOWER DECIMAL arrow on the HOME TAB to reduce the values by two decimal places. This is depicted in the image above.

The third activity on this task was to insert a new Pivot table, then drag the STUDENT ID to the VALUE section and the BLOOD TYPE to the ROW section, resulting in a pivot table showing the summation of students. I changed the SUM to COUNT, which produced the total number of students and their various blood types.

The fourth activity on this task was to insert a new Pivot table, then drag the STUDENT ID to the VALUE section and the SMOKING to the ROW section, which produced a pivot table showing the summation of students. I changed the SUM to COUNT, which produced the total number of students smoking and those who do not smoke.

To determine the total number of diabetic students, I inserted a new Pivot table. The pivot table fields box popped up containing all the headers on my table, then I dragged the DIABETES to the ROW section and the STUDENT ID to the VALUE section This produced a pivot table showing the summation of students; I changed the SUM to COUNT, hence this produced the total number of diabetic students and non-diabetic students. I also took the grand total out of this area.


# DATA REPORT AND VISUALIZATION

I created a data report using pivot charts from the pivot tables. The data was visualized using information derived from the pivot tables to create a complete presentation in chart format to provide a better view and understanding of the work that was done. This was shown on each of the pivot tables that were created.
![DATA REPORT](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/DATA%20REPORTING%20FILE.png)

I picked PIVOT CHART on the 'Insert Tab' after clicking on a cell in the Pivot Table. This presented the ALL CHART box, where I selected the 'column chart' and then moved the chart to a new worksheet. I removed the field buttons and added a CHART TITLE that described the chart as the 'Average Student Health Metrics' and inserted a text box to summarize my findings on the dataset given. 'The legend button' was retained because the column bars were too many to distinguish each piece of medical data. This process was repeated for Pivot Tables 2, 3, 4, and 5.

Doughnut and pie charts were utilized for pivot tables 4 and 5 because the points evaluated were few in comparison to pivot tables 1, 2, and 3. For pivot table 3, a bar chart was utilized. I designed the bars using the color orange from the darkest to the lightest accent after making the five pivot charts and determining the highest to lowest values.
The data graphics of the pivot tables are seen in the image above.

# CONCLUSION
This task broadened my use of pivot tables and their functions for visualizing data on an Excel spreadsheet.

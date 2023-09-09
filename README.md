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

The first activity required me to create a pivot table in order to determine the average medical data. I first highlighted a cell in the cleaned data table, then clicked 'INSERT TAB,' then picked 'Pivot Table,' and then selected a specific cell in the new worksheet where I wanted the pivot table to be shown. The pivot table fields box popped up containing all the headers on my table, then I dragged the 'Gender' to the 'rows' section, and then the 'age', 'BMI', 'temperature', 'heart rate', 'blood pressure', and 'cholesterol' of males and females were dragged to the 'values' section of the pivot table section. This automatically developed a pivot table showing the summation of the data I dragged to the 'value' section into six columns. I right-clicked on the 'Sum of BMI' header and then summarized the numbers by 'average' across the new six columns formed, as seen in the pivot table below.
![PIVOT TABLE](https://github.com/Sheygreene/ANALYSIS-ON-STUDENTS-MEDICAL-RECORDS/blob/main/PIVOT%20TABLE.png)

The second activity of this task was to create a pivot table showing the average weight and height of the male and female genders by highlighting a cell in the cleaned raw data table, then clicking on 'INSERT TAB', then selecting 'Pivot Table, then clicking an empty cell in the worksheet where I displayed 'Pivot Table'. The pivot table fields box popped up, containing all of my table's headers, so I dragged the 'Gender' to the 'rows' section, then the height and weight to the 'values' section of the pivot Table section, which automatically created a pivot table showing the summation of the height and weight in columns, with their grand total, so I changed the 'sum' to average' by right-clicking to summarize the numbers to 'Average of Height' and 'Average of Weight', then right-clicking to remove the grand total. I highlighted the data and then clicked on the 'lower decimal' arrow on the 'home ribbon' to reduce the values by two decimal places. This is depicted in the screenshot above.

The third activity on this task was to insert a new Pivot table, then drag the 'student ID' to the 'value' section and the 'blood type' to the 'row' section, resulting in a pivot table showing the summation of students. I changed the 'sum' to 'count,' which produced the total number of students and their various blood types. The fourth activity on this task was to insert a new Pivot table, then drag the 'student ID' to the 'value' section and the 'smoking' to the 'row' section, which produced a pivot table showing the summation of students. I changed the 'sum' to 'count', which produced the total number of students smoking and those who do not smoke. To determine the total number of diabetic students, I inserted a new Pivot table. The pivot table fields box popped up containing all the headers on my table, then I dragged the 'Diabetes' to the 'row' section and the 'Student ID' to the 'value' section This produced a pivot table showing the summation of students; I changed the 'sum' to 'count', hence this produced the total number of diabetic students and non-diabetic students. I also took the grand total out of this area.



# BI practice homework

## Task 1.

Create a data warehouse for analyzing completed calls in telecommunications services. The dimensions include customer dimension, date dimension, time dimension, and operator dimension (VIP, Tomato, etc.). The crucial factor is the call duration.

Establish a data warehouse. <br>
Note: Dimension tables (customers and operators) have several rows each, while the fact table should include several tens of thousands of rows. The date dimension should encompass dates from the past three years.
In the Microsoft Power BI tool, create several views using concepts covered in exercises (filtering, hierarchies, grouping...).

### Answers:
Image Z1_1 depicts the layout of a dashboard consisting of a pie chart displaying operator names and the total number of call minutes per operator. The graph on the right displays names of individuals and the sum of call durations for each operator. The bar chart at the bottom shows the total call duration per operator for each month. <br>
Image Z1_2 illustrates a filter where operator A1 is selected, displaying the mentioned data for that operator. <br>
Image Z1_3 contains a bar chart showing the sum of call durations per operator for each year and includes a pie chart with two groups: females and males. <br>
Image Z1_4 specifically shows the minutes women spent on calls per operator in each year. <br>
Image Z1_5 displays a date hierarchy, indicating how operator calls have increased/decreased from quarter to quarter. <br>


## Task 2.

Create a data warehouse for evaluating activities (grades 1-5) of students in various subjects (seminar work, exercises, written exams, oral exams, etc.). The granularity level of the fact table is the grade per activity for a specific student and subject. The dimensions include student dimension, subject dimension, activity dimension, and date dimension.

Requirements:
1. Establish a data warehouse. Note: Dimension tables have several rows each, the date dimension includes around 100 dates, and the fact table should contain several hundred rows.
2. Generate several "different" reports using the Microsoft Power BI tool.

### Answers:
Image Z2_1 features a bar chart displaying students' last names and the total count of grades according to each grade (how many 1s, how many 2s, etc.). <br>
Image Z2_2 specifically shows how many grades of 5 each student has. <br>
Image Z2_3 contains a table with students' last names, activities, subject names, grades from the mentioned activities, and a pie chart showing how many times each student has been graded. <br>
Image Z2_4 specifically displays all activities from all subjects and the grades for those activities for a student with the last name Mikulec. <br>

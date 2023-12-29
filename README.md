# BI practice homework

## Task 1.

Create a data warehouse for analyzing completed calls in telecommunications services. The dimensions include customer dimension, date dimension, time dimension, and operator dimension (VIP, Tomato, etc.). The crucial factor is the call duration.

Establish a data warehouse. <br>
Note: Dimension tables (customers and operators) have several rows each, while the fact table should include several tens of thousands of rows. The date dimension should encompass dates from the past three years.
In the Microsoft Power BI tool, create several views using concepts covered in exercises (filtering, hierarchies, grouping...).

### Answers:
Image Z1_1 depicts the layout of a dashboard consisting of a pie chart displaying operator names and the total number of call minutes per operator. The graph on the right displays names of individuals and the sum of call durations for each operator. The bar chart at the bottom shows the total call duration per operator for each month. <br>

![Z1_1](https://github.com/petakantonio/BI_practice_homework/assets/126813875/6f4cf307-b008-4d53-8db1-594c417d760d)

Image Z1_2 illustrates a filter where operator A1 is selected, displaying the mentioned data for that operator. <br>

![Z1_2](https://github.com/petakantonio/BI_practice_homework/assets/126813875/63aa7865-a8b5-4444-b154-072d553b0764)

Image Z1_3 contains a bar chart showing the sum of call durations per operator for each year and includes a pie chart with two groups: females and males. <br>

![Z1_3](https://github.com/petakantonio/BI_practice_homework/assets/126813875/2a4b91be-e569-4ae9-961e-1df321ac5fa7)

Image Z1_4 specifically shows the minutes women spent on calls per operator in each year. <br>

![Z1_4](https://github.com/petakantonio/BI_practice_homework/assets/126813875/fbeaa81f-4efc-49cb-bd35-34855dab3c54)

Image Z1_5 displays a date hierarchy, indicating how operator calls have increased/decreased from quarter to quarter. <br>

![Z1_5](https://github.com/petakantonio/BI_practice_homework/assets/126813875/5ae3eb5b-1b51-4220-9103-e68708d447e7)



## Task 2.

Create a data warehouse for evaluating activities (grades 1-5) of students in various subjects (seminar work, exercises, written exams, oral exams, etc.). The granularity level of the fact table is the grade per activity for a specific student and subject. The dimensions include student dimension, subject dimension, activity dimension, and date dimension.

Requirements:
1. Establish a data warehouse. Note: Dimension tables have several rows each, the date dimension includes around 100 dates, and the fact table should contain several hundred rows.
2. Generate several "different" reports using the Microsoft Power BI tool.

### Answers:
Image Z2_1 features a bar chart displaying students' last names and the total count of grades according to each grade (how many 1s, how many 2s, etc.). <br>

![Z2_1](https://github.com/petakantonio/BI_practice_homework/assets/126813875/45755f5d-f547-4707-8f27-9267ae7f40ed)

Image Z2_2 specifically shows how many grades of 5 each student has. <br>

![Z2_2](https://github.com/petakantonio/BI_practice_homework/assets/126813875/0c5741fa-82fa-430b-b831-dfc80f65322d)

Image Z2_3 contains a table with students' last names, activities, subject names, grades from the mentioned activities, and a pie chart showing how many times each student has been graded. <br>

![Z2_3](https://github.com/petakantonio/BI_practice_homework/assets/126813875/ecf84fa8-3be2-49ed-a207-cd474f316196)

Image Z2_4 specifically displays all activities from all subjects and the grades for those activities for a student with the last name Mikulec. <br>

![Z2_4](https://github.com/petakantonio/BI_practice_homework/assets/126813875/0b94e33d-2abe-4ec9-b481-736b6492568b)


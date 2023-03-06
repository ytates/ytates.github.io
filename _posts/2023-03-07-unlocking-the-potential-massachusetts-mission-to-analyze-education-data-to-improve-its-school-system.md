---
layout: post
tags: data
author: Yolanda Tates
---

As a data analyst, I'm always excited to take on new challenges and explore ways to present complex information in an easily understandable way. Recently, I worked on a data project analyzing the State of Massachusetts education data. I chose the Massachusetts school system because they are always at the forefront of education in their public schools. With a focus on student success and equity, I sought to discover how the school system could use data to improve key critical areas.

Using the powerful data visualization tool, Tableau, I created a series of charts and graphs that shed light on critical questions such as the impact of class size on college admission, identifying the top math schools in the state, and pinpointing the schools that are struggling the most. With such critical insights to be gleaned, I was eager to dive into the data and create a report that would provide meaningful information on those areas within the Massachusetts education system.

I used the data set found on [Kaggle](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data).  This is REAL data taken from the Massachusetts Department of Education Website from the year 2017 and is compiled of data such as:

*   Enrollment by Grade
*   Enrollment by Selected Population
*   Enrollment by Race/Gender
*   Class Size by Gender and Selected Populations
*   Teacher Salaries
*   Per Pupil Expenditure
*   Graduation Rates
*   Graduates Attending Higher Ed
*   Advanced Placement Participation
*   Advanced Placement Performance
*   SAT Performance
*   MCAS Achievement Results
*   Accountability Report

### **Analysis**

**Graduation Percentages**

After connecting the MA\_Public\_Schools\_2017 spreadsheet to Tableau, I did an analysis to see what are the bottom 10 high schools in terms of graduation percentage.  To do this, I created a bar chart where the graduation percentages are displayed for each school.  So that the bar chart shows clean data, I filtered for schools with non-null values and then sorted the data in ascending order.  So that we can easily see how the schools are performing and added Red-Green Diverging with the dark red color on top and move to green as the graduation rates improved. 

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQF4EAzaqjqL8A/article-inline_image-shrink_1500_2232/0/1677546722188?e=1683158400&v=beta&t=YZCaWcLFbYtFLfKHQ_5Ch87niiDT-HH6yNMgh5kqYMM)

Schools with the Lowest Graduation Rates

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQHhHCt2HHOnuA/article-inline_image-shrink_1500_2232/0/1677546871859?e=1683158400&v=beta&t=XGlwh7dJHd9oNq7fCnKiog1rbieiMAdmjftnm-j9_gg)

Schools with the Highest Graduation Rates

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQGIoYXDBrEsbQ/article-inline_image-shrink_1500_2232/0/1677548695454?e=1683158400&v=beta&t=LTNw7ILH0u4Lr1Xw3UmQ0jt_y_S1FFCTM7hCPiabdl0)

State of Massachusetts School and District Profiles

After digging a little deeper to determine why certain schools had lower graduation rates, I revisited the [State of Massachusetts School and District Profiles](https://profiles.doe.mass.edu/statereport/selectedpopulations.aspx). What I discovered is those schools have needs and are in lower-income areas.

**Class Size and College Attendance**

Next, I evaluated the relationship between class size and college attendance and decide to use a scatter plot to evaluate the data.  After adding the dimensions for class size and college attendance, I initially did not see a correlation because the majority of the data had a square shape, which indicates there isn't too much of a relationship between the two variables. 

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQFAU-R6gnQvRQ/article-inline_image-shrink_1500_2232/0/1677547099795?e=1683158400&v=beta&t=TB3MLDA7u3MPpMCmDuyUNFpDnUvgDtYrmhayFepLOE8)

Percentage of Students Attending College vs. Class Size

![No alt text provided for this image](https://media.licdn.com/dms/image/D4E12AQH8E7XipBSomw/article-inline_image-shrink_1500_2232/0/1677722014242?e=1683158400&v=beta&t=oQeg8PK2iTZT2m8mCQZq7Yu31a3KYCs4R61tlWtGtcY)

To further evaluate the relationships, I added color to see if any patterns emerge.  Maybe the percentage of Economically Disadvantaged could show a trend? Maybe the higher the disadvantaged, the lower the attending college percentage?  I added that column to the Color shelf to see if there is a pattern.  Here I could see that economically disadvantaged students attended college at a lower rate.



**Fourth Grade Math Scores**

The superintendent is focused on improving student success by targeting 4th-grade math, an essential building block for future educational achievement. By identifying districts that are excelling with MCAS proficiency scores of 50% or higher, the state hopes to leverage best practices from these successful schools and share their methods across the rest of Massachusetts.

The Massachusetts Comprehensive Assessment System (MCAS) reports Hingham and Winchester districts as the top performers, with 91% and 90.2%, respectively - a strong indication that student performance in these areas is above average. An additional 75% of assessed districts across the state are meeting or surpassing proficiency goals set at 50%. These positive trends demonstrate tangible progress towards statewide educational objectives.

I created a line graph with numerical values to show which schools are performing over the 50% desired threshold.

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQFsukBuhaEL0A/article-inline_image-shrink_1500_2232/0/1677547541329?e=1683158400&v=beta&t=bc5-DEnyPLPUjTP7OYFNEF-djtyTSNwzpkSnWN4x_0E)

Percentage of Schools Meeting the Passing and Efficient Threshold of 50%

**Final Dashboard**

Finally, I created the [Massachusetts Education Overview](https://public.tableau.com/authoring/MassEduProject/MassachusettsEducationOverview#3) dashboard and combined all the data visualizations I made onto one page.

![No alt text provided for this image](https://media.licdn.com/dms/image/D5612AQGYMs1dlraEjg/article-inline_image-shrink_1500_2232/0/1677547688011?e=1683158400&v=beta&t=RwuoY387cqJGk2J7z5TRDtTa7mw7r9lLT-k4mSjSk-M)

### Insights

*   Schools with higher need and lower-income populations have the lowest graduation rates
*   Classroom size does not impact whether or not a student attends college, instead, there is a strong correlation between income and need the level of the school.
*   75% of the schools in the state meet the 50% proficiency goal for 4th Grade Math testing standards.

**Recommendations**

To improve the graduation rates of schools that are higher needs and lower incomes, I suggest the following:

*   Provide early intervention programs that can help identify students who may be struggling and provide them with targeted support to prevent them from falling behind.
*   Encourage parental involvement in their child's education to help improve student outcomes. Schools can offer workshops or parent-teacher conferences to keep parents informed about their child's progress.
*   Create smaller class sizes to allow teachers to provide more individualized attention to students, which can help struggling students catch up.
*   Provide more funding to schools in need can help them offer better resources, such as updated textbooks, technology, and experienced teachers.

After discovering that income and need the level of the school impact the chances of students attending college, I recommend the following to increase students' chances of going to college.

*   Schools can offer college preparation programs, such as college application workshops, financial aid counseling, and college visits, to help students navigate the college application process and understand the financial obligations of attending college.
*   Provide college-level courses on-site, allowing students to earn college credits while still in high school. This can help reduce the financial burden of attending college and allow students to take on a lighter course load in college.
*   Increase college awareness and readiness in lower grades.  By starting early in middle school or even elementary school, schools can provide age-appropriate information on college and career readiness, including financial planning, college visits, and discussions about college life.
*   Monitor and track student progress through regular assessments and use data to identify areas where students may need additional support. This can help schools adjust their programming to better support students' college readiness.

For the 25% of schools that do not meet the 50% proficiency threshold, I suggest the following for improvement:

*   Provide targeted support for struggling students by offering additional support and resources, such as tutoring or small-group instruction, to students who are struggling with math.
*   Implement cross-disciplinary instruction by integrating math concepts into other subject areas, such as science or social studies, to help students see the relevance of math to their everyday lives.
*   Schools that are meeting the math proficiency standard can share their best practices with other schools to help them improve their math instruction and support.
*   Schools that are meeting the standard can offer mentoring or coaching programs to teachers at other schools who may need additional support in teaching math.

Let me know your thoughts or any additional recommendations!
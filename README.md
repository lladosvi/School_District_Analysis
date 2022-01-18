# School_District_Analysis

Overview of the School District Analysis

A school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect. The school board asked for the data to be removed and analyzed again.

Results

How is the district summary affected?

Origonal Analysis:

![image](https://user-images.githubusercontent.com/96096924/149880964-e4399e08-8f97-49ff-926b-84dc3a74b45c.png)

The testing data of the 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.

Updated Analysis:

![image](https://user-images.githubusercontent.com/96096924/149880588-6a48133f-6214-4517-9322-47f785991aee.png)

When comparing the two charts, the updated analysis had a nominal impact on the results. As you can see from the charts the differences in some of the metrics are minimal and the results would still round to the same whole number.

How is the school summary affected?

Origonal Analysis:

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being very high.

![image](https://user-images.githubusercontent.com/96096924/149882126-f2b4e713-8cd2-455d-a1ee-12831e2faf42.png)
![image](https://user-images.githubusercontent.com/96096924/149882554-04cde081-5786-4d69-80b5-51f85b478355.png)

Updated Analysis:

Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate.

![image](https://user-images.githubusercontent.com/96096924/149882126-f2b4e713-8cd2-455d-a1ee-12831e2faf42.png)
![image](https://user-images.githubusercontent.com/96096924/149882254-7a9380ae-6313-4729-b5dd-2d384ca3a97e.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, Thomas High School ranked 2nd in the district.

Original Analysis:

![image](https://user-images.githubusercontent.com/96096924/149883030-e6ca48f8-8b5d-41f8-9aad-1debf39b342e.png)

After adjusting the 9th grade data, Thomas High School ranked in about 8th of 15 campuses.

Updated Analysis:

![image](https://user-images.githubusercontent.com/96096924/149883555-0c41d6f9-f713-4237-8a86-ab1ca4eaa1dd.png)

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade

In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts.

Math by grade:

![image](https://user-images.githubusercontent.com/96096924/149884444-c0218b86-733b-4fd6-add1-ad3d26190619.png)

Reading by grade:

![image](https://user-images.githubusercontent.com/96096924/149884501-06b59961-9fcb-417c-9459-a0aa28e8eb52.png)

Scores by school spending

Thomas High School falls in the $630-$644/student spending range. However, the hundredths place was needed to see the nominal changes. When rounding results to integers there absolutely no change as you can see below.

Original Analysis:

![image](https://user-images.githubusercontent.com/96096924/149885135-e9b98008-c022-4705-a54b-a116cd99dfc5.png)

Updated Analysis:

![image](https://user-images.githubusercontent.com/96096924/149884941-28da35c4-4692-45b6-b08a-62cace6be4d8.png)

Scores by school size

Thomas High School is defined as a medium sized school. The hundredths place was needed to see the nominal changes similar to above when rounding there is absolutely no change as you can see below.

Original Analysis:

![image](https://user-images.githubusercontent.com/96096924/149885438-0ef72599-9058-4f11-9d87-885fcb1adbed.png)

Updated Analysis:

![image](https://user-images.githubusercontent.com/96096924/149885499-d9f25b13-4e27-4118-aba7-aa068ef7eafa.png)

Scores by school type

Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes but as you see below no changes when rounding.

Original Analysis:

![image](https://user-images.githubusercontent.com/96096924/149885736-b83477a0-ad11-4187-a6bc-79425d063d80.png)

Updated Analysis:

![image](https://user-images.githubusercontent.com/96096924/149885799-4d3b07f0-287d-42e0-baa0-fc65dba133c8.png)

Summary

1) The overall passing rate for Thomas High School changed dramatically from 91% to 65%.

2) Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses.

3) Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

4) In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw shifts.

The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.

# Module 5 Challenge - PyBer Ride Sharing Analysis
An analysis was performed and visualizations of the data was created regarding PyBer rideshare data from January to May 2019 to help improve access to ride-sharing services and affordability for underserved neighborhoods. 

## Summary of Tasks
* Inspected CSV input files
* Merge City and Ride data for analysis
* Calculate the Following Metrics:
  * Total Number of Rides by City Type
  * Total Number of Drivers by City Type
  * Total Amount ($) of Fares Collected By City Type
  * Total Weekly Amount ($) of Fares Collected City Type
* Create Visual Graph Charting Total Monthly Fares Collected by City Type

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.9.12, Jupyterlab 3.3.2, Pandas 1.4.2, MatPlotLib 3.5.1

## Summary of Results
### Summary of School District Analysis
#### Prior to Removing 9th Grade Test Scores from Thomas High School
There were 39,170 students included in the school district summary.
![Previous Summary of PyCity School District Statistics](Resources/School_District_Stats_Summary_Previous.PNG)

#### Summary After Removal of Students
There 461 student test scores (reading and math) were removed from the aggregation. The 1.2% difference in the district populate barely made a difference on the test scores.
![Summary of PyCity School District Statistics](Resources/School_District_Stats_Summary.PNG)

### Performance Summary by School Name
![Summary by School Name](Resources/Summary_by_School_Name.PNG)

The removal of 461 students from Thomas High did not have a significant impact on the average school performance. Below is the original performance summary that includes all students.
![Original Thomas High School Performance](Resources/Thomas_Performance.PNG)

### Top Five (5) Performing Schools
Thomas High School was in the original top five schools and remains there even without 461 9th grade scores.
![Summary of Top Five Schools](Resources/Summary_Top_Five.PNG)

### Lowest Five (5) Performing Schools
![Summary of Top Low Schools](Resources/Summary_Low_Five.PNG)

### Math and Reading Scores by Grade Level
Thomas High School scores for 9th grade math and reading were marked 0.0 because there were excluded.
![Math and Reading by Grade](Resources/Math_Reading_Grade.PNG)

### School Performance and School Spending Analysis
There is noticeable affect on the school spending analysis metrics compared to previous metrics.
![Summary of School Scores and Spending](Resources/Scores_Spending.PNG)

### School Performance and School Size Analysis
There is noticeable affect on the school performance and school size analysis metrics compared to previous metrics.
![Summary of School Scores and Size](Resources/Scores_Size.PNG)

### School Performance and School School Type Analysis
There is noticeable affect on the school school performance vs. school type analysis metrics compared to previous metrics.
![Summary of School Scores and School Type](Resources/Scores_Type.PNG)

## Final Conclusion Statement
THe 1.2% change in student population made a less than 1% difference in Thomas High Schools testing score metrics, and an even smaller impact on the overall metics oc the school district. Thomas High School remains in the top five performing schools.

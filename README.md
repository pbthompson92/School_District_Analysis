# School District Analysis

## Overview
The purpose of this project is to review testing scores across a district and perform an analysis on them across different criteria, including spending per student, school size and more. Due to concerns of academic dishonesty the testing scores for 9th graders at Thomas High School have been removed from this dataset. These results will be compared to a prior analysis to further review if academic dishonesty at Thomas High School is likely and any impact this may have on the testing metrics. 

## Results
### How was the district summary affected?
* Below you can see a side by side comparison of the overall school district analysis including and excluding the 9th graders from Thomas High School. There was no impact on the Average Reading Score. However, you can see slight drops in all other metrics, with the most notable being a decline in the percentage of students passing math by 0.2% and a decline in the percentage of the overall students passing of 0.3%. 

Initial Analysis (Including 9th graders)
![District Summary Old](https://user-images.githubusercontent.com/91712554/140659254-a5d41c61-82a2-42cb-8b4a-7de18942a984.png)

New Analysis (Excluding 9th graders)
![District Summary New](https://user-images.githubusercontent.com/91712554/140659258-14687024-864b-4926-b6c2-180dbf016443.png)

### How was the school summary affected?
* As can be seen in the screen shots below, the exclusion of the 9th graders at Thomas High School did slightly lower the averages and percentage passing scores for Thomas High School. The Overall Passing Percentage at Thomas High School decreased by 0.3%. This is consistent with the result we saw in the overall school district analysis above. There are also slight declines across the percentages of students passing math and reading and the average math and reading scores. As no scores were altered for any other school, there is no impact to any other schools scores. 

Initial Analysis (Including 9th graders)
![Per School Summary Old](https://user-images.githubusercontent.com/91712554/140661555-11aba3c1-e29b-45a0-a79b-ebb0bc87f464.png)

New Analysis (Excluding 9th graders)
![Per School Summary New](https://user-images.githubusercontent.com/91712554/140661561-2cca442c-c730-45c5-aa29-e1606dcdb271.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* The replacement of the 9th graders math and reading scores did not impact how Thomas High School performed relative to the other schools in the district. Below you can see the top five schools identified in the initial analysis and the new analysis, where the 9th graders scores were removed. In both cases Thomas High School is ranked second in the district, although the overall passing percentage has decreased slightly. This slight decrease indicates that although the 9th graders at Thomas High had results slightly above the average, the 10th to 12th graders at Thomas High School performed at a level consistent with top results in the district. 

Initial Analysis (Including 9th graders)
![Top Schools - Old](https://user-images.githubusercontent.com/91712554/140836315-157a77ad-6dfb-47b7-9929-3f2e90435641.png)

New Analysis (Excluding 9th graders)
![Top Schools - New](https://user-images.githubusercontent.com/91712554/140836341-27145473-a06a-4b1a-8a3e-9a76386003b7.png)

### How does replacing the ninth-grade scores affect the math and reading scores by grade? 
* Replacing the 9th graders scores only impacted how the 9th graders scores at Thomas High School as it now shows up as a "nan" value. The scores across the other grades and other schools were not impacted. 

### How does replacing the ninth-grade scores affect the math and reading scores by school spending? 
* Replacing the 9th graders scores had minimal impact on the passing percentages of the district. For this analysis we rounded to the nearest whole number for the percentage of students passing. If the numbers were presented with additional decimal places we would be able to see that the $630 - $644 bucket, which includes Thomas High School, has seen a slight decrease in percentage overall passing of 0.08%.

Initial Analysis (Including 9th graders)
![Spending - Old](https://user-images.githubusercontent.com/91712554/140838645-30928c65-5710-46fb-af59-c097b3430510.png)

New Analysis (Excluding 9th graders)
![Spending - New](https://user-images.githubusercontent.com/91712554/140838656-28e3070b-d0d4-4040-986c-888f8db7e963.png)

### How does replacing the ninth-grade scores affect the math and reading scores by school size?
* There is minimal impact to the reading and math scores by school size that resulted from replacing the 9th grader scores at Thomas High School. There is a slight decline in the overall passing percentage in the medium bucket (where Thomas High School is) but it cannot be seen in the below numbers as they are rounded to the nearest whole number. 

Initial Analysis (Including 9th graders)
![Size Old](https://user-images.githubusercontent.com/91712554/140840946-17869aef-19c4-4b0c-b489-163fc54e840c.png)

New Analysis (Excluding 9th graders)
![Size New](https://user-images.githubusercontent.com/91712554/140840978-f709291d-b4f0-44f9-84b2-20f989767542.png)

### How does replacing the ninth-grade scores affect the math and reading scores by school type?
* Replacing the ninth graders scores did not impact the average math and reading scores by school type, as can be seen below. There was a small drop in the overall percentage passing in the Charter school type by 0.04%. 

Initial Analysis (Including 9th graders)
![Type Old](https://user-images.githubusercontent.com/91712554/140841112-2227eef9-1a53-41e7-b72f-678274b40deb.png)

New Analysis (Excluding 9th graders)
![Type New](https://user-images.githubusercontent.com/91712554/140841118-e0b1a69e-1ecf-4321-adeb-3219960e3d61.png)

## Summary 
Four changes that occurred as a result of replacing the Thomas High School 9th graders scores are: 
* The overall percentage of students passing across the district decreased by 0.3%
* The average math score for all 9th graders across the district decreased by 0.2%
* The average reading score for all 9th graders across the district decreased by 0.1%
* The overall percentage of students passing in the $630 to $644 bucket decreased by 0.1%

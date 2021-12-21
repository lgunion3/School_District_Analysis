# School District Analysis w Jupyter

## Overview
Maria, Data Scientist analyzes trends and performance patterns of the school district. I aggregated school data and student standardized test scores to highlight trends in performance and cost.

### Preprocessing 

After the initial school district analysis, Maria informed me that academic dishonesty compromised the Thomas High School ninth grade math and reading scores.  During reanalysis, I replaced the Thomas Highschool ninth grade reading and math scores with “NaN”. This enabled me to maintain the integrity of the remaining data. The "first" sets of data were analyzed prior to knowing the data was compromized. The "second" sets of data were analyzed after modifying THS ninth grade information.

### Analysis Parameters
- District Summary
- School Summary
- School Performance
- Math and Reading Scores by Grade
- Scores by School Spending
- Scores by School Size
- Scores by School Type
-----------------------
## DistrictSummary

There is a decrease in the Average Math Score, %Passing Math, %Passing Reading, and %Overall Passing.

### First District Summary
  
<img width="482" alt="First District summary" src="https://user-images.githubusercontent.com/87162266/135374839-53cf9d76-28ea-44c8-b3ac-04de7762a35c.PNG">

### Second District Summary

<img width="484" alt="Second District summary" src="https://user-images.githubusercontent.com/87162266/135376838-be9ea8c4-67db-4241-9291-e28018c14295.PNG">

------------------------
## School Summary

Thomas High school’s %Overall, %Reading and %Math scores decreased an average of 30%.

### First School Summary

<img width="443" alt="First School summary" src="https://user-images.githubusercontent.com/87162266/135376244-dc9bf356-e6bf-4374-b39a-a6b5187266cb.PNG">

### Second School Summary

<img width="439" alt="Second School summary" src="https://user-images.githubusercontent.com/87162266/135388967-5fa019b7-690a-4024-9a15-e4befb631628.PNG">

------------------------
## School Performance

Thomas High school was the second top-performing school before removing the ninth-grade math and reading scores. The average score didn’t change much. 

### First School Performance of Top Five schools

<img width="436" alt="First School Performance of top five" src="https://user-images.githubusercontent.com/87162266/135376153-fe27bbc3-5dcb-4c96-a65c-dc23fd277d62.PNG">

### Second School Performance

<img width="350" alt="Second School Performance " src="https://user-images.githubusercontent.com/87162266/135391882-ba2f340e-ec93-43e9-a733-c0ac65815493.PNG">

------------------------
## Math and Reading Scores by Grade

THS math and reading scores weren’t extremely affected by replacing the ninth-grade scores.

### First Math and Second Math Scores

### First Math Scores

<img width="148" alt="First math scores by grade" src="https://user-images.githubusercontent.com/87162266/135393957-d22f26e7-071a-4053-8c68-2acc73b6f15c.PNG">

### Second Math Scores

<img width="141" alt="Second math scores by grade" src="https://user-images.githubusercontent.com/87162266/135376600-a61c6a26-cff5-42a7-95b1-eb313765a01a.PNG">

## First Reading and Second Reading Scores

### First Reading Scores

<img width="153" alt="First reading scores by grade" src="https://user-images.githubusercontent.com/87162266/135376575-72b6f7f3-871f-4f31-ba95-9b6ea9554e0a.PNG">

### Sceond Reading Scores

<img width="139" alt="Second reading scores by grade" src="https://user-images.githubusercontent.com/87162266/135376609-c838aa80-ad7b-4d9f-a78b-c83b9ea9b0d6.PNG">

------------------------ 

## Scores by School Spending

The average cost per student maintained while the %Overall passing rate per student decreased.

### First School Spending Summary

<img width="439" alt="First School Spending Summary" src="https://user-images.githubusercontent.com/87162266/135376124-3e50b809-7975-4da1-81bf-eb8c81ed9aeb.PNG">

### Second School Spending Summary

<img width="378" alt="Second School Spending Summary" src="https://user-images.githubusercontent.com/87162266/135376425-f8289d05-7689-48c1-a37c-3dd22ba001be.PNG">

------------------------ 
Replacing the ninth-grade scores didn't have an effect the scores based on size. 

## Scores by School Size

### First School Size

<img width="352" alt="First School Size Summary" src="https://user-images.githubusercontent.com/87162266/135396470-169fa48d-9bf4-49f2-875f-7b3ce41b0de4.PNG">

### Second School Size

<img width="342" alt="Second School Size Summary" src="https://user-images.githubusercontent.com/87162266/135376411-705b09ee-d4bf-42c0-8eb6-0a21990f3638.PNG">

------------------------  

## Scores by School Type

Scores by each type of school wasn't affected much by replacing the ninth-grade scores

### First School Type Summary

<img width="353" alt="First School Type Summary" src="https://user-images.githubusercontent.com/87162266/135376330-7b2eb93b-dd88-4a76-a833-e659712bab1e.PNG">

### Second School Type Summary

<img width="324" alt="Second School Type Summary" src="https://user-images.githubusercontent.com/87162266/135376490-786e717e-3ce3-45f7-bdd5-74b4191fc6b0.PNG">

----------------------------

## Conclusion
Updating the NaN values for the ninth-grade THS students decreased the overall passing rate for THS while maintaining the same cost per student. The school size, type, math, and reading scores didn’t vary much from the first analysis. 

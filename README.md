# School District Analysis
## Project Overview 
The purpose of this project is to analyze the data of an entire School District such as funding and student grades that visually provide clear result on each school performance .This project will  assist school on make decision regarding the school budget and prorities.This Analysis was conduced twice due to potential academic dishonesty among a group of students .


## Resources :
-  Data Source: school_complete.csv and students_complete (Resources)
- Software: Python 3.7 , Anaconda ,Jupyter Notebook 


## Results 
 This analysis was conducted twice  due to potential academic dishonesty by the ninth grade students of Thomas High School.The first trial of this analysis included the full set of student data. In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations by replaced  their scores with NaN.
 
 ### 1. Ninth grade students of Thomas High School had their scores omitted from the calculations by replaced  their scores with NaN.
 
 ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/math_read_NaN.png)
 
### 2. The district summary

 ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/District%20Summary.png)

### 3. The school summary  top 5 and bottom 5 performing schools, based on the overall passing rate

 - Top 5 School performing schools
 
 ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/top%205%20%20performing%20schools.png)
 
  School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
 
 - Bottom 5 performing schools
   
   ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/bottom%205%20performing%20schools.png)
 
 ### 4.The average math score for each grade level from each school
 
   ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/new_math_9_12.png)
   
 ### 5. The average reading score for each grade level from each school
    
   ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/new%20_read_9_12.png)
    
    
    
 ### 6. The scores by school spending per student, by school size, and by school type

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to drop.

  ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/updated%20metrics%20for%20Thomas%20High.png)
 
 -  The scores by school spending per student
 ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/school%20spending%20per%20student.png)
  
 - The scores by school size
  ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/school%20size.png)
  
 -  The scores by school type
   School Sizes  considering  "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages
  ![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/school%20type.png)
 
 
 
###  First analysis included the full data set of all student 
 - The District summary of full data set 
  
![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/Old_Disrtrict_Summary.png)
 
 -The school summary of full data set 

![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/old_metric%20thomas%20high%20School.png)

### Second analysis doesnot included  ninth grade students of Thomas High School had their scores
- The District summary not include   ninth grade students of Thomas High School had their scores 

![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/District%20Summary.png)

- The school summary not include   ninth grade students of Thomas High School had their scores 

![This is an image](https://github.com/NadaAdem/School_District_Analysis/blob/main/Resources/updated%20metrics%20for%20Thomas%20High.png)



The entire ninth grade class of Thomas High School have had their scores replaced with NaN and the ninth graders' of Thomas High School had their scores omitted from the calculations resulted in the following changes for Thomas High School

- The overall passing percentage for Thomas High School fell to 65%
- The overall passing percentage for the entire district fell to 64.9%
- The overall passing percentages of Thomas High School decreased by 0.11%
- The average scores of Thomas High School for math and reading increased by 0.06
- For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
- School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

## Summary 

Summarize  Analyzing this dataset after  the updated school district analysis in reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

 - Average Scores and Passing Percentages do not increase as spending per student increases.
 - School Sizes  considering  "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages.
 - Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter           schools, whereas the bottom five are all District Schools. 
 - Charter schools have a 36% higher overall passing percentage than District schools.
 - Average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. 
 - Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to drop. 

To view the full script, please open PyCitySchools_Challenge.ipynb in Jupyter Notebook.

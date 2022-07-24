# School_District_Analysis
#OVERVIEW OF PROJECT 
An analysis was conducted, along with a list of deliverables. Which include: 

i) A high-level snapshot of the district's key metrics, presented in a table format

ii) An overview of the key metrics for each school, presented in a table format

Tables presenting each of the following metrics:
1) Top 5 and bottom 5 performing schools, based on the overall passing rate
2) The average math score received by students in each grade level at each school
3) The average reading score received by students in each grade level at each school
4) School performance based on the budget per student
5) School performance based on the school size 
6) School performance based on the type of school
 
 The Client also notified the analyst team that inorder to uphold academic integrity math and reading grades for ninth grade students at Thomas High School ahould be removed and the analysis repeated with the new data.  

#Resources: students_complete.csv, schools_complete.csv 
software: Jupyter Notebook, Python. 

#Results 
The overall results on student performance were not significantly different when the analysis was repeated using the new data.  
How is the district summary affected?
The district summary remains the same for other schools not affected except the values for Thomas High School. Row image attached below.

There are insignificant differences accross the scores in the district summary as we see in the immages attached below. As average math scores, % passing math, %Overall passing differs in new analysis district table.  
How is the school summary affected?

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the grades for ninth grader with Nan had little or an insignificant effect on rank comparison by school. Thomas High School retained it's rank as 2nd place and the differences in scores and passing % for both math and reading differ varied from a a decimal tenth to a hundredth in the per school summary data frame.

#Summary 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.<img width="554" alt="Screen Shot 2022-07-24 at 2 51 50 PM" src="https://user-images.githubusercontent.com/80330988/180661684-e4d2340b-4935-4856-8b73-2e6a78a3f2f5.png">
New District summary above 
<img width="579" alt="Screen Shot 2022-07-24 at 2 53 10 PM" src="https://user-images.githubusercontent.com/80330988/180661729-3c1389f4-633e-4ed3-8e96-d578fea134e5.png">
Old District Summary Above(including THS Grade 9 grades)
<img width="617" alt="Screen Shot 2022-07-24 at 3 02 16 PM" src="https://user-images.githubusercontent.com/80330988/180662032-d147aad3-dced-4e4e-ab6e-af2ce0d8086b.png">
Thomas High school Distric Summary row above
<img width="671" alt="Screen Shot 2022-07-24 at 3 14 58 PM" src="https://user-images.githubusercontent.com/80330988/180662432-f49062b9-5636-4a42-ad82-bf87d23ab205.png">
Per School Summary(new) DataFrame Attached above.
<img width="585" alt="Screen Shot 2022-07-24 at 3 17 04 PM" src="https://user-images.githubusercontent.com/80330988/180662488-918070a6-4824-4bfd-a29f-8a1720624991.png">
Per School Summary(old analysis) above

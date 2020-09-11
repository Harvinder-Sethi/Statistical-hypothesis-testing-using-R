# Statistical-hypothesis-testing-using-R

The 7 Step Process of Statistical Hypothesis Testing :-
      Step 1: State the Null Hypothesis. ...
      Step 2: State the Alternative Hypothesis. ...
      Step 3: Set alpha ...
      Step 4: Collect Data. ...
      Step 5: Calculate a test statistic. ...
      Step 6: Construct Acceptance / Rejection regions. ...
      Step 7: Based on steps 5 and 6, draw a conclusion about Ho.
Link:- https://online.stat.psu.edu/stat502/lesson/1/1.2

Our dataset is about patients who undergo a public or private hospital’s formal admission process to receive treatment. And, We will seek to understand if there is any significant difference in the average length of stay (ALOS) between large and medium hospitals (using some basic statistics and R), which might make patients choose one over the other. 
We would be applying some statistical tests and plot them on a graph to see that’s if there is any significant difference in the average length of stay between large and medium hospitals.  We got the data from Australian Institute of Health and Welfare website.

Dataset Link:- https://www.aihw.gov.au/reports-data/myhospitals/sectors/admitted-patients

Note:- You can download the presentation and have a look at the code and detail description of what is being done. Happy if it help s you in any manner. 

Extras:- 
Hypothesis Testing:- 	
		similar types of probability when added = P-Values.
		Significance level = 0.05 = Confidence Interval = 95%.
		If P-values < Significance level = 0.05  =H0 is rejected 
		If P-values > Significance level = 0.05  =H0 is accepted.

Types of Testing:-
		1) one sampleT-test, 
		2) Normal 2 sample T-test,  
		3) Homogeneity 2 sample T-test (we compare and assume the variances is qual. 	  
		Also known as levene test.) ho= accepted then, statistically significant otherwise not.
		4) Welch Test( When the homogeneity of variance doesn’t hold true, we can use welch test.)

		paired = dependant data
		unpair = independant data
		



java c
Problem Set 2 
ECO3121 - Fall 2024 
Due 3 PM, November 2, 2024 
No late submission is allowed 
Please combine your answer, Stata code and requested output in one pdf ﬁle and upload it to Blackboard
Question 1 Download from the Blackboard site and load into Stata the Indonesia education and earning data inpresdata.dta. The main data we use is the 1995 intercensal survey of Indonesia (SUPAS), which is a nationally representative large cross section of men born between 1950 and 1972 from the 1995 intercensal survey of Indonesia.  It is the main dataset used in the influential paper “Schooling and Labor Market Consequences of School Construction in Indonesia:  Evidence from an Unusual Policy Experiment” by Esther Duflo.
Since this will be a multiple linear regression model, we’ll be estimating regressions of the form. (model 1):
wageij  = α + β1 educationi + β2 ninj  + μi
First, let’s analyze the efect of years of education of each individual i and province-level (indexed by j) number of inpres school per children on monthly wages.
1. Run the regression and report the estimated coefflcients, and their standard errors, and comment on the statistical signiﬁcance of the regression estimates and R2 .
2. Let’s assume the speciﬁcation on question 1 is the true model, and you misspeciﬁed the model as model 2:
wage ^ij = ˜α + β˜1education
Comparing the estimates from these two models (speciﬁcations), What would be the bias and in which direction of the misspeciﬁed model? Be as precise as possible to explain the comparison.
3. Based on the estimates and comparison from these two models, what’s the direction of cov(educationi , ninj ) from theoretical judgment? Based on the dataset itself, what’s the direction of cov(educationi , ninj )?
Are these two results consistent with each other?
4. A professor thinks about adding an additional variable “en71” to model 1, and asks that does the enrollment rate in 1971 of each province also change the wage outcome? Run the regressions recommended by the professor. Write down the new model (speciﬁcation) as model 3.
5. Formally write down the corresponding hypothesis testing (t-test) to verify the professor’s ques- tion step by step (5 steps). And please make your conclusion to the professor’s question.
6. Comparing model 3 and model 2, the professor wants to test the joint signiﬁcance of variables “nin” and “en71” . What kind of test shall we use? Please ofer the detailed procedure for the test step by step and conclude.
Question 2: Linear and non-linear probability model 
Now a pro代 写ECO3121 - Fall 2024 Problem Set 2Python
代做程序编程语言fessor is thinking about introducing dummy variables in the regression to better understand the contribution of education on wage.First, we introduce a dummy variable to the dependent variable by dividing wages into high and low levels. Speciﬁcally we deﬁne high wage = 1 if wage >= 192000 and is not a missing value, and high wage = 0 if wage < 192000.
1. Please run a regression of Y :  high wage  on Xi :  years of education (yedu) and Zj :  number of inpres school per children (nin) using 1) linear probability model, and 2) Probit model, respectively.Summarize these estimates in a table with 3 columns (the format of the table can refer to the table on page 24 of the “week 8-2” slide, but the information in the last row of that table does not need to be displayed), and only interpret the coefficient of yedu in the linear probability model.
2. The professor uses the following Probit model,
P (Yi  = 1jXi , Zj ) = Φ(β0 + β1 Xi + β2 Zj )
where i denotes an individual.  Discuss 2-3 potential drawbacks of using a linear probability model instead of a non-linear model when Y is a binary variable.
3. Use the Probit model and the results from the table you ofer in question (1), and calculate the change in probability when Z = 3 and X  increases from 8 to 12.  (Note: you can keep Φ(·) in your answers without solving for it.)
4. Use a graph of cumulative standard normal distribution to demonstrate such change in probability in question (3), and label the direction of the change.  (Note: no need to spend time drawing a very neat ﬁgure. The information conveyed by this ﬁgure is more important.)
Question 3: Dummy variable as the independent variable The professor is also interested in studying whether high-education groups of people have higher wages than low-education groups of people.  Therefore, the professor divides education level into high-level (high level = 1) if years of education are >= 9 and there is no missing value in years of education. And the variable of high level = 0 if years of education are < 9.
1. Run a regression of monthly wages on high level. Demonstrate the coefficient of high level and interpret the estimate.
2. The professor wants to study whether urban as the birthplace (urban = 1 in the data) can afect the slope of high level on wage by introducing the interaction term.
1) Please write down the model (speciﬁcation) and report your estimates. (Don’t forget to include urban as an independent variable in your model.)
2) Conduct your hypothesis testing using p-value, and conclude.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

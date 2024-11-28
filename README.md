java c
125.785 S1 2024 -- Assignment 2 (Part A and Part B)
Due date: 18th October 2024
The assignment is 30% to the course assessment, including two parts:
Part A. Practice binary and panel data regressions (15%), Part B. Critical Reading (15%).
Part A Practice binary and panel data regressions (Head start codes of SAS are provided in Stream)
A-1. Binary Model practice (5% contribution to the course assessment)Use the data provided (loanData_Assignment 2) to practice the binary model regression and analysis.
The variables used are defined as follows:•      approve=1 if the application is approved and 0 if not•      loanamtloan amt in thousands•      pricepurchase price•      loanprcloanamt/price•      married=1 if applicant married (and 0 for not married)•      black=1 if applicant is black (and 0 for others)• white=1 if applicant is white (and 0 for others)
A-1-1. Estimate the model below using OLS and discuss any problem in the variables used. (You may need to produce the basic statics of the used variables in the discussion.)
approve = a + β1* loanamt +  β2  *  price + β3*  loanprc + β4* married+  β5* black + β6* white
A-1-2. Estimate the above model using logit regression after making some treatment to any problem identified in the above requirement. (A-1-1).
Logit(approve=1)
= a + β1* loanamt1 + β2  *  price + β3  *  loanprc + β4  * married+  β5  * black + β6  * white
A-1-3. Interpret the statistical and economic meaning of β1  and β3.
A-1-4. Try the following two models and discuss the difference of the coefficients of β5  out of the two models.
Model 1:
Logit(approve=1)= a + β1* loanamt +  β2*  price + β3*  loanprc + β4* married+  β5* black + β6* white +e
Model 2:
Logit(approve=1)= a + β1* loanamt +  β2*  price + β3*  loanprc + β4* married+  β5* black + e
A-1-5. Use the above model 1 (logit) to estimate the probability of loan approval for a married white applicant with medians of other variables (loanamt1 price  loanprc).
A-1-6. What is the difference of approval rate between white and black applications based on the condition that there is no difference in other variables?
A-1-7 Write a conclusive summary of the Binary model testing results.
A-2. Panel data practice) (10% contribution to the course assessment)
Download the Stream provided data (wageFactors_assignment2. The two indicators for time cross section and time series are nr year.
The variables are defined as follows:
•      nr
person identifier
• year
1980 to 1987
• lwage
log(wage)
• exper
labor market experience
• hours
annual hours worked
• married代 写125.785 S1 2024 -- Assignment 2
代做程序编程语言=1 if married (and 0 if not married)
• educ
years of schooling
• union
=1 if in union (and 0 if not in union)
A-2-1. Estimate the following model with OLS regression (pooled data regression):
lwage = a+ + β1* exper + β2* hours + β3* married + β4* educ + β5* union;
A-2-2. Estimate the above model using the time-fixed effect. Discuss the impact of experience (exper) on wage. Is the result different from the OLS model?
A-2-3. Test whether the time-fixed effect model or the OLS model is more appropriate.
A-2-4. Test whether the time-random effect model is appropriate.
A-2-5. Create the squared variable of the experience (exper2=exper *exper) and use the best
performance form. (among OLS, time-fixing and random-fixing) to estimate the following model:
lwage = a+ + β1 * exper + β2* hours + β3 * married + β4 * educ + β5 * union  + β6  *exper2;
A-2-6. Discuss again the impact of experience (exper) on wage based on the results in A-2-5.
A-2-6 Write a conclusive summary of the panel data regression results. The interested question is which panel data is most appropriate in the tested relation and how the working experience influence the level of wage in the labour market.
Part B. Critical Reading (15% to the course assessment).Choose one of the following two articles and write a report of your selected one. The report should provide a summary on the research. The focus should be on describing and commenting on the econometric models and analyses used in the study. Specifically, you are expected to describe what is the specifical formula expressing the tested relation, and where (which table) and how the results are  reported and discussed. Additionally, discuss the common points, such as how the  data  is treated before testing, why the models are chosen, what are the relative advantages of the used models, and how these advantages are shown in the results, etc.). To improve your performance, you may make some critical comments on the testing methodology issues.
Word length should be about 1000 words.
Article 1:
Fang, Vivian W., Xuan Tian, and Sheri Tice, (2014), “ Does Stock Liquidity Enhance or Impede Firm Innovation?”, Journal of Finance, Vol. LXIX, no. 5, 2085-2125.
Article 2:
Nguyen, Thi Lam Anh, and Xuan Vinh Vo (2020), “Does corporate governance really matter for bank efficiency? Evidence from ASEAN countries”, Eurasian Economic Review, vol 10, no.4, 681–706.
Submission (to the Stream Drop-Box of the assignment):A Word file, including the contents for part A and Part B (Same format as required in Assignment 1).

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

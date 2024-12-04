java c
BUSI4528-E1
BUSINESS SCHOOL
A LEVEL 4 MODULE, AUTUMN SEMESTER   2021-2022
QUANTITATIVE RESEARCH METHODS FOR FINANCE AND INVESTMENT
1.   a)   Consider   an   experiment   on   student   scores.   Students   were   randomly   assigned   within   schools   into   three   types   of   classes:   small   classes   with   13-17   students,   regular-sized   classes   with   22-25   students,   and   regular-sized   classes   with   a   full-time   teacher   aide   to   assist   the   home   teacher.   Student   scores   on   academic   tests   were   recorded   as   well   as   some   information about the students, teachers,   and   schools. The   experiment   considers   two academic years   data.
Score: total examine scores   of each   student.Small: an indicator variable Small=1 if   the student is in a small class, and 0 otherwise.   Aide:    an   indicator variable Aide=1   if there   is a full-time   teacher   aide   in   the   regular-   sized classes, and   0   otherwise.
Tchexper: teacher’s experiences   in terms of years.
Male: an   indicator variable   Male=1   if the student is   male, and   0   otherwise.
Tchmasters: an indicator variable Tchmasters=1   if the teacher has   a   master degree,   and 0   otherwise.
Absent:   number of days the student is   absent   from   school.   tchid:   individual teacher’s ID.
schid:   individual school’s   ID.Using   Stata,   we    regress    by    OLS   student   score   on   small   class   size,   teacher’s   aide,   student’s gender, teacher’s experience and education.   The   estimated   results   are   shown   below:

(i)                            Write   down   the   regression   model   and   interpret   the   meaning   and   significance   of each coefficient. Are the signs and relative   magnitudes   consistent   with   the   intuition?       [25   marks]
(ii)                            The table   below shows the   results of an alternative specification.   Compare      the   results from the table   below to those   in   part   (i). In   particular, comment   on the standard   errors.
[10   marks](iii)                         Let INCOME= income per   capita (in thousands of U.S. dollars) and BACHELOR=   percentage of   the population with a bachelor’s degree or more for selected U.S.   states,    a    total    of      N=52      observations.      The      results      from      a      simple      linear   regression of INCOME and   BACHELOR are
INCOM(̂)E=12.11+1.24BACHELOR   se                     (2.75)            (0.132)
Construct a 99%   interval estimate of the coefficient   for   BACHELOR.   Interpret   the   interval estimate.    [15   marks]
b)   Explain the setup of the   Logit   model and   how   it   provides   a   remedy   to   the   shortcomings   of the   Linear   Probability   Model (LPM).    [35   marks]c)    Explain    how    to    use    estimates    of    the      Logit      model    to    calculate      marginal      effects      of continuous explanatory variables and discrete effects of   binary   explanatory variables.    [15   marks]Total   [100 marks]
2.    a)   Consider    the    experiment    and    initial      estimation      of    Question      1.a.      We      estimate      the   determinants    of    Score    using    a    different    model,    and    the    results    are    shown    below.   Compare the results of   the new estimation and those in Question 1.a. State the difference   between the two   models.


[25   marks]
b)   What   is type I and type   II   error   in   hypothesis   testing?       [15   marks]
c)    What are the main characteristics of t-distribution and under what circumstances   should   we   use t-distribution   rather than   normal distribution?       [10   marks]
d)   For   time   series   data,   outline   the   static   model   and   the   ARDL(1,1)   model   with   serially correlated errors.   Discuss the conse代 写BUSI4528 QUANTITATIVE RESEARCH METHODS FOR FINANCE AND INVESTMENT AUTUMN SEMESTER 2021-2022Python
代做程序编程语言quences for OLS estimators and   standard   errors.       [30   marks]
e)   Outline the   Dickey-Fuller test for the   null   hypothesis   (H0)   of the   presence   of   a   unit   root   in   an   autoregressive time   series   model   against the   alternative   hypothesis   (HA) that the   autoregressive time series   model   is stationary around a   zero   mean.       [20   marks]Total   [100 marks]
3.   a)   Consider an experiment on whether government subsidies reduce the impact of recession   on company’s bankruptcy. Suppose that, before the recession, the government provided   subsidies   to   companies   in   some   selected   cities.   Companies   in   the   other   cities   received   no   subsidies.   Before   the   recession,   there   were   102   companies   receiving   subsidies   and 153   companies   that    did    not.    After   the    recession,    for    the    companies    that    received   subsidies,    93    survived.    Among    the    companies    that    did    not    receive    subsidies,      123   survived after the   recession.


(i)                Let the companies without subsidies before the recession be the control group and   those that received subsidies   be the treatment group. Draw   a   graph   showing   that   treatment effect. Calculate the   magnitude of the treatment effect.       [15   marks]
(ii)             Suppose that we have data of these two groups for 6 years including the recession   year, so that   N=12.   Let AFTER   t=1 for years after the   recession and AFTER   t   =0   for years before the recession. Let TREATi=1 for the group whose companies received   subsidies and TREATi=0 for the group whose   companies   did   not   receive   subsides.   Let   Numcompi,t       be    the    number   of   companies   in   each   group   in   each   year.   We   obtained the estimation   below:
Numcom(̂)pl,t    =   166   −   2.87TREATi      − 47AFTER   t+   20.3(TREATi      × AFTER   t)
(se)                                                         (8.8)                                 (7.6)                           (10.6)
What is the treatment effect from above   equation?   Is the   estimated   treatment   effect significant at   the   5%   level?       [10   marks]
b)   Explain what the Central   Limit Theorem   is.       [10   marks]
c)    What are the assumptions of estimating a   multiple   linear   regression   model?       [15   marks]
d)   Outline the   Linear   Probability   Model (LPM) and explain   in detail   its   main   limitations.       [30   marks]
e)   What   is   meant   by   saying   that   a   time   series   is   stationary?      Is   the   following   time   series   stationary or   non-stationary?
yt      =   yt−1    + vtwhere   error   terms vt      are   i.i.d.   with   mean   zero   and   variance σv(2)   ,   and   t   denotes   the   t-th time   period. Justify your answer.       [20   marks]Total   [100 marks]
4. a)   Define   the   term   multicollinearity   and   explain   how   it   can   be   detected.   Also,   list   the
negative consequences of multicollinearity and explain   how they   can   be   mitigated.    [50   marks]
b)   Consider the following time series   model   :
yt      =    β0    + β1xt      + β2xt−1    + yyt−1      +   εt
It   is   suspected   that   the   model   suffers   from   serial   correlation   in   the   error   term   of   the   form.	
εt      =   Pεt−1    + utwhere ut       is an   identically and   independently   distributed error   term   and   t denotes   the   t-   th time   period.   Describe   in   detail a test to   detect serial   correlation   in   the   above   form   of   the   model.       [25   marks]
c)    Explain   the   Engle-Granger   test   for   cointegration   and   write   down   the   steps   involved   in   the test.       [25   marks]Total   [100 marks]
   



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

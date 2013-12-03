###The Math
- Let T denote the total catalog duration
- Let tm,n,p denote the pth percentile of writing times to the nth event after an event of magnitude m
- Let Nm denote the number of counts of magnitude M in the catalog
- If we turn on an alarm of length tm,n,p after every event of magnitude M, that “should” capture >p*Nm*n events and contribute Nm*tn,m,p to the total value of Tao. 
- Let eM(t) denote the average number of events in a window of length t after an event of magnitude M
- If we turn in an alarm of length t(M) after every count of magnitude M, we expect to produce N¬m*am(tm) events (ignoring ) and we 

###Optimization Problem (greedy method)
#####Pick tm, m in M to maximize
-	tm is window length; pick a collection of these
-	M = {3,3.1,3.2,…, 9}
-	you want expected number of lengths to be as big as possible

	Sum(m in M) Nm am (tm)  s.t. 
    tm > 0, m in M
    tm1 > tm2 if m1 > m2
    (1/T)*Sum(m in M) Nm*tm < Tao

-	subject to some constraints: no negative alarm lengths AND total alarm duration divided by time is Tao
-	this will give us what window lengths do we use to correspond to a particular point in the error diagram
  - you can use slack variables (linear programming) to account for the fact that the function is monotonically increasing
Methodology
-	am and tm are not linear; so there will need to be an iterative method
  - make a locally linear approximation; start with trial value of t and linearize around t. Solve linear programming problem. Iterate across multiple values of t.
  - take tm to be in increments of, say, days. Utilize a grid search or other stochastic method to approximate 



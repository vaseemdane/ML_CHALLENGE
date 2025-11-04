# 30 Days Machine Learning Algorithms Challenge

## Day 1: Linear Regression
Explored Linear Regression using the California Housing dataset.

using the mathematical formula or expressions

## steps 

1.calculate the cost using the cost function
   ->which is mean squared error 
   ->j(w,b)=(((w*x)+b)-y)^2/(2*m)
   ->where w=weights and b=bias and x=input and y=output

2.calculate the deravatives of the function j(w,b) with respect to w and b
   ->dj_dw,dj_db


3.use the gradient descent optimization technique get the  appropiriate w and b values and also reduce the cost or converge it
  -> w= w-(alpha/m)*dj_dw
  ->b=b-(alpha/m)*dj_db
  ->where as alpha is learning rate
  ->m is no.of data points counts
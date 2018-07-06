# Classifying_Hand-Written_Digits
Process:

•Randomly select about 20% of the data and set it aside as a test set.
•Train a linear SVM with soft margin.  Cross-validate the margin parameter.
•Train  an  SVM  with  soft  margin  and  RBF  kernel.   You  will  have  to  cross-validate  both  the  soft-margin parameter and the kernel bandwidth.
•After you have selected parameter values for both algorithms, train each one with the parameter value you have chosen.  Then compute the misclassification rate (the proportion of misclassified data points) on thetest set.

Result:

1.  Plot the cross-validation estimates of the misclassification rate.  Please plot the rate as(a)  a function of the margin parameter in the linear case.(b)  a function of the margin parameter and the kernel bandwidth in the non-linear case (you are encouragedto use heat map here).
2.  Report  the  test  set  estimates  of  the  misclassification  rates  for  both  cases,  with  the  parameter  values  youhave selected, and compare the two results. Then discuss whether linear SVM a good choice or non-linear one?

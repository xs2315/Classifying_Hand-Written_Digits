# Classifying_Hand-Written_Digits
Process:

1. Randomly select about 20% of the data and set it aside as a test set
2. Train a linear SVM with soft margin and Cross-validated the margin parameter
3. Train a SVM with soft margin and RBF kernel and cross-validate both the soft-margin parameter and the kernel bandwidth
4. Compute the misclassification rate on the test set and compare the results

Result:

1.  Plot the cross-validation estimates of the misclassification rate.  Please plot the rate as(a)  a function of the margin parameter in the linear case.(b)  a function of the margin parameter and the kernel bandwidth in the non-linear case (you are encouragedto use heat map here).
2.  Report  the  test  set  estimates  of  the  misclassification  rates  for  both  cases,  with  the  parameter  values  youhave selected, and compare the two results. Then discuss whether linear SVM a good choice or non-linear one?

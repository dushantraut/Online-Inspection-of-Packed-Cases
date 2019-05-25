#Online Inspection of Packed Cases

Leaves of Crops are threshed and are packed into cases,these packed cases are then inspected for Conformity to approve in terms of:
1.Color
2.Ripeness
3.Uniformity

Using Machine Learnig and Image Proecessing three separate algorithms which imitate Color,Ripeness and Uniformity inspection while keeping the processing time for each of the algorithm under one minute are created.
First Calculate Moments: mean_H,mean_S,mean_V,stddev_H,stddev_S,stddev_V,entropy_H,entropy_S,entropy_V,Skew_H,Skew_S,Skew_V,Kurtosis_H,Kurtosis_S,Kurtosis_V
where (H-Hue,S-Saturation,V-Value)

With the help of XGBOOST Classifiers we predict the Color Code ,Ripeness Code And Uniformity Code.

Acurracy :
1.Color-77.6744 %
2.Ripeness-70.2325 %
3.Uniformity-73.9534 %

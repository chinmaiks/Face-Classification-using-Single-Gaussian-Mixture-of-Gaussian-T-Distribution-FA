# Computer-Vision
Repository contains projects that were developed as part of the Computer Vision course

Project 1: Build a Face Classification Model using Single Gaussian, Mixture of Guassian, T-Distribution and Factor Analyzer.

Model 1:Learn single Gaussian model using training images- Single_Gaussian.ipynb


Model 2:Learn Mixture of Gaussian model using training images- Mixture_of_Gaussian.ipynb


Model 3:Learn t-distribution model using training images- T_Distribution.ipynb


Model 4:Learn factor analyzer using training images- Factor_Analyzer.ipynb

Dataset
Goto http://vis-www.cs.umass.edu/fddb/ and click on the link <Original, unannotated set of images> and download it in the data folder. 
Extract the data. Next, click on the link <Face annotations> and download the data. Extract the data. (Data_Extraction.ipynb)
 
 
 Main Tasks performed:
• Visualize the estimated mean(s) and covariance matrix for face and non-face respectively; Used RGB images. 

• Evaluate the learned model on the testing images using 0.5 as threshold for the posterior. Compute false positive rate (#negatives being classified as faces / #total negatives), and false negative rate (#positives being classified as non-face / #total positives), and the misclassification rate ((#false-positives + #false-negative)/#total testing images)     

• Plot the ROC curve where x-axis represents false positive rate and y-axis true positive rate (i.e, 1-false negative rate). To plot the curve, you change the threshold for posterior from +∞ (use maximum posterior across testing images in practice, then all being classified as non-faces) to −∞.

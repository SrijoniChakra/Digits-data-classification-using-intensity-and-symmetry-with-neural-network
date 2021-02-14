# Digits-data-classification-using-intensity-and-symmetry-with-neural-network
The code uses digits dataset to classify handwritten digits. The first column in the dataset is the digit label, and the next 256 columns are values between -1 and 1 representing a grayscale image.
The following preprocessing steps for both training and testing datasets have been performed:
1) The dataset is filtered to include only digits labeled as ‘1’ and ‘5’. 
2) The labels are converted into labels for binary classification, i.e., ‘1’ and ‘-1’.
Intensity and symmetry features on the dataset are extracted. For the training dataset, I have plotted a 2D scatter plot with the two features that have been extracted. Color red indicates digit 1 and color blue indicates digit 5.
Digit 5 has more black pixels so the average intensity of '5' is greater than '1' whereas '1' is more symmetric than '5'. 

For the neural network the following dimensions have been considered:
1) Input layer dimension: (1561,2)
2) Layer 1 weights: (2,10)
3) Layer 2 weights: (10,1)
4) Output layer: (1561,1)

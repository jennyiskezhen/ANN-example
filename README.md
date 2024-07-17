# Artificial Neural Network (ANN)-Election Forecasting

<div align="center">
<img src="https://raw.githubusercontent.com/jennyiskezhen/ANN-example/main/image.png" width="400">
</div>

In this example, I used ANN to forecast the binary voting results of the United States elections on the county level in 2016, which is public information. Economic and sociological factors and the geographic structure of the counties were used as features to make the predictions on the voting results. Results of 1555 counties were predicted and the final weighted accuracy of the predictions was around 80%.

I compared ANN to several other basic machine learning models including k-nearest neighbors (k-NN), linear discriminant analysis (LDA), and support vector machine (SVM) learning methods.

K-NN, LDA and SVM were specified using the `scikit-learn` package and ANN was specified using the `PyTorch` package. Model evaluation and comments are in the **`Election_Forecasting.ipynb`** file. 
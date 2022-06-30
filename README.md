# Insurance Rater 
![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Insturance%20truck.png "Logo Title Text 1")


# Trucking Insurance 

 
## Overview and Origin

* 5 years of insurance clients demographics
* Data was driven from up-to-date Prestige Insurance clients csv file format
* Three models to predict client insurance premiums
* Tensor flow, Scikit-learn, Pytorch & Principal Component Analysis (PCA) were used for our Insurance Rater end results
* Insurance Rater was created by Sam Pearlman, Viri Segura & William Riera

## Business Activities:

* An insurance analysis is a widely used product that is rapidly growing in popularity.

* Our insurance rater software is not only easy to use. This tool is also free to everyone in the trucking industry even brokers.

#
# Loss Function Graphs
#
## Loss Function 1 Hidden Layer
* Description of Image: This Image is differentiating how the test data performed in the model compared to the training data. When you compare this image to image two you can see that the data because much more accurate with much fewer epochs. You can see a significant accuracy around 50 epochs opposed to 250 from model 1.

  ![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Loss%20Function%201%20Hidden%20Layer.png "Logo Title Text 1")

## Loss Function Training 1 & 2 Hidden Layer
* Loss function Training – 1 hidden layer vs 2 hidden layers
Description of Image: We see that on our model with 2 hidden layers the data becomes more accurate around 150 epochs while the model with only 1 layer remains consistently inaccurate.

![alt text](![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Loss%20Function%20Training%201%20%26%202%20Hidden%20Layer.png "Logo Title Text 1")

## Loss Function Training Vs Testing
* Description of Image: This Image is differentiating how the test data performed in the model compared to the training data. It shows that the test data became much more accurate around the 250 epochs then the trained data in model 1

   ![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Loss%20Function%20Training%20Vs%20Testing.png "Logo Title Text 1")

# Scatter Plot Graphs

## Scatter Plot Actual Vs Prediction Model 1
* Graphing a Scatter of the actual Yearly Premium vs the 1st Predictive model
Why are both scatter plots using “predictions 1 as y?

![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Scatter%20Plot%20Actual%20Vs%20Prediction%20Model%201.png "Logo Title Text 1")

## Scatter Plot Actual Vs Prediction Model 2
* Scatter plot of actual premiums vs predicted premiums

![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Scatter%20Plot%20Actual%20Vs%20Prediction%20Model%202.png "Logo Title Text 1")

## Scatter Plot Actual Vs Prediction
* Description of Image: Here we show Model 3 which used pytorch. This scatter plot shows more inaccuracies in the predictions then the other 2 models.

![alt text](https://raw.githubusercontent.com/wdriera33/FintechProject2/main/Charts/Scatter%20Plot%20Actual%20Vs%20Prediction.png "Logo Title Text 1")


## Landscape:
* We used three models to predict our Insurance Premiums. The first two models were put together using Scikit Learn and Tensor flow. Our third model used Pytorch with Linear regression. We found the model 2, our model with two hidden layers was the best choice. We also the keras algorithm with this model. This was the best model for us. We used also used a PCA to help us determine which were the most important X’s This model was able to predict our insurance premiums almost to an exact number.


## Results Machine Learning
* Model 1 – Neural_n
·        1 Shallow Layer
·        1 Hidden Layer ( 30 units, 10 input_dim, activation, Relu Activation(Rectified Linear Unit))
·        1 Output layer ( 1 units, Linear activation,)
·        Optimizer (adam)
·        Epochs 250
·        Verbose – 0
* Model 2- nn2
·       First Hidden layer (30 units, input dim 10, activation relu)
·       Second Hidden layer ((units 20, activation relu)
·       Output layer (units 1 (activation Linear)
* Model 3 -Neural Network Model Using Pytorch- Linear Regression


## Recommendations

* More years of company database
* Bigger variety of insurance carrier
* Free phone app to get your own quote

## Written By: 
Sam Pearlman, 
Viri Segura &
William Riera

## References

* Active Company DataBase
* Scikit-learn
* Keras
* Markdown Cheatsheet (GitHub)
#
 Insurance Rater (Presentation)

[Insurance Rater (Presentation Site) ] https://docs.google.com/presentation/d/1GlFEjqVX_jQBgYzT7lOlE7AwW9LDa1fX9k3gPf-cofM/edit#slide=id.g13a8ee6be26_0_46


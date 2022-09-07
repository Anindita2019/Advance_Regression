# Advance Regression Assignment 1&2
> Upgrad Advance (lasso+redge) regression Case Study
> Identifiying  linear model, predictions, RMSE and evaluation of   US housing and prices
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Project Set-up
* [Setting-up Virtual Environment]
* [Running Jupyter Notebook]
* [Data Location]

<!-- You can include any other section that is pertinent to your problem -->

## Setting-up Virtual Environment
- Python 3.8+ needed locally
- `python install-poetry` #if poetry is not avialable locally
- `poetry install` #Poetry will create a virtual environment locally for current project
- `poetry run jupyter notebook` # Jupyter notebook install will be created
## Running Jupyter Notebook
- open /main/ANINDITADAS_BoomBikesMODEL_Assignment_07132022.pyb
- Notebook has presved graphs

## Data Location
- ../resources
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.

- #These are the final features that should be selected for predicting the price of house


 - Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10)+ 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients)
 - The higher values of positive coeeficients suggest a high sale value.

 - The higher values of negative coeeficients suggest a decrease in sale value.
 - The optimal lambda value in case of Ridge and Lasso is as below:

#Ridge RMSE - 0.11485785595060997
#Lasso RMSE - 0.12573595366706636
 - The Mean Squared error in case of Ridge and Lasso are:

#Ridge - 0.015809530044566658
#Lasso - 0.015809530044566658
 - The Mean Squared Error of Lasso is slightly lower than that of Ridge

 - Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

 - Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area

.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter notebook
- python 3.8+
- gitbash

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Acknowledgements

- Anindita Das (anin08.birati@gmail.com)
- Github_link: https://github.com/Anindita2019/Advance_Regression



## Contact
Created by [@Anindita2019] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
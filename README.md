# Developing-Data-Products

Peer-graded Assignment: Course Project: Shiny Application and Reproducible Pitch

This peer assessed assignment has two parts. First, you will create a Shiny application and deploy it on Rstudio's servers. Second, you will use Slidify or Rstudio Presenter to prepare a reproducible pitch presentation about your application.

## MyShinyApp

Using this application, the effect of different types of diets over the weight of chickens can be determined using linear regression model where the outcome variable is the weight and predictor variable is the age.

This application was designed for Developing Data Products as part of the Coursera Data Science Speicalization Course.

The first part of the assignment to create a Shiny application can be found here: 

The second part of the assigment to prepare a reproducible pitch presentation about the application can be found here: 

This App need two type of enter data, In the first one, the user should specify the type of diet, given a number between 1 and 4, and in the second part, the user must enter the age of the chick, given a number between 0 and 20.

## Data

 The dataset was taken from ChickWeight dataset in R. The ChickWeight dataframe has 578 rows and 4 columns from an experiment on the effect of diet on early growth of chicks.
 
This dataframe contains the following columns:

- weight: a numeric vector giving the body weight of the chick (gm).

-Time: a numeric vector giving the number of days since birth when the measurement was made.

- Chick: an ordered factor with levels 18 < ... < 48 giving a unique identifier for the chick. The ordering of the levels groups chicks on the same diet together and orders them according to their final weight (lightest to heaviest) within diet.

- Diet:  a factor with levels 1, ..., 4 indicating which experimental diet the chick received 


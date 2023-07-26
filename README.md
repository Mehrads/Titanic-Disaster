# Titanic-Disaster

# Titanic - Machine Learning from Disaster 🛳️

!["Our framework"](Framework.png)


## 1. Problem Definition

The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).


## 2. Data

Our data is from kaggle website.The data has been split into two groups:

* training set (train.csv)
* test set (test.csv)

For the **training set**, they provide the outcome (also known as the “ground truth”) for each passenger. Our model will be based on “features” like passengers’ gender and class. You can also use `feature engineering` to create new features.

For the **test set**, we do not provide the ground truth for each passenger. It is our job to predict these outcomes. For each passenger in the test set, use the model we trained to predict whether or not they survived the sinking of the Titanic.


### Data Dictionary

survival   ►   0 = No, 1 = Yes <br>

pclass   ►   Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd <br>

sex  ►   Sex <br>

Age  ►   Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5 <br>

sibsp   ►   The dataset defines family relations in this way... Sibling = brother, sister, stepbrother, stepsister Spouse = husband, wife (mistresses and fiancés were ignored) <br>

parch   ► 
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them. <br>

ticket   ►   Ticket number <br>

fare   ►   Passenger fare <br>

cabin   ►   Cabin number <br>

embarked   ►   Port of Embarkation  C = Cherbourg, Q = Queenstown, S = Southampton <br>

You see other phases throughout notebook.

Hope you enjoy reading my code and I would be happy to hear your opinions and suggestions!
 
 
## 3. Evaluation

### Metric

Your score is the percentage of passengers you correctly predict. This is known as accuracy.
We should achieve 1.0 accuracy for being among the best submissions.

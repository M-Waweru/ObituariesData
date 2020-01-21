# ObituariesData

This project deals with a obituaries dataset gathered from the Daily Nation. The data is a sample of mortality in Kenya that is intended to inform the creation and marketing of various life insurance products.

## Getting Started

The notebook in this project can be used in both Jupyter Notebook on Anaconda and Google Colab. There will be a link in the repo to Colab.

## Kaplan-Meier Survival Analysis

The first objective was coming up with a Kaplan-Meier survival curve using various variables. Below is an exmaple using the deceased's gender to determine the survival probabilities of each gender.

### Survival Curve for Gender

![Image of Survival Curve Gender](images/scfunding.PNG)

From the graph above, we can observe that the survival rate of individuals, whose obituaries asked for fundraising, was lower than those who did not ask explicitly. This is especially evident for adults from the youth and gets worse for middle-aged adults. This may be due to poor financial planning when it comes to the event of death. Most people do not account for this and most families or involved members must fundraise to cover costs of burial, upkeep of the household and even to pay debts.

## Model to predict those who need fundraising

The second objective is to create and train a model that can predict who needs fundraising based on the dataset provided. This will also inform us on who needs life insurance the most.

### Algorithms used
Since this is a classification problem, all the algorithms used are classifiers.

#### Decision Trees

![Decision Tree classification report](images/dt_report.PNG)

![Decision Tree Confusion Matrix](images/dt_cm.PNG)

<!-- #### Random Forest 

![Image of Survival Curve Gender](images/scfunding.png)

#### XGBoost

![Image of Survival Curve Gender](images/scfunding.png)

#### CATBoost

![Image of Survival Curve Gender](images/scfunding.png) -->

## Conclusion

* Hat tip to anyone whose code was used
* Inspiration
* etc

# Data-Science-Machine-Learning-Titanic-Walkthrough
Data science is a field that studies data and how to extract meaning from it, whereas machine learning is a field devoted to understanding and building methods that utilize data to improve performance or inform predictions
## Introduction
In this walkthrough, I'll utilize Titanic Datasets to demonstrate data cleansing and forecast the passenger's survival using python language and jupyter notebook.

The train and test data frames describe the survival status of individual passengers 
on the Titanic. The titanic data frame does not contain information for the crew, but it does contain 
actual and estimated ages for almost 80% of the passengers. The principal source for data about 
Titanic passengers is the Encyclopedia Titanica.<br/>

The training set used to build your machine learning models. <br/>
The test set used to see how well your model performs on unseen data.

# Variable Descriptions

Pclass Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd) <br/>
survival Survival (0 = No; 1 = Yes) <br/>
name Name <br/>
sex Sex <br/>
age Age <br/>
sibsp Number of Siblings/Spouses Aboard <br/>
parch Number of Parents/Children Aboard <br/>
ticket Ticket Number <br/>
fare Passenger Fare (British pound) <br/>
cabin Cabin <br/>
embarked Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton) <br/>
boat Lifeboat <br/>
body Body Identification Number <br/>
home.dest Home/Destination <br/>

# Special Notes
Pclass is a proxy for socio-economic status (SES)  <br/>
1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower <br/>
Age is in Years; Fractional if Age less than One (1) <br/>
If the Age is estimated, it is in the form xx.5 <br/>
Fare is in Pre-1970 British Pounds () <br/>
Conversion Factors: 1 = 12s = 240d and 1s = 20d <br/>

With respect to the family relation variables (i.e. sibsp and parch) some relations were 
ignored. The following are the definitions used for sibsp and parch.<br/>
Sibling: Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic <br/>
Spouse: Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances 
Ignored) <br/>
Parent: Mother or Father of Passenger Aboard Titanic <br/>
Child: Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic <br/>

GoTO [training model](training_test_data_titanic.ipynb) file for a description of the code.

# Titanic-Survival Prediction 
  PROBLEM STATEMENT:<br><br>
   We will be creating a machine learning model on the famous Titanic dataset, which is used by many people all over the world. It provides information on the fate of passengers on the Titanic, summarized according to economic status (class), sex, age and survival.<br><br>
  INTRODUCTION:<br><br>
  We have a data set of passenger on the ship titanic and we have to predict that who among them chould survive when ship will sink. The sinking of the RMS Titanic caused the death of thousands of passengers and crew is one of the deadliest maritime disasters in history. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. The interesting observation which comes out from the sinking is that some people were more likely to survive than others, like women, children were the one who got the priority to rescue. The objective is to first explore hidden or previously unknown information by applying exploratory data analytics on available dataset and then apply different machine learning models to complete the analysis of what sorts of people were likely to survive. After this the results of applying machine learning models are compared and analyzed on the basis of accuracy.<br><br>
DATASET USED<br><br>
Downloaded the dataset from kaggle<br>
train.csv contains the details of a subset of the passengers(name, age, price of ticket, etc)on board (891 passengers)
test.csv does not have a "Survived" column (we need to predict this)<br><br>
SOFTWARE AND LIBRARIES USED<br><br>
Language:Python<br>
Libraries:<br>
NumPy<br>
pandas<br>
seaborn<br>
sklearn<br>
matplotlib<br>
Software:
Google Colab<br>

ALGORITHMS USED <br>

K nearest-Neighbors     82.60<br>
Logistic Regression    78.56 <br>
Naive Bayes   77.55<br>

PROCEDURE FOLLOWED:<br><br>
  Firstly I have done prerocessing on  my dataset where I changed the column Embarked to numerical format as pre-processing in string is difficult and with numerical format of data it will be easy to get co-relations between attributes. And i have changed sex column to 0,1 where male=0, female=1.<br>
  Then Classifying is done that is Classify or categorize our samples and Deciding which features within the dataset contribute significantly to our solution goal.<br>
  Then in the dataset there were missing values for this data preparation is done to esminate any missing values within a feature . Creating new features based on an existing feature that the new feature follows the correlation, conversion.<br>
Then i have done Model making and evaluation by calculating the accuracy.<br><br>
SOME OBSERVATIONS DRAWN OUT BY ANALYSIS<br><br>

Female passengers had much better survival rate than males.<br>
Pclass=3 had most passengers, however most did not survive<br>
Infant passengers in Pclass=2 <br> Pclass=3 mostly survived.<br>
Large number of 15-25 year olds did not survive.<br>
Most passengers are in 15-35 age range.<br><br>



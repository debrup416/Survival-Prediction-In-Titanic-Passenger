# Survival-Prediction-In-Titanic-Passenger-Using-Random-Forest

<a href="https://github.com/debrup416"><img style="position: relative; top: 0; left: 0; border: 0; class="center";" src="https://68.media.tumblr.com/38ae897f20630ef88e6484dea00db3b3/tumblr_mm8fhitR3u1rwwvg9o1_500.gif" alt=" Fork this repo" data-canonical-></a>

### Description

RMS Titanic sinking is one of the most infamous shipwrecks in history. During
its maiden voyage, the Titanic sank after colliding with an iceberg, killing many
passengers including crew. This sensational tragedy shocked the international
community and led to better safety regulations for ships. One of the reasons that
the shipwreck led to such loss of life was that there were not enough lifeboats
for the passengers and crew. Although there was some element of luck involved
in surviving the sinking, some groups of people were more likely to survive
than others, such as women, children, and the upper-class. In this paper we are
going to make a predictive analysis of what sorts of people were likely to
survive using some tools in machine learning to predict which passengers
survived the tragedy.

### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [scikit-learn](http://scikit-learn.org/stable/)

### Problem Defination

The most infamous disaster which occurred over a century ago on April 15,
1912, that is well known as the sinking of “The Titanic”. The collision with
the iceberg ripped off many parts of the Titanic. Many classes of people of all
ages and gender were present on that fateful night, but the bad luck was that
there were only a few lifeboats to rescue. The dead included a large number of
men whose place was given to the many women and children on board. The
men travelling in second class were dead on the vine. The goal is to classify
whether a person was likely to survive or not. To achieve this, we have used
machine learning classification methods to fit a function that can predict the
discrete class of new input

### Project Goal

The objective is to perform exploratory data analytics to mine various
information in the dataset available and to know the effect of each field on
survival of passengers by applying analytics between every field of the dataset
with “Survival” field. The predictions are done for newer data sets by
applying a machine learning algorithm. The data analysis will be done on
applied algorithms and accuracy will be checked. Different algorithms are
compared on the basis of accuracy and the best performing model is suggested
for predictions.


### Methodology

* Data Selection:
Data is the foundation for any machine learning project. The
job is to find ways and sources of collecting relevant and comprehensive data,
interpreting it, and analyzing results with the help of statistical techniques.

* Data Visualization:
A large amount of information represented in graphic form
is easier to understand and analyze. Some companies specify that a data analyst
must know how to create slides, diagrams, charts, and templates.

* Data cleaning:
This set of procedures allows for removing noise and fixing
inconsistencies in data. A data scientist can fill in missing data using imputation
techniques. A specialist also detects outliers — observations that deviate
significantly from the rest of distribution.

* Data Splitting: 
A dataset used for machine learning should be partitioned into
three subsets — training, test, and validation sets.

* Model Selection:
After a data scientist has preprocessed the collected data and
split it into three subsets, he or she can proceed with a model training. This
process entails “feeding” the algorithm with training data. An algorithm will
process 14 data and output a model that is able to find a target value in new
data. The purpose of model training is to develop a model.

* Model Evaluation: The goal of this step is to develop the simplest model able
to formulate a target value fast and well enough and check the accuracy



### Project Objective

The main objective of this is to determine what sort of a person was likely to
survive the Titanic.


### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

- `survival` ? Survival (0 = No; 1 = Yes)
- `pclass` ? Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` ? Name
- `sex` ? Sex
- `age` ? Age
- `sibsp` ? Number of Siblings/Spouses Aboard
- `parch` ? Number of Parents/Children Aboard
- `ticket` ? Ticket Number
- `fare` ? Passenger Fare
- `cabin` ? Cabin
- `embarked` ? Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
- `home` ? Home
- `dest` ? Destination
- `body` ? Body
- `boat` ? Boat











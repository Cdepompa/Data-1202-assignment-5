Project Title:
dicision tree analysis

Short description:
This projects contains a data file known as raisin data set that describes different attributes of raisins which are then used to predict what type of rasin each rasin will be.
There are two possible raisin results, Kecimen and Bensi. The code is describing a discision tree model which takes the attributes into account and uses them to predict if a raisin will be kecimen raisin or a bensi raisin

Getting Started:

needed for this project is the Rasin_Dataset.csv file
jupyter notebook install and project jupyter


Installing:
need to install local libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns

Running the tests:
there are fourimportant parts for running the disicion tree tests
1. creating the x and y variables
x variable is the independat variables, which in this case is every variable but class
while y is the dependant variable which in this case is class
2. splitting the data, there needs to be a set sample of data for the model to train on,
as well as a different set of data for the model to train on, and a set of data for the model to test on
3. scaling the data to so the model does not over emphasize certain variable
4. create a model for that simulate a disicion tree and run the code

Breakdown of the tests:
These test what the variables on each rasin to determine if it is a kecimen or Bensi raisn. The first split of the data is training the data on what values determine which type of rasin it will be based on the variables, and the second set is applying the model to the variables given to predict the type, and seeing if the type of raisin martches the models prediction

Deployment:
To deploy this code jupyter 3 is needed, as well as the base dataset Raisin_Dataset.csv

Contributing
only the author christopher De Pompa can contribute

Authors:
Christopher De Pompa

License:
not liscensed

acknowledgements:
code used from Data 1200 instructor

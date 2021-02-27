### Starbucks Capstone Challenge
I was given a simulated dataset that mimics customer behavior on the Starbucks rewards mobile app. I performed some data engineering, analysis and visualizations to get more insights to our data. I also made a model which predicts how many of the given offers will be completed by each user.
### Table of Content
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Libraries](#libraries)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

I used the simulated data set to:

1. Inspect and process data to transform to more interpretable formats
2. Create an offer-user data for accessing to offer responder statistics.
3. Visualize and determine which demographic group responds best to which offer type.
4. Preprocess and merge all the data we have for each user and prepare a complete and clean user-offer dataset for the model training
5. Apply a machine learning classifier method and build a model to predict the number of responses by each user to the given offers.

## Libraries <a name="libraries"></a>
python libraries used in this project:
-  pandas
-  numpy
-  math
-  statistics
-  datetime
-  json
-  matplotlib.pyplot
-  seaborn as sns
-  sklearn.model_selection
-  sklearn.ensemble
-  sklearn.metrics
-  pickle

## File Descriptions <a name="files"></a>

Data folder:
1. portfolio.json — containing offer ids and metadata about each offer (duration, type, etc.)
2. profile.json — demographic data for each customer
2. transcript.json — records for transactions, offers received, offers viewed, and offers complete

image folder:
Contains all the visualization plots used in the process

Starbucks_Capstone_notebook.ipynb:
A Jupyter notebook containing all the coded used for this analysis

Starbucks_model.sav:
Our deployed model for using on new data.

## Results<a name="results"></a>
The main findings of the code can be found at the post available [here](https://nima-ghasemitafreshi.medium.com/starbucks-capstone-challenge-51cb5053db29).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Starbucks and Udacity for providing this data.  Otherwise, feel free to use the code here as you would like!

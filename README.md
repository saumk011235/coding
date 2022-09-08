# Unsupervised Learning Project
## Author: Saumya Kothari

------------------------------------------------------------------------

## This Project has been divided into 5 parts (Part I to Part V) and below is an overview:
#### Part I: 
AIML module project part I consists of industry based problems statement which can be solved using clustering techniques
#### Part II: 
AIML module project part II consists of designing a synthetic data generation model for a company which has a predesigned dataset.
#### Part III: 
AIML module project part III consists of industry based problems statement which can be solved using dimensional reduction techniques
#### Part IV: 
AIML module project part IV consists of designing a data driven ranking model for a sports management company.
#### Part V: 
AIML module project part V consists of implementing dimensionality reduction on multimedia dataset.

------------------------------------------------------------------------

# Part I
#### DOMAIN: 
Automobile
#### CONTEXT: 
The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5
continuous attributes
#### DATA DESCRIPTION: 
The data concerns city-cycle fuel consumption in miles per gallon
#### Attribute Information:
- mpg: continuous
- cylinders: multi-valued discrete
- displacement: continuous
- horsepower: continuous
- weight: continuous
- acceleration: continuous
- model year: multi-valued discrete
- origin: multi-valued discrete
- car name: string (unique for each instance)

#### PROJECT OBJECTIVE: 
Goal is to cluster the data and treat them as individual datasets to train Regression models to predict ‘mpg’
Steps and tasks:
- Import and warehouse data: 
Import all the given datasets and explore shape and size. Merge all datasets onto one and explore final shape and size. Export the final dataset and store it on local machine in .csv, .xlsx and .json format for future use. Import the data from above steps into python.
- Data cleansing: 
Missing/incorrect value treatment. Drop attribute/s if required using relevant functional knowledge. Perform another kind of corrections/treatment on the data.
- Data analysis & visualisation:
Perform detailed statistical analysis on the data. Perform a detailed univariate, bivariate and multivariate analysis with appropriate detailed comments after each analysis. [Hint: Use your best analytical approach. Even you can mix match columns to create new columns which can be used for better analysis.] Create your own features if required. Be highly experimental and analytical here to find hidden patterns.
- Machine learning: 
Use K Means and Hierarchical clustering to find out the optimal number of clusters in the data. Share your insights about the difference in using these two methods.
- Answer below questions based on outcomes of using ML based methods.
Mention how many optimal clusters are present in the data and what could be the possible reason behind it. Use linear regression model on different clusters separately and print the coefficients of the models individually. How using different models for different clusters will be helpful in this case and how it will be different than using one single model without
clustering? Mention how it impacts performance and prediction.
- Improvisation: 
Detailed suggestions or improvements or on quality, quantity, variety, velocity, veracity etc. on the data points collected by the company to
perform a better data analysis in future


# Part II
#### DOMAIN: 
Manufacturing
#### CONTEXT: 
Company X curates and packages wine across various vineyards spread throughout the country.
#### DATA DESCRIPTION: 
The data concerns the chemical composition of the wine and its respective quality.
#### Attribute Information:
- A, B, C, D: specific chemical composition measure of the wine
- Quality: quality of wine [ Low and High ]

#### PROJECT OBJECTIVE: 
Goal is to build a synthetic data generation model using the existing data provided by the company.
Steps and tasks: 
- Design a synthetic data generation model which can impute values [Attribute: Quality] wherever empty the company has missed recording the data.


# Part III
#### DOMAIN: 
Automobile

#### CONTEXT: 
The purpose is to classify a given silhouette as one of three types of vehicle, using a set of features extracted from the silhouette.
The vehicle may be viewed from one of many different angles.

#### DATA DESCRIPTION: 
The data contains features extracted from the silhouette of vehicles in different angles. Four "Corgie" model vehicles were used for the experiment: a double decker bus, Cheverolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.
• All the features are numeric i.e. geometric features extracted from the silhouette.

#### PROJECT OBJECTIVE: 
Apply dimensionality reduction technique – PCA and train a model using principal components instead of training the model using just the raw data.

#### Steps and tasks: 
- Data: Import, clean and pre-process the data
- EDA and visualisation: Create a detailed performance report using univariate, bi-variate and multivariate EDA techniques. Find out all possible hidden patterns by using all possible methods. For example: Use your best analytical approach to build this report. Even you can mix match columns to create new columns which can be used for better analysis. Create your own features if required. Be highly experimental and analytical here to find hidden patterns.
- Classifier: Design and train a best fit SVM classier using all the data attributes.
- Dimensional reduction: perform dimensional reduction on the data.
- Classifier: Design and train a best fit SVM classier using dimensionally reduced attributes.
- Conclusion: Showcase key pointer on how dimensional reduction helped in this case.



# Part IV
#### DOMAIN: 
Sports management
#### CONTEXT: 
Company X is a sports management company for international cricket.
#### DATA DESCRIPTION: The data is collected belongs to batsman from IPL series conducted so far. Attribute Information:
- Runs: Runs score by the batsman
- Ave: Average runs scored by the batsman per match
- SR: strike rate of the batsman
- Fours: number of boundary/four scored
- Six: number of boundary/six scored
- HF: number of half centuries scored so far
#### PROJECT OBJECTIVE: 
Goal is to build a data driven batsman ranking model for the sports management company to make business decisions.
Steps and tasks: 
- EDA and visualisation: Create a detailed performance report using univariate, bi-variate and multivariate EDA techniques. Find out all possible hidden patterns by using all possible methods.
- Build a data driven model to rank all the players in the dataset using all or the most important performance features.




# Part V
#### Questions: 
1. List down all possible dimensionality reduction techniques that can be implemented using python.
2. So far you have used dimensional reduction on numeric data. Is it possible to do the same on a multimedia data [images and video] and text data ? Please illustrate your findings using a simple implementation on python.

<img width="1211" alt="Captura de pantalla 2021-05-26 a las 16 36 39" src="https://user-images.githubusercontent.com/79402322/119680016-1df9e480-be41-11eb-8149-e896020fe807.png">


**Introduction:**

In this project, executed in collaboration with Ironhack, my team and I performed an exploratory data analysis focusing on people’s perception about climate change. 
Specifically, we were interested in analysing the factors that influence citizens who do not believe in climate change. 
We gathered the data from the European Social Survey (ESS). This survey has the aim to measure behaviour patterns of the European population.

**Data analysis:**
Here’s a list of the major computations done to explore, clean and process the data:
* Database import
* Columns renaming
* Database filtering to get only Spanish data
* New database import
* Databases merging
* Target variable definition
* Null values identification (6, 7, 8, 9, 66, 77, 88, etc.)
* Dealing with null values (substitution by Mean or Random Forest Method depending on null percentage over total individuals)
* Categorical variables treatment (One Hot Encoding or Label encoding depending on the nature of the variable)
* Correlation study 
* X and Y definition
* Dealing with imbalanced data (SMOTE)
* Train test split
* Logistic Regression
* Confusión matrix
* Precision, recall and f1 scores

**Results:**
We have found a correlation between 38 different variables and people who believe or not in climate change. Out of this variables, the most insightful one related to political interest, human values, education and demographics. 
Check the presentation to have a full overview about our findings!

**Authors:**
* Nicolò Paolo Ferrari
* Jorge Palacios
* Marta Coll

**Content of this repo:**
* Source of the data: ESS (European Social Survey)
* Google Colab containing all the codes performed during the analysis
* Presentation (PDF format)
* Visualisations done in Tableau (see presentation)


















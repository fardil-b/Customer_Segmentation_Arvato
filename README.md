# Customer_Segmentation_Arvato
Identifying potential customers using Machine Learning 


### Table of Contents

1.  [Project Motivation](#motivation)
2.  [Methods Used](#method)
3. [File Descriptions](#files)
4. [Results](#results)
2. [Installation](#installation)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>

In this project, I will use the data provided by Bertelsmann Arvato Analytics, I will analyze demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. I will be using unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core customer base of the company. Then, I will apply what I've learned on a third dataset with demographics information for targets of a marketing campaign for the company, and use a model to predict which individuals are most likely to convert into becoming customers for the company.


## Methods Used <a name="method"></a>
- Exploratory data analysis to understand the dataset
- Feature selection and elimination using Correlation,  and Chi-Square statistical tests
- Use PCA for dimensionality reduction and Kmeans Unsuperised ML Technique for Clustering
- Using varoius Machine Learning model for prediction

## File Descriptions <a name="files"></a>
1. `Insurance_severity_claims.ipynb` : Notebook containing the whole project combined including EDA & Machine learning model
2. `API` : folder containing 3 files : 
                   1. `claimsPrediction_model_API.py` : flask API code for deployment       
                   2. `columns_to_drop.csv`  : csv files containing features to be dropped and is used in the API file
                   3. `tunedmodel_rf` : pickle file containing the RandomForest model used for prediction
3. `dataset.zip` :zipped folder containing the train and test datasets
4. `requirements.txt` : text file containing the required  libraries & packages to execute the code


## Results<a name="results"></a>
- I was able to drop the number of features from 130 to 39 and I trained a ML algorithm which work quite was and was able to make prediction
- The prediction using the test dataset was submitted on Kaggle and a score of 3011.62 was achieved which can be improved.

More information about the project and the main findings of the code can be found at the post available [here](https://fbhugaloo.medium.com/customer-segmentation-and-acquisition-a-machine-learning-approach-8827b0e580b7)

## Installation <a name="installation"></a>
- To clone the repository use: git clone https://github.com/fardil-b/Insurance-Claims-Severity-Prediction.git

- The code should run with no issues using Python versions 3.0 and above. The additional libraries required to execute the code can be installed using `pip` with `pip install -r requirements.txt`


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Arvato/Bertelsmann and Udacity for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/udacity-arvato-identify-customers/data). Otherwise, feel free to use the code here as you would like! 

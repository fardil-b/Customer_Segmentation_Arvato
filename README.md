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
- Feature selection and elimination using Correlation 
- Use PCA for dimensionality reduction and Kmeans Unsuperised ML Technique for Clustering
- Using varoius Machine Learning model for prediction

## File Descriptions <a name="files"></a>
1. `Arvato Project Workbook Final.ipynb` : Notebook containing the whole project combined including EDA & Machine learning model
2. `terms_and_conditions` : contains information about data privacy
3. `requirements.txt` : text file containing the required  libraries & packages to execute the code


## Results<a name="results"></a>
- I identified clusters of relevance of future customers and identified positive responders to the mail-order campaign successfuly, 
- More information about the project and the main findings of the code can be found at the post available [here](https://fbhugaloo.medium.com/customer-segmentation-and-acquisition-a-machine-learning-approach-8827b0e580b7)
- Results of prediction can also be found on [Kaggle](https://www.kaggle.com/c/udacity-arvato-identify-customers/data)
## Installation <a name="installation"></a>
- To clone the repository use: git clone https://github.com/fardil-b/Customer_Segmentation_Arvato.git

- The code should run with no issues using Python versions 3.0 and above. The additional libraries required to execute the code can be installed using `pip` with `pip install -r requirements.txt`


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Must give credit to Arvato/Bertelsmann and Udacity for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/udacity-arvato-identify-customers/data). Otherwise, feel free to use the code here as you would like! 

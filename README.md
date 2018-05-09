# Modeling and Analysing RECS data using dimensionality reduction and t-SNE visualization

This project visualizes Residential Energy Consumption Survey (RECS) 2009 (n-dimensional data) and uses feature reduction techniques to find what are the factors which have the most impact on residential energy usage

## Project flow
 * Prepare a RECS 2009 data, which is a high-dimensional dataset
 * Understand challenges with visual interpretation of the raw data
 * Reduce the dataset to 2 dimensions by using t-SNE for plotting and interpretation
 * Assess if the type of housing unit feature's impacts on the energy consumption pattern of US households 

## How to Run
### Prerequisites
You will need a python 3 interpreter with the following packages:
  - jupyter notebook  
  - scikit learn
  - scipy
  - matplotlib
  - pandas
  - seaborn
  - sqlite3
  - regular expression
  
   ### Running the code
  1. Clone (or download) the repository: 
  
  `git clone https://github.com/sakshi-mishra/modeling_and_analysing_RECS_data_using_dimensionality_reduction-_and_t-SNE.git`

  2. Open/Run the jupyter notebook [t-SNE_with RECS_2009_final_version.ipynb](t-SNE_with_RECS_2009_final_version.ipynb)
  
### Learnings/usage of the code: 
* reading big dataset from csv format and writing it to different file format databases (sql)
* data-cleaning: removing character features values and replacing nans.
* data-transformation: normalization and applying transformation techniques during the feature reduction stage.
* Visualization: ploting the data in the reduced dimentionality
* t-SNE algorithm implementation: reducing the data into two dimensions and creating effective 2-D plot.

## Input Data
I have download the RECs 2009 data from eia's website: https://www.eia.gov/consumption/residential/data/2009/index.php?view=microdata


*Note*: Please read the  _**Notes**_  and _**Observations**_  throughout the Notebook to understand the approach, concepts used, and flow of the project.
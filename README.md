# Neural_Network_Charity_Analysis

## Overview of Project  

**Purpose:**  
The purpose of this project is to create a deep learning neural network model for a non-profit foundation, Alphabet Soup, to predict which organizations are worth donating to and which are too high risk.  

## Resources:  
- Data Source: [charity_data](https://github.com/tonywang3571/Neural_Network_Charity_Analysis/blob/master/Resources/charity_data.csv)  
- Software: Python 3.9.7, Jupyter Notebook 6.4.5, scikit-learn, tensorflow  

## Analysis and Results  

**Analysis:**  
I performed ETL on our dataset to aquire the data needed for our specific analysis. I then created a density plot to determine how to split the data into different bins or buckets, encode the categorical variables using one-hot encoding, then merge merging the dataframes and dropping the original columns. Next, I split the data into training and testing datasets and scaling the datasets with StandardScaler.  

**Results:**  
- Data Preprocessing  
  - What variable(s) are considered the target(s) for your model?  
  - What variables are considered to be the features for your model?  
  - What var are neither targets nor features and should be removed from the input data?  

- Compiling, Training, and Evaluating the Model  
  - How many neurons, layers and activation functions did you select for your neural network model, and why?  
  - Were you able to achieve the target model performance?  
  - What steps did you take to try and increase model performance?  

## Summary  

**Conclusion**  

### Codes Used  
(Please look at specific files for codes used)  
Code for [initial analysis](https://github.com/tonywang3571/Neural_Network_Charity_Analysis/blob/master/AlphabetSoupCharity.ipynb)  
Code for [first optimization attempt](https://github.com/tonywang3571/Neural_Network_Charity_Analysis/blob/master/AlphabetSoupCharity_Optimization1.ipynb)  
Code for [second optimization attempt](https://github.com/tonywang3571/Neural_Network_Charity_Analysis/blob/master/AlphabetSoupCharity_Optimization2.ipynb)  
Code for [third optimization attempt](https://github.com/tonywang3571/Neural_Network_Charity_Analysis/blob/master/AlphabetSoupCharity_Optimization3.ipynb)  
# Welcome to my Credit Risk analysis Project

I will be doing some explorations through the German Credit Risk dataset to understand their distributions and patterns. I will use this readme file to document all my steps and thinking processes used in my analysis.

# Introduction 

### Context
The original dataset contains 1000 entries with 20 categorial/symbolic attributes. In this dataset, each entry represents a person who takes credit by a bank. Each person is classified as good or bad credit risks according to the set of attributes.

### Content
It is almost impossible to understand the original dataset due to its complicated system of categories and symbols. Thus, I wrote a small Python script to convert it into a readable CSV file. Several columns are simply ignored, because in my opinion either they are not important or their descriptions are obscure. The selected attributes are:

- Age (numeric)
- Sex (text: male, female)
- Job (numeric: 0 - unskilled and non-resident, 1 - unskilled and resident, 2 - skilled, 3 - highly skilled)
- Housing (text: own, rent, or free)
- Saving accounts (text - little, moderate, quite rich, rich)
- Checking account (numeric, in DM - Deutsch Mark)
- Credit amount (numeric, in DM)
- Duration (numeric, in month)
- Purpose(text: car, furniture/equipment, radio/TV, domestic appliances, repairs, education, business, vacation/others
- Risk (Value target - Good or Bad Risk)

# Libraries

Here we are importing the libraries and the dataset.

# Looking at the data

- Looking for the type of data
- Null values
- Unique Values
- The first rows of our dataset

# Some Explorations

Since GitHub cannot show the visualizations of the plotly library, You can check out this [link](https://nbviewer.org/github/TheArc21/Credit-Risk/blob/main/Credit_Risk_Model.ipynb) for a rich view of the notebook.
- Starting by distribution of Age column
- Some seaborn graphs
- Columns Crossing


# Wine Dataset Exploratory Data Analysis (EDA)

This repository contains a simple exploratory data analysis (EDA) workflow applied to the Wine dataset, sourced from the sklearn.datasets module. The goal is to understand the structure of the dataset, perform basic manipulations, and analyze the variables.

### Libraries Used
The code uses the following Python libraries:

pandas: For data manipulation and analysis.

matplotlib: For creating static, animated, and interactive visualizations.

seaborn: Built on top of matplotlib to provide high-level data visualization.

sklearn: For loading the Wine dataset.

### Dataset Information
The dataset consists of 13 features that describe different properties of wine, along with a target column that classifies wines into three categories. Below are the features included in the dataset:


alcohol
malic_acid
ash
alcalinity_of_ash
magnesium
total_phenols
flavanoids
nonflavanoid_phenols
proanthocyanins
color_intensity
hue
protein_concentration (renamed from od280/od315_of_diluted_wines)
proline
The target column classifies wines into three categories (0, 1, 2).


### EDA Workflow
Loading the Dataset: The Wine dataset is loaded using the load_wine() function from sklearn.datasets. It is then converted to a pandas DataFrame for easier analysis.

### Basic Data Exploration:

    df.head(): Display the first few rows of the dataset.
    
    df.tail(): Display the last few rows.
    
    df.shape: Shows the dimensions of the dataset.
    
    df.describe(): Provides summary statistics for numerical columns.
    
    df.info(): Gives information about column data types and missing values.
    
    df.columns: Lists all the column names.
    
    df.duplicated().sum(): Checks for duplicated rows.

Column Renaming: The column od280/od315_of_diluted_wines is renamed to protein_concentration for better readability.


Installation & Setup

Clone this repository:

    git clone https://github.com/yourusername/wine-dataset-eda.git

Install the required dependencies:

    pip install pandas matplotlib seaborn scikit-learn
Run the Python script:


## Results

The EDA provides insights into the Wine dataset such as:

  Basic statistics like mean, standard deviation, and percentiles.
  
  Checking for any missing or duplicated data.
  
  Summary of the feature variables.
  
## Future Enhancements
  
  Add advanced visualizations for deeper insights.
  
  Perform correlation analysis to study relationships between different variables.
  
  Apply feature engineering and dimensionality reduction techniques for modeling.
  

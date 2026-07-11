### Assignment no-13- Data Gathering,preproccesing & EDA
- This assignment contains multiple task tp practice data gathering, preprocessing, cleaning and exploratory data analysis (EDA) using python,pandas,Numpy,matplotlib,and seaborn.

## PART-1 Data Gathering
# Task-1:- Load data from CSV
- Loaded a kaggle dataset('International_Education_Costs.csv').
- Printed shape,columns,first 5 rows,and basic preprocessing.

# Task-2:- Load data from JSON
- downLoaded the JSON file from kaggle.
- Loaded using pd.read_json('iris.json').
- Converted dataset to DataFrame, and displays.

# Task-3:- Load data from SQL
- Downloaded Xampp from the sources.
- Downloaded mysql in my envoirnment using pip install mysql.connector.
- Loaded data using mysql.connector.connect.
- Inserted records,and read into pd.read_sql_querry.

# Task-4:- API mini Project(TMDB)
- i have tried to create account in tmdb but it is not responded.
- But i imported  api from rapidapi.
- i have printed(response) but, it gave the respone [403].

## PART-2 Data preprocessing & Cleaning
# Task-5:- Understanding the data
- check shape.
- data types.
- Checks Numerical/Categorical columns,and missing values.

# Task-6:- Data Cleaning
- Handled missing values but not found any missing values,and duplicates in the dataset.
- Rename the column name and fixes the data types.

# Task-7:- Feature Preparation
- Encoded the dataset, using Label encoder.
- Separated features and targets.

## PART-3 Exploratory Data Analysis (EDA)
# Task-8:- Univariate Analysis
- Plotted distribution of numerical column using Histplot, and kdeplot.
- Plotted count plot for categorical column.
- Plotted box plot for outliers.

# Task-9:- Bivariate Analysis
- Visualize numerical numerical column using scatter plot.
- Visualize correlation using heatmap.
- Plotted bar plot , and box plot for categorical numerical columns.

# Task-10:- Insights & Observations
- All insights and observations are written.
- These insights and observations are written in the form of given patterns---> patterns,outliers,relationships,and data quality.
- All ponts are written in markdown cells only.

## How to run
- Install dependencies---> Pandas,Numpy,matplotlib,seaborn,requests,and mysql.connector
- Run the all TASKS using-
- pd.read_csv.
- pd.read_json.
- mysql.connector.connect
& etc.
- print(response)
- sns.hist,bar,box,line,heatmapplot().etc
### :- Assignment-14 Feature Engineering, Encoding, Scaling & Pipeline 
- This assignment covers Feature engineering, encoding, Scaling, and ML pipeline using (pandas,numpy,scikit-learn).
- Each task builds steps by steps toword creating & complete ML workflow.

## PART-1 Feature Engineering
# Task:-1 Creating New Features
- Data set used (train.csv,test.csv)
- Picked up 2 existing columns(sibsp and parch) from the dataset and added this with single column Family Size.
- generates the function to add the new column in the data set(Family Type).
added some ner features like individual fare,family size,Name Prifix

# Task:-2 handling data & Text Features
- - There is no date column in this data set, so i have skipped this
- but i have tried to create a new features text_length, and word_count

## PART-2 Feature Encoding
# Task:-3 One Hot Encoding
- Identified categorical columns and convert it to nominal_data
- used pd.get_dummies()
displayed the transformed DataFrame

# Task:-4 Column Transformer
- 1. Seperates- Numerical & categorical features
- impoerted remainder from math
- used columntransformer----> applied onehotencoder to categorical columns
- Pass numerical column unchanged.
Fitted and transform dataset.

## PART 3-Feature Scaling
# Task:-5 Standardization(StandardScaler)
- Applied StandardScaler on numerical features.
- Explained----> mean=0, and Standard deviation=1

# Task:- Normalisation(MinMaxScaler)
- Applied MINMaxScaler on numerical features.
- Valued scaled between 0 to 1.
- Compare results with StandardScaler.

## PART-4 Building ML pipeline
# Task:-7- Preprocessing Pipeline
- Created seperate pipelines.
- Numerical-->Scaling-->Numeric_pipeline
- Categorical---> OneHotEncoder-->Ordinal_pipeline
- Combined using ColumnTransformers.

# Task:-8 Full sciket-learn Pipeline
- Data->Encoded->Scaled-> and created model
- Uses simple model LogisticRegression
- Split data into train-test sets
- Fitted pipeline on training data
- Predicted the test data, accuracy appears approx 91%.

# Task:-9 Pipeline Benefits(Conceptual)
# 1.Importance of pipeline
- Pipeline make the whole machine learning process organized.they connect steps like data cleaning,feature selection, and model training into one flow.This saves time and reduces mistakes. 
- Pipeline helps to chain together multiple steps,such that output data--->Imputing----> Encoding ---->Feature Scaling.
# 2.Problem solving pipeline
- Doing the same steps again and again manually.
- Forgetting or mixing up peprocessing steps.
- Making sure training and testing dat are processed in the same way.
# 3. Difference b/w manual and pipeline based preprocessing
- MANUAL PREPROCESSING-Cleaning and transforming data step by step by self,easy to make mistakes or forget steps.
- PIPELINE PREPROCESSING- Steps are defined once in the pipeline.every time data goes through,the same process is applied automatically.its consistent and less error-prone 

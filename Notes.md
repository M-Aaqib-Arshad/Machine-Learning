# Notes of Machine Learning
## Data
- Numerical 
  - Age 
  - weight
  - CGPA
- Categorical
   - Gender
   - Nationality
   - Yes and No

### 1. Data Collection
- API
- Web Scrapping
## Challenges
### 1. Insuficient Data or Un Labelled data
For big data Algorithm does not matter
but for small data algorithm matters.
### 2. Non Representative Data
> Collect data from one side like wining servey of T20 match in Pakistan
> Sampling Noise
  Data from one side
> Sampling Bias
  Data of same type people

### 3. Poor Quality Data
### 4. Irrelevent Features
  If you are giving a model garbage, so it give garbage.
### 5. Overfitting
Means Same concept apply on different types of data
100% Accuracy means it is doing overfitting
### 6. Underfitting
### 7. Software Integration
### 8. Offline Learning

## Machine Learning 
> Learn from data (Input and Ouput) and generate an logic, On this Logic it will predict an output on unknown data

### Types of Machine
- Supervised 
   1.  Regression 
      -  Output is Numerical Value
   2.  Classfication
      -  Output is categorical like Yes and No
- UnSupervised
   1. Clustering
      - Grouping the data
      - Google Photos
   2. Dimentionality Reduction
       - Reduce Two columns into one or feature Extraction
       - PCA
       - Mnist
   3. Anomaly Detection
       - Remove Outliers
   4. Association Rule Learning
      - Use in Grocery stores Like Products Pattern
      - Find relationship b/w Products
- Semi Supervised
    - Label one or two things 
    - And Unsupervised learning give labels to same pictures
    - Google Photos
- Reinforement 
   1. Punishment and Reward
   2. Agent

In a dataset, labels and features are two fundamental components that are used in supervised machine learning. They play distinct roles in training and building predictive models. Here's the key difference between them:

## Features

* Features are the input variables or attributes that describe the characteristics of each data point in the dataset.
* Features are used to represent the data and provide information about the input space.
They are the independent variables that are used to make predictions or classifications.
* Features can be numeric (e.g., age, temperature), categorical (e.g., color, category), or even more complex representations like text or images.
* Features are the aspects of the data that the model uses to learn patterns and relationships.

## Labels

* Labels are the output variable or target variable in a supervised learning dataset.
Labels represent the ground truth or the desired outcome that the model is supposed to predict or classify.
* For a classification task, labels are typically categorical (e.g., class labels such as "spam" or "not spam").
* For a regression task, labels are typically continuous (e.g., predicting a numerical value like house prices).
* Labels are used to train the machine learning model by providing it with examples of input data (features) along with their corresponding correct output (labels).
* The model's primary goal is to learn a mapping from features to labels, so it can make predictions on new, unseen data.


### Batch vs Online Machine learning
1. Batch mean offline 
  - Away from internet
  - life cycle is late
2. Online Machine learning
  - Dynamic
  - Up to date data
  - Always learning new data
  - Advantages
     - Learning fast because learning in small packages
     - Cost Effective
  - Disadvantages
    - Risky : Because it depends upon data which comes from outside.
    - Tricky to use 

### Instance and Model Based Learning
#### 1. Instance
- Memorize the data
- Give respones quickly 
- KNN Algorithm 
- Plot the data and where the test point is lying,or Give the answer from your near points or Neighbours
- React according
#### 2. Model Based
- Taking a concept from data
- And give answer on base of concepts


### Machine Learning Development Life Cycle (MLDLC):
##### Similar to SDLC
Guide lines for build a Software
1. Frame of Problem
   - What is the Problem
   - What is the budget and Time to build 
   - Team for Project
   - Algorithm, Batch Mode, Problem Owner
   - End Product
2. Gathering Data
    - Direct Data 
    - API (JSON format)
    - Web Scrapping
    - Clustering
3. Data Preprocessing
   (Cosumable Data) 
   - Missing Values
   - Outliers
   - Duplicates
   - Noisy Data
   - Scale,Standardization
4. Explotary Data Analysis
   - Enalyz the data, extract Relationships
   - Visulization
   - Univariate,bivariate, Multivariate
   - Imbance Data(One thing data is more than the other one)
5. Feauring Engineering and Selection
   - Create Columns on existing data
6. Model Training and Evaluation
7. Model Deployment
8. Testing
9. Optimize
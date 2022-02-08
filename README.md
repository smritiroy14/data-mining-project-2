# data-mining-project-2
Problem 1: (15 points)

(a)   Consider a data object corresponding to a set of nucleotides arranged in a certain order. What is this type of data?

 

(b)  It is desired to partition customers into similar groups on the basis of their demographic profile. Which data mining problem is best suited to this task?

 

(c)  Suppose in problem 1.b, the merchant already knows for some  of the customers whether or not they have bought widgets. Which data mining problem would be suited to the task of identifying groups among the remaining customers, who might buy widgets in the future?

 

Problem 2: (30 points):

Download Heart Disease dataset from

http://archive.ics.uci.edu/ml/datasets/Heart+Disease (Links to an external site.)

This dataset contains patient information from Cleveland hospital where each row represents a patient. Labels are the test results of the presence of the disease where “0” means no presence for heart disease and 1-4 represent the level of the disease. The dataset contains some missing values, and these values are denoted as “?”. There are 303 patients in the original dataset and 75 features. The processed version of the dataset has the following attributes (which will be used in this assignment):

·      age: age in years

·      sex:  sex (1 = male; 0 = female)

·      cp: chest pain type:

o   value 1: typical angina

o   value 2: atypical angina

o   value 3: non-anginal pain

o   value 4: asymptomatic

·      trestbps:  resting blood pressure (in mm Hg on admission to the hospital)

·      chol: serum cholestoral in mg/dl

·      fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

·      restecg: resting electrocardiographic results:

o   value 0: normal

o   value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)

o   value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

·      thalach: maximum heart rate achieved

·      exang:  exercise induced angina (1 = yes; 0 = no)

·      oldpeak: ST depression induced by exercise relative to rest

·      slope: the slope of the peak exercise ST segment:

o   value 1: upsloping

o   value 2: flat

o   value 3: downsloping

·      ca: number of major vessels (0-3) colored by flourosopy

·      thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

·      num: Label 0 - 4

Answer the following questions using one of the following programming languages Python, R, Java, or MATLAB (you cannot use excel or any equivalent software):

a.     The associated task with this dataset is multiclass classification. Change the problem to binary classification and compute the proportion of each class in the binary case? Is this a balanced dataset?

b.     Remove all patients that have any missing values in their records, how many patients do you have now?

c.     Now, impute missing values by mean values of corresponding attributes. Report how this imputation affected the overall distribution of corresponding attributes?

d.     Draw a scatter plot and explain the relationship between chest pain type and age?

e.     How sex affects having or not having a heart disease? Draw a box plot and explain.

f.      Generate 6 random samples (without replacement) of size 50 and answer the following:

i.      What the proportion of each class in each sample? Is each sample a balanced dataset?

ii.     How sex affects having or not having a heart disease in each sample? Draw a box plot.

g.     Compare results from e with results from f.ii

 

Problem 3: (10 points)

You are given a set of m objects that is divided into K groups, where the i-th group is of size mi . If the goal is to obtain a sample of size n < m , what is the difference between the following two sampling schemes? (Assume sampling with replacement.)

a.     We randomly select n ∗ mi /m elements from each group.

b.     We randomly select n elements from the data set, without regard for the group to which an object belongs.

 

Problem 4: (20 points)

Download the image hw2_2022_problem4_Face.pgm from the class homework data folder. Find a PCA package and use it to compute eigenvectors and eigenvalues for this image.

a.     Compute 2, 5, and 10 principal components and show original and the resulting images.

b.     What is the minimal number of principal components needed to retain 80% of data variance?

 

Problem 5: (30 points)

The decision-makers at GymX would like to improve their services using data mining and machine learning techniques to better understand their customers. They have a large database that contains many fields such as customer_id, customer_name, age, sex, height, weight, membership_type, diet_restrictions, and more. The problem is that the database has many missing data, because most customer do not fill all necessary fields when they join the gym. This problem will affect their customer analysis. Help GymX to solve their problem. Download hw2_2022_problem5_GymX.cvs dataset from the class homework data folder. The dataset contains the following attributes:

·       Customer ID

·       Customer Name

·       Age

·       Sex (male = 1, female = 0)

·       Height in feet

·       Weight in pounds

·       Membership type (adult, youth, or kids)

a.     Report the number of missing values in each feature.

b.     Using a naive solution could solve the missing data problem. What are the advantages/disadvantages of this solution?

c.     Propose a better solution to solve the missing data problem.

d.     Compare results of the naïve handling of missing data vs your better solutions based on:

i.      Plot a histogram of customers’ age.

ii.     Plot a histogram of height for all customers and report mean and standard deviation

iii.   Plot a histogram of weight for all customers and report mean and standard deviation

iv.   Create a bar plot that shows the number of customers from each sex from each membership type.

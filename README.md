# Linear Regression for health insurance

## Instructions

### Description of the problem
The important insurance company 4Geeks Insurance S.L. wants to calculate, based on physiological data of its customers what will be the premium (cost) to be borne by each of them. To do this, it has assembled a whole team of doctors and based on data from other companies and a particular study have managed to gather a set of data to train a predictive model.

#### setup 0: Pip & Requirements, Imports, Initalization

#### Step 1: Data collection
The dataset can be found in this project folder under the name medical_insurance_cost.csv. You can load it into the code directly from the link (https://raw.githubusercontent.com/4GeeksAcademy/linear-regression-project-tutorial/main/medical_insurance_cost.csv) or download it and add it by hand in your repository. In this dataset you will find the following variables:

age. Age of primary beneficiary (numeric)
sex. Gender of the primary beneficiary (categorical)
bmi. Body mass index (numeric)
children. Number of children/dependents covered by health insurance (numeric)
smoker. smoker (categorical)
region. Beneficiary's residential area in the U.S.: northeast, southeast, southwest, northwest (categorical)
charges. Health insurance premium (numerical)

#### Step 2: Exploration and data cleaning
This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Be sure to conveniently divide the data set into train and test as we have seen in previous lessons.

#### Step 3 & 4: Analysis of univariate variables & Analysis of multivariate variables
Analysis of diferent variables with graphical representation for a better understanding of the data set

#### Step 5 : Feature engineering & Outliers
Outlier Analysis: Identifying data points that deviate significantly from the majority using statistical methods, z-scores, or machine learning techniques, and addressing them by removing, transforming, or adjusting to enhance model robustness and accuracy. Feature Engineering: Developing new features through scaling, encoding, and polynomial expansion, and selecting the most relevant ones to enhance predictive power and improve model performance while reducing dimensionality.

#### Step 6 : Feature selection
Feature Selection: Identifying and choosing the most relevant features to improve model performance, reduce dimensionality, and enhance computational efficiency.

#### Step 7: Save Model
save up the clean and ready to deploy model
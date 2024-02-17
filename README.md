# Statistical analysis and prediction of Diabetes
This repository contains a PIMA Indian Diabetes dataset, curated for research and analysis purposes. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.

#### Dataset Description
The datasets consists of several medical predictor variables and one target variable.

Missing attribute values: none

Class distribution: 500 non-diabetic, 268 diabetic records

#### Features
1. Pregnancies
2. Glucose
3. BloodPressure
4. SkinThickness
5. Insulin
6. BMI
7. DiabetesPedigreeFunction
8. Age
9. Outcome

#### Notebook
This notebook predicts non-diabetic and diabetic records.
Notebooks has following :
1. Import the dataset
2. Exploratory data analysis 
-  Detection of missing values
- Statistical analysis
- Outlier removal
- Handling the imbalanced dataset 
- Data scaling
3. Model building and selecting the model with highest evaluation metric
4. Save the finalized model 
5. Validate the model

Classifer with highest accuracy was saved and used for validation.

#### Citation
Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.

#### License
CC0: Public Domain

#### Disclaimer
This dataset and classifier is not intended for diagnostic or clinical use. It is crucial to consult with healthcare professionals and use validated medical data for any medical-related decisions.


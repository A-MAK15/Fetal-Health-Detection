## Fetal Health Prediction Model
This repository examines the fetal health state based on the results that were produced in the 
cardiotocogram (CTG) procedure that was done on various mothers. The results from this 
procedure includes but are not limited to the baseline value, accelerations, fetal 
movement, uterine_contractions, light_deceleration, sever_deceleration of the fetal and 
mother. These CTG results are utilized to determine the health state of the fetal of which 
the main purpose of this repository is to dissect the process that was followed to produce a 
quality model that can predict the fetal’s health.

### Features 
For a brief background about the data, this data is about the conditions that are taken 
into consideration when detecting fetal health in order to prevent child and maternal 
mortality. A non-invasive procedure called Cardiotocogram (CTG) is done on the mother 
by placing an ultrasound on the mother's abdomen and the results of those ultrasound 
are analysed and recorded then a decision about the health of the fetal is deduced.

The dataset was extracted from Kaggle and it did not contain any null values but there 
was one modification that was done on the dataset which was to find and delete the 
duplicates hence they might have a certain effect on the accuracy of the model. Based 
on the purpose of the model in question, the decision tree is the modeling technique that 
was utilized.

There was no need to implement data conversion hence all the data was in numerical 
form and the normalization of the features was not needed as it did not have any impact 
on the accuracy of the model when it was attempted.

### Requirements
To run the project, ensure you have the following installed:

- **Python 3.8+**
- **Libraries**
  - **pandas**
  - **numpy**
  - **matplotlib**
  - **seaborn**
  - **scikit-learn**

### Results
The results of the CTG procedure was utilized as features in this data model to predict the 
fetal health state, this fetal health state is the target. The data is split into 80% training 
data and 20% of the testing data. The model is trained with the training data and when 
the model is fit, it is then tested with the data that it was not trained with of which it 
produces an accuracy of 93.85%.

### Future Work
  - Incorporate various kinds of features to strengthen the accuracy of the model
  - Explore various kinds of modeling techniques with an intention to increase the accuracy of the model.
  - Integrate the model into a web application for real-time predictions.

# Parkinsons-Disease-Predection

This is a Health Care project to predict certain diseases.  Parkinson’s disease can neither be diagnosed nor treated. The doctor assesses the symptoms and decides based on the medical history. The idea of this project is to predict the risk of having the disease according to some attributes, such as the patient’s average vocal fundamental frequency. Those with a higher risk of developing Parkinson's will require constant medical attention and that will slow down the progression of symptoms, thus alleviating pain and suffering.

* In this project I will carefully analyze a dataset of 195 records to predict the likelihood of having Parkinson’s disease using an XGBBoost model

### Task:
* IMport Libraries
* Read and explore data
* Understand the relationship between different variables through visualization
* Carry out feature selection to determine the variables that are most related to the target output.
* Build a machine learning model
* Use metrics, such as accuracy and ROC curve, to evaluate the model’s performance.
* Save the trained model into a file to be used for future predictions.

### Dataset
* Url: https://www.kaggle.com/datasets/wajidsaw/detection-of-parkinson-disease

### Dataset attribute:
* MDVP:Fo(Hz) - Average vocal fundamental frequency
* MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
* MDVP:Flo(Hz) - Minimum vocal fundamental frequency
* MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency
* MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
* NHR,HNR - Two measures of ratio of noise to tonal components in the voice
* status - Health status of the subject (one) - Parkinson's, (zero) - healthy
* RPDE,D2 - Two nonlinear dynamical complexity measures
* DFA - Signal fractal scaling exponent
* spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

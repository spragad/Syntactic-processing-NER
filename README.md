# Named Entity Recognition - Continuous Random Field (CRF) model

## PROBLEM STATEMENT

"BeHealthy" is a health-tech company and has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.
So, companies like "BeHealthy" are providing medical services, prescriptions and online consultations and generating huge data day by day.

The following snippet of medical data may be generated when a doctor is writing notes to his/her patient or as a review of a therapy that he or she has done.
"The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy."

As we can see in this text, a person with a non-medical background cannot understand the various medical terms. We have taken a simple sentence from a medical data set to understand the problem and where one can understand the terms 'cancer' and 'chemotherapy'. 

## DATASET

There are four datasets provided to process, which are as follows:

- train_sent
- test_sent
- train_label
- test_label

The train dataset is used to train the Continuous Random Field (CRF) model, and the test dataset is used to evaluate the built model.
 
## SOLUTION

There are eight major tasks that we need to perform. They are as follows:

- Data preprocessing
- Concept identification
- Defining the features for CRF
- Getting the features words and sentences
- Defining input and target variables
- Building the model
- Evaluating the model
- Identifying the diseases and predicted treatment using a custom NER


 

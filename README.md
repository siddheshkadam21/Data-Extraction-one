## Data-Extraction-one
# Imported the necessary libraries.
# Load traning data
# Loading spacy english model
# Writting Function
- Which will take tranning data as a input
- We will add name entity recognition at thr last position in pipeline
- Then we will add custom lable in pipeline
- Preaparing data for traning
- We have disable all the pipeline components expect name entity recognition
- We are going to do 10 iteration, the traning data is shuffled to ensure the model doesn't make any generalization based on other example.
- we are adding a dropout od 0.2 which means that each feature or internal representation has 1/5 likehood of being approach

# Saving the model 
The model is saved in the same folder
# Load the saved model
- Testing first resume of traning data set
- Passing resume to the model
# Testing model on unseen data/Resume
- Opening resume
- extraction text text using getText()
# Passing extracted text to model for summary

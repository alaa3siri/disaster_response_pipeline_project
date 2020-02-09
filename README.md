# Disaster Response Pipeline Project
This project is to classify disaster response messages through machine learning. 

### The process was carried out as follows:

1. Data Processing
    Assessing and cleaning the data, so that it can be utilized by machine learning algorithms.
    
2. Model training
    Data was passed through a pipeline and a prediction model is made.
    
3. Prediction and Visualization
    

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

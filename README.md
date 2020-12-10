##End to End Flask web application that predicts the price of Flight given the details of the Fly.
Deployed to Heroku.##

- https://flightprice111.herokuapp.com/predict

- Kaggle dataset FlightPrice dataset

- Regression Problem

- Exploratory Data Analysis

- Fit model using Random Forest 

- Hyper Parameter Tuning using RandomizedSearchCV
      - Accuracy score of 79.8 %

- Save to Pickle

- Create a Flask Application for providing Users an interface to enter Details

- The Application, loads the model from the pickle file 
    - and returns Fight Ticket's predicted price.

- Deployed to Heroku

- Step followed in deploying Flask app to Heroku
    - Create a new folder (FlightPrice) and copy all the application files there
    - Create Procfile, requirements.txt files in the same folder
    - Install Heroku CLI.
    - In command prompt login by entering heroku login 
    - cd to FlightPrice folder
    - git init
    - git add .
    - (can check the remote using)  git remote -v
    - git commit -m "Initial push of Flight Price Predictor flask app code to Heroku"
    - heroku create flightprice111
    - git push heroku master
    - Verifying deploy... done. To https://git.heroku.com/flightprice111.git
    

# The demo website: 
- https://data-visualization-analysis.herokuapp.com/

# Getting Started
This is a flask app that visualizes data from the world bank csv file. Data is downloaded and then visualized using Plotly.

This is a project in development for the Udacity Data Scientist Nanodegree.

## First, installing neccessary libraries
Open terminal, and run 
  - pip install pandas, flask, gunicorn  
Or we can run
  - pip install -r requirements.txt

Save dependancies into requirements.txt
  - pip freeze > requirements.txt

## Secondly, creating Profile is prior to deployment
Create a file without extension, and type
  - web: gunicorn worldbank:app

## Thirdly, login to heroku account:
- heroku login
- heroku create app-name

## Fourth, move to the project location, and deploy the project
- git init
- git add .
- git commit -m "first"
- git push heroku master


For website maintenance, run the following commands
- heroku git:remote -a app-name
- git add .
- git commit -m "first"
- git push heroku master
- // git add . && git commit -m "first" && git push heroku master

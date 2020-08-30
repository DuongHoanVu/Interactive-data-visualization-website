Firstly, creating Profile is prior to deployment


Secondly, run the following commands:
- heroku login
- heroku create app-name

- pip freeze > requirements.txt

- git init
- git add .
- git commit -m "first"
- git push heroku master


For website maintenance, run the following commands
- heroku git:remote -a app-name
- git add .
- git commit -m "first"
- git push heroku master
- # git add . && git commit -m "first" && git push heroku master

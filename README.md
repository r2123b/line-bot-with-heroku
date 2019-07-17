# Line Chatbot using Heroku as a server

### File Description
1. `Procfile` is a config file for Heroku:

    e.g. ```web: gunicorn test:app```, which tells Heroku your app is a web service and your entry application is `test` that in my project is for `test.py`

2. `requirements.txt` is a list of packages you want to install while pushing code up to Heroku server

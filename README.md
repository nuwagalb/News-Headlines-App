# News-Headlines-App

An application that displays up-to-date news headlines, weather information, and currency exchange rates to users.

#### Badges

[![Build Status](https://travis-ci.org/nuwagalb/News-App.svg?branch=master)](https://travis-ci.org/nuwagalb/News-App) [![Coverage Status](https://coveralls.io/repos/github/nuwagalb/News-App/badge.svg?branch=master)](https://coveralls.io/github/nuwagalb/News-App?branch=master) [![Maintainability](https://api.codeclimate.com/v1/badges/288abda30d16f0c3fcb5/maintainability)](https://codeclimate.com/github/nuwagalb/News-App/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/288abda30d16f0c3fcb5/test_coverage)](https://codeclimate.com/github/nuwagalb/News-App/test_coverage)

#### Author:

Albert Nuwagaba

#### Technologies and Tools used to develop this App

1. Python
2. VSCODE (for editing and debugging)
3. Flask micro framework

#### API's used
- OpenWeatherMap API
- Open Exchange Rates API

#### The application is Hosted on Heroku on the link below.
https://news-headlines-app.herokuapp.com/

#### Set up project to get it up and running

clone repository from link below

1. $ https://github.com/nuwagalb/News-App.git
2. $ cd News-App

#### Set up Virtual environment by running commands below

- virtualenv -p python3 venv
- source venv/bin/activate (for linux)

#### Install all project dependencies by running the command below.

$ pip install -r requirements.txt

#### To run the unit tests invoke/run the command below.

$ nosetests or pytest

#### or for detailed output on unit tests run with verbose.

$ nosetests --with-coverage --cover-erase --cover-package=headlines --cover-html

#### To run the application invoke the command below.

$ python headlines.py

#### Now that the server is running , open your browser and run one of the links below.

$ localhost:5000 or 127.0.0.1:5000

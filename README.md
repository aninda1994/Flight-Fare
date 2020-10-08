# Flight Fare Prediction

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)
  
## Demo
![Screenshot from 2020-10-08 11-27-18](https://user-images.githubusercontent.com/68215691/95422549-21e20080-095d-11eb-97e3-bbf5c103d00b.png)
![Screenshot from 2020-10-08 11-27-27](https://user-images.githubusercontent.com/68215691/95422622-463ddd00-095d-11eb-85ee-b40b41971114.png)

https://flight-fare-prediction-ml.herokuapp.com/

## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Motivation
What to do when you are at home due to this pandemic situation? I made this project because I wanted to get more hands on expierence on Machine learning and Data Science

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:
```bash
pip install -r requirements.txt
```
## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

![Screenshot from 2020-10-08 11-27-27](https://user-images.githubusercontent.com/68215691/95422622-463ddd00-095d-11eb-85ee-b40b41971114.png)
Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt

## Technologies Used
![python-logo-master-v3-TM-flattened](https://user-images.githubusercontent.com/68215691/95423773-48a13680-095f-11eb-8a49-a68744bf7609.png)
![1200px-Scikit_learn_logo_small svg](https://user-images.githubusercontent.com/68215691/95423801-522a9e80-095f-11eb-87cd-c98a087fd335.png)
![Gunicorn_logo_2010 svg](https://user-images.githubusercontent.com/68215691/95423884-6d95a980-095f-11eb-879b-6a9ab561b7f1.png)
![1200px-Pandas_logo svg](https://user-images.githubusercontent.com/68215691/95423964-8a31e180-095f-11eb-93e6-e8895f6b0c57.png)
![heroku](https://user-images.githubusercontent.com/68215691/95424066-bcdbda00-095f-11eb-8d1b-975fa544fa2a.png)
![1280px-Flask_logo svg](https://user-images.githubusercontent.com/68215691/95424205-eeed3c00-095f-11eb-8fbb-78fff2870164.png)


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/aninda1994/Flight-Fare/issues) here by including your search query and the expected result

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 


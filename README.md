# Ware house appreal Detection using yolov5 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)



## Demo
Link: [https://fuel-efficiency-prediction557.herokuapp.com/](https://fuel-efficiency-prediction557.herokuapp.com/)

[![](https://i.imgur.com/2DkhSnF.jpg)](https://fuel-efficiency-prediction557.herokuapp.com/)
[![](https://i.imgur.com/Gh06Sbf.jpg)](https://fuel-efficiency-prediction557.herokuapp.com/)


## Overview
This is a Flask web app which detects helimate an image.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning and Deep Learning models to get most out of it. I came to know mathematics behind Object detection Yolov5. Finally it is important to work on application (real world application) to actually make a difference.


## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── .circleci 
│      ├── config.yml
├── com_ineuron_utils 
│      ├── __init__.py
       ├── utils.py
├── tests 
│      ├── __init__.py
       ├── test_script.py       
├── templates
│      ├── index.html
├── Procfile
├── README.md
├── main.py
├── config.yml
├── Dockerfile
├── faster_rcnn_R_50_FPN_3x.yaml
├── ObjectDetector.py
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://curiousily.com/static/dff66fd0972574ae284f7df9533d369f/3e3fe/detectron2-logo.png" width=280>](https://detectron2.readthedocs.io/en/latest/)  




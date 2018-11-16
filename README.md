# Unity Web Application
The goal of this project was to create a web application that would showcase the projects from the Made With Unity showcase.
I chose to build a Python based application using Flask. It tracks the user's GET requests so that each project is visited before repeating projects, and uses web scrapping to gather the data on specific projects.
<br>
All data was obtained from: https://unity.com/madewith

## Getting Started

Download the source code into a folder. Jump to the Prerequisites below to ensure the necessary installations are complete.
Once they are complete, continue to Deployment. 

### Prerequisites

You should have Python installed on your machine first.
<br>To check if it's installed, try running the following command in your terminal:
```
python --version
```
If you need to download it, go to: https://www.python.org/

Download Flask: http://flask.pocoo.org/
```
pip install Flask
```
Navigate to requirements.txt, a text file in the repo. This contains the libraries and versions needed for this application.
Install them by running:
```
pip install libraryname
```


## Deployment

I compiled my web application from my terminal. From the command line, cd to your source code's
directory. You can then run the following command to deploy your web app. Go to http://localhost:5000/ to view it.
```
python app.py
```

## Built With

* [Python](https://www.python.org/) - Programming Language
* [Flask](http://flask.pocoo.org/) - Web framework
* [Sublime Text](https://www.sublimetext.com/) - Text editor
* [BootstrapCDN](https://www.bootstrapcdn.com/) - Used to load CSS


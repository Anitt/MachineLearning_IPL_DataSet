# MachineLearning_IPL_DataSet
Machine learning , CLustering , Python , Data Analysis , Data Modelling , Visualization using D3.JS
# Project Description

Analyzing the player skills and identifying the right players for the team is crucial for all sports. It becomes even more important when there are lot of players competing for a single spot. In order to ease the scouting process, we have created a visualization system with help from machine learning algorithms for the [IPL](https://en.wikipedia.org/wiki/Indian_Premier_League) data. Coaches/Managers can make use of the various visualizations to find the right players for their team. 

Coaches/Managers can make use of this system to analyze the statistics about the players and compare how they fare against other players. They can also make use of this system to analyze how their team has performed over the years and find the areas to be strengthened. The visualization systesm is built following the UI design principles. The system also allows the user to apply various customizations to their 
results. 

# Technologies

**Languages:** Python, JavaScript, HTML, CSS

**Libraries:** Node.js, pandas, SciKit Learn, NumPy, Flask, d3.js, Bootstrap

**Tools:** Heroku, Git, PyCharm, Sublime Text

# Dataset

Kaggle Link: https://www.kaggle.com/harsha547/indian-premier-league-csv-dataset/data

# Architecture

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/architecture.PNG)

# Installation

### 1) Clone the repository
* Make sure git is installed locally
* To clone the repo: `git@github.com:visakan4/Visual_System_IPL_ML.git`

### 2) Prerequisites
#### 2.1) Windows Prerequisites
* `py -m pip --version`
* `py -m pip install --upgrade pip`
* `py -m pip install --user virtualenv`
* `py -m virtualenv env`
* `.\env\Scripts\activate`


#### 2.2) Mac/Unix Prerequisites
* `python3 -m pip --version`
* `python3 -m pip install --upgrade pip`
* `python3 -m pip install --user virtualenv`
* `python3 -m virtualenv env`
* `source env/bin/activate`


# Screenshots

### Streamgraph

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/StreamGraph.png "Stream Graph")

### TreeMap

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/TreeMap.png "Tree Map")

### Line Graph

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/LineGraph.jpg)

### Stacked Bar Graph

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/StackedBarGraph.png)

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/StackedBarGraph2.png)

### Clustering

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/clustering.PNG "Clustering")

### Forced Layout

![alt text](https://github.com/Anitt/MachineLearning_IPL_DataSet/blob/master/images/ForcedLayout.jpg "Forced Layout")


### 3) Start server

* Install project dependencies with this line : `pip install -r requirements.txt`
* Run this in termimal to start the backend server ` gunicorn index:app --log-file=-`



### 4) Test app
* In the browser, test the index route where the server is running
For example: If the server started on port 8000, then the root path `localhost:8000` should return the text "test index route"

# Recommendations-with-IBM

### Table of Contents
1. [Project Motivation](#motivation)
2. [The Process](#process)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#license)

## Project Motivation<a name="motivation"></a>

In this project, the objective is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like. Below is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![IBM-Watson-Article-Recommendation](IBM-Watson-Article-Recommendation.png)

Though the above dashboard is just showing the newest articles, we could imagine having a recommendation board available here that shows the articles that are most relevant to a specific user.

In order to determine which articles to show to each user, you can create your own account to become a part of their community, and get a better understanding of their data by creating an account on the platform [here](https://dataplatform.cloud.ibm.com/).


## The Process <a name="process"></a>
The project is divided into the following tasks:

### I. Exploratory Data Analysis

Before making recommendations of any kind, we will need to explore the data we are working with for the project. 

### II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. These are the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

### IV. Content Based Recommendations
Using NLP, implement a content based recommendations system.

### V. Matrix Factorization

Finally, complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with. Finally, discuss which methods we might use moving forward, and how well the recommendations are working for engaging users.

## File Description <a name="file"></a>

* **Data**: This folder contains data from [World Bank](https://data.worldbank.org/indicator/SP.RUR.TOTL.ZS?view=chart) in csv format.
    * `articles_community.csv` : Python module for rendering html pages.
    * `user-item-interactions.csv` : Package initilization file
    
* **Unit_Tests**: This folder contains the package files.
    * `project_test.py` : Python module for rendering html pages.
    * `top_5.p` : Package initilization file.
    * `top_10.p` : Folder containing images.
    * `top_20.p` : Folder containing html file.
    
* **Recommendations_with_IBM.ipynb**: Folder contaning a python module.

* **Profiling_Report- df_content.html**: file that specifies the commands that are executed by the app on startup.

* **Profiling_Report- df.html**: This folder contains the plots generated using Plotly. These images are also displayed in the web application deployed on Heroku. 
    
* **user_common_article**:  This file contains the list of python libraries needed to run this web application.


## Licensing, Authors, Acknowledgements <a name="license"></a>
This web application was developed as part of the [Udacity Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

Author: Rahul Gupta Copyright 2021

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

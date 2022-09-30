# Link to the website: [https://my-world-bank-pv.herokuapp.com/]

# World Bank Dashboard

This app uses flask to visualize data from the world bank website on the land use of top 10 economies

This project has been developed as part of Udacity Data Science Nanodegree and the guidance provided within the course have been followed to produce the final product
The app utilizes plotly to plot four vizualizations, namely 2 line charts, a scatter plot and a bar chart, to visualize land use
World bank API has been used to get the data

# Getting Started
This flask app can be used as a template for visualizing your own data. Use the template to enhance your professional portfolio.

# Prerequisites
python3

To install the flask app, you need to open a terminal and type the following:

```
    py -m pip install flask
```

python packages in the requirements.txt file

Install the packages with

```
    pip install -r requirements.txt
```

To run a local version of the code:

Open *worldbank.py*

Add the following line:

```
app.run(host='0.0.0.0', port=3000, debug=True)
```
    
Open the terminal and execute the following command
    
```
py worldbank.py
```

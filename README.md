APAC Tech Hackathon Northern Trust Team-5

The Project consists of the use of various libraries pandas, matplotlib, plotly and dash.

Key Features

In this project we generate various graph for Currency Conversion, there are over 40-50 currencies that were compared with USD($) currency.
In this project users have the option to select weekly, monthly, quarterly, and yearly charts showing how the particular currency changes with respect to USD.
The user can also select the year from the dropdown menu and plot the data.
Displayed the date on which the rate was highest with the actual rate and date on which the rate was lowest along with the rate.
Displayed a UI screen to display all currencies along with the short code and description.
Responsive Cursor which shows Date and value of currency.
There is a slider which shows how we are viewing the data overall.
Technologies

Plotly
Pandas
Dash
Python
Libraries Used

Dash
Plotly
Matplotlib
Pandas
Numpy
Process

We have preprocessed the data and found out the null values and filled the null values with its preceding date's value.
Data Preprocessing is done by file "Nt pb.py" file
Main code is run by "northern trust dash.py", The excel files generated in the datapreprocessing file(NT_pb) is accessed in the main file.
Setup

All your excel files, requirements.txt and all .py files must be in the present source current working directory.
Install all the requirements file by
pip install -r requirements.txt
Then Run "northern trust dash.py" or ".ipynb" file`
Open the URL generated on the bottom on screen
Then click on the url: http://127.0.0.1:8055/
The Interactive Dashboard will be visible on the new tab

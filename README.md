# INF 554 Assignment 1

Google sheet source link
https://drive.google.com/open?id=1zAP6AXge8PT-rv_Ga212EOFBG6YYaZ-AjZ7iWK_hrDY

Introduction

The goals of this assignment were as follows.
1. Understand and explore UN datasets as a source of data. 
2. Create the same visualization with three different methods. (1. Embedded Image, 2. iframe 3.Built by browser using JS and Google chart api)
3. Make a submission on github in the form an index.html page that will allow the user to understand what data was chosen and why was it chosen and to be able to infer meanigfull conclusions from the data.

The data was taken from the following link
http://data.un.org/Data.aspx?q=population+&d=PopDiv&f=variableID%3a12

It is a population sensus of combined (male and female) in thousands for the following ten countries 
China
France
India
Portugal
Singapore
Spain
Sweden
Switzerland
United Kingdom
United States of America

for the year starting backwards from 2018 for the last five years with an interval of ten years.

There are a total of 50 data points.

A simple HTML page was created which contained three charts and a brief description of the data used.

The first step was loading the data into google sheets and using a pivot table to organize the data into a suitable format. Next step was to utilize the inbuilt chart editor to create a line chart.

Since, It is a data over time and with only three columns, line chart was an appropriate depction menthod. The X-axis was used to denote year, Y-axis for populationa and the coloured lines for Countries.

The image was loaded with a local source onto the webpage, and the the same image was published from google sheets as an embedded iframe object. 

For the third part, the data was hardcoded onto the js part of the index.html and then using google charts api was used to create a line chart.


Conclusions

1. Three countries do not even register on the graphs. Showing that Singapore, Portugal,Sweden and France have populations so low that operate on a differnet magnitude as compared to larger countries like India and China.

2. Both China and India showed an increasing population trend but in the recent years china rate decreased and India will most probably overtake it in the comming years.

3. United states a developed country does show an increasing population but unlike India and China it is not exponenetial.

4. A line chart is a good method to handle such data and Inferences and the ability to link data between Google sheets and Google chart is a usefull feature. 

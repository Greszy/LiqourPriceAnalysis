# LiqourPriceAnalysis

1. Introduction

This project presents my attempt of a data collection and analysis set up. 

I chose the wine and liqour industry as an example of the type of data that can be collected and analyzed about different types of alcoholic beverages.  This document presents all the steps I took to collect and analyze data from one of the ecommerce platforms specializing in selling wine and liqour. This project was developed for learning purposes with intent to a better understanding about how certain elements of the web work. I did not use this knowledge in any malicious way. I worked on this for learning purposes, to strenghen my knowledge about how the Web works and different ways of working with data.  

2. Website Analysis 

Before I could start collecting information about wine and liqour products I had to analyze the website to see how the responses are built that are sent back when a user makes a request to see some specific product that can be displayed on the website. For this step I used tools called Burp and Postman to analyze requests and responses responsible for getting information about the products sold on the website.

Burp allowed me to see how a request is constructed for a particular resource. After that I could use Postman to confirm that the specific request returns the required resource, in this case information about a specific product. Additionally thanks to Chrome developer tools I was able to learn that the data is past to the client in a JSON format. Thanks to this information I was able to start collecting public information about several products displayed on the website. 

3. Data Collection

Once I knew enough about the structure of the website and how the requests and responses were built I was able to start working 
on a page scraper that allowed me to automate the process of collecting product information from the website. For this I created a program in Java with the use of jsoup and JSON.simple libraries. 

The final product is a page scaper that let's me collect item information displayed on the website like name, price and volume. The requests can be so modified that they target a specific area in which the liqours and wines are sold. The same can also be done with the type of beverage. 

4. Data Storage and Analysis







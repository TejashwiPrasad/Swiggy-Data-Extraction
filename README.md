# Swiggy-Data-Extraction
This project utilizes Python web scraping techniques to extract restaurant data from Swiggy, a popular online food delivery platform. The data is then processed and cleaned using Pandas for further analysis and visualization.

Libraries Used
Requests: This library is used to send HTTP requests and retrieve the HTML content of the Swiggy website.
Pandas: Pandas is employed to manipulate and analyze the extracted data in the form of a DataFrame.
BeautifulSoup (bs4): BeautifulSoup is utilized to parse the HTML content and extract specific information from the Swiggy web pages.

Data Extraction
The Python script uses the Requests library to send a GET request to the Swiggy website, retrieving the HTML content of the restaurant pages. BeautifulSoup is then employed to parse the HTML and extract the desired information such as restaurant name, variety of food, rating, food price, and discount coupon.

Data Cleaning and Processing
The extracted data is structured and organized using Pandas, a powerful data manipulation library in Python. The DataFrame object is utilized to store the extracted information, with each column representing a specific attribute of the restaurants. Further data cleaning techniques can be applied using Pandas to handle missing values, remove duplicates, and format the data appropriately.


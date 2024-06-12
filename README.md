# Amazon-Web-Scraper-Project

## Introduction:
This project is a Python-based web scraping application designed to fetch and monitor the price of a T-shirt listed on Amazon. It utilizes the BeautifulSoup library for web scraping, the Requests library for HTTP requests, and other libraries such as smtplib, time, and datetime for additional functionalities.

## Project Overview:

1. Importing Libraries:

The project begins with importing necessary libraries including BeautifulSoup, Requests, smtplib, time, and datetime.

2. Connecting to Amazon Website:

A function is created to establish a connection with the Amazon website using the Requests library.

3. Scraping Price Data:

BeautifulSoup is utilized to extract the price of the T-shirt from the Amazon website. This information is then stored locally in a CSV file using the csv library, providing a convenient way to track price changes over time.

Data Analysis with Pandas:

The Pandas library is imported to read the CSV file within a Jupyter notebook, allowing for data analysis and visualization of price trends.
Automated Price Monitoring:

A while loop is implemented to continuously call the scraping function at regular intervals using the time library. This ensures that the price data remains up-to-date without manual intervention.
Price Change Notification:

Lastly, a function is developed to send a notification via email or other means whenever there is a change in the price of the T-shirt. This feature provides timely updates to the user, enabling informed purchasing decisions.
Conclusion:
The Amazon Web Scraper project demonstrates the practical application of web scraping techniques in monitoring product prices on e-commerce platforms. By leveraging Python libraries such as BeautifulSoup and Pandas, users can automate the process of gathering and analyzing price data, ultimately facilitating smarter shopping decisions.

Note:

The project can be further enhanced with features such as error handling, user input validation, and additional data analysis capabilities.
Ensure compliance with Amazon's terms of service and respect the website's policies while conducting web scraping activities.





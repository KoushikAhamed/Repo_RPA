��# Repo_RPA

The robot is used to automate the process of https://www.researchgate.net/ literature collection for the user-defined topic. Result of the process is an email with attached excel with info about each found article.

Used libraries
selenium - web-browser automation
pandas - work with datatables
smtplib \ email - email creating and sending
wcm - function for working with Windows credential manager
Algorithm
User defines a topic, number of pages, and receiver of the resulting email
Robot creates links for each search results page
Robot collects links to the articles from each page
Robot scraps article's info and downloads source docs if available
Robot writes all info to excel and sends email

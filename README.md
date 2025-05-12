# URL_Webscrape
Web Scraping Script for Audit Exploration Tool

This Python script uses various libraries to access HTML elements on the Massacusetts State Auditor's Office website. 
https://www.mass.gov/lists/all-audit-reports-2011-to-today

Script accesses the webpage, grabs the most recent year, and iterates through all elements in the year. 

Year of release, audit title, and audit webpage URL are extracted for audits from 2023 to present and put into a pandas dataframe. 
The dataframe is then exported as an Excel file. 

The file is currently being used as a datasource for OSA's Audit Exploration Tool Tableau dashboard. 

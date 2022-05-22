# Extract, Transform, Load

## Summary

In order to prepare data for a hackathon, movie data was extracted from three sources, transformed and cleaned, and loaded into a SQL database for use by participants.

## Tools

 - Python 3.9.7
 - Jupyter Notebook
 - pgAdmin 4
 - PostgreSQL 11
 - Wikipedia 
 - Kaggle

## Method

 - Utilizing the Pandas library, data was loaded from a json extracted from Wikipedia and two csv sources from Kaggle and MovieLens.
 - Data was then analyzed and transformed to reduce redundancy, and present clean and clear data for hackathon participants
 - Data was merged into a single coherent Pandas DataFrame containing all relevant information
 - Using the sqlalchemy toolkit, data was then loaded into a SQL database to be presented to participants.
 - The Extract-Transform-Load pipeline was implemented into one reusable function, in order to keep data up-to-date on a daily basis.


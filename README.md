This following Azure Data Engineering pipeline repository is my own excercise from a tutorial created by RutujaKajam95 (you can search her github account) where she posted 
her end to end pipeline creation steps in youtube: https://www.youtube.com/watch?v=J1cyf5B1wWU

This is a practice for creating a Data Engineering pipeline using Microsoft Azure environment. These includes various softwares consisting of:
  1. Azure Data Factory
  2. Azure Databricks
  3. Azure Data Lake Storage gen2 / Storage Account
  4. Microsoft Power BI
  5. Azure VM Instance on Windows 10 OS

You need to create a free Azure Cloud account first for accessing all the Azure modules including Azure Data Factory, and the Azure Data Lake Storage 2. 
The Azure VM Instance and is only needed when you cannot install Microsoft Power BI desktop on your local device (eg. you're using MacOS, etc).

Once you have the Azure cloud account, you can access all setup all the required apps from the marketplace and run the 2 existing ipynb files in this repository using Databricks.
The template for this pipeline is using Medalion Architecture which is commonly known for its effectivenes on streaming data using 3 different layers called Bronze, Silver, & Gold.
Each layer have their own dedicated functions, Bronze is purposed to extract raw data to the database, Silver for data cleaning, Gold for data transformation and sink data to the target platform.

# 🏃🏽‍♀️Boston Marathon Data Project

## Objective
In this project, I scrapped and analyzed data from the Boston marathon. The project steps include:

1. Scrapped data from the Boston Marathon Data website and loaded into a Dataframe for further processing.
2. Cleaned and transformed the data using Python on Jupyter Notebook.
3. Data analysis
4. Developed a dashboard on Tableau.

The sections below will explain additional details on the technologies and files utilized.

## Table of Contents

## Dataset Used

This project uses the 2024 Boston Marathon data which include fields capturing total time, age group, team, state, and time splits.

More info about dataset can be found in the following links:

* [Data Dictionary](https://www.baa.org/races/boston-marathon/results/search-results)
* [Raw Data (CSV)](https://github.com/JorlynLG/Boston-Marathon/blob/main/marthon_data.csv)

## Technologies
The following technologies are used to build this project:

* Language: Python
* Extraction and transformation: Jupyter Notebook
* Dashboard: Tableau

## Step 1: Data Scraping
In this step, I scraped all the race and personal attributes of each runner from the 2024 Boston marathon website. 

[Link to the script](https://github.com/JorlynLG/Boston-Marathon/blob/main/Marathon_Data_Scraping.ipynb 'Link to script')

![image](https://github.com/JorlynLG/Boston-Marathon/assets/39361211/ae8fe581-94ba-4524-ae25-68f8c3bc53a5)
I started by creating a list of the urls associated with each runnner.

![image](https://github.com/JorlynLG/Boston-Marathon/assets/39361211/29e8ccf2-62c9-4d86-ae11-b8c9d4924ee5)
![image](https://github.com/JorlynLG/Boston-Marathon/assets/39361211/f4370d7f-8508-4fe1-9635-23d14598b29d)
I used the url list to extract personal and race result data on each runner. The list of variables includes: name, team, age group, state, finish time, and splits. 

![image](https://github.com/JorlynLG/Boston-Marathon/assets/39361211/fcd97dd1-b9ca-41ca-a052-213081785b0c)
I separately extracted gender information because it was not provided on the individual urls. 

Refer to the following [script](https://github.com/JorlynLG/Boston-Marathon/blob/main/Marathon_Data_Scraping.ipynb 'Link to script') for more information. 

## Step 2: Cleaning and Transformation
In this step, I loaded the CSV file into Jupyter Notebook and carried out data cleaning and transformation activities prior to organizing them into fact and dim tables.

## Step 3: Analysis

## Step 4: Dashboard

# Feature Engineering Process: Video Games Reviews Analysis

Final project of the [feature engineering course](https://mcd-unison.github.io/ing-caract/) taught in the first semester of the [master's degree in data science](https://mcd.unison.mx/) at the [University of Sonora](https://www.unison.mx/). 

The goal of this project is to perform a data analysis following a feature engineering process **to find out which video game genres, platforms and platforms families are the highest rated by the users**. The work is divided in four sections:

1. **Data extraction and data tidying processes**: Data about video games platforms and video games ratings is extracted from [IGDB](https://www.igdb.com/discover) using its [API](https://api-docs.igdb.com/#about), then, retrieved data is tydified and stored in [raw_data]() folder. Also, data dictionaries are created and stored in [data_dicts]() folder. The details are in [1_problem_statement_and_data_extraction.ipynb]().

2. **Data cleaning**: Raw data is processed, column types are adjusted, repeated and missing values are handled, and outliers detection is performed. Finally, cleaned data is stored in [cleaned_data]() folder. The details are in [2_data_cleaning.ipynb]().

3. **Exploratory Data Analysis**: An exploratory data analysis is performed over platforms and video games data. Details in [3_eda.ipynb]().

4. **Report generation**: Data is used to answer the main questions of the analyis and automatically a pdf report is generated. Images and the pdf report file are stored in [report]() folder. All the details are in [4_report_generation.ipynb]().

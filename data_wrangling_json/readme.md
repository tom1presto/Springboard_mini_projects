***********************************************
Data Wrangling Project: Using JSON datasets
***********************************************

My completed assignment is stored as Scheinert_json_exercise_working.ipynb

Open this file using Jupyter Notebook

Three tasks were attempted and completed:
  1. Identify the counties with the 10 most World Bank Projects
  
    1.1. I first loaded the data, acquired the necessary dataframe, sorted, and viewed the top 10 entries
    1.2. I was not satisfied with a whole continent being included in the country list, so extracted any continent references and re-aquired the list of top 10 countries, using only countries
  
  2. Identify the top 10 themes
  
    2.1. Top 10 themes are those seen the most often
    2.2. I acquired the nested data set from the original JSON data
    2.3. I removed entries with blank themes (text was a blank string) and reported the top 10 reported themes using the same sort and count method as in question 1

  3. Fill in the blank themes
  
    3.1. I used two methods to fill in the data, each reported separately:
      3.1.1: create a dictionary based on codes and themes
      3.1.2: sort and backfill
    3.2. Each method is followed, with the separate steps labeled and described

Each task is labeled and detailed steps explained in the comments in the file.

# Customer_call_list_cleaning
This is a guided data cleaning project based on video of Alex the Analyst


# Importing pandas library and retrieval of excel data
  import pandas as pd
  df = pd.read_excel(r"D:\Downloads\Customer Call List.xlsx")
  df

# Dropping duplicate rows
  df.drop_duplicates(inplace=True)
  df

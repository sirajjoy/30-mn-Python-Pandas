# 30-mn-Python-Pandas
Complete Python Pandas Data Science Tutorial!.csv
#for selecting new Jupitar notebook directory

import os 
path="directory where I want to save my jupitar notebook tasks"
os.chdir(path)

#Python pandas started 
https://www.youtube.com/watch?v=vmEHCJofslg&list=LL&index=4&t=313s
#Loading data into Pandas
import pandas as pd
df= pd.read_csv("filename.csv")
#or df= pd.read_excel("filename.csv")
#for txt format file       df=pd.read_csv('filename.txt", delimiter="/t")

#print(df)
#only top 3 rows showing
print(df.head(3))
#only bottom 3 rows showing
print(df.tail(3))
#Read Headers
print(df.columns)
##Read each Column
print(df["Name"])
##Read each Column top 5 observation only
print(df["name"][0:5])
print(df.Name[0:5])
##Read each column
print(df[["Name", "Type 1", "HP"]])
#Read each Row
print(df.head(4))
##Read each row
print(df.iloc[0:4])

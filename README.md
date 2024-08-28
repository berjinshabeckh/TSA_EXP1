# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('score.csv')
plt.plot(df['Hours'], df['Scores'])
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.title("Student Study Hours")
plt.show()











# OUTPUT:


![download](https://github.com/user-attachments/assets/1ec6a9cc-729e-41b1-9d44-33fc1545bf24)`




# RESULT:
Thus we have created the python code for plotting the time series of given data.

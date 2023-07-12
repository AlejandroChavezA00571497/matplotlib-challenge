# matplotlib-challenge
Module 5 Challenge for the Tec de Monterrey Data Analysis Bootcamp, Introduction to Matplotlib

Python Script that reflects information on the effectiveness of specific drug treatments on mice with cancer, applying statistical methods and graphics to aid in the report's understanding. 
First, the data is analyzed in a DataFrame, and cleaned of repeated values. Then we create a Summary Statistics table, taking Mean, Median, Variance, Standard Deviation and SEM values for the Tumor Volumes.
Then, we create a series of charts:
- Bar Chart relating Drug Regimen and number of observations, to determine the most used drugs.
- Pie Chart showing the distribution of sex among mice.
- Boxplot relating Drug Regimen and Final Tumor Volume, to find which drugs result in the smaller tumor volumes.
- Line Plot, relating timepoints, or observations, and Tumor Volume of a specific mouse, showing how a certain drug altered the Tumor Volume over time.
- Scatter Plot and Linear Regression Model, relating the weight of mice and the Average Tumor Volume. In this case, the correlation is .84, pointing to the fact that the bigger the mouse, the bigger the tumor on average.

The main file for this project is called Main_Pymaceuticals.ipynb, and exists in the Pymaceuticals folder. At the same level of the Pymaceuticals folder is the data folder, where the CSV Files required for this analysis exist.
As the file is a Jupyter Notebook File, cells are run individually, and the analysis section at the top is summary of the information.

Contributions:
- Data Analysis Bootcamp Classes
- https://pandas.pydata.org/

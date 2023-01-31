# Medical-data-visualization_project
 In this project I used the pandas and seaborn liberaries to analyze and visuzlize a sample dataset of medical data.
 
 I set to complete the following tasks:
   1. Add an overweight column to the data. To determine if a person is overweight, I first calculated their BMI by dividing their weight in kilograms by the square of their height in meters. If that value is > 25 then the person is overweight. I used the value 0 for NOT overweight and the value 1 for overweight.

   2. Normalize the data by making 0 always good and 1 always bad. 

   3. Convert the data into long format and create a chart that shows the value counts of the categorical features using seaborn's catplot(). 

   4. Clean the data.

   5. Create a correlation matrix using the dataset. Plot the correlation matrix using seaborn's heatmap(). Mask the upper triangle. 
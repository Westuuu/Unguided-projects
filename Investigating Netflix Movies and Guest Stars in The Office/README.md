# Investigating Netflix Movies and Guest Stars in "The Office"

The goal of this project is to draw conclusions with available data.\

I started by importing data from CSV file. Once it was done I created a DataFrame. I added another column with colors based on the ratings of each episode(Green - rated very high, red - rated very low). I moved on to adding another column to original DataFrame, but this time I included marker sizes that would be bigger for episodes with guests. I split the data between two DataFrames to distinquish episodes with and without guests. After that, I created a scatter plot where dots represent episodes without guests and stars represent episodes with guests. I noticed that past episode 130 viewership as well as rating began to drop. 


## Things I learned:
* Creating new columns of data based on the previous given data(Adding colors and marker sizes in this case)
* How to include 3 types of data on 2 dimensional plot
* How to express informations with 2 different markers on the same plot
* Interpreting the plot


## Ideas for future updates:
* Examine how high each season was rated
* Examine viewership of each season
* Examine ratings based on how many votes episode received
* Check which season had the most guests
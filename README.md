# Data-Mining-with-Python
Including various project using Jupyter Notebook
# Homework Assignment #1: Setup Your Workstation
# Details:
 
1. Download and install Jupyter notebook, and get familiar with the software. Create a new notebook and call it "Homework #1".

2. Review the data sources mentioned in the "Sample Datasets" video. Browse through any datasets that interest you, until you find a dataset that includes a "date" column. Download that dataset and save it in the same directory as your new notebook. (DOWNLOADED DATA SETS IS FROM KAGGLE)

3. Import the data into your notebook.

4. Use df.shape() to determine the number of rows and columns in the data.

5. Use df.head() to display a small sample of the data (~15 rows) in your notebook

6. Add a "day of the week" column  (which parses the date column and computes the day of the week automatically)

7. Add a comment to the code you wrote in step #6, explaining what that code is doing.

# Homework Assignment #2: Correlation

# Details:
 
1. Review the dataset you used in homework #1. Find two numerical columns that you think may be related.

2. Following the examples in the previous lectures, create a graphic plot of the statistical correlation between those two columns. You can use any charting/graphing technique you wish, as long as your graph makes the correlation between those columns is easy to understand.

3. Add a comment to the code you wrote in step #2, explaining what that code is doing.

# Homework Assignment #3: Apache Spark

# Details:

Should undo all pyspark installation (improper way of installation)

# Homework Assignment #4: Matrices
# Details:

Why is matrix multiplication useful? How would you use that in practice?

For this assignment, pick one of the matrix methods and apply it your any of your earlier datasets in a practical / meaningful way. Above your formulas, write an explanation (1 paragraph long) explaining how the method is useful and what kind of analysis it enables in real-life.

Stumped? Do a bit of independent research on the topic. There are many real-world applications of these processes, but there not necessarily intuitive. If the datasets you've chosen so far don't lend themselves well to matrix manipulation, pick any new dataset that does./

# Homework Assignment #5: SQL Databases

# Details:
 
1. Download SQLite or pick any other database to use for this exercise. (I prefer using SQL server)

2. Go to Kaggle and choose a historical-weather dataset (for any region) that includes temperature data, and load it into your database .

3. Within the SQL editor for your database, select all the days where the temp was less than 1 Fahrenheit than the previous day.

4. Export the results into a new CSV.

5. Import the new CSV into your notebook and display a portion of the rows as a data frame.

# Project #1: Thinking About Fake News

# Details:
 
The work you do in this project will carry forward to your final exam (project #3).

1. Go to Kaggle (or any other dataset source) and find a few (2-3) datasets that provide news headlines/articles that have been labeled as "fake news" and "real news".

2. Open up each dataset in your notebook and explore the datasets manually. Browse the rows and columns and get a firm understanding of the data.

3. Below each dataset, write your thoughts (a paragraph) for how a machine learning algorithm could use this training data to prepare itself to analyze news headlines. Specifically, elaborate:

          A. What methods you could use to review the given data and learn keywords or phrases to watch out for.

          and B. How you could apply those learnings to spotting fake news headlines in the future.


4. Perform research to identify 3-5 sources for APIs you could use to stream in news headlines in the future. 

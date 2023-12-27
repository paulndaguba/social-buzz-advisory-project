# social-buzz-advisory-project

# TASK;
# Analyse their (social buzz) content categories that highlights the top 5 categories with the largest aggregate popularity.
# There were a lot of information and in order not to get lost in the data. I had to make sure I was using the right data to answer the business questions. So I used these following steps to guide myself: Requirements gathering, Data cleaning, Data modeling.
# Relevant Datasets -  I identified Reaction, Content, and Reaction Types as our relevant data sets. All CSV files have been attached on here.
# Clarification - To clarify why I made this selection: 1. The brief carefully stated that the client (Social Buzz) wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”. 2. As explained in the data model, popularity is quantified by the “Score” given to each reaction type. 3. So therefore, what I needed was data showing the 'content ID', 'category', 'content type', 'reaction type', and 'reaction score'. 4. So, to figure out popularity, I had to add up which content categories had the largest score.
# Data Cleaning - I cleaned the data by: 1. Removing rows that have values which are missing 2. Changing the data type of some values within a column 3. Removing columns which are not relevant to this task.
# Data Modelling - I followed these steps to complete the Data Modeling; 1. I created a final data set by merging my three tables together (I used the Reaction table as my base table, then joined the relevant columns from my Content dataset, and then the Reaction Types dataset) - I used the “VLookUp” formula. 2. I figured out the Top 5 performing categories by adding up the total scores for each category - I used the “SumIf” formula


# Recommendation System - Categorize User Interests From Twitter_Data
Strategic Marketing Based on User's Interests From Twitter Data
Steps to run the notebook file:
-----------------------------------
Step 1) 
--------
Install tweepy API using the command “pip install tweepy”

Step 2) 
-------
Write the below in a separate notebook in a separate cell
import nltk
nltk.download()

a) By doing this, a pop-up box will be opened. In that pop-up box, go to models menu and search for the identifier “vader_lexicon” , “punkt” , “averaged_perceptron” and click on download.

b) In the corpora section, search for the identifier “stopwords”,"Averaged_perceptron and Punkt" and click on download.

Step 3) 
--------
Place the excel sheet named ‘Category_List.csv’ in your present working directory where the provided notebook is referred.

Step 4) 
--------
Open the provided notebook file and click on ‘Run All’ option from the ‘Cell’ menu.

Step 5)
-------
An UI dialog box would be opened. In the UI dialog box, click on browse button and
select the file name ‘User_Set_1’ and click on Open.

Step 6) 
--------
Ensure that the path is populated in ‘path of the user file’ field.

Step 7) 
---------
Click on execute button and observe the pie charts generated in the notebook file and bar
chart being generated in a separate tab.

Step 8) 
--------
Verify that the file named ‘Users_Catergory_List.csv’ gets generated that contains the
numbers of users against each category.

Step 9)
--------

Click on 'Execute' button from the UI.

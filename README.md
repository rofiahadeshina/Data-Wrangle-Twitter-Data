# Wrangle Twitter Data
## by Rofiah Adeshina


## Dataset

In this project, we are concerned about making meaningful insights from tweets on the WeRateDogs Twitter page.
Though we extracted three datasets they are not done correctly, hence the data is unclean and requires wrangling.
The data are basics tweets data from WeRateDogs Twitter archive broken including the retweet and favorite count pulled using the Twitter API.


In the assessment stage, we were able to identify the following quality and tidiness issues

**Quality**

* Contain retweets records
* tweet_id is an int instead of a string
* Irrelevant columns were dropped.
* timestamp is a string not DateTime
* column dog_breed based on image prediction from the image predictions table, 
we can get the breed of dog by carrying out a voting mechanism based on the confidence level of the model, 
by picking the breed whose prediction has the highest confidence level.
* misrepresentation of NAN as none in name, dog_breed
* Naming issues
* Replace non-descriptive name

**Tidiness**

● retweet and favorite should be part of df table and all 3 tables should be one
● doggo, floofer, pupper and puppo should be one column dog_stage


## Summary of Findings

The objective of the project was to wrangle the data from the @WeRateDogs page on Twitter. 
We wrangled the data and were able to Identify 8 data quality issues and 2 tidiness issues, all of which were addressed appropriately in the wrangle_act notebook.
At the end of the wrangling, we came up with a master dataset with 22 features and a 1994 row saved in a CSV text file twitter_archive_master_data.csv.

An exploratory analysis was also carried out on the master dataset in with full description in `act_report.pdf`


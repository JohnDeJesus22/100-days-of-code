
# 100 Days Of Code - Log

## I will be using this repo as a journal log. The code done during this challenge will reside in other repos made for those projects. Links will be provided here.

### Day 1: 3/14/18 Pi Day

**Today's Progress**: Forked #100DaysofCode challenge repo (first fork)
 and started Personality Text Classifier using a Myers Briggs data set provide by Mahek Hooda on Kaggle 
 
**Thoughts:** The data set came with two columns: One for personality type and one with fifty text elements separated by "|||". I wanted to separate them so that I had more entries to work with. The data set has 8675 rows. Had trouble separating at first, then found a function made by a Kaggle user that worked but used BeautifulSoup and re. I then tested so see if the re input with my original separater code was enough...turned out it was :). Yeah for experimenting

**Link to work:** [Data Wrangling Script](https://github.com/JohnDeJesus22/Personality-Text-Classifier/blob/master/PTCDataWrangling.py)

### Day 2: 3/15/18 

**Today's Progress**: Began Exploratory Data Analysis on melted dataset
 
**Thoughts:** Made use of the os library to change directory for the first time. Used [missingno](https://github.com/ResidentMario/missingno) bar and dendrogram to explore null values and use pandas to remove them (done before this project). Interesting to see that introverts may be proving more online text content then extroverts. Will of course explore further. EDA to be continued.

**Link to work:** [Exploratory Data Analysis Notebook](https://github.com/JohnDeJesus22/Personality-Text-Classifier/blob/master/PTCEDA.ipynb)


### Day 3: 3/16/18 

**Today's Progress**: Refined code to pull #makeovermonday tweets
 
**Thoughts:** Code was converted into functions. Need to work on keeping the irrevelant tweets that can pulled. Will create a data set of these tweets then work on the suggested machine learning model made by my teammates.

**Link to work:** [#MakeoverMonday Refined Tweet Finder Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/RefinedMOMTweetRetrieverCode.py)

### Day 4: 3/17/18 

**Today's Progress**: Continued EDA for Personality Text Classifer.
 
**Thoughts:** Updated requirements doc. Continued EDA to discover that 3/4 of the entries are introverts doing online writing! Explored the text_length of the content written and will investigate the word structure next.

**Link to work:** [Updated Exploratory Data Analysis Notebook](https://github.com/JohnDeJesus22/Personality-Text-Classifier/blob/master/PTCEDA.ipynb)

### Day 5: 3/18/18 

**Today's Progress**: Continued EDA for Personality Text Classifer Part 3
 
**Thoughts:** Updated requirements doc. Continued EDA with ECDF on text length and word counts and first Q-Q Plot on word count. Had to subset both columns due to large outliers. These will need to be top-coded for ML classifiers.

**Link to work:** [Updated Exploratory Data Analysis Notebook](https://github.com/JohnDeJesus22/Personality-Text-Classifier/blob/master/PTCEDA.ipynb)

### Day 6: 3/19/18 

**Today's Progress**: Started prepping data for classifier
 
**Thoughts:** Began prepping posts for classifer. Will start with a bag of words model fitlering out stopwords. Will have to look into dask or pyspark to run code due to file size.

**Link to work:** [Personality Classifier Beginning of Data Prep](https://github.com/JohnDeJesus22/Personality-Text-Classifier/blob/master/PersonalityClassifier.py)

### Day 7: 3/20/18 

**Today's Progress**: Experimenting with NLP on Tweets
 
**Thoughts:** Experimented a bit using code from last update on #makeovermonday tweets with nltk Tweettokenizer. Not all the lines of code are necessary due to the stemming not working well.

**Link to work:** [NLP Tweettokenizer experimenting](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/NLPwithMOMTweets.py)

### Day 8: 3/21/18 

**Today's Progress**: Start Script for Bot
 
**Thoughts:** Decided to create a twitter bot with Tweepy to automate data mining of Makeovermonday tweets. Did some initial testing.

**Link to work:** [Initial TwitterBot Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMTweetTesting%20-%20Copy.py)

### Day 9: 3/22/18 

**Today's Progress**: Setting up pull for false tweets
 
**Thoughts:** setting up pull for false tweets. Imported refined tweet pull functions and credentials into bot script.

**Link to work:** [Initial TwitterBot Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMTweetTesting%20-%20Copy.py)

### Day 10: 3/23/18 

**Today's Progress**: Pulled FalseTweets and other data. Refined and Tested Bot Script
 
**Thoughts:** Pulled the FalseTweets for this week into a csv along with the original data pull. Refined bot code so I could do a hard coded filtering and manual retweet of remaining tweets. Not 100% perfect yet.

**Link to work:** [Refined Bot Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMTweetTesting.py)
[FalseTweets CSV](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/falseTweets.csv)

### Day 11: 3/24/18 

**Today's Progress**: Began EDA of #MakeoverMonday Participants as of today.
 
**Thoughts:** Began EDA of participants. I feel I may have to investigate the data I collected since there are still extra entries that don't belong to participants. Instead they belong to advertisers of the project. 

**Link to work:** [#MakeoverMondayViz EDA](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/%23MakeoverMonday_EDA.ipynb)

### Day 12: 3/25/18 

**Today's Progress**: Continued EDA to filter out more false tweets
 
**Thoughts:** Explored different routes to clean up data. Explored totals for number of posts a participant made. Set up TweetTokenizer thinking it would help filter tweets based on the text. Then remembered a phrase participants had to use to signal their entry for the week and built on that using Rodrigo Calloni's posts. 

**Link to work:** [#MakeoverMondayViz EDA](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/%23MakeoverMonday_EDA.ipynb)

### Day 13: 3/26/18 

**Today's Progress**: Filtered out more tweets
 
**Thoughts:** Getting a system to filter out false tweets by using a dictionary matching tweeters to the number of posts. Making progress.

**Link to work:** [#MakeoverMondayViz EDA](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/%23MakeoverMonday_EDA.ipynb)

### Day 14: 3/27/18 

**Today's Progress**: Wrote function to filter and update data and falsetweets csvs
 
**Thoughts:** function sped up cleaning. Still need to explore the data to confirm removal of all fake participants. Also need to figure out how to remove tweets that do not have a viz pic.

**Link to work:** [#MakeoverMondayViz EDA](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/%23MakeoverMonday_EDA.ipynb)

### Day 15: 3/28/18 

**Today's Progress**: Refined Cleaning Code and improved data sets
 
**Thoughts:** Condensed data cleaning code. Jupyter notebook was getting overwhelming and clumbersome to use since there was too much there. Generalized the function from yesterday so column can be parameter. Dropped duplicates based on url. Had to unfortunately hardcode but it allowed me to see patterns in the false tweets text.

**Link to work:** [MOM_Condensed_Data_Cleaning_Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOM_Data_Cleaning.py)

### Day 16: 3/29/18 

**Today's Progress**: Continued Cleaning
 
**Thoughts:** Continued cleaning data set. Tried to find a subset of the strings I could use to filter more tweets at once but so far all efforts caused necessary tweets to be pulled into falsetweets csv. Will keep working at it.

**Link to work:** [MOM_Condensed_Data_Cleaning_Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOM_Data_Cleaning.py)

### Day 17: 3/30/18 

**Today's Progress**: Creating ML model script and built test data
 
**Thoughts:** Started ML model script by building training set. Will hopefully clean data tomorrow to apply classifiers

**Link to work:** [MOM ML Model Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMmachinelearningTest.py)

### Day 18: 3/31/18 

**Today's Progress**: Started building tweet classifier
 
**Thoughts:** Great Day Today! I applied regex, tweettokenizer and mosesdetokenizer to clean tweet text. Then I created a bag of words and naive bayes model from what I learned from my machine learning udemy course. 

**Link to work:** [MOM ML Model Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMmachinelearningTest.py)

### Day 19: 4/1/18 Easter and April Fool's Day 

**Today's Progress**: Testing and Assessing NB classifiers
 
**Thoughts:** Not much done since it is a holiday. Used another version of NB classifier made more for text and applied k-fold cross-validation to both versions and resulted in about 50% and a bit of variance. Will need to investigate using other classifiers.

**Link to work:** [MOM ML Model Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMmachinelearningTest.py)


### Day 20: 4/2/18

**Today's Progress**: Slightly improved accuracy with tfidf and kernel svm
 
**Thoughts:** Experimented with Tfidf and Hashing Vectorizer. No improvements using those with the two classifiers I used yesterday. Then tried SVM and Kernel SVM in combination with all three vectorizers. Kernel SVM with Tfidf proved about a 5% improvement but still dealing with a lot of false negatives.

**Link to work:** [MOM ML Model Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMmachinelearningTest.py)


### Day 21: 4/3/18

**Today's Progress**: Attempted other Relevant Classifiers
 
**Thoughts:** Used other relevant classifiers to improve yesterday's accuracy but no success. May have to consider pulling submissions form data.world. Perhaps that will be optimal...

**Link to work:** [MOM ML Model Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMmachinelearningTest.py)

### Day 22: 4/4/18

**Today's Progress**: Accessed page behind data.world login with Requests
 
**Thoughts:** Followed a tutorial from PyBites to access the submission page behind a login page with Requests. May need to improve understanding of HTML and/or turn to Scrapy to get desired data. 

**Link to work:** [Requests Login Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/RequestsLogin.py)

### Day 23: 4/5/18

**Today's Progress**: Updated Repos and Did Selenium and Scrapy Tutorials
 
**Thoughts:** Updated Repos, finished tutorial series on scrapy, and dove into some intro tutorials for Selenium per the advice of @pybites. I believe I found the html I need to access for my scraping.

**Link to work:** None

### Day 24: 4/6/18

**Today's Progress**: Pulled weekly data and updated bot script
 
**Thoughts:** Pulled Weekly data and filtered manually...Retweeted mostly all correct tweets based on the name. Need to get this ml model up and running.

**Link to work:** [TwitterBot Test Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MOMTweetTesting.py)

### Day 25: 4/7/18

**Today's Progress**: Cleaned data and studied more on Selenium and Xpath
 
**Thoughts:** Cleaned some of the data in my project and watched more tutorials on Selenium and Xpath

**Link to work:** None

### Day 26: 4/8/18

**Today's Progress**: Experimented with Selenium
 
**Thoughts:** Experimented with Selenium by testing code from the docs, a couple of my own examples, and took note of necessary html for my project.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 27: 4/9/18

**Today's Progress**: Logged in and out with selenium
 
**Thoughts:** Able to log in and out of data.world with Selenium and xpaths. So cool!

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 28: 4/10/18

**Today's Progress**: Web scraped with Selenium!
 
**Thoughts:** Was able to access desired page after logging in to data.world. Extracted names and viz pics with some slicing.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)


### Day 29: 4/11/18

**Today's Progress**: Scraping links and posts
 
**Thoughts:** Continuing the webscraping on the website I was able to extract posts and viz links based on text label. Need to access posts to generalize extraction.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 30: 4/12/18

**Today's Progress**: Refining extraction script
 
**Thoughts:** Refining extraction script to find the posts and scrap select info for each post instead of the information separating. Prove to not be as straight forward as expected but fun!

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 31: 4/13/18

**Today's Progress**: Pulled data and reviewed some more xpath and selenium docs
 
**Thoughts:** Pulled twitter data, reviewed more on xpath and html.

**Link to work:** None

### Day 32: 4/14/18

**Today's Progress**: Successful Scraping
 
**Thoughts:** Successfully scraped #makeovermonday discussion viz entry thread!! Now I need to now work on generalizing for all 16 links and clean the data.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)
[First Thread Scraped(Raw)](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/datadotworld_wk13_vizzes.csv)

### Day 33: 4/15/18

**Today's Progress**: Continued modifying scraping script
 
**Thoughts:** Improved link pulls from thread posts, but still need to improve it since it fails with inclusion of name tags. Also indirectly found a means to extract real names of participants :)

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 34: 4/16/18

**Today's Progress**: Started generalizing for discussion pages
 
**Thoughts:** Not much done today...Got all links to scrap in a list to see patterns in urls. Also began creating loop to go through all links.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 35: 4/17/18

**Today's Progress**: Looped through all viz_threads
 
**Thoughts:** Made loop with enumerate to get through all viz threads. Attempted to clean links and get real names of participates but will have to try different approaches.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)
[Full Data Scrap Attempt](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/datadotworld_full_scrap_attempt.csv)

### Day 36: 4/18/18

**Today's Progress**: Got real names of participants and created draft viz of participant activity
 
**Thoughts:** Got real names of participants. Created quick draft of @tableau viz to show participant activity with data. 

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)
[Full Data Scrap Attempt](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/datadotworld_full_scrap_attempt.csv)

### Day 37: 4/19/18

**Today's Progress**: Profile pics and adjusting links
 
**Thoughts:** Explore the patterns in html to get to the correct links for the viz submissions since they are not consistent. Started looking again at Flask tutorials and practiced a bit for future use.

**Link to work:** [Selenium Testing](https://github.com/JohnDeJesus22/WebScrapingApplication/blob/master/SeleniumTest.py)

### Day 38: 4/20/18

**Today's Progress**: Cleaning Data for new ML model
 
**Thoughts:** Taking a short break from selenium to explore my ML model for the twitter bot. Started by cleaning the data from my two CSVs.

**Link to work:** [New_ML_Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLTweetTest2.py)

### Day 39: 4/21/18

**Today's Progress**: Completed Swapping data from csvs
 
**Thoughts:** Completed swapping data from CSVs and created new copies. Tomorrow another round of building the retweet classifier for the twitter bot!

**Link to work:** [New_ML_Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLTweetTest2.py)

### Day 40: 4/22/18

**Today's Progress**: Started building new tweet classifier model
 
**Thoughts:** 2nd attempt at building twitter bot classifier. Small improvement after a little extra feature engineering combined with tfidf vectorizer and multinomial naive bayes.

**Link to work:** [Model Version 2 Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLModelTest2.py)

### Day 41: 4/23/18

**Today's Progress**: Improved variance with FE
 
**Thoughts:** Feature engineered text data more and did different prep to get the same accuracy but lowered variance. Need to look into other models and research more on text feature engineering, or maybe I just need more data?

**Link to work:** [Model Version 2 Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLModelTest2.py)

### Day 42: 4/24/18

**Today's Progress**: Pulled and Cleaned Tweet Data
 
**Thoughts:** Didn't have much time today. Pulled and cleaned tweet data to add to ml twitter bot model.

**Link to work:** None

### Day 43: 4/25/18

**Today's Progress**: Improved accuracy and variance
 
**Thoughts:** More data and some parameter tuning helped! Got mean accuracy to 77% and variance to .01! Will tune a bit more once I get even quantity reps of both classes. Very eager to try out with bot.

**Link to work:** [Model Version 2 Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLModelTest2.py)

### Day 44: 4/26/18

**Today's Progress**: Organized bot files and refined some code.
 
**Thoughts:** Created folder for twitter bot files and started to refine the code in them. Perhaps I should start making classes?

**Link to work:** [Twitter Bot Folder](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/tree/master/Twitter_Bot)

### Day 45: 4/27/18

**Today's Progress**: Built first 2 classes
 
**Thoughts:** Built a test Dog class and began building a test first for a class that will be used for the twitter bot.

**Link to work:** [Class Building Practice](https://github.com/JohnDeJesus22/Experiments/blob/master/Class_Practice.py)

### Day 46: 4/28/18

**Today's Progress**: Fixed class definition and code refinement
 
**Thoughts:** Refined some of the code in the ML and Retriever Scripts. Fixed a definition in my class related to the tweet corpus construction.

**Link to work:** [Class Building Practice](https://github.com/JohnDeJesus22/Experiments/blob/master/Class_Practice.py)

### Day 47: 4/29/18

**Today's Progress**: Continued Refining code
 
**Thoughts:** Refined code so most of the functions for the Tweets pipeline are under a single class. Began refining code in bot script to reflect this. Just having trouble importing credentials with the class function...

**Link to work:** [Twitter Bot Folder](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/tree/master/Twitter_Bot)

### Day 48: 4/30/18

**Today's Progress**: Refined ML Model code
 
**Thoughts:** Almost finished refining ML model code to a single class. Still need to fix the last bit but I am unfortunately having eye problems...

**Link to work:** [Nearly Refined ML Model](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/Twitter_Bot/RefinedMLModel.py)

### Day 49: 5/1/18

**Today's Progress**: Tested model against new tweets
 
**Thoughts:** Attempted to test model against new tweets without class structures. Need to figure out why the creation of that data frame only includes 46 of the 345 tweets pulled with tweepy

**Link to work:** [Twitter Bot Folder](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/tree/master/Twitter_Bot)

### Day 50: 5/2/18

**Today's Progress**: Need to balance training data
 
**Thoughts:** Fixed issue from yesterday. As I suspected I will need to balance my training data since there are too many false positives. Collected more data today for that.

**Link to work:** [Twitter Bot Folder](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/tree/master/Twitter_Bot)

### Day 51: 5/3/18

**Today's Progress**: Began pulling false tweets
 
**Thoughts:** Began pulling more false tweets from twitter users that product them.

**Link to work:** None

### Day 52: 5/4/18

**Today's Progress**: Pulled false tweet data
 
**Thoughts:** Pulled false tweet data and appended it to the false tweets csv. Also learned more about Big O notation and Dash.

**Link to work:** [False Tweets Collecting Script](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/Data%20Mining%20and%20Cleaning/FalseTweetCollecting.py)

### Day 53: 5/5/18

**Today's Progress**: First Retweet with ML model
 
**Thoughts:** Did first retweets for #makeovermonday bot with ML model! First retweets were with 4 tweets with 75% accurracy. Still need to tune but it feels great that this finally happened.

**Link to work:** [Model Version 2 Testing](https://github.com/JohnDeJesus22/-MakeoverMonday-Collaborative-Project/blob/master/MLModelTest2.py)

### Day 54: 5/6/18

**Today's Progress**: Repo for Regents Dashboards
 
**Thoughts:** Setup repo for Tableau Dashboards for NY math regents cluster analysis. Data prepped with pandas. Going to redo these using the Dash Python Library.

**Link to work:** [Regents Cluster Analysis Repo](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards)

### Day 55: 5/7/18

**Today's Progress**: Created First Personal Dash App
 
**Thoughts:** Created first dash app displaying question frequency of geometry #regents by cluster! Btw switching to this due to a presentation I will be giving.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 56: 5/8/18

**Today's Progress**: Styled Dash App
 
**Thoughts:** Did some styling to the dashboard. Need to figure out why the background color on the bar chart isn't changing...

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 57: 5/9/18

**Today's Progress**: Fixed Style issue and working on line chart
 
**Thoughts:** Fixed Style issue due to a silly error on my part. Testing out a line chart. Still need to work on the proper filtering.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 58: 5/10/18

**Today's Progress**: Fixed Line Chart to display correctly
 
**Thoughts:** Fixed Line Chart for geometry standard so it displays like Tableau version. Although I feel there is probably a better way to do this. Looking at more Dash tutorials for interactivity.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 59: 5/11/18

**Today's Progress**: Tested Markdown and Dropdown feature
 
**Thoughts:** Experimented with the Markdown and Dropdown interactive feature. Not sure why the markdown is not doing what it is suppose to. Will try it out again later.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 60: 5/12/18

**Today's Progress**: Created Stacked Bar for Clusters
 
**Thoughts:** Built Stacked Bar Chart for clusters to show breakdown of #geometry #regents by cluster and question type with the help of #pandas. Getting closer.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 61: 5/13/18

**Today's Progress**: Update chart with dropdown
 
**Thoughts:** Got simple bar of #geometry #standards frequency to update with dropdown but just not formatted the way I wanted. Need to figure out why change in format causes issues.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 62: 5/14/18

**Today's Progress**: Update line chart with dropdown
 
**Thoughts:** Provided a dropdown for the #geometry #regents cluster line chart. Getting better at this! Continued with more Dash Tutorials.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 63: 5/15/18

**Today's Progress**: Refined code and added summative bar view
 
**Thoughts:** Refined code so almost all filtering for dropdown is in callback functions. Created a summative view for simple bar chart in dropdown options. 

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 64: 5/16/18

**Today's Progress**: Refined code and improved filters
 
**Thoughts:** Continued to refine code. Changed stacked bar to a nested bar chart. Created filter for that bar chart and gave descriptive labels for line chart filter.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 65: 5/17/18

**Today's Progress**: Experimented with percentages and watched more dash tutorials
 
**Thoughts:** Continued learning with my dash tutorials. Trying to change simple bar chart to a bar chart of percentages of each cluster in the whole exam.

**Link to work:** None

### Day 66: 5/18/18

**Today's Progress**: Created percentage bar chart
 
**Thoughts:** Changed simple count bar chart to a percentage version with filters by #regents date. Now I got all three of my main tableau charts in one #dash layout. Next is fine tuning :)

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 67: 5/19/18

**Today's Progress**: Fixed up charts
 
**Thoughts:** Fixed error in nested bar so counts are correct, fixed percentage on simple bar y-axis, and improved hovertext on line chart.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 68: 5/20/18

**Today's Progress**: Changed line chart dropdown to accept multiple entries
 
**Thoughts:** Altered line chart dropdown to select multiple cluster inputs. Will definitely check out the correlation between these time series. There are some interesting pairings here.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 69: 5/21/18

**Today's Progress**: Touched up details and some functionality
 
**Thoughts:** Refined code a little and cleaned up minor details such as titles and some dropdown functionality.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 70: 5/22/18

**Today's Progress**: Cleaned time data from csv
 
**Thoughts:** Didn't get much time today. Got to clean up time code so it will hopefully give a cleaner display for the dropdown menus.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 71: 5/23/18

**Today's Progress**: Fixed display of exam dates in dropdown
 
**Thoughts:** Fixed display of exam dates in dropdown to just month and year. The way I changed the code messed up the line chart but I fixed it.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 72: 5/24/18

**Today's Progress**: Refined code a bit
 
**Thoughts:** Not much done since I needed to work on my presentation for an ignite talk. Did a bit of code refining.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 73: 5/25/18

**Today's Progress**: Started adding correlation functionality
 
**Thoughts:** Attempted to add a correlation function using pandas corr method on time series of two clusters. Just need to fix the code to display it.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 74: 5/26/18

**Today's Progress**: Added borders and correlation function
 
**Thoughts:** Created borders btw charts and created correlation function for pairs of cluster timeseries. So far best correlation is about -0.5. Majority of correlations checked are unfortunately closer to 0.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 75: 5/27/18

**Today's Progress**: Added repository and did more tutorials
 
**Thoughts:** Continued practice from Dash Tutorials on my course. Also created a repository for a future pdf editor for my wife's job.

**Link to work:** None

### Day 76: 5/28/18

**Today's Progress**: Setup Postgres Connections and experimented with pyscopg2 and sqlalchemy
 
**Thoughts:** Setup Postgres and pyscopg2 connection (finally lol). Then experimented with connections to postgres through pyscopg2 and sqlalchemy with a simple select * query.

**Link to work:** [Postgres Experiments](https://github.com/JohnDeJesus22/Experiments/blob/master/sqlpythonConnectionTest.py)

### Day 77: 5/29/18

**Today's Progress**: Query practice
 
**Thoughts:** Practiced some simple queries using sqlalchemy.

**Link to work:** [Postgres Experiments](https://github.com/JohnDeJesus22/Experiments/blob/master/sqlpythonConnectionTest.py)

### Day 78: 5/30/18

**Today's Progress**: Setting up for updatable bar chart
 
**Thoughts:** Returning to the dash app.Laying groundwork for a bar chart that will update based on the hover data from the line chart. 

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 79: 5/31/18

**Today's Progress**: Explored pyPDF2 module
 
**Thoughts:** Started experimenting with the pyPDF2 module. Admittedly didn't have much time since I am going to be giving my first time tomorrow.

**Link to work:** [PDF Exploration](https://github.com/JohnDeJesus22/pdfEditor/blob/master/pdfeditor.py)

### Day 80: 6/1/18

**Today's Progress**: Experimented with gensim word2vec
 
**Thoughts:** Experimented with gensim word2vec. Now I need to find some text data to apply some clustering algoritms to with this

**Link to work:**[Word2Vec Experiments](https://github.com/JohnDeJesus22/Experiments/blob/master/word2vecTest.py)

### Day 81: 6/2/18

**Today's Progress**: Visualized words from word2vec test
 
**Thoughts:** Created visualizations of test sentences using in word2vec experiment in matplotlib and plotly. Plotly again making it easy to display the words associated to each point.

**Link to work:**[Word2Vec Experiments](https://github.com/JohnDeJesus22/Experiments/blob/master/word2vecTest.py)

### Day 82: 6/3/18

**Today's Progress**: Kmeans with matplotlib
 
**Thoughts:** A little under the weather but couldn't resist doing kmeans clustering with the test sentences in matplotlib! See pics below. 

**Link to work:**[Word2Vec Experiments](https://github.com/JohnDeJesus22/Experiments/blob/master/word2vecTest.py)

### Day 83: 6/4/18

**Today's Progress**: Using Ann_visualizer
 
**Thoughts:** Tried out the ANN_visualizer library after seeing an article on it from a #linkedin connection. Tried it on my old classifier but would not display the output layer.

**Link to work:**[MLB Classifier](https://github.com/JohnDeJesus22/MLB-Baseball-Player-Classifier/blob/master/MLBPlayerClassifier.py)

### Day 84: 6/5/18

**Today's Progress**: Started doing interview questions
 
**Thoughts:** Started doing interview practice questions off a udemy course. Challenging but the fun kind of challenging!

**Link to work:**[Interview Question Solutions](https://github.com/JohnDeJesus22/Experiments/blob/master/InterviewQuestionSolutions.py)

### Day 85: 6/6/18

**Today's Progress**: Did two more interview questions on my own
 
**Thoughts:** Tackled two more interview questions that I did solo!

**Link to work:**[Interview Question Solutions](https://github.com/JohnDeJesus22/Experiments/blob/master/InterviewQuestionSolutions.py)

### Day 86: 6/7/18

**Today's Progress**: Setup markdown text and import

**Thoughts:** Going back to the #dash app. Created seperate file for markdown text and setup import for that file.

**Link to work:** [Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards)

### Day 87: 6/8/18

**Today's Progress**: Incorporated Markdown and fixed alignment issue

**Thoughts:** Incorporated Markdown into main dash app script file. Fixed an alignment issue of two charts.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 88: 6/9/18

**Today's Progress**: Work on filter function for line and bar chart

**Thoughts:** Continued working on the function of bar chart that will filter based on interaction with time series. This may lead to smoothing out the filtering in my other functions.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 89: 6/10/18

**Today's Progress**: Apply CSS to improve layout

**Thoughts:** Under the weather again but still at it! Learned some more CSS to improve the layout. Specifically used CSS to align chart instructions with respective dropdowns.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 90: 6/11/18

**Today's Progress**: Continued building interactivity for time series

**Thoughts:** Continued building function for interactivity on time series chart. Still needs some work...

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 91: 6/12/18

**Today's Progress**: Did recursion interview questions
 
**Thoughts:** Solved some coding problems on recursion and tested one function for the first time. The idea of recursion is just like how I teach it to my students in math class.

**Link to work:**[Interview Question Solutions](https://github.com/JohnDeJesus22/Experiments/blob/master/InterviewQuestionSolutions.py)

### Day 92: 6/13/18

**Today's Progress**: Did more recursion interview questions
 
**Thoughts:** Did more recursion questions. Learned about the itertools python package and some programming with memoization.

**Link to work:**[Interview Question Solutions](https://github.com/JohnDeJesus22/Experiments/blob/master/InterviewQuestionSolutions.py)

### Day 93: 6/14/18

**Today's Progress**: Continued learning memoization
 
**Thoughts:** Continued to study memoization by studying resources provide by my course and playing with code solutions to course problems.

**Link to work:** None

### Day 94: 6/15/18

**Today's Progress**: Improved time series bar chart

**Thoughts:** Improve the bar chart associated with cluster time series chart so it provides cum_sum of cluster types by question type. Still need to improve the click data interaction.

**Link to work:** [Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards)

### Day 95: 6/16/18

**Today's Progress**: Applied login and adjusted chart design

**Thoughts:** Applied authorization to my dash app using the dash_auth library. Also made a same design adjustment on previously mentioned bar chart.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 96: 6/17/18

**Today's Progress**: Fixed clickData interaction

**Thoughts:** Created a function to check the clickData json to fix the issue with my chart interactions. Found the issue and fixed the interaction. Now just have to adjust it when multiple time-series are displayed.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 97: 6/18/18

**Today's Progress**: Added Missing cluster functionality

**Thoughts:** Added missing cluster functionality to the bar charts to display clusters not assessed on #regents. Refreshed on #CSS to create a box around the message.

**Link to work:** [First Dash App](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/blob/master/DashTest.py)

### Day 98: 6/19/18

**Today's Progress**: Foundation for Web App and improvements

**Thoughts:** Refined some code, improved the bar associated time-series chart, and layed foundation files and file structure for app to go multipage thanks to awesome #plotly #dash documentation.

**Link to work:** [Regents App Repo](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/tree/master)

### Day 99: 6/20/18

**Today's Progress**: Prepping Alg1 and 2 Dashboards

**Thoughts:** Prepping scripts for the Alg 1 and 2 Regents Dashboards. Still need to prep some of the data and refine the code with functions and a class.

**Link to work:** [Regents App Repo](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/tree/master)

### Day 100: 6/21/18

**Today's Progress**: Created File for functions and tested them

**Thoughts:** Created separate file for functions and created test version of original app with refactored code. Looks so much neater. Still some more steps until deployment. Man this is fun!

**Link to work:** [Regents App Repo](https://github.com/JohnDeJesus22/NY-Regents-Cluster-Dashboards/tree/master)

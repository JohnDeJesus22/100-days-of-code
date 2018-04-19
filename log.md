
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

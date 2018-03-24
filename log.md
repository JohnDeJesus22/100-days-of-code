
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

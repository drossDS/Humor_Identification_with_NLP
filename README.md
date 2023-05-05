# Project 3 - 'Wait, was that a joke?' - Language Model Identification of Absurdist Humor and Satire
## Daniel Rossetti, Data Scientis for College University English Department

# 1. Problem Statement
This project is conducted from the standpoint of a data scientist hired by a university researching the relatability of AI chat bots and their ability to identify nuances of human language, particularly humor.  Some statements are considered funny, but are not necessarily presented as a joke.  The task is to come up with a language model that can identify humorous strings of text which are not structed in the format of a joke but are of similar structure to factual information.  Text must sourced to train and test a model which can differentiate between humorous and non-humorous statements.

**Can an NLP model be trained to recognize satire or absurdist humor?**

# 2. Project Approach
The Onion is a satirical news organization which produces news titles and news stories often relevant to real, current events that are satirical or would otherwise be classified as absurdist humor.  For clarity **news articles and titles from The Onion are not real.**  The tiles are however, formated in the format of actual news titles and articles which, from legitimate news agencies - are not humorous.

Comparing the titles of posts to the subreddit r/TheOnion against the subreddit r/worldnews (which posts news stories from actual news agencies) provides a way to compare strings of text which share many of the same formatting characteristics, but have completely different goals with respect to humor.

## 2.1 - High-level Steps
* Data Collection: Article titles from the World News and The Onion subreddits were collected
* Data Cleaning:  Titles were cleaned or removed as necessary to remove illegitimate titles and errors 
* Initial Modeling:  Some simple ensemble models were run to veryify model operability on the cleaned data
* Second-round Data Cleaning:  Information in titles that would confuse the model or make the titles easily identifiable were removed
* Exploratory Data Analysis:   
* Final Modeling:  Several models were run, a subset of those were optimized and then input into a borader ensemble model

# 3 - Description of Data

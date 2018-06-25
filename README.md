# nlp-blog-analysis

Data: http://u.cs.biu.ac.il/~koppel/BlogCorpus.htm  
Research Topic: Exploratory Analysis on Blog Posts of Different User Groups

## Part I: EDA  
The Blog Authorship Corpus consists of the collected posts of 19,320 bloggers gathered from blogger.com in August 2004. The corpus incorporates a total of 681,288 posts and over 140 million words - or approximately 35 posts and 7250 words per person.  

Each blog is presented as a separate file, the name of which indicates a blogger id# and the blogger’s self-provided gender, age, industry and astrological sign. (All are labeled for gender and age but for many, industry and/or sign is marked as unknown.)

## Part II: Preprocessing  
This part remove all the tags and dates from the XML files and only leave all the text.  

It should be noted that word-level prcessing such as stemming, punctuation removing are not included in this phase. Since we will do sentiment analysis later on, normalizing the words would probably remove some important information and lead to biased results.  

## Part III: Sentiment Analysis
The sentiment of blogs from each user is generated using the sentiment analyzer in TextBlob.  

## Part IV: Topic Modelling
Given different groups of users, we want to see if there is any difference in the topics that they talk about.  

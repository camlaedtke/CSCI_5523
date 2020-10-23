# CSCI 5523 Reddit Analysis Project

### Athentication

To scrape Reddit posts and comments, Reddit has an API called praw. To use it, follow steps in praw's quick start documentation.

https://praw.readthedocs.io/en/latest/getting_started/quick_start.html### 


### Some Potential Subreddits to Analyze

Politically charged and/or partisan subreddits
- conspiracy (1.4m)
- PoliticalDiscussion (983k)
- LateStageCapitalism (571k)
- libertarian (429k)
- republican (150k)
- socialism (296k)
- liberal (96k)
- Feminism (190k)
- anarchism (188k)
- anarcho_capitalism (216k)

General political discussion
- NeutralPolitics (337k)
- moderatepolitics (88k)

Controversial
- MensRights (281k)
- climateskeptics (29k)


Idea: build a classifier to classify comments as being from a liberal or conservative subreddit. 
- Try different methods for tokenization and dimensionality reduction (PCA, embeddings, autoencoders). 
- Naive Bayes may work well with huge amounts of data

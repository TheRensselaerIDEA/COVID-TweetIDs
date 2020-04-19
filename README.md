# COVID-TweetIDs
A dataset of tweets gathered during the 2020 COVID-19 pandemic.

As of 4/19/2020, there are ~41M tweet IDs ranging from March 17th to April 15th 2020.

## Data Sharing Format
Per [Twitter's terms of serivce for content redistribution](https://developer.twitter.com/en/developer-terms/agreement-and-policy) we provide lists of tweet IDs which can be found [here](tweet_ids). Each month of tweets gets its own folder containing one text file per hour named with the date and UTC hour.

## Collection strategy (as of 3/21/2020):
We use the twitter streaming API to collect tweets related to keywords that are related to the ongoing coronavirus pandemic.
Filter keywords were selected based on the following methods:
- A term frequency analysis was done on a random sample of 30,000 tweets collected with keywords "coronavirus" and "covid". Of the top 200 most frequent non-stopword terms, 50 were manually selected.
- Some keywords were borrowed from a [similar effort at USC](https://arxiv.org/abs/2003.07372).
- Some keywords were added based on knowledge of emerging discussion topics related to the pandemic.

**Note on keyword selection:**

While many of the keywords in our list are specific to COVID-19, there are some that are more general such as "school", "work", "sick", "testing", and "closed". By including these keywords we are casting a wider net to pick up discourse on topics that are heavily influenced by the COVID-19 pandemic but may not be directly related to the virus. We believe that this broader view is necessary in order to be able to capture the impact that the pandemic is having on society at large.

## Keyword list (as of 3/21/2020):
See [keywords.txt](keywords.txt)

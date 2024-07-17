## Data Organization
This directory holds the contents of **ArCOV-19**. These are the components:

- all_tweets: All source tweet IDs collected as part of ArCOV-19. Directory contains one tweet IDs file per day in the collection. 
- top_tweets: IDs of most popular tweets per day in ArCOV-19. Directory contains one top tweet IDs file per day in the collection. The propagation_networks directory under this directory contains the replies and retweets for the top 1K tweets per day in ArCOV-19
- search_queries.txt: List of search queries, including keywords, phrases, and hashtags, used in each period of time to collect source tweets.

## How to collect tweets starting from IDs?
- [Hydrator](https://github.com/DocNow/hydrator)
- [Twarc](https://github.com/DocNow/twarc#hydrate)
- Please follow our [guide](https://docs.google.com/document/d/1irkgPwPHiuU0gtVVv548JL4d9sjhyefgGw6BDEUeZRI/edit?usp=sharing) on how to extract the tweets content into csv files.

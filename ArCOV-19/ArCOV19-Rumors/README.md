# ArCOV19-Rumors

**Team:** [bigIR](https://sites.google.com/view/bigir) from Qatar University ([@bigIR_group](https://twitter.com/bigIR_group))

**Initial release date:** October 17, 2020

**Paper:** [ArCOV19-Rumors: Arabic COVID-19 Twitter Dataset for Misinformation Detection](https://camel.abudhabi.nyu.edu/WANLP-2021-Program/40_Paper.pdf)

ArCOV19-Rumors is an Arabic COVID-19 Twitter dataset for misinformation detection composed of tweets containing claims from 27th January till the end of April 2020. We collected 138 verified claims, mostly from popular fact-checking websites, and identified 9.4K relevant tweets to those claims. We then manually-annotated the tweets by veracity to support research on misinformation detection, which is one of the major problems faced during a pandemic. We aim to support two classes of misinformation detection problems over Twitter: verifying free-text claims (called claim-level verification) and verifying claims expressed in tweets (called tweet-level verification). Our dataset covers, in addition to health, claims related to other topical categories that were influenced by COVID-19, namely, social, politics, sports, entertainment, and religious.

## Data Organization
This directory holds the contents of **ArCOV19-Rumors**. These are the components:

- claim_verification: Verified claims, their relevant tweets (and veracity labels) and propogation networks of tweets including retweets and conversational threads. 
- tweet_verification: Verified tweets with their veracity labels, and propogation networks including retweets and conversational threads. 

# ArCOV19-Rumors Statistics 
|**Claim Verification Subset** |  |  |**Tweet Verification Subset**| |
| ------ | ------ | ------ | ------ | ------ |
| **Total Tweets** | 9,414|  |3,584| |
| False Tweets | 1,753 | (18.6%)|1,753 |(48.9%) |
| True Tweets | 1,831 | (19.4%)|1,831 | (51.1%) |
| Other Tweets | 5,830 | (61.9%)|0 | |
| Average \#tweets / claim | 68 | | 26 | |
| Tweets with Replies | 3,161 | (33.6%)|1,222 |(34.1%)|
| Tweets with Retweets | 3,810 | (40.5%)|1,629 |(45.5%)|
| Tweets with Replies & Retweets | 2,006 | (21.3%)|772 |(21.5%)|
| Average \#replies / tweet | 33 | |31| |
| Average \#retweets / tweet | 16 | |19| |


# Contact us
- [Fatima Haouari](mailto:200159617@qu.edu.qa)
- [Maram Hasanain](mailto:maram.hasanain@qu.edu.qa)
- [Reem Suwaileh](mailto:rs081123@qu.edu.qa)
- [Dr. Tamer Elsayed](mailto:telsayed@qu.edu.qa)

# Acknowledgments
This work was made possible by NPRP grant\# NPRP 11S-1204-170060, GSRA grant\# GSRA5-1-0527-18082, and GSRA grant\# GSRA6-1-0611-19074 from the Qatar National Research Fund. The statements made herein are solely the responsibility of the authors. 

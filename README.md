# FakeNewsNet
This is a repository for an ongoing data collection project for fake news research at ASU. The detail description for the dataset refers to the paper [Fake News Detection on Social Media: A Data Mining Perspective]

## News Content
It includes all the fake news articles, with the news content attributes as follows:
1. _source_: It indicates the author or publisher of the news article
2. _headline_: It refers to the short text that aims to catch the attention of readers and relates well to the major of the news topic.
3. _body_text_: It elaborates the details of news story. Usually there is a major claim which shaped the angle of the publisher and is specifically highlighted and elaborated upon.
4. _image_video_: It is an important part of body content of news article, which provides visual cues to frame the story.

## Social Context
It includes the social engagements of fake news articles from Twitter. We extract profiles, posts and social network information for all relevant users. 
1. _user_profile_: It includes a set of profile fields that describe the users' basic information
2. _user_content_: It collects the users' recent posts on Twitter
3. _user_followers_: It includes the follower list of the relevant users
4. _user_followees_: It includes list of users that are followed by relevant users

## Source Code
We will publish the Python code that are used to collect this dataset. Stay tuned.

## Data Availability
We will public the dataset soon. Due the term of service of social media platform, we are not able to public raw data of social context. We anonymize sensitive user information, and provide bag-of-word features for user profile and content, and keep social relationship of users. If you would like the raw data of user profiles and contents, please send email to **<kai.shu at asu.edu>**, and do not distribute it.

## References
If you use this dataset, please cite the following papers:
~~~~
@article{shu2017fake,
  title={Fake News Detection on Social Media: A Data Mining Perspective},
  author={Shu, Kai and Sliva, Amy and Wang, Suhang and Tang, Jiliang and Liu, Huan},
  journal={ACM SIGKDD Explorations Newsletter},
  volume={19},
  number={1},
  pages={22--36},
  year={2017},
  publisher={ACM}
}
~~~~
[Fake news detection on Social Media: A Data Mining Perspective]:<https://arxiv.org/abs/1708.01967>

(C) 2017 Arizona Board of Regents on Behalf of ASU
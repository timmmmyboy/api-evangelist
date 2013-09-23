---
layout: post
title: "Twitter Continues to Restrict Access to Our Tweets"
url: 'http://apievangelist.com/2012/06/29/twitter-continues-to-restrict-access-to-our-tweets/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/twitter-access.png'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-access.png" alt="" width="200" align="right" />

Twitter has become a global communication platform, allowing anyone in the world to express anything, from simple everyday thoughts, to ideas that some say have the potential to be the seeds of revolution. Twitter’s success was made possible because of open access to Twitter via the web and mobile phones via either SMS or native apps--with a large portion of this access made possible via an open Twitter API.

While the Twitter API is still showcased as an important part of the platform, access via the API is certainly not what it used to be.

While most every feature on Twitter.com is accessible via the API, overall access has been diminished through what is known as “rate limiting”. Rate limits began in 2007, to help limit the load on Twitter servers by reducing the number of calls anyone can make in an hour. But over 6 years these rate limits morphed into not just hourly limits, but to restricted access to Twitter increasingly valuable data stores--something that is not at all related to server stability.

##  Restricting Access

As the importance and value of the Twitter data grows, API access limits have become an vital tool for Twitter to tame the Twitter API ecosystem. Twitter has also slowly establish 100% control over web and mobile clients, while also setting the stage for the commoditization of Tweets, creating a new ecosystem where only sanctioned firehose partners are allowed to provide API access.

While the Twitter firehose began as a way to provide wider access to developers, and not as a monetization strategy, it has become just that--a way for Twitter to monetize each and every Tweet, leaving access to Twitter data looking something like this:

**Provider**
**Access**
**Cost**
**License**

**Twitter REST API**
350 calls per hour and 1500 total Tweets via search and 3500 total for a user's timeline
FREE
Display

**Twitter Streaming API**
400 track keywords, 5,000 follow user ids, and 25 0.1-360 degree locations
FREE
Display

**DataSift**
100% Firehose Access
Pay as You Go w/ 3K, 5K, 10K, 15K monthly tiers
Analysis Only
No Display

**Gnip**
1-2%, 10% or 100% (filtered) Firehose Access
Up to 50K / month depending on needs
Analysis Only
No Display

As rate limits have evolved from hourly limits into overall data limitations, access has shifted to firehose partners. Most recently it has been handed to the two sanctioned firehose partners, slowly reducing access to Twitter’s API, and its value to developers.

##  Selling Access

In the past, even with hourly rate limits, developers were able to navigate through a Twitter search or a user’s timeline and go back in history without limitations. However over the past 2-3 years, history has been moved out of reach, by limiting the total volume of Tweets for a search, user timeline and other endpoints, clearing way for a new way to commoditize Twitter history:

**Provider**
**Timeframe**

**Twitter REST API**
1500 total Tweets via search and 3500 total for a user's timeline

**Twitter Streaming API**
Real-time, no historical access

**Datasift**
Back to January 2010

**Gnip**
30 Days with more historical access coming

Twitter history is now off limits to developers via the Twitter family of APIs, with control relinquished to only two sanctioned partners, who are able to commoditize access to history only for analysis, not for display--leaving the ability to display of Tweets to Twitter.  When it comes to history, Twitter has provided access to the Library of Congress, but two years later they are still trying to find the best way to provide access to the archives, without any news of what they have or how they will share this history with the rest of us.

##  Marketing "Open"

Twitter started as a truly open API, openly accessible by the entire ecosystem, and over the last six years Twitter has actively marketed its API as an open ecosystem, encouraging developers to build. This has allowed Twitter to maintain the historical perception that they are an open API platform. In reality, developers who are building actual businesses around Twitter are not just limited, but actively having their access cut-off--leaving Twitter API access to only hobby level projects.  If you are looking to build a business on Twitter you need to use one of the Twitter resellers, which means you will have to spend thousands of dollars a month to get data.

Access to Twitter API has been a topic of discussion since they began rate limiting in 2007, but rate limits were not actively used to control what developers could build until 2010, when Twitter began its quest for monetization. This quest has involved controlling every Twitter endpoint as well as the brand, something that has historically involved developers.

##  Control

As a API owner I understand Twitter’s need to maintain control over their brand and platform, but I feel their approach has severely damaged the entire open API movement. Twitter has actively maintained the legacy image of Twitter as an open API platform, encouraging developers to build, while quietly reducing access, stifling innovation around what is the most important global communication and API platforms in the world--a process which doesn't just destroy their ecosystem, but has damaged developer's taste for building with open APIs.

Analyzing the last six years of Twitter's history, it's very clear that Twitter does not have the respect for the ecosystem that has significantly contributed to the company's success. Beginning in 2010 Twitter saw developers as an obstacle to their goals for extracting value from the passionate user base, and monetizing the increasingly valuable stream of Tweets, that we generate on a daily basis, around the globe.  

Twitter wraps itself in the rhetoric of free speech, but has done nothing but restrict the voice of the developer and everyone's access to our Tweets.
---
layout: post
title: "Whats Next for APIs?  Learning From Social APIs"
url: 'http://apievangelist.com/2011/05/24/whats-next-for-apis-learning-from-social-apis/'
image: ''
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/Qwerly-A-Data-API-for-the-Social-Web.png" alt="" width="325" align="right" />][1]The modern Web API got its start in CRM with [Salesforce][2], and in E-commerce with [Ebay][3] and [Amazon][4], but it really found traction with social platforms like [Flickr][5], [Twitter][6], and [Facebook][7].

If we want a glimpse of whats next for APIs we need to look at the areas where web APIs have been applied for the longest. We need to look at examples like[Amazon's integration of their affiliate program with their Product API][8], and [Qwerly's aggregation of social media profiles][1] into a single API.

The social space is an area where the future of APIs is being played out right now. Since the social arena has reached a critical mass in the number of platforms, users, mobile apps, and available Web APIs, the sector has matured beyond other industries, and offers great insight into what the future holds.

I've talked about [unified APIs that allow you to work with multiple APIs through a single interface][9], and the [potential of API discovery services for industry or common API areas][10], but Qwerly's approach offers another view.

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/qwerly.png" alt="" width="200" align="right" />[Qwerly][11] aggregates social profiles across many networks into a single dead-simple data API for the social web.

With Qwerly you can get data about a user by querying the API with an email address or a social identifier, like a Twitter handle, a Facebook username or a Facebook ID, and the Qwerly API returns:

  * the person's name
  * their location
  * a short description, like a Twitter bio
  * their social networking profiles and usernames across the web, including Facebook, Twitter, LinkedIn and other social networks
  * a score of their online influence among their peers, like [Klout][12]
Qwerly API responses are delivered in JSON, and you only pay for what you use. The API combines information from web crawling, public web directories, other APIs with powerful heuristics and spam-detection algorithms, delivering high quality results.

Other industries and sectors can benefit from such data and service discovery APIs, deployed in a RESTful way, using a pay for what you use API pricing model.

   [1]: http://qwerly.com/ (Querly's aggregation of social media profiles)
   [2]: http://blog.apievangelist.com/2011/01/28/history-of-apis-salesforce-com/ (Salesforce)
   [3]: http://blog.apievangelist.com/2011/01/26/history-of-apis-ebay/ (Ebay)
   [4]: http://blog.apievangelist.com/2011/01/28/history-of-apis-amazon-e-commerce/ (Amazon)
   [5]: http://blog.apievangelist.com/2011/02/09/history-of-apis-flickr-api/ (Flickr)
   [6]: http://blog.apievangelist.com/2011/01/26/history-of-apis-twitter/ (Twitter)
   [7]: http://blog.apievangelist.com/2011/01/28/history-of-apis-facebook-development-platform/ (Facebook)
   [8]: http://blog.apievangelist.com/2011/05/06/amazon-affiliate-is-integrated-with-product-api/ (Amazon's integration of their affiliate program with their Product API)
   [9]: http://blog.programmableweb.com/2011/05/02/unified-apis-or-api-standards-the-race-is-on/ (unified APIs that allow you to work with multiple APIs through a single interface)
   [10]: http://blog.apievangelist.com/2011/05/21/discovery-services-for-common-apis/ (potential of API discovery services for industry or common API areas)
   [11]: http://qwerly.com/ (Qwerly)
   [12]: http://beta.klout.com/home (Kout)
---
layout: post
title:  "Twitter Bubbles"
tagline: "Emphasizing Quieter Voices"
subtitle: "Emphasizing the lesser heard voices"
date:   2013-04-05 20:48:46
categories: project
tags: webdev projects featured
---

With 36% of all the Internet’s worldwide users<sup>[1][1]</sup>, and an average of 340 million Tweets sent per day (as of March 2012)<sup>[2][2]</sup>, Twitter can safely be called a noisy place. The Twitter firehose (a term used in their documentation<sup>[3][3]</sup>) inundates users with a constant stream of the latest Tweets from the people they follow. Buried in this stream could be important announcements from friends, breaking current events, and relevant, interesting articles. The lists feature, introduced in 2009, helps sort the flow a little, however, the problem remains that the prolific Tweeters obscure the more reserved, and the mundane often drowns out the profound.

This web app experimented in cutting through the noise of Twitter and emphasizing the lesser heard voices.

> "The less you talk, the more you're listened to."<br>
> <small>_~ Abigail Van Buren_</small>

#### Solution

<div class="thumb-group">
    <a href="{{ site.url }}/assets/img/twitter/final-1-login.jpg" data-lightbox="twitter" data-title="Final Login: Users could sign into their own Twitter Account using Oauth 2.0" class="thumbnail"><img alt="Final Login" src="{{ site.url }}/assets/img/twitter/final-1-login.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/final-2-intro.jpg" data-lightbox="twitter" data-title="Final Intro: Introducing the concept of how bubbles are sized and shaded." class="thumbnail"><img alt="Final Intro" src="{{ site.url }}/assets/img/twitter/final-2-intro.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/final-4-friends.jpg" data-lightbox="twitter" data-title="Final Friends Page: Alternate page that listed accounts the user follows in order of most recent tweet." class="thumbnail"><img alt="Final Friends Page" src="{{ site.url }}/assets/img/twitter/final-4-friends.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/final-5-bubbles-clean.jpg" data-lightbox="twitter" data-title="Final Alternate Bubble Stream: User preference could determine if they wanted to show profile pictures in the bubble or not." class="thumbnail"><img alt="Final Alternate Bubble Stream" src="{{ site.url }}/assets/img/twitter/final-5-bubbles-clean.jpg"></a>
</div>
<div>
    <a href="{{ site.url }}/assets/img/twitter/final-3-bubbles.jpg" data-lightbox="twitter" data-title="Final Main Bubble Stream: Live feed of the latest hundred tweets. Darker bubbles are older, larger bubbles are the less frequent tweeters."><img alt="Final Main Bubble Stream" src="{{ site.url }}/assets/img/twitter/final-3-bubbles.jpg"></a>
</div>
<div class="thumb-group">
    <a href="{{ site.url }}/assets/img/twitter/twitter-sketches.jpg" data-lightbox="twitter" data-title="Concept Wireframe Sketches" class="thumbnail"><img alt="Concept Wireframe Sketches" src="{{ site.url }}/assets/img/twitter/twitter-sketches.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/processing-sketch.jpg" data-lightbox="twitter" data-title="Early Processing Exploration: Getting data from Twitter API and charting it." class="thumbnail"><img alt="Early Processing Exploration" src="{{ site.url }}/assets/img/twitter/processing-sketch.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/early-ui.jpg" data-lightbox="twitter" data-title="Early UI Exploration" class="thumbnail"><img alt="Early UI Exploration" src="{{ site.url }}/assets/img/twitter/early-ui.jpg"></a>
    <a href="{{ site.url }}/assets/img/twitter/color-variations.jpg" data-lightbox="twitter" data-title="Variant Color Explorations" class="thumbnail"><img alt="Variant Color Explorations" src="{{ site.url }}/assets/img/twitter/color-variations.jpg"></a>
</div>

<small>_This experiment is no longer hosted live. Contact me if you would like to try it out._</small><br>
[View Source on GitHub](https://github.com/hannahd/twitter-bubbles) 

#### Process 
This app was developed as a part of my graduate coursework at Iowa State (February 2013). The assignment was to use the theme of noise as a point of departure to design and develop a website or web app. I was interested creating an interactive data visualization with a large data source and Twitter seemed to be an appropriate fit. The project took about a month and a half to complete, and I was the sole contributor.  

##### Skills Used
- Twitter API
- PHP / HTML / CSS
- Processing JS
- Competitive Analysis
- Wireframing
- Visual/UI Design

##### Contents
- Problem Statement&nbsp;&nbsp;&nbsp;_p. 5_
- Competitive Research&nbsp;&nbsp;&nbsp;_p. 8_
    - Twitter Feeds&nbsp;&nbsp;&nbsp;_p. 9_
    - Data Visualization&nbsp;&nbsp;&nbsp;_p. 21_
    - Tech Tools/API Investigation&nbsp;&nbsp;&nbsp;_p. 36_
- Process&nbsp;&nbsp;&nbsp;_p. 41_
    - Wireframes&nbsp;&nbsp;&nbsp;_p. 42_
    - Site Architecture&nbsp;&nbsp;&nbsp;_p. 49_
    - Rough Proof of Concept Prototypes (Processing & Processing.js)&nbsp;&nbsp;&nbsp;_p. 50_
    - Visual/UI Design Exploration&nbsp;&nbsp;&nbsp;_p. 61_
    - Development Process&nbsp;&nbsp;&nbsp;_p. 69_
- Solution&nbsp;&nbsp;&nbsp;_p. 78_
    

<iframe class="scribd_iframe_embed" src="https://www.scribd.com/embeds/262362521/content?start_page=1&view_mode=slideshow&access_key=key-JrJFASMnbjf1hr0cUYzc&show_recommendations=false" data-auto-height="false" data-aspect-ratio="1.3323485967503692" scrolling="no" id="doc_64897" width="100%" height="500" frameborder="0"></iframe>





[1]: http://www.businessinsider.com/twitter-blew-out-facebook-in-last-nights-super-bowl-2013-2#ixzz2JwgvKbAt
[2]: http://blog.twitter.com/2012/03/twitter-turns-six.html
[3]: https://dev.twitter.com/tags/firehose
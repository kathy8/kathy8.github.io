---
layout: post
title:      "Nokogiri meet my CLI project"
date:       2018-07-29 20:29:49 -0400
permalink:  nokogiri_meet_my_cli_project
---


![](https://www.pexels.com/photo/wood-tool-saw-9280/)


*What am I going to scrape?* 
In my opinion the first step to your CLI Gem Project is fiquring out what site you are going to scrape. This really sets the foundation for your entire project.  I fumbled from idea to idea and looked at what felt like hundreds of sites. I feel I was truly stumped on this the longest. While I beleive that any site is scrapeable for information not all sites are created equal and truly make it challenging to accomplish this task. 

I decided to step out of the box of overwhelm and do a little research on Nokogiri. Well I found out that it means saw in Japanese and it's really perfect for aggregating information on any website for a variety of digital and technical uses. I watched lots of youtube videos,  went back a few lessons to review scraping all over again, again, and again. 


Now that I had a better understanding of what Nokogiri is, and how it is used. I started my search for a site that would serve the purpose of completeing my project. Here are the steps I used to research the sites before adding my project. PC instructions.

1. Select site 
2. Click on the right side of your mouse or go to developer tools and click INSPECT page
3. Then search for your css selectors that can be parsed such as h1, h2, div etc
4. While in the INSPECT mode I click the search tab on the top left, it looks like a little mouse arrow with a box under            it or just type Ctrl + Shift + C
5. Now I go through and start looking for information that would be great to extract for the project.



My little JavaScript trick before coding anything in the terminal is to go to the *console* and type:
***document.queryselectorALL("enter the selector")***  and hit enter, you should get a list of what your are looking for and that's what helped me determine if this site would be useful. 

Connect your project to github, this blog post was very helpful [https://sillhouette.github.io/crowder_news_data_gem.]

Next step is to set up your gem, follow along Avi's Daily Deals video and start coding your environment. 
Commit to github often. 

Once your environment is up and running enter your site into Nokogiri and get to scraping that website. 


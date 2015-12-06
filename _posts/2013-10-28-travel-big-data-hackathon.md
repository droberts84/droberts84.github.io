---
layout: post
status: publish
published: true
title: Travel Big Data hackathon
author:
  display_name: David Roberts
wordpress_id: 14
wordpress_url: http://www.drob.net/?p=14
date: '2013-10-28 03:18:47 -0400'
date_gmt: '2013-10-28 03:18:47 -0400'
categories:
- Tech
tags:
- travel
- big data
- hackathons
- tech
---
This weekend I had the opportunity to attend the Travel Big Data Hackathon at the Hack/Reduce space. I am very passionate about travel, so this was an event that I could not miss. After bribing a friend who works with Hadoop and making last minute travel arrangements, we were off to Boston!!

I had attended GiftCamp and the past, but at that event the customer had a very specific goal set prior to the event. This was my first real free-form hackathon, where I could build anything I wanted.

I set out several lofty goals for the 12 hour event
- Find as many trends as I can about the airline industry using the massive datasets provided
- Learn how to use NoSQL tools to analyze "Big Data" ( I only had experience with traditional SQL databases)
- Network with professionals in the travel industry

Friday night was purely to socialize and learn about the datasets. I had many ideas racing through my head of what I might do with this data and it was great to discuss with other participants and bounce around ideas.</p>
<p>By Saturday morning we had a team of 8 formed with diverse skillsets, and settled on a project. The plan was to first determine the average fare of a particular city pair, then graph the price of the flight as a percent above/below this average depending on the number of days in advance.  We would then add data showing how far in advance customers purchased tickets on the same graph.  I had no grand visions of being able to predict the perfect time to buy the cheapest tickets, as I know there are many many variables involved, but I thought it would be interesting to see what this trend looks like, and if the price trend had much of a correlation to when customers actually purchased.  My guess is there would be many cases when it did not.</p>
<p>We put together a data model and outlined a plan for how to transform the data from each source to get the data important to us, join the result sets, and generate visuals.  Initially we were going to use Hadoop to run map/reduce, but technical limitations made that not a practical endeavor.  We hastily switched to a tool called ElasticSearch, because a cluster had already been set up, but we were not very familiar with this tool or its advantages/disadvantages.  Unfortunately too much time was spent formatting the data to load into ElasticSearch, and by the time the day was over, less then 20% of the data was loaded and we had barely done any analysis, let alone coding the complex statistical facets we would need to produce the planned graphs.</p>
<p>When it came time to present our results, I put on my best game face and walked the audience through our concept, the process to achieve it, and the issues that prevented us from finishing it.  I was also lucky to have some very snazzy visuals that team members had put together based on the raw data.  It was clear from seeing the other presentations that we had got caught up in the grand idea of looking at "big data" and threw aside the practicality of the 9 hours we actually had to achieve it.  Several groups came up with no presentable findings like us, and most of the teams that did achieve their endgame looked at a very small subset of the data using traditional SQL databases.  There were many impressive results and even more impressive ideas, but one team in particular, FlightR, really stood out.  Similar to our team, they were looking at the cheapest time to buy tickets, and they actually managed to build an interactive demo by using a statistical analysis package called R.</p>
<p>Despite not completing our project, several of the representatives from the sponsoring companies approached us and complimented our plans, and apparently we were even a finalist!</p>
<p>When I look back at my goals I had for the day, the hackathon was far from a failure.  I wanted to learn about new tools, instead of play with the familiar.  I wanted to have a grand concept, instead of build something basic that likely already existed.  I realized that, unlike in my professional life, this was a place where it not necessary to have a finished product.  The goal was to explore the possibilities and ask questions that may not have been asked before.</p>
<p>Regardless, I already have ideas to improve for my next hackathon and look forward to participating again!</p>

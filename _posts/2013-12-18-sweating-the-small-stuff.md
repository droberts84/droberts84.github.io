---
layout: post
status: publish
published: true
title: Sweating the Small Stuff
author:
  display_name: David Roberts
wordpress_id: 19
wordpress_url: http://www.drob.net/?p=19
date: '2013-12-18 22:56:20 -0500'
date_gmt: '2013-12-18 22:56:20 -0500'
categories:
- Uncategorized
tags:
- Coding
- Best Practices
---
This weekend I participated in Global Day of Code Retreat, where developers in cities all over the world get together to focus on good software development practices.  You pair off with other developers you don't know and have 45 minutes to work together to implement [the game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). When time is up you `rm -rf` your code, debrief with the group, and have to start fresh with a new partner.  Immediately it became apparent we were not going to complete this in the allotted time, particularly if you take time to discuss a strategy or setup Test Driven Development, as I always do.    And this continued all day.  To keep it interesting, different constraints were thrown in each round, such as new programming languages, or forbidding any talking with your partner.  But every time, I was rarely much closer to a complete implementation.  To be honest, it was a frustrating as experience.  Just as I started to feel comfortable with the partner or newest constraint and get into the groove, time would be called and the fruits of labor were never seen.
It took me until the final debrief to fully appreciate the point of the day.

For an entrepreneur, it is important to have a vision and always keep the big picture in mind.  The same holds true when you put on the software developer hat, but once you have the end goal in mind it is even more crucial to focus on the details.  Even when there is a crazy unrealistic deadline imposed, you cannot just throw away good software development practices to conform to the timeframe.  Maybe you tell yourself you will rewrite the code when 'things slow down' but realistically there is never a slow period.  Years later, you end up with poorly performing code that is not well documented and is too risky to remove since no one fully understands its purpose.  I have seen this first hand in my job, but this weekend it really resonated with me how this code is born.  Everyone knows bugs are cheaper to fix the earlier you catch them, so is it really worth increasing the risk of bugs to save a few hours?

By the end of the day, I had learned a number of ways to look at the problem from a diverse group of people, different methods of pair programming, and played with some new programming languages.  The only thing I didn't do was actually code the complete game of life.  I left with more then enough tools under my belt to do it the right way though.

Keep your eye on the prize, but don't let it distract you from practicing TDD and good software development practices.

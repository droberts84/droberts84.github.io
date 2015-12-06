---
layout: post
status: publish
published: true
title: Own the Airwaves with Argus TV
author:
  display_name: David Roberts
wordpress_id: 16
wordpress_url: http://www.drob.net/?p=16
date: '2013-11-07 12:51:05 -0500'
date_gmt: '2013-11-07 12:51:05 -0500'
categories:
- Tech
tags:
- tv
- cord cutting
- aereo
- argus tv
- ota
- hulu plus
---
I cut the cord on cable over a year ago, and have been on Netflix for the majority of my TV entertainment and Hulu plus for my fix of the latest primetime TV. This arrangement has worked very well, as both services are available on my PC, android products, and the WD TV boxes that I have placed at every tv in my house.  However, recently my subscription to Hulu has been bothering me as a bad value proposition.  Its not like $9/month is that big of a deal, but when you compare to Netflix... it has commercials, only very limited shows (most of which are available for free over the air), and usually only the most recent episodes instead of multiple seasons.  As essential as Hulu seems to cord cutting, I decided it had to go as it was not pulling its weight in my ideal TV watching utopia.

### The Problem: Replace Hulu plus with another solution for watching/recording primetime TV

- Must work with WD TV boxes (this is my main tv viewing device on every TV in my house)
- Must support my android tablet
- Offline access would be a major plus for air travel

My first thought was [Aereo](https://www.aereo.com), the tv service that has been in the news recently for successfully fighting some of the major networks.  This looks like a great service that records Over the Air (OTA) tv for you and stores it in a "DVR cloud".  However, there were several issues preventing me from using it.. the biggest hurdle being that it is not  yet available in my hometown of Philadelphia.  Additionally, it did not support WD TV, so no watching on my big screen, and you need an internet connection..   Hmmm.. this doesn't really meet any of my requirements.  But then I thought about how it works.. It is just an antenna recording to a server with some slick software in front of it.
I have a computer with plenty of storage, and can easily get an antenna.. why can't I build my own solution?
After doing some research at tvfool.com, I picked up an attic antenna for $50 and a Hauppauge 1850 pc tuner card for $15 courtesy of eBay.  Now I have all of the hardware I needed, and can record a file in full HD my computer.  Even better, it is DRM free, so I can watch it on any WD TV in the house or compress it and copy to my tablet when traveling.  The amount of TV I can record is only limited by the size of my NAS so storing entire seasons of multiple shows is no issue. However, I was still lacking some slick software to control it and get that all important WAF (wife approval factor).

####The Solution: Argus TV
[Argus TV](http://www.argus-tv.com/) started off as an enhanced recording component for MediaPortal but was forked into a fully fledged solution that could be run independently.  It runs as a sever on a windows box, and can be controlled via gui or (mobile friendly!) web client.  It allows all sorts of advanced rules for scheduling recordings, and can kick off post-processing tasks, such as video conversion, commercial cutting etc. One pain point is it does not have an out of the box solution for getting TV guide data, but I found [Web Grab](http://webgrabplus.com/) worked well for pulling US tv guide data.  This requires playing with some XML files to get everything setup, but the documentation walks you through the process, and once you have it figured out, you can easily scrape data from virtually any tv guide site.  I personally went with Zap2It.  I still had a few problems with getting accurate season/episode #s, but an addon called [Guide Enhancer](https://code.google.com/p/ftr-guide-enhancer/) quickly corrected it.

Ok, so it does take some time and a small investment to get everything going, but you are rewarded with a kick ass networked DVR set up that you can customize for your exact needs.

Now I'm enjoying my proper TV utopia, with unlimited access to my primetime shows anywhere I want.

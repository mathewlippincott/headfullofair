---
layout: single
title: "getting a high altitude balloon back"
author: Mathew
toc: true
tags:
 - balloons
 - high altitude
 - rigs
categories: 
 - post

header:
 image: /assets/images/publiclab/Screen_Shot_2014-09-03_at_10.08.19_PM.png
 teaser: /assets/images/publiclab/Screen_Shot_2014-09-03_at_10.08.19_PM.png
 
---



### What I want to do
fly a high altitude balloon and get it back.  This means tracking where it goes and calling home.
I want to use GPS to track the flight, and see what different radios will send back location data.

### My attempt and results
I thought I would do this through APRS, an amateur radio data network, but with the advent of cheap satellite-based commercial trackers it is cheaper to buy a pre-made device. I went with a [Spot 2](http://www.findmespot.com/en/). It [cost $60](http://www.amazon.com/gp/offer-listing/B002PHRDO2/ref=sr_1_2_olp?s=gps&ie=UTF8&qid=undefined&sr=1-2&keywords=spot&condition=used), but the Iridium satellite service costs $150 per year to send GPS coordinates every 10 minutes when it is on. Luckily, I can transfer the service to a new device if I lose this one. That is appealing. And its satellite system doesn't require an amateur radio license.  

![Spot satellite tracker](/assets/images/publiclab/Screen_Shot_2014-09-03_at_9.56.48_PM.png)

I could have gone with other satellite systems. things like:

* [Habduino](http://www.habduino.org/), an arduino telemetry board that costs 105 british pounds.
* [Build-my-own Spot clone](https://www.sparkfun.com/products/retired/11088) with Sparkfun's plans for their discontinued product.
* Use [the RockBLOCK](https://www.rock7mobile.com/products-rockblock.php), a serial modem for [sending 50 character text messages](http://arduiniana.org/libraries/iridiumsbd/) into Iridium for ~10 british pence a message.  

##### Amateur radio systems

I have an a amateur radio license for doing just this very thing, and have looked at it. 
The amateur radio system I liked was an all-in-one transmitter called the [BeelineGPS](http://www.bigredbee.com/zc139/index.php?main_page=product_info&cPath=66&products_id=207). I also looked at [were the Tiny Track 4](http://www.byonics.com/tinytrak4/) and a [transmitter, a system of this sort.](http://simsat.net/carrollsat/), But this radio would probably not be able to communicate with a tower at lower altitudes.  So with an amateur radio system, we would need a ground tracker

##### Ground Trackers

This [Balloon News article has several options.](http://balloonnews.wordpress.com/2013/07/03/buzz-off-recovering-your-payload-from-dense-vegetation/) 

###### [Doppler radio setups]

[Doppler Radio](http://members.chello.nl/~w.hofman/pa8w/dopplerRDF.htm), or Time Difference Of Arrival, [TDOA Radio](http://www.handi-finder.com/) or Radio Direction Finding, [RDF](http://wiki.spench.net/wiki/SDRDF) is a way of finding a simple transmitter.

[Finding the direction to the transmitter requires one to measure phase difference of pseudo-doppler signal against a known reference (e.g. 'North'). The pseudo-doppler signal is introduced (superimposed on the demodulated signal) by electronically rotating the antenna array against a reference signal of the same frequency as half the switching rate.](http://wiki.spench.net/wiki/SDRDF)

[![Screen_Shot_2014-09-03_at_9.20.04_PM.png](/assets/images/publiclab/Screen_Shot_2014-09-03_at_9.20.04_PM.png)](http://www.handi-finder.com/)

##### Questions and next steps

I got the Spot... I need to fly the balloon. It seems to report more regularly when facing upwards. 


##### Comments

[@amysoyka](http://publiclab.org/profile/amysoyka):

What about repurposing an old smartphone & using Google latitude (or similar) to ping it...?

@mathew:

That is a great idea and works well some places, but it won't work in most of Western N. America-- not enough cell towers. I'm launching East of the Cascades in Oregon-- I didn't really look into it.  

![Screen_Shot_2014-09-05_at_10.24.00_AM_1.png](/assets/images/publiclab/Screen_Shot_2014-09-05_at_10.24.00_AM_1.png)

[@Wonko](http://publiclab.org/profile/Wonko):

A couple of things:

First, it is illegal to use cell phones for high altitude flights. It messes with too many towers. I don't believe they are allowed in any airborne uses including rc planes and drones.

Second, I got my balloon to 108,000 feet. APRS worked great down to about 5500 feet within a few miles of the Colorado, Nebraska, Wyoming junction. I got 2 pings from the spot unit on board over the whole of the flight. Fortunately they were right before landing. That was luck, not skill. I would not depend on a Spot for other reasons too. The position of the antenna is somewhat critical to the function of a Spot. It is difficult to guarantee this on a balloon. Also, commercial GPS units are speed and altitude limited by law. You have to buy specific chips if you are going over 40,000ft or 200 mph, either of which are probable at some point on your balloons journey. Make sure whatever GPS you use it is unlocked. I used one from bigredbee.com that I wouldn't hesitate to recommend.

[https://www.youtube.com/watch?v=7ysm8bBZJzc](https://www.youtube.com/watch?v=7ysm8bBZJzc) if you want to see some of our footage.

@mathew:

@Wonko,
I don't know that its illegal to track a balloon with cell phone-- can you cite that somewhere?  balloons are a different flight category from dirigible aircraft. 

[@nshapiro](https://publiclab.org/profile/nshapiro):

I don't think you need cell service to use the GPS on a phone. We used one in the middle of the pacific where there was no service. Thinking back, it could have been picking up some wifi from the boat we were on but it certainly didn't need a tower.



{: .notice} 
Archived 4th of March 2018 [from Publiclab.org](https://publiclab.org/notes/mathew/09-04-2014/getting-a-high-altitude-balloon-back).

*[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)*
 


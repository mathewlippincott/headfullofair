P2390759.jpg

## Overview

[Airpup](https://headfullofair/com/tags/airpup) is a small kite balloon designed to provide a quiet, long-duration flight in most weather without the restrictions placed on drones. You can [read more about Airpup](https://headfullofair.com/tags/airpup), [get Airpup on Crowd Supply](https://crowdsupply.com/head-full-of-air/airpup), and download Airpup's [assembly patterns on github](https://github.com/mathewlippincott/airpup-balloon).

All 2D plans are made with open source [QCAD](https://www.qcad.org). 3D models are made with Autodesk's [Fusion 360](https://www.autodesk.com/products/fusion-360/overview).

## Design goals and features


Airpup's design grew out of the ways people have used [balloon and kite mapping](https://publiclab.org/wiki/balloon-mapping), and the issues they faced moving helium tanks, moving inflated balloons and long kites, and flying on their own schedule-- not the wind's.

I wanted to combine the reliability and simplicity of a balloon with the ability to fly in higher winds like a kite. The balloon needed to be inflated from a backpack-able quantity of helium.

I also wanted to make payload attachment simple, so there are few strings to get tangled and no stabilizers to set up.  

I built rails into the belly that accept a standard 1/4-20 tripod mount, based on [Ranon's](https://publiclab.org/profile/ranon) [rail mounts](https://publiclab.org/notes/ranon/08-10-2016/reconfigurable-rig-pole-configuration-and-github-repository). 

![Airpup's belly rails](../assets/images/airpup/airpup-config-wide.jpg)

*Kestrel 5500 weather station, Feiyu SPG gimbal & phone, Canon camera is mounted on an [Aerobee Bracket](http://kaptery.com/product/aerobee-rig-kit)*

Airpup packs down small and can be [borrowed by mail](https://crowdsupply.com/head-full-of-air/airpup) with string, owing to to my uniquely narrow [winder design](https://www.headfullofair.com/post/flat-line-winder/).

![packed up](../assets/images/airpup/airpup-packedup-inbox.jpg)


## Field testing and performance

I walked the balloon and tank 4 miles round trip to the beach. At 25lbs, it was manageable in daypack with a hip band. 

![image](../assets/images/airpup/P2390691-contrast.jpg)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/0rGuT0tnSNg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Using a Kestrel 5500 from my [Aeropod](https://publiclab.org/notes/cfastie/10-17-2017/winds-aloft-sensor-overload), I recorded the winds in 30 second averages and overlayed them on the video.

To simulate higher wind speeds, I do [tow tests by bike](https://www.youtube-nocookie.com/embed/2imR-zk1Fjo).



## Design process

![a starting sketch before I had a balloon in hand](../assets/images/airpup/early-sketch.png)

I intended to use keels for stability, since they simplify rigging and free up the belly for payload attachment. I also intended to use a 3-gore pattern that can be seemed flat, and accept some balloon wrinkles. Fabrication had to be affordable and quick.

I made a clay prototype and measured out the three panels, hoping to create a somewhat flat belly out of a single panel, and an airfoil-curved top made from two panels.

![clay prototype](../assets/images/airpup/clay-pup.jpg)


[Blimp Works](http://www.theblimpworks.com/) made the envelope for me with a three-gore pattern. I sent assembly diagrams showing the folded interior panel. Danny Hogan fixed my nose and tail, making them slightly pointier than this diagram suggests. The flat valve I was familiar with making (the tail-like thing) was subbed for a standard vinyl blow-up valve. 

![assembly diagram](../assets/images/airpup/pup-simple-fold.png)


I started with an 8 cubic foot prototype since this is a standard quantity of helium at many grocery stores. It also had the advantage of being easy to fit through my front door. 

The shape came out close to what I wanted but different than I expected. The "belly" panel curved under internal pressure, and the two "top" panels tensioned fairly flat. 

![3-view-photo.png](../assets/images/airpup/3-view-photo.png)

So I flipped the balloon upside down. 

![my test bridling for adjustment](../assets/images/airpup/test-bridle_1.jpg)

I then noticed a curious and desirable property. From a front profile the balloon was close to a "natural shape" under pressure. As the balloon lost pressure, it continued to maintain its shape even with the weight of a payload pulling on the belly. see *c* and *d* below.


![Natural Shape balloons, invented by Robert Upson. Yajima et. al. Scientific Ballooning: Technology and Applications of Exploration Balloons Floating in the Stratosphere and the Atmospheres of Other Planets. New York 2004.](../assets/images/airpup/Natural-shape-pg25-Yajima-etal-Scientific Ballooning2004.png)




## Best practices for bridling and balancing wind load

My goal was to have a balloon whose angle of attack without wind pressure matched its angle of attack under wind load. To do this,
I let the balloon float freely, and observed it's chosen position in free flight. I also played around with a bridle position and some weights to simulate a tail. 

I intended to bridle the balloon with keels mounted around the middle of the balloon's sides. I wanted the bridle point to be just in front of the balloon's center of mass and center of static lift. I also wanted to closely align the center of static lift with the aerodynamic center of pressure to minimize turning momentum. I set these goals thanks to reading articles from [Flight International Magazine](https://archive.org/details/Flight_International_Magazine) in the 1920's immediate post-war balloon developments, especially P.H Sumner's "Principle of the Captive Balloon" in [10 June 1920](https://archive.org/details/Flight_International_Magazine_1920-06-10-pdf/page/n9) issue.

## Speculative concepts

I intend to derive aerodynamic lift from the balloon body itself. Since the balloon is a thick and inefficient airfoil, some strategy is needed for reducing turbulence and increasing attachment on the back side of the airfoil. This need is well-described by [R. Dale Reed in Wingless Flight: The Lifting Body Story](https://history.nasa.gov/SP-4220/sp4220.htm).

[![Diagram from chapter 5 of Wingless Flight: The Lifting Body Story by R. Dale Reed, 1997](../assets/images/airpup/ch5-wingless-flight-reed.png)](https://history.nasa.gov/SP-4220/sp4220.htm)

On Airpup, space between the keels and the rear wing is intended to vent air into the turbulent flow on the back side and promote attachment. 

## Modeling

I made a CAD model to garner some information to start with, such as the center of static lift. I modeled the envelope in Autodesk's Fusion 360.

![calculated aerodynamic center](../assets/images/airpup/CAD-center.gif)

Centering the bridle around the center of static lift, I added area to a rear wing such that 2/3 to 3/4 of the total wing area would be behind the center of static lift. 

![CAD-projection.png](../assets/images/airpup/CAD-projection.png)


The simple planar model was a very rough start. I don't have the ability to do proper aerodynamic simulations, but needed a place to begin tweaking based on actual flight performance. 

I made a taped-on a prototype pattern made from Tyvek. To my surprise, the chosen bridle point worked great on the first try, and flew with a payload in place as-designed.

![test-wing2_1.jpg](../assets/images/airpup/test-wing2_1.jpg)

After the successful test I asked my friends if they could help me sew a prototype.


## Scaling up

Scaling up required adding a cross spar for stability in the rear. 


## Previously in kite balloons

A kite balloon featured in the [first real-world conversation](https://www.headfullofair.com/2010/09/24/kite-balloon-construction-ideas-with-boston-folks/) I had with @warren and my first time e-mailing with @danbeavers. A DIY kite balloon was the first thing I flew with @gonzoearth and @olivia, and the [wiki page for a Kite-Balloon Hybrid](https://publiclab.org/wiki/kite-balloon-hybrid) was the first thing I posted to Publiclaboratory.org in January 2011, trying to collect @warren, @lizbarry, @eymund's experimental designs with some sources I'd collected.

![Flying a kite balloon with Stewart Long and Olivia Everett, March 2011. It flew alright but leaked helium over 20 minutes and got stuck in a tree.](../assets/images/balloons/1299869655936-orig.jpg)

The project didn't go very far because we couldn't seem to make a small, lightweight balloon that both held helium and held up in the force of the wind. Our DIY mylar balloons were taped together and all leaked. The heat-seamed plastics I was working with couldn't hold pressure. A double envelope on top of a rubber balloon was over-weight. Party balloons weren't big enough to be kites and hold a camera. The manufacturer we worked with at the time, the now-defunct Southern Balloon Works only had 4 mil polyurethane that was too thick and heavy to make anything small.

Some hints have been posted of functional DIY designs, such as @Alex_the_Ukranian's [carbon-fiber framed polyethylene balloon](https://publiclab.org/notes/Alex_the_Ukrainian/03-21-2015/small-diy-aerostat-made-in-kharkiv-ukraine). 

#### Prototypes:

* @Shannon [Prototype 'pufferfish' balloon from EcoHack](https://publiclab.org/notes/shannon/4-21-2012/prototype-pufferfish-balloon-ecohack)


#### Concepts:

* @Valerie [Balloon Kite design and prototype](https://publiclab.org/notes/valerie/4-21-2012/balloon-kite-design-and-prototype)
* @Eustatic [Sketches for "Corset-Chiton" idea for Pufferfish mod](https://publiclab.org/notes/eustatic/5-2-2012/sketches-corset-chiton-idea-pufferfish-mod)
* [Making a balloon making jig](https://publiclab.org/notes/mathew/5-18-2012/making-balloon-making-jig)

#### Examples:

* @liz [1967 dart balloon](https://publiclab.org/notes/liz/1-31-2013/dart-balloon-1967)
* [American Kite Fishing, low-tech Kite-Balloon hybrid](https://publiclab.org/notes/mathew/2-1-2013/american-kite-fishing-low-tech-kite-balloon-hybrid)
* [Arthur W. Mears Kite Balloon, archetype for Kingfisher, Skystar?](https://publiclab.org/notes/mathew/4-13-2012/arthur-w-mears-kite-balloon-archetype-kingfisher-skystar)
* [Kite balloon of R.H. Upson](https://publiclab.org/notes/mathew/4-13-2012/kite-balloon-rh-upson)


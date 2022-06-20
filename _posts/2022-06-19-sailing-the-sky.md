---
layout: single
title: "sailing the sky: endless gliding takes shape"
author: Mathew
categories: 
 - post
tags:
 - aerocene
 - kites
 - gliding

header: 
 image: assets/images/aerocene/sailing/sail-glider.jpg
 teaser: /assets/images/aerocene/sailing/sail-glider.jpg

---
While sailing the sky is often used as a flight metaphor, sailing physics may be directly applicable to continuous flight. Can two wings, one functioning as a "keel" and the other as "sail," generate continuous lift? The question is being actively researched, and I've collected the core technologies in this post. 
 
## boats get new wings
Ocean sailing has experienced a recent infusion of soaring technology, as parawings developed for soaring have been adapted to kiteboats and kite foiling.  Experimental sailcraft and aircraft suggest that soaring may benefit from ocean sailing strategies.

A sailing vessel generates its motion through the difference in speed between two fluids — air and water. 

![sailboat illustrated by the Syroco project](/assets/images/aerocene/sailing/Voilier-width-800.jpg)
*Image: [Syroco](https://syro.co/en/news/laile-deau-and-the-weightless-yacht-concept/)*

A traditional sailboat uses its mass to stabilize itself, but more recent techniques, such as kite foiling, reduce the sailing system to two wings, one in the air and the other in water. 

![kitefoil](/assets/images/aerocene/sailing/Kitefoil.jpg)
*Image: [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Kitefoil.jpg)*

Parawing designer Luc Armant's *l'aile d'eau* (water-wing) concept ([PDF link in French](http://www.augredelair.fr/wp-content/uploads/2015/01/luc_armant_ailedeau.pdf)) aligns the forces of the wings in the water (hydrofoil) and air (aerofoil) to garner even greater efficiency. <sup>[1]</sup> 

![l'aile d'eau concept illustrated by the Syroco project](/assets/images/aerocene/sailing/Speedcraft-width-800.jpg)
*Image: [Syroco](https://syro.co/en/news/laile-deau-and-the-weightless-yacht-concept/)*

 Armant's ambitions are now reaching full-size through the [Syroco](https://syro.co/en/) project, which aims to break 150kph in a sailing vessel by implementing the *l'aile d'eau* concept. Armant is an advisor to Syroco.
 
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Blb2S6Ytngg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## sailing between winds

![Engblom's DAP vehicle concept from NIAC](/assets/images/aerocene/sailing/engblom_sail_board.jpg)

What if, instead of the airfoil and hydrofoil of the *l'aile d'eau* concept, two airfoils were used? The idea of sailing the sky with two airfoils connected by a cable long enough to bridge two different wind currents precedes the *l'aile d'eau* in concept, if not in execution. Richard Miller, editor of *Soaring* Magazine in the 1960s and a popularizer of hangliding, spread the concept and claimed to have experimented with it.<sup>[2]</sup> 

Regardless of the idea's provenance, the dual airfoil concept has become the subject of serious inquiry by William Engblom and his team at Embry-Riddle through a series of NASA Innovative Advanced Concepts (NAIC) grants.<sup>[3]</sup> Engblom's Dual Aircraft Platform (DAP) is intended as an 
"[atmospheric satellite](https://en.wikipedia.org/wiki/Atmospheric_satellite)," a long-duration flying craft that can replace the functions of an orbital satellite. 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/fidiDPaLWWw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

DAP can derive positive lift from any two winds with 10% or greater sheer, a condition that should be common enough to enable DAP to circle an area indefinitely (station-keeping).<sup>[4]</sup> The DAP system, however, does not rely entirely on soaring — it uses wind sheer, when available, to spin its propellers and charge on-board batteries. When wind sheer is not available, the propellers are used to sustain flight. 

![Engblom's DAP vehicle concept from NIAC, detail](/assets/images/aerocene/sailing/niac_engblom_phii.png)

The DAP system hinges on its ability to calculate a flight path based on sensor data about air currents. I can't find any reference to a specific sensor system in the DAP literature, but the use case appears similar to the [Ball Aerospace Optical Autocovariance Wind Lidar (OAWL)](https://www.ball.com/aerospace/programs/earth-science-weather/oawl-wind-lidar). OAWL uses green (532nm) and/or UV (355nm) lasers to track the movement of water vapor and particles to infer wind speed. These sensors [appear to be deployed](https://www.technologyreview.com/2018/11/14/139092/darpa-is-testing-stratospheric-balloons-that-ride-the-wind-so-they-never-have-to-come-down/) for navigation on a series of [experimental US military balloon flights](https://www.thedrive.com/the-war-zone/40638/what-we-know-about-the-high-tech-balloons-lingering-off-the-coasts-of-the-u-s-recently). 

DAP captures wind energy using kiting on a tether, giving it more in common with tethered [airborne wind energy](https://airbornewindeurope.org/about-airborne-wind-energy/) concepts than other aircraft. Indeed, Engblom states that the traditional glider shape of DAP was chosen to jumpstart prototyping, and a different platform was initially intended for study.<sup>[5]</sup> Given the vast array of airborne wind energy concepts, the ideal DAP-style craft appears as-yet unknown.

![Figure 2. DOE. 2021. Challenges and Opportunities for Airborne Wind Energy in the United States. Report to Congress. Washington (DC): US Department of Energy.](/assets/images/aerocene/sailing/DOE-AWE.jpg)
*different airborne wind energy concepts (DOE 2021)<sup>[6]</sup>* 

## future developments

As I hinted in the header image of this post, I am most interested in whether this flight strategy can be applied to personal aircraft, especially foot-launched aircraft (hangliders and paragliders). 

![Concept for paraglider sailing](/assets/images/aerocene/sailing/sail-glider.jpg)

Could a robotic kite on a tether be deployed while paragliding for long-distance sailing/soaring? The possibility is tantilizing, and much of the hardware appears near term: robotic kites are established technology (at least at the research level of airborne wind energy), and the sensors and computing hardware necessary to calculate the flight path can't be far off, given that my phone has lidar and high-powered 532nm and 355nm laser diodes are commercially available at fairly low cost. Still, several crucial questions remain:

* Does the flight space of ultralight aircraft (below 19,000 feet) include enough sheer winds?
* What sort of tether markings are required (flags, strobes, etc.), and is their drag acceptable?
* Are the simple wings of paragliders and hangliders efficient enough to exploit wind sheer?
  * Akimov and Polivanov<sup>[4]</sup> claimed sustained flight was possible with 10% sheer but assumed a glide ratio of 40. A paraglider has a glide ratio of about 10 and the best hangliders have glide ratios of about 20.  

What other issues do you see? [Get in touch](/contact). I'll add your comments to this post.

## notes

[1] Luc Armant [is responsible for many refinements of modern parafoils](https://www.flyozone.com/paragliders/team/luc-armant). Armant has a [charming video](https://youtu.be/1tEw_mlUh7g) compiling his late 1990s *l'aile d'eau* experments with small, unguided models that he chased across the water in a motorboat (it makes me wish I understood French).

[2] Richard Miller wrote about the dual airfoil concept in his influential 1967 book on glider experimentation, *[Without Visible Means of Support](https://www.worldcat.org/title/without-visible-means-of-support/oclc/430247).* Miller claimed that [Alois Wolfmüller](https://en.wikipedia.org/wiki/Alois_Wolfm%C3%BCller) experimented with a free-flying system of two kites in 1909, and that Miller himself replicated such tests (Miller 115). He also implies that Soviet experimenters used a similar system to slingshot a rigid-wing glider to record-breaking altitude in 1937, with a Fyodorov at the controls (Miller 43). I can find no confirmation for any of Miller's claims. 

[3] William Engblom's team conducted a [virtual flight simulation](https://www.nasa.gov/feature/virtual-flight-demonstration-of-stratospheric-dual-aircraft-platform/), [tested of a single scaled model on a tether](https://ntrs.nasa.gov/citations/20190001176) from the ground, and [designed a sailing path optimization algorithm](https://arc.aiaa.org/doi/abs/10.2514/6.2018-3887). Engblom describes the system in-depth in [his talk at the 2015 NASA Innovative Advanced Concepts (NIAC) Conference](https://livestream.com/accounts/7167144/events/4425551/videos/103083420).

[4] [A.M. Akimov and P.A. Polivanov. 2019. *Study of the Possibility of Steady Horizontal Flight of the Dual Aircraft Platform with the Wind Shear.* Journal of Physics: Conference Series 1404 012075. Bristol: IOP Publishing Ltd.](https://iopscience.iop.org/article/10.1088/1742-6596/1404/1/012075/meta)

[5] The initial proposal for the DAP platform involved a tandem-wing aircraft that looks like a canard glider with extremely exaggerated canards. It is the subject of a graduate thesis:
[McKee, Michael E. 2012. *Novel Airframe Design for the Dual-Aircraft Atmospheric Platform Flight Concept.* Masters Thesis. Daytona Beach: Embry Riddle Aeronautical University.](https://commons.erau.edu/edt/104/)

[6] DOE. 2021. *Challenges and Opportunities for Airborne Wind Energy in the United States.* Report to Congress. Washington (DC): US Department of Energy. [*PDF link*](https://airbornewindeurope.org/wp-content/uploads/2021/12/report-to-congress-challenges-opportunities-airborne-wind-energy-united-states.pdf)

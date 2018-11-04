#Airborne Networking: mesh node flies to 500ft on Airpup

Airpup and a wireless network node can fit in a backpack and be taken anywhere. 

{backpack.jpg}

Flying to 500' extended our amateur radio mesh node's range from 0.2 miles to 1.25 miles. We managed about 4m hours of broadcast time for a Raspberry Pi 3 and a WiFi dongle. 

{airpup-wireless.jpg}

This project was a quick hack-- with further power optimization we hope to fly all day without changing the battery, and keep the network up all weekend without refilling Airpup.

{meshnode.gif}

## Fly-able Broadband-Hamnet node

Mitch Bayersdorfer of [Clackamas County ARES](http://clackamasares.org) has been working on a Raspberry Pi-based replacement for the WRT54G-based [Broadband-Hamnet](http://www.broadband-hamnet.org/) nodes CARES currently deploys. The system serves up CARES Field Operations site, emergency response info, and VoIP functionality.

{mesh-new.jpg}

Mitch Bayersdorfer brought a mesh node to [Dorkbot PDX](https://dorkbotpdx.org/) the same night I brought Airpup. We made an impromptu flight to 50 feet, as well as plans to try again at a higher altitude.

{mesh-current.png}

Using Mitch's Raspberry Pi 3, Tendak USB 3 hub, and an Alfa AWUS036NH WiFi dongle, we made some quick hacks and a 10Ah USB battery to reduce the size of the setup.

{meshnode.jpg}

{airpup-wireless.jpg}

I launched the node from the backyard, and Mitch drove a second node around to check the signal strength.

{mesh-500ft.jpg}

{mesh-car.jpg}

50% signal strength was observed at 1.25 miles, a significant range boost without any antenna optimizaton.

{mesh-cares.png}

## Next steps

The goal is to reduce the flying node to a Pi Zero, smaller battery, and a better antenna, probably a Discone.
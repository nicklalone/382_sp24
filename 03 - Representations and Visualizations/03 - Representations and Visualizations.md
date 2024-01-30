---------------- Table of Contents ---------------- 

1. [Reading this Week](#reading)
2. [Concepts to Date](#todate)
3. [Concepts for This Week](#thisweek)
4. [Day 1](#day1)
5. [Day 2](#day2)

---------------- Table of Contents ---------------- 
# <a id="reading"></a>Reading for this week

# <a id = "today"></a>Concepts for This Week 
* GIS - https://www.esri.com/en-us/what-is-gis/overview
* GPS - https://www.geotab.com/blog/what-is-gps/
* Trilateration - https://www.lifewire.com/trilateration-in-gps-1683341
* Storymaps - https://storymaps.arcgis.com/stories/9a500acb526f4be8b0a3c66ffa8e53fa
* Geospatial Data - [Long URL](https://aws.amazon.com/what-is/geospatial-data/#:~:text=Geospatial%20data%2C%20or%20geodata%2C%20is,by%20latitude%20and%20longitude%20coordinates.)
* Sidecar - https://learn.arcgis.com/en/projects/build-a-sidecar-in-your-story/
* Guided Map Tour - https://storymaps.arcgis.com/collections/dd4c2e6d5c2a40dd98e881f6ba616605
* Explorer Map Tour - https://storymaps.arcgis.com/stories/2ed07d655eb64835b2244ef95da667fd
* Swipe - https://storymaps.arcgis.com/stories/4afb9aefc2ff43fd81db3f74ddbf05d0
* Timeline / TimelineJS - https://storymaps.arcgis.com/stories/701e58d3c43f4359af21fd91a224a0e2
* Express Map - https://storymaps.arcgis.com/stories/3dac3a051c2e40929a327619315d44d1
* Living Atlas - https://storymaps.arcgis.com/stories/820980061e124d71b19c7bc124390bef
# <a id = "day1"></a>Day 1 - The Deal
Overview of GPS - Ground stations keep track of 24 satellites and your device (phone, garmin, smart watch, etc) will ping the satellites and the ground station will also use trilateration to figure out not just location, but altitude and other factors. 

Trilateration description and overview

Overview of Storymaps - this will be a demo, mostly. The above terms after Geospatial data are all from Storymaps.

I pulled these images from here: https://gisgeography.com/gps-accuracy-hdop-pdop-gdop-multipath/ but they are very good at illustrating how both GPS and Trilateration works. 

So typically, we have our satellites in place and they refer to the ground stations and atmosphere. So it grabs signals from the time it takes to gether to get how high or low you are, where you're at, and more.

![](/images/gps/GPS-GDOP-good-850x603-1.png)

## What can interfere with GPS?

Satellite time - we have to account for the time it takes to deal with satillites and how long it takes to get a signal. For those of you who play online games, think about how lag is shown. Or if you play Niantic games, you'll see it on your player. 

![](/images/gps/GPS-Trilateration-1265x870.png)

Satellites are so close together you can't get an accurate space.


![](/images/gps/GPS-GDOP-poor-440x550.png)

The other issue is if things are in a bad space.
![](/images/gps/GPS-multipath-effect.png)

# Day 2 - Storymaps
### Resources
* [Planning your Storymap](https://www.esri.com/arcgis-blog/products/arcgis-storymaps/sharing-collaboration/planning-and-outlining-your-story-map-how-to-set-yourself-up-for-success/)
* [Best of 2020](https://www.esri.com/arcgis-blog/products/story-maps/sharing-collaboration/meet-the-2020-storymaps-competition-winners/)
* [Best of 2021](https://www.esri.com/arcgis-blog/products/story-maps/constituent-engagement/2021-in-arcgis-storymaps-wrapped/)
* [Best of 2022](https://storymaps.arcgis.com/collections/b374d444bb3340fb82165712903e4991)
* [Best of 2023](https://storymaps.arcgis.com/collections/68ba1955f063424884fc7c77dea8480e)
* [ESRI Course on Storymaps](https://learn.arcgis.com/en/projects/share-the-story-of-an-expedition/)

### Assignment 2
This assignment will see you using StoryMaps. I went over in class how to access StoryMaps but if you need some help figuring them out, please let me know.

For this assignment, please publish your storymap and paste the link in the text submission. 

What I want is the following: 

Select a Prompt (just 1)

1. **Prompt 1:** If you travelled around the world, what are the 10 or more places you'd stop along the way?
2. **Prompt 2:** Tell us, Show us, and locate a trip you went on recently. 

Once you have selected the prompt, i'll be treating this like a checklist (10 points each): 

1. At least 10 locations (on a map of some kind) with images that either you own, or are creative commons.
2. A timeline with pictures of said highlights.
3. At least 3 text blocks.
4. What your favorite part of the trip was. 
5. What you learned from the trip and why.
6. Where you will go next and why.

Your grade will also consist of 20 points devoted to cohesion, grammar/syntax, and if your images are yours or are creative commons / open.



---------------- Table of Contents ---------------- 

1. [Reading this Week](#reading)
2. [Concepts for This Week](#thisweek)
3. [Day 1 - The Deal](#day1)
4. [Day 2 - Geocaching](#day2)

---------------- Table of Contents ---------------- 
# <a id="reading"></a>Reading for this week
Bollnow - Human Spaces Introduction
[What are geospatial technologies?](https://www.aaas.org/programs/scientific-responsibility-human-rights-law/overview-geospatial-project#:~:text=Geospatial%20technologies%20is%20a%20term,were%20drawn%20in%20prehistoric%20times.)
[Geospatial - A Complete Introduction](https://www.heavy.ai/learn/geospatial#:~:text=Geospatial%20technology%20is%20used%20to,environmental%20events%20and%20socioeconomic%20trends.)
[What's in a Map?](https://www.geographyrealm.com/whats-in-a-map/)
[Coordinate Systems, Map Projections, and Transformations](https://pro.arcgis.com/en/pro-app/3.1/help/mapping/properties/coordinate-systems-and-projections.htm#:~:text=Geographic%20coordinate%20systems%20(GCS)%20are,latitude%20(y%2Dcoordinates).)
# <a id = "thisweek"></a>Concepts for This Week 
* Bar Scale - representative distance in reference to scale of a map (e.g. 1" = 1mil). 
* compass -  https://support.esri.com/en-us/gis-dictionary/compass
* Conformal Map - a type of map where angles, scales, and shapes on a map are preserved rather than adapted for the projection.
* direction -  https://support.esri.com/en-us/gis-dictionary/direction
* distance (or scale) - https://support.esri.com/en-us/gis-dictionary/scale
* GPS - https://support.esri.com/en-us/gis-dictionary/gps
* grids - https://support.esri.com/en-us/gis-dictionary/grid
* index - https://support.esri.com/en-us/gis-dictionary/index
* labels -  https://support.esri.com/en-us/gis-dictionary/label
* Map Scale - https://support.esri.com/en-us/gis-dictionary/scale
* Projection - When laying a globe down on a 2D surface, we have to adjust the shapes and angles of things. For example, we use the Mercator Projection but Authagraph can be a more accurate projection whereas the Gall-Peters Projection is far more equitable and deals with the various ways we've misrepresented information over time.
* Locator / Inset - https://support.esri.com/en-us/gis-dictionary/inset-map
* Way finding - https://support.esri.com/en-us/gis-dictionary/wayfinding#:~:text=Wayfinding%20consists%20of%20acquiring%20information,the%20cognitive%20component%20of%20navigation.

# <a id = "day1"></a>Day 1 - The Deal
Maps have been around for quite some time. We have some early maps content in the form of a wikipedia article: https://en.wikipedia.org/wiki/Early_world_maps. This article provides some neat context about early map use. We know that folks wrote on papyrus when that was created but mostly they used drawing on the ground, drawing on wood, or carving into stone and that is where things are now. 

The map I note in class is an influence map. We can see an influence map in action via EVE Online:
<iframe width="560" height="315" src="https://www.youtube.com/embed/JyQOhZYRswc?si=FXj1Mreg-Y5OB3Rz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 
Another way that folks used maps back before computers, paper, or anything else we can carry with us was how Rome used what they called itinerarium. We see these all over the place now mostly on highways, interstates, and state routes. We can find them here: https://en.wikipedia.org/wiki/Itinerarium

Now, the thing to know about technology is simple: incremental change in some kinds of technologies afford other kinds of changes. Another way to say this is, "stuff, it's always happening." I personally think about tech in the way of individuation or, "what it took for this thing with a name to be fully realized." This is a theory from a guy named Simondon who is just now getting translated into English from the early 1900s. https://en.wikipedia.org/wiki/Gilbert_Simondon

I bring this up because sometimes things take a LONG time to come about. Let's take the quest to figure out longitude because it took some 5000 years. By the bronze age, we had a pretty good idea of how to navigate around. We've seen current maps, maps of landmarks, and things. There wasn't a real need to have more than that as around the world navigation simply wasn't possible. 

So what is latitude and longitude. Let's approach that first. The easiest I can say is that latitude separates the earth into equidistant slices horizontally. Longitude treats the earth like an orange.

For latitude, you just find the middle point of our sphere, the equator, and then separate it north and south. For longitude, there's the prime meridian but where the prime meridian is is kind of arbitrary. 

![[/images/latlong.png]]

So when navigating, latitude is simple. We can figure out what band we're on and just make sure we stay on it. We can use celestial bodies to help us and that's fine. This isn't the case with longitude. 

I liked this quote: 

	Since longitude is a distance in the direction of the Earth’s daily rotation, the longitude difference between two places can be thought of as the difference between their local times as defined by the Sun’s position, local noon occurring when the Sun is highest in the sky. The Earth rotates through 360° in twenty-four hours, so one hour of time difference is equivalent to 15° of longitude. Put another way, the Earth turns through one degree of longitude every four minutes.

There's a lot here. So, the issue of longitude is that before clocks were invented as a unit of measurement, we really didn't have a way to calculate what would be needed for longitude. As a result, we can say that development of longitude hinged on the development of our current operationalization of time of which we have kind of gone nuts with: https://simple.wikipedia.org/wiki/Orders_of_magnitude_(time)

We got the clock from China who invented it in something like 700 AD. We also got the magnetic compass from China. Both of these inventions were seen and poached by Europeans and the clock especially factors heavily into the development of capitalism. The clock was important because suddenly we had numbers that could attach themselves to time and give them form. We didn't have morning, midday, and evening, we had 6am, 7am, 10pm, and so on. 

From here, we enter into a super fun moment. So consider this timeline: 

1. Bronze Age, we figure out navigating the seas.
2. We attempt to draw some world maps but they're mostly just europe, africa, and asia and the world is flat.
3. Ptolemy 150AD draws a world map with latitude and longitude.
4. The clock is invented in the 700s.
5. By the 1500s, we start seeing contests to figure out how longitude might work. From a modern lens, these were equivalent to the government saying, "I'll give you 5-10million dollars to figure this problem out."
6. 200 more years go by and in 1772, a guy in England named John Harrison brings us his clock. It looked like this: 
![[/images/harrison.jpg]]

Eventually, Harrison took this initial prototype and shrunk it down. The shrunken clock that could sit on a boat and remain accurate up to 3 seconds a day is an astounding achievement. It's important to note here that European clocks were mostly pendulum based at the time of Harrison's life in the 1700s and this was why it was so hard. 

![[/images/harrison4.jpg]]

And so here, we go back to Napoleon. We had now latitude, longitude, telegraphs, and what Napoleon gave us was rapid surveying for war as well as a desire to achieve better odds at battle. This confluence of developments, thousands of years in the making, provides us with what we can refer to as the geospatial turn.

The rest of class will be devoted to going over the vocab which you can click and read about above or listen in class though i'll mostly be sticking to the definitions but attaching them to the paper maps i'll bring in. 
# <a id="day2"></a>Day 2 - Geocaching
**Before we begin, there are 3 rules:** 

1. If it's blisteringly cold, this assignment will get put off.
2. Don't break anything.
3. Follow the rules of good geocaching:
    1. [https://infoedmonton.com/article/geocaching-101-geocaching-dos-and-donts/#:~:text=Be%20a%20good%20neighbour%20and,%2C%20damaged%2C%20or%20illegal%20caches.](https://infoedmonton.com/article/geocaching-101-geocaching-dos-and-donts/#:~:text=Be%20a%20good%20neighbour%20and,%2C%20damaged%2C%20or%20illegal%20caches.)

**Part 1:**

1. Download the Geocaching App:
    1. [https://www.geocaching.com/play/mobile](https://www.geocaching.com/play/mobile)
    2. SET UP ACCOUNT
        1. DO NOT PAY FOR IT
2. Find 5 Geocaches on RIT Campus
    1. Get their coordinates.
    2. [Convert them to 3 different coordinate systems.](https://coordinates-converter.com/en/decimal/43.156093,-77.557522?karte=OpenStreetMap&zoom=8 "Convert them to 3 different coordinate systems.")
    3. Take a selfie at the site.
3. Put the data into MyMaps on [Google Maps](https://www.google.com/maps/d/u/0/ "Google Maps").
    - Create a layer for your map.
    - Select a baselayer of your choosing.
    - Place a point near where your geocaches are.  
    - Place all of the coordinates in the notes.

**Part 2:**

1. Produce a report with the following:
    1. Page 1 has:
        1. Geocache names and Coordinates
        2. A screenshot of your map on google maps.
        3. A link to your map on google maps.
    2. Pages 2-6 has:
        1. Geocache Name Plus Coordinates in 3 styles (easiest is just lat long decimals, degrees, and Universal Transverse Mercator coordinate system or **UTMREF**).
        2. Map of Point with label (from the app).
        3. Selfie Image of folks at the cache.
2. Save to PDF.
3. Designated Course Rep submits PDF by due date.
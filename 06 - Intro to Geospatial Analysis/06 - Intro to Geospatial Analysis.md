---------------- Table of Contents ---------------- 

1. [Reading this Week](#reading)
2. [Concepts to Date](#todate)
3. [Concepts for This Week](#thisweek)
4. [Day 1](#day1)
5. [Day 2](#day2)

---------------- Table of Contents ---------------- 
# <a id="reading"></a>Reading for this week
Not a lot of readings this week. I had initially intended to do an exercise and go over Open Street Map but we'll move that back to disaster. Instead, I wanted to provide a few videos that are worthy of your attention. 

* [How to Perform Hydrology Analysis and Flood Risk Mapping in ArcGIS? A Complete Tutorial.](https://www.youtube.com/watch?v=0DVVihogMQ0&ab_channel=HealthGIS)
* [Geospatial Analysis for Retailers](https://www.youtube.com/watch?v=Ol0SvsF2kP0&ab_channel=CARTO)
* [Spatial Analysis with ArcGIS](https://www.youtube.com/watch?v=KOPpQicK3Hg&ab_channel=ArcGIS)
* [Traffic Data Analysis in GIS](https://www.youtube.com/watch?v=AEC37x04tcw&list=PLGZUzt4E4O2KQz9IxGKrEyKB8rA0UVx1W&ab_channel=ArcGIS)
* [Spatial Data Analysis and Its Role in GIS](https://www.linkedin.com/pulse/spatial-data-analysis-what-its-role-gis-vladimir-ovramenko#:~:text=Geospatial%20analysis%20plays%20an%20important,public%20health%20in%20various%20areas.)

Each one of these videos could be an entire course. If you're interested in this sort of thing, dig on in!
# <a id = "today"></a>Concepts for This Week 
* Geospatial Analysis - a form of computational analysis that uses geographic information, spatial data, location data, and increasingly, high-resolution imagery, computer vision, and other forms of AI to extract structured data that can be used for specific applications and industries. [From here](https://capeanalytics.com/blog/geospatial-analytics-what-is-it-how-can-it-give-you-a-competitive-edge/#:~:text=Geospatial%20analytics%20is%20a%20form,for%20specific%20applications%20and%20industries.)

# <a id = "day1"></a>Day 1 - Geospatial Analysis: What it is, what it does
The basis of GIS from ESRI is Google Maps + Excel at its most basic. However, what this comparison provides is incomplete. To make it more complete, we can say that GIS is _actually_ Google Maps + Excel + the Python Interpreter. 

You may wonder how and why Python is involved here and we won't specifically get into this in this course. Instead, we will discuss analyses that have been performed using the full breadth and depth of GIS and talk a little bit about how and what went into those analyses. 

For the most part, I have tried to grab a higher level analysis that has data that is available and with the help of a whole lot of tutorials, you could begin an analysis. First and foremost, at least for my time as a sort-of geospatial analyst, we tend to use the data from the United States Census. 

Collecting data is enormously expensive and any decisions to study something has to begin with finding or collecting it in some capacity. Here are a few fun repositories: 

* https://data.census.gov/
* https://catalog.data.gov/dataset/?metadata_type=geospatial
* https://data.world/datasets/geospatial
* https://freegisdata.rtwilson.com/
## Examples of Geospatial Analysis
From examining travel patterns in a municipality to trying to figure out where a new Starbucks or Target could go, there is an enormous amount of information out there that folks can crunch to figure this stuff out. We'll briefly go over a few of those things. 
### Travel Studies
Every decade or so, municipalities reform their strategic plan. For example, here's Rochester's: https://www.cityofrochester.gov/rochester2034/

They then contact a statistics and data gathering firm to perform a study of how people travel in the area. From here, they use the data to identify traffic patterns, where new roads or new subdivisions or strip malls or commercial zones could be located. They'll also look for areas of crime, areas of congestion, and look for ways to deal with them. You can read about a few of these projects here: 
* https://www.nrel.gov/transportation/secure-transportation-data/tsdc-atlanta-regional-travel-survey.html
* https://libguides.northwestern.edu/c.php?g=114808&p=748275
### Retailers
Retailers will use GIS for 2 distinct reasons: where to locate a store and where to locate items in a store. There is a TON of work on this from a variety of different spaces.
* https://www.youtube.com/watch?v=Ol0SvsF2kP0&ab_channel=CARTO
### Segregation
Most of our work on desegregating and correcting the history of our founding has been policy driven. While policy tends to try and force equity, there's still an absolutely huge amount of work to do. Geospatial analysis can provide us with a literal microscope to evaluate where that work is successful and not. 
Check out the following: 
* http://www.radicalcartography.net/index.html?chicagodots
* https://dsl.richmond.edu/panorama/redlining/map#loc=5/39.1779/-95.8425
### Disaster Planning and Mitigation
One of the oversights of humans in general is that we build things with little to no consideration of the world. The world then reminds us that things like water, fire, and earth can create massive problems for anyone nearby. To that end, we've really begun to work in and around the concept of "mitigation" or staging a bunch of resources and preparing for the inevitable events that will impact wherever we are. 

* https://www.linkedin.com/pulse/unleashing-power-geospatial-data-disaster-mitigation-guru-pavan?trk=article-ssr-frontend-pulse_more-articles_related-content-card
* https://www.linkedin.com/pulse/gis-disaster-management-vishwadeep-das
* https://www.esri.com/en-us/industries/emergency-management/solutions/disaster-resilience

# Day 2 - Data Manipulation
For this assignment, we're going to do something a little different than I had intended. From the past assignment, it became clear to me that the GIS software is almost totally new for you all.

And so, let's pivot a bit to get a bit more exposure to what GIS can do. We're going to add data to GIS from somewhere else, filter some data, and produce a new spreadsheet.

So, let's get into it. 

We are going to work off of a dataset of ALL Starbucks in the world as of 2014. That dataset can be found: [https://www.arcgis.com/home/item.html?id=33f0d1a9b4d6453e8f6110c9eb2c36d5](https://www.arcgis.com/home/item.html?id=33f0d1a9b4d6453e8f6110c9eb2c36d5)

You will be exporting this for ArcGIS Pro which is located on the right in the "Open in ArcGIS Desktop" menu.  

Once clicked, this will download a file named, "item.pitemx"

If you are on a machine with GIS installed, all you should have to do is double click it and it will open up a new project and then open up the file.

Your job is to do the following: 

1. Filter the Data for everything in the Rochester area. We discussed how to do this in class. Remember this: lower bound of zip codes, upper bound, US only.
2. Create 2 Layouts.
    - Layout 1:
        - Your name and the date.
        - Map of Starbucks in the Rochester area.
        - Data Table
    - Layout 2:
        - Explanation as to why some Starbucks are not included.
        - Did any of the Starbucks on your 2014 list close?
        - Provide the addresses of 2 Starbucks in or near Rochester that are not on the list.

Print both of these to PDF and combine them into 1 PDF. You can do this via Adobe Acrobat which everyone has access to with your student email account. 

Please submit that one item.
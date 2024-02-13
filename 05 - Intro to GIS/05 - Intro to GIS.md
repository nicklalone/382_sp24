---------------- Table of Contents ---------------- 

1. [Reading this Week](#reading)
2. [Concepts to Date](#todate)
3. [Concepts for This Week](#thisweek)
4. [Day 1](#day1)
	1. [We Finally Get Started](#getstart)
		1. [Introducing ArcGIS Pro](#intro)
		2. [Filetypes, extensions, and things](#filetypes)
		3. [UI Tutorial](#UItut)
			1. [The Barebones of Ribbons](#barebo)
		4. [Let's Explore Wellington](#welling)
		5. [How does it all work?](#howwork)
	2. [Let's Think About Rochester](#rochome)
		1. [Getting Started](#getstart)
		2. [What features do we want to highlight?](#highlight)
		3. [Doing it](#doing)

---------------- Table of Contents ---------------- 
# <a id="reading"></a>Reading for this week
Mostly this week, we are offering a bunch of tutorials and resources. 

# <a id="midterm"></a> Concepts This Week
* **Raster** - https://www.caliper.com/glossary/what-is-raster-data.htm
* **Vector** - https://www.caliper.com/glossary/what-is-vector-data.htm
	* **Discussion of Both**: 
		* https://www.gislounge.com/geodatabases-explored-vector-and-raster-data/
		* https://gisgeography.com/spatial-data-types-vector-raster/
		* https://www.esri.com/content/dam/esrisites/en-us/media/pdf/teach-with-gis/raster-faster.pdf
		* https://gis.stackexchange.com/questions/57142/what-is-the-difference-between-vector-and-raster-data-models
		* https://id.land/blog/raster-vs-vector-data-the-ultimate-guide
		* https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* **Scale** - https://www.caliper.com/glossary/what-is-a-map-scale.htm
* Data Model - https://spatialvision.com.au/blog-raster-and-vector-data-in-gis/
* Data Structure - https://support.esri.com/en-us/gis-dictionary/data-structure
* Cartesian Coordinate Systems - 
	* https://www.andrews.edu/~rwright/Precalculus-RLW/Text/01-01.html#:~:text=The%20Cartesian%20%2C%20or%20rectangular%20%2C%20coordinate,as%20(x%2C%20y)
	* https://support.esri.com/en-us/gis-dictionary/cartesian-coordinate-system#:~:text=%5Bcoordinate%20systems%5D%20A%20two%2D,by%20an%20x%2Cy%20coordinate
* Types of Layers
	* Thematic Layer - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map#:~:text=Isarithmic%20maps%2C%20also%20known%20as,of%20values%20of%20the%20field.
	* Coropelth - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* Proportional Symbol - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable.
	* Dot Density - https://www.axismaps.com/guide/dot-density
	* Isarithmic (heat) - http://wiki.gis.com/wiki/index.php/Isarithmic_map
* Types of Layers
	* **Thematic** - https://en.mimi.hu/gis/thematic_layer.html
		* Wikipedia has an excellent list of thematic layers: https://en.wikipedia.org/wiki/Thematic_map
	* **Coropelth** - https://doc.arcgis.com/en/insights/latest/create/choropleth-maps.htm
	* **Proportional Symbol** - https://wiki.gis.com/wiki/index.php/Proportional_symbol_map#:~:text=A%20Proportional%20symbol%20map%20is,to%20represent%20a%20quantitative%20variable
	* **Dot Density** - https://www.axismaps.com/guide/dot-density
	* **Isarithmic (heat)** - http://wiki.gis.com/wiki/index.php/Isarithmic_map
* **Map Scale** - https://education.nationalgeographic.org/resource/map-scale/
* **Map Projections** - https://www.gislounge.com/map-projection/
* **Generalization** - https://support.esri.com/en-us/gis-dictionary/generalization

# <a id="day1"></a>Day 1
## <a id ="getstart"></a>We Finally Get Started
So for the past couple of weeks, we've been stuck in a bit of a torpor. I didn't have permissions to show GIS in class unless I brought a windows machine to class. This led to a week of delaying new instruction. Now, I have the permissions for us to really begin running. 

What I thought i'd do this week is relatively simple: 

1. Introduce Map Concepts
2. Introduce the ArcGIS UI
3. Prompt everyone to explore with an assignment in class. 

So on Tuesday, we will explore GIS, on Thursday, we'll do an assignment. 

### <a id ="intro"></a>Introducing ArcGIS Pro (alternate things)
If the stuff we talk about in class doesn't work for you, give this tutorial a shot: 
* Part 1: https://www.youtube.com/watch?v=BbUctneHfKc&t=1558s&ab_channel=GeoDeltaLabs
* Part 2: https://www.youtube.com/watch?v=t7ZnT5NgqlM&ab_channel=GeoDeltaLabs

I also like this collection from RIT's own Brian Tomaszewski: 
* https://www.youtube.com/watch?v=zrFm5HzwPNw&list=PLtrmEEvdGsNqsQ5ZpOapSmVQklIG9Bu5W&ab_channel=GIScience

This is also a great starting tutorial:
* https://www.youtube.com/playlist?list=PLRrQArPWjCiXlwfR9wN2XAphIbj56GNCi 

# <a id="day2"></a>Thursday

### <a id ="welling"></a>Let's Explore Wellington
You can find the data for this here: https://pro.arcgis.com/en/pro-app/latest/get-started/introducing-arcgis-pro.htm?adumkts=social&utm_source=social&aduc=social&adum=external&aduca=social_technical&adusf=youtube

You can also find it in GIS itself. I'll show you how to do this.
### <a id ="uitut"></a>UI Tour

Here is a general appearance of the mapping windows.
![[/images/whole.png]]
**Ribbons** - this is the current way that ESRI has decided to collect and organize their commands and structure. At times, depending on the information in the window, you'll see different ribbons show up. 

**Map Explorer** - is the gist of GIS, where the map goes.

**Database Editor** - all data on the map, especially entities and vector data, come out of a csv file like R or SPSS or some stats package. You can add fields here, adjust entries, etc. 

**Python Editor / Jupyter Notebook** - This is ESRI's language of choice. Here, you can do all matter of visualization, machine learning, AI, or just geospatial analysis. For examples of python and GIS, see: https://automating-gis-processes.github.io/2016/Lesson1-Intro-Python-GIS.html

**Table of Contents** - took this from the GIS website: "The table of contents lists all the layers on the map and shows what the features in each layer represent. The map's table of contents helps you manage the display order of map layers and symbol assignment, as well as set the display and other properties of each map layer." https://desktop.arcgis.com/en/arcmap/latest/map/working-with-arcmap/using-the-table-of-contents.htm

Let's take a brief tour through the ribbons. One *important thing to note here* is that you can customize these much the same way as you can word's ribbons. 

### <a id="filetypes"></a>Filetypes, extensions, and things.
Just like a powerpoint file, the way you save, its file type and other options all have impacts on how your data is saved and transferrable. There's a good discussion here: https://pro.arcgis.com/en/pro-app/latest/help/projects/what-is-a-project.htm but we'll consolidate that information a bit.

* **GDB** = Every project has a default geodatabase, which is usually a new file geodatabase (.gdb) created with the project.

* **PPKX / APRX** = A project is stored on your computer as a file with the extension .aprx. By default, it is stored in a system folder created with the project. The project file is associated with a geodatabase and a toolbox. Other folders and files, such as the [project index](https://pro.arcgis.com/en/pro-app/3.1/help/projects/index-project-items.htm) and the [backup project file](https://pro.arcgis.com/en/pro-app/3.1/help/projects/save-a-project.htm#ESRI_SECTION1_090E953C44C54D35BC0DB35E35340FD4), are created with the project or during your ArcGIS Pro session. These files also contain: 
	* -   A connection to the [home folder](https://pro.arcgis.com/en/pro-app/3.1/help/projects/change-a-project-s-settings.htm#ESRI_SECTION1_3DEF4003F07E48B2A691C57FC4C692AC) (the system folder that contains the project file)
	-   A connection to the project's [default geodatabase](https://pro.arcgis.com/en/pro-app/3.1/help/projects/change-a-project-s-settings.htm#GUID-E40436B0-4B13-4DC3-A1C7-B0A815F406F0)
	-   A connection to the project's [default toolbox](https://pro.arcgis.com/en/pro-app/3.1/help/projects/change-a-project-s-settings.htm#GUID-9E5402D2-0050-4469-AC3B-880D99A36E0E)
	-   Connections to default [styles](https://pro.arcgis.com/en/pro-app/3.1/help/projects/styles.htm)
	-   Connections to default [locators](https://pro.arcgis.com/en/pro-app/3.1/help/data/geocoding/about-locators.htm)
	-   A connection to an [active portal](https://pro.arcgis.com/en/pro-app/3.1/help/projects/manage-portal-connections-from-arcgis-pro.htm#ESRI_SECTION1_1D170FE7526E4FCB8A36FAAD8A4D5D5B) if you are [signed in](https://pro.arcgis.com/en/pro-app/3.1/help/projects/sign-in-to-your-organization.htm) to ArcGIS Pro.

* **APTX** = these are template files.
  
* Default Filepath is always:  C:\Users\<username>\Documents\ArcGIS\Projects but you can change it. 

#### Use cases for GIS
There are around 4 ways to think about what kind of project and what kind of setup you want to worry about with regard to GIS. Those 4 approaches can be found here: https://pro.arcgis.com/en/pro-app/latest/help/projects/what-is-a-project.htm but I will paste them below: 

-   You work mainly alone. You create and save projects on your own computer. 
	- This is what we'll be doing in this class almost always.
-   You work with others on the same projects that are stored on a network drive.
	- We do have a network drive here at RIT. 
-   You and your colleagues work on different projects, but your projects use a common template for consistency in maps, layouts, and other items.
	- This is going to feel a lot like working for a software designer with a standard frame for coding.
-   You share maps, layers, and other project items with colleagues. You may also share entire projects.
	- Here, you have to decide if you want to send all the files or make them available online.

One final note: 
	Projects can't be copied, moved, renamed, or deleted using ArcGIS Pro commands. Using file system commands for these operations isn't supported (except to delete projects) and risks corrupting the project. To copy, move, or rename a project, share it as a project package or [save the project with a new name](https://pro.arcgis.com/en/pro-app/3.1/help/projects/save-a-project.htm#ESRI_SECTION1_3DF32703CF96472384AE757C155039FC).

Let's walk through GIS.

### <a id ="barebo"></a>Barebones of Ribbons
Ribbons for ARCGIS work the same way as those in the Office Suite from Microsoft. In fact, that seems to be the guiding light in terms of software design. What i'd probably call the GIS is a mix between the curated experience of Office with the power of something like PyCharm or even a simple piece of software like notepad++. 

Getting to know these ribbons is super important as it will help you do something very powerful: make the maps or analyze the maps you want and share them with others. At its most basic, we can see the following:

- **Map Ribbon:** Navigating, adding data, and selecting features 
- **Analysis Ribbon:** Performing spatial analysis 
- **Editing Ribbon:** Editing and creating new features in your map 
- **Share Ribbon:** Packaging or publishing a map layer or the map itself 

![[/images/map.png]]
**Navigate** - this is a group of commands that you can use to directly manipulate the view of the map. 
**Layer** - it does what it says. It adds layers, allows you to add data, and you can change the base map.
**Selection** - This does what it says. When you need to select things whether they be points, lines, polygons, or some other things, this will help you. It can be confusing when you're working with layers because (much like photoshop or anything in the adobe suite) sometimes what you want to select is under something or somethings. I liked this article: https://desktop.arcgis.com/en/arcmap/latest/map/working-with-layers/selecting-features-interactively.htm
**Inquiry** - 
**Labeling** - Allows you to go in and label your map. I know, i've used the word to define the word. Have a look at: https://pro.arcgis.com/en/pro-app/latest/get-started/label-your-map.htm
**Offline** - Makes your maps and things available without logging in. This part of the toolbar, at least for what we're doing in class, is probably a bit silly as you need to be online to work in GIS due to our license.

![[/images/insert.png]]
**Project** - Allows you to start making new layers or reports based on your map. 
**Layer Templates** - When you're making a new layer, you might use these to help make the busywork less...busy. https://pro.arcgis.com/en/pro-app/latest/help/layouts/layout-files.htm
**Link Analysis** - sometimes you need a way to deal with the various things that are linked together in your mind, or in the city's mind. What this does is basically network analysis but it can also do so much more: https://doc.arcgis.com/en/pro-intelligence/latest/help/link-analysis-with-arcgis-pro.htm
	These last 3 items are specific to reports.
	**Measurements** 
	**Styles**
	**Favorites**

![[/images/analysis.png]]
**Geoprocessing** - 
**Tools**
**Portal**
**Workflows**
**Raster**

![[/images/view.png]]
Generally, this tab of the ribbon is about manipulating what you see, getting your windows and panes in order, and everything related to how your map is currently looking.

**View**
**Link**
**Windows**
**Thumbnail**
**Accessibility**
**Annotation**
**Device Location**
**Scene**
**View Clipping**
**Navigation**

![[/images/edit.png]]
**Clipboard**
**Manage Edits**
**Snapping**
**Selection**
**Tools**
**Elevation**
**Corrections**
**Data Reviewer**

![[/images/imagery.png]]
**Ortho Mapping**
**Alignment**
**Analysis**
**Image Classification**
**Mensuration**
**Tools**
**Share**
**Motion Imagery**

![[/images/share.png]]
**Package**
**Share As**
**Status**
**Manage**
**Save As**
**Output**

![[/images/help.png]]
**Customize**
**Help**
**Performance**
**Contact Us**
### There are also Contextual Tabs in the Ribbon.
These will appear when your have selected things that require them.
Table
Data
Labeling
Appearance
...and more.

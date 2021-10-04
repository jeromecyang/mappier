---
layout: page
title: Portfolio
---

This page lists various visualization projects that Jerome has done prior to 2018.

## Smart Mapping

An intelligent system that recommends how you can visualize your geospatial data

![](https://blogs.esri.com/esri/arcgis/files/2020/02/SD_heatmap.jpg)

"We want to go one step further for you" is the motivation of this project. Instead of letting you set visualization method, color, symbol, etc step by step, ArcGIS.com is now going one step further for you. We analyze your data and recommend good ways to visualize them for you. By no means this means you lose your control over your visualization, but our smart default will make your visualization production process quicker and more enjoyable.

I was the primary prototype developer on this project, involving extensively in research and product version development. This technology has been published as a US patent.

* [Smart Mapping Home](https://www.esri.com/software/arcgis/smart-mapping) (overview & video)
* [Introducing Smart Mapping](https://blogs.esri.com/esri/arcgis/2015/03/02/introducing-smart-mapping/) (blog post)
* [Systems and methods for smart cartography](https://patents.google.com/patent/US20160246468A1/en) (US Patent US20160246468A1)

## Knowing your Customers with Pointillist

An revolutionary customer journey analytics platform

![](https://www.pointillist.com/wp-content/uploads/2017/05/Discover-Full-Size.png)

Nowaways, millions of web user events (such as clicking a button, checking out a URL, etc) happen and are recorded every day. Pointillist pulls all these events together to show the big picture behind the scene.

This platform was built as a big data analytics solution for non-technical users, and therefore there is significant amount of work on its front-end, as well as the web services to support the it. As a founding and primary developer, I have been in charge of the UI/UX, visualization, and REST services since the beginning of the product.

## Evolving Geo-Visualization at Esri, 2013-2014

Data Visualization with ArcGIS API for JavaScript

![](https://blogs.esri.com/esri/arcgis/files/2014/10/visualization-5-1.png)

"Let geographic data tell stories via the Internet" is this project's goal. As world-wide web becomes the primary media of maps and geographic information, how should traditional maps and cartography evolve to meet the emerging needs and challenges of web mapping?

Throughout the years of 2013 and 2014, we significantly expanded our web mapping platform with more intuitive, comprehensive and east-to-use API for developers. Now a pretty dot density map or a choropleth with opacity variation can take only a few lines of code. While many customers have taken these new tools to create their own cool pieces, we also built a bunch of pretty demos to prototype, to inspire and to explore the future of geospatial data visualization.

My blog posts

* [Data visualization with ArcGIS API for JavaScript](http://blogs.esri.com/esri/arcgis/2014/09/05/data-visualization-with-arcgis-api-for-javascript/)
* [Show Data by Unique Value](http://blogs.esri.com/esri/arcgis/2014/09/11/data-visualization-with-arcgis-api-for-javascript-show-data-by-unique-value/)
* [Enhancement Options](https://blogs.esri.com/esri/arcgis/2014/09/24/data-visualization-with-arcgis-api-for-javascript-enhancement-options/)
* [Show Data by Color](https://blogs.esri.com/esri/arcgis/2014/10/10/data-visualization-with-arcgis-api-for-javascript-show-data-by-color/)
* [Show Data by Size](https://blogs.esri.com/esri/arcgis/2014/12/01/data-visualization-with-arcgis-api-for-javascript-show-data-by-size/)

My conference videos

* [What's New for ArcGIS API for JavaScript (2014)](http://video.esri.com/watch/3840/whats-new-for-arcgis-api-for-javascript)
* [ArcGIS API for JavaScript, Mapping and Visualization](http://video.esri.com/watch/3843/arcgis-api-for-javascript_comma_-mapping-and-visualization)

Demos

* [One dataset, multiple ways to visualize](https://jeromecyang.github.io/bos3/vector.html)
* [Scale-dependent dot density map](http://developers.arcgis.com/en/javascript/samples/renderer_dot_density_multiple_classes/) (A web-based dot-density map I developed. Try zoom in/out to see how the dot value changes with scale.)
* [Choropleth map without class breaks](http://developers.arcgis.com/en/javascript/samples/renderer_color_ramp/) (No class break anymore - we just map it from the minimum to the maximum!)

## Angular-based Visualization: Urban Population of the World 2015

An attempt to manipulate SVG with Angular.js, and to show both quantity and percentage simultaneously

![](http://jeromecyang.github.io/home/images/urban-pop-2015.png)

I tried to achieve two goals in this visualization.

Graphically, a quantity and a percentage are displayed with one single graphic for each country. The bar length shows population, whereas 10 different colors are used to show various percentages. The countries are ordered from the most urbanized to the least, so the order in the sequence can help the audience grasp how urbanized a country is compared to others.

Technologically, this visualization was created with only Angular.js. No d3.js is used. The advantage of this approach is a more contemporary, declarative, succinct way to manipulate SVG elements (compared to d3.js or jQuery). Also Angular's native directives, such as ng-mouseenter, ng-if, provide easy access to trigger events or toggle elements.

You can check out the application [here](https://jeromecyang.github.io/bos2/urban-pop-2015/).

## AfricaMap

Web-based geospatial data visualization in collaboration with the [Center for Geographic Analysis, Harvard University](http://worldmap.harvard.edu/africamap)

![](http://jeromecyang.github.io/home/images/africa.png)

AfricaMap is an open-source web mapping platform designated for archiving, visualizing and integrating geospatial statistics particularly for Africa. One can easily find statistics from various organizations and governments, but how do we fit them together in one single platform?

As a GIS analyst at [Center for Geographic Analysis (CGA), Harvard University](http://gis.harvard.edu/icb/icb.do), I worked with African-Art-and-Architecture historian [Dr. Suzanne P. Blier](http://aaas.fas.harvard.edu/directory/faculty/suzanne-p-blier) to retrieve statistics from various sources, and explored the options to make these number "visible" on map. To handle data in various formats and qualities, I employed my fimilarity with data syntax and skills in programming for text processing to handle the data effectively and accurately. This is an ongoing project and all results are available at http://worldmap.harvard.edu/africamap.

* [AfricaMap](http://worldmap.harvard.edu/africamap)
* [Announcing 6 Digital Humanities Implementation Grant Awards](http://www.neh.gov/divisions/odh/grant-news/announcing-6-digital-humanities-implementation-grant-awards-july-2013) (July 2013)

## Map as a Communication Tool

Various thematic maps as storytelling media

![](http://jeromecyang.github.io/home/images/thumbnail/map1.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/map2.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/map3.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/map4.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/map5.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/map6.jpg)

A map with good graphic design can convey messages in an informative and vivid way. As both a cartographer and a graphic designer, making maps with proper design is what I am striving for. This section contains maps I made for various projects.

### How many rooms are in your house?

![](http://jeromecyang.github.io/home/images/map1.jpg)

### The ratio of owner-occupied houses

![](http://jeromecyang.github.io/home/images/map2.jpg)

### Creating conservation areas for red-legged frogs

![](http://jeromecyang.github.io/home/images/map3.jpg)

### Fishing ports and annual production

![](http://jeromecyang.github.io/home/images/map4.jpg)

### Shrinking air routes

![](http://jeromecyang.github.io/home/images/map5.jpg)

### Special college admission program

![](http://jeromecyang.github.io/home/images/map6.jpg)

## Visualization from Scratch: Air Pollutants Mapping

Beginning with collecting first-hand air quality data in the field

![](http://jeromecyang.github.io/home/images/thumbnail/air1.png)
![](http://jeromecyang.github.io/home/images/thumbnail/air2.png)
![](http://jeromecyang.github.io/home/images/thumbnail/air3.png)
![](http://jeromecyang.github.io/home/images/thumbnail/air4.png)
![](http://jeromecyang.github.io/home/images/thumbnail/air5.png)
![](http://jeromecyang.github.io/home/images/thumbnail/air6.png)
     
Air pollution mapping requires interpolation from point data. Instead of obtaining observations from existing monitoring stations, in this project we mapped air pollution from scratch - that is, we designed a monitoring network where the distribution of stations is optimized, went into the field to collect first-hand data, and explored the best way to visualize the data. Works included spatial optimization algorithm, experiment design, field particulate matter measurement, and visualization.

This project, which was proposed and coordinated by me, ultimately involved a interdisciplinary and collaborative effort of two professors and four graduate students with background in GIS, environmental science, physics, etc. It was awarded by Geller's Research Grant at Clark University.

* [Conference poster](https://jeromecyang.github.io/bos3/files/AirQuality_Poster4Research.pdf)
* [Full project report](https://jeromecyang.github.io/bos3/files/Mapping%20the%20Concentration%20of%20Ambient%20Air%20Pollutants%20for%20Central%20Massachusetts.pdf)

## GIS off the Shore: Eelgrass Mapping

Getting GIS on board with the Maine Department of Marine Resources

![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass1.png)
![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass2.png)
![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass3.png)
![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass4.png)
![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass5.png)
![](http://jeromecyang.github.io/home/images/thumbnail/eelgrass6.png)
     
Eelgrass (Zostera) is an vital species in coastal ecosystems. It provides nutritions for many shallow ocean animals, and consequently sustains the fishery economy in the state of Maine. The goal of [eelgrass mapping](http://www.maine.gov/dmr/rm/eelgrass/index.htm) is to investigate, monitor and visualize eelgrass distribution.

Before entering the field, potential eelgrass patches were identified on low-tide aerial imagery and digitized in ArcGIS. While in the field, we drove a boat, navigated by ArcPad to visit every location we identified, and recorded the actual condition with notes, GPS tracklogs, photos and videos. After the field work, the data collected were summarized and released as public-accessible information in a web mapping application.

## Web GIS Crowd-sourcing

Developing interactive, collaborative web mapping applications

![](http://jeromecyang.github.io/home/images/crowdsource1.png)
![](http://jeromecyang.github.io/home/images/crowdsource2.png)
 
Internet provides an effective way for multiple people to contribute geospatial data to one database. I participated in two crowd-sourcing GIS projects.

Maine Elver Map was designed for marine patrol officers to report locations where illegal harvesting of elvers (young eels) were found. It successfully gathered 85 locations reported by about 10 officers. It employed Google Maps API and Google Fusion Table to provide a user interface and a publicly accessible database. Any input data was immediately reviewed by administrators via email to ensure the quality of the data.

[QianTang River Map](http://www.qiantangriver.org/) was built to gather succeptible water pollution activities along the river. This project was initiated by [Green Zhejiang](http://www.greenzj.com/), an environmental protection NGO in China. I worked as the primary technical lead to implement the system. Built upon [Ushahidi's CrowdMap](http://www.ushahidi.com/) platform, it leverages open-source tools to provide a zero-cost and easy-to-use solution to the NGO's need for crowd-sourcing.

## When Something is Built

3D terrian visualization of prospective constructions

![](http://jeromecyang.github.io/home/images/thumbnail/construction1.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction2.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction3.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction4.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction5.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction6.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction7.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction8.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction9.jpg)
![](http://jeromecyang.github.io/home/images/thumbnail/construction10.jpg)
         
In the beginning of the 21st century, Taiwan government proposed several "mega projects", including a highway crossing a 10,000-ft mountain ridge, a 4000-acre artificial reservoir for industrial water supply, etc.

To simulate these projects' impact on the landscapes, I independently created 12 3-D visualization scenes to give the public a chance to "preview" the changed landscapes when the construction is complete. These scenes were made by scanning and georeferencing maps from the project plans, retrieving Google's sattelite imagery, overlaying data with digital terrain model (DTM) in ArcScene, and post-export editing with Corel PhotoImpact.
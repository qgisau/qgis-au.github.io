+++
title = '008 - 9th April 2024'
date = 2024-04-09T07:07:07+01:00
draft = false
+++

### This week we view GIS in the wild, harvest some tips from the Socials, and congratulate Chartis for becoming a QGIS Sustaining Member!
### Events are on this week
- Perth: Wednesday night
- Newcastle: Thursday
More information below in Events.

## QGIS News
- Firstly, a big shout-out of Thanks to Chartis Technology as it becomes a QGIS Sustaining Member. Read more about it [here](https://chartistechnology.com/proud-sustaining-members-of-the-qgis-project).  
![](qsmallsustaining.png)

- GDAL has released a new version: [v3.8.5](https://github.com/OSGeo/gdal/blob/v3.8.5/NEWS.md)

## GIS Sightings
- [Hard Quiz s9 ](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://iview.abc.net.au/show/hard-quiz/series/9/video/LE2231V008S00&ved=2ahUKEwjcxLquybOFAxX11TQHHTsuDWoQwqsBegQIChAE&usg=AOvVaw3e3ZTLtvdS14DNLn7lY4uR): The contestants, Bronwyn's expert topic was the Mercator Projection - see Tom Gleeson be normal and react like everyone else when we start to discuss GIS.
![](/hardquiz.png)  


- [Typo](d) has their mappy designs back with green  notebooks and pencil cases in the contour design - but not online - only in store.  
![](/typo.png)

## Resource Sharing - Update
Our QGIS AU Github repo is a great place to share resources for Australian QGIS operations and we are working towards connecting it to the QGIS Style Hub as well. In the meantime, you can load up your collection under the [QGISAU-Resources](https://github.com/qgisau/QGISAU-Resources) collections folder and add it into the readme.
In regards to which Style hub to use...let's go with this [one](https://plugins.qgis.org/styles/).
![](/style.png)

## QGIS Tips and Tricks
- From the community - there was a need to update the length of a line once it was generated and instead of doing it via the Field Calculator, here is the nifty solution via the attribute forms [Update Geometry Attributes in QGIS](https://gis.stackexchange.com/questions/389709/automatically-updating-geometry-attributes-in-qgis-without-using-virtual-fields) Thanks to Iain and Andrew!

- [Rendering Print Layouts from QGIS Models](https://spatialthoughts.com/2024/04/08/rendering-print-layouts/) Another great tutorial from Spatial Thoughts that builds a model that will automatically:
  - Download the latest shapefile of active fires from FIRMS.
  - Extract fires intersecting the continental US.
  - Style the layer using a pre-configured QGIS style file.
  - Render a pre-configured Print Layout.

- [Automate your Polygon's colour strokes](https://x.com/helenmakesmaps/status/1745834461164347676). The following will undertake this for all your project work using darker(color,factor):
  - In your Project properties, go to Styles and click on Fill/ Configure symbol
  - Next to Stroke color, click on the data defined drop down box and select Edit
  - Enter the following expression: darker(@symbol_color, 120)

- Use GeoNadir in your [QGIS for drone mapping](https://x.com/GeoNadirAu/status/1777456432117411884)  A quick method to add in your GeoNadir data by copying the TMS link and pasting it into your XYZ tiles.

- [Tilted Perspectives in QGIS](https://proj.org/en/9.4/operations/projections/tpers.html) when you need to show a globe.

## QGIS Plugins
- [SciPy ](https://docs.scipy.org/doc/scipy/index.html) SciPy is built to work with NumPy arrays, and provides many  user-friendly and efficient numerical routines, such as routines for  numerical integration and optimization. Together, they run on all  popular operating systems, are quick to install, and are free of charge.  NumPy and SciPy are easy to use, but powerful enough to be depended  upon by some of the world's leading scientists and engineers. If you  need to manipulate numbers on a computer and display or publish the  results, give SciPy a try!

- [MapSwipe](https://github.com/lmotta/mapswipetool_plugin) This plugin is a map tool for swipe active layer, for example, you can see the difference with others layers below. The active layer, or group, will appear above all others.

## Events
**New Event Tomorrow night! Geogeeks Talks: the GIS journey**
- April 10, 2024  5:30 pm - 8:00 pm at Riff (Spacecubed), 45 St Georges Terrace, Perth WA 6000, Australia
- Come for an evening of short talks from local geospatial practitioners. This time we’re focused on the GIS journey, featuring stories from  students & early career professionals. We’ll hear about drones,  metadata, and learning QGIS through the eyes of people finding their way  into the geospatial community.
- https://geogeeks.org/2024/0410_gis-journey.html
- Sponsored by OSGeo Oceania.

**Newcastle GeoRabble**
- This Thursday

**Melbourne GeoRabble**
  - Next week on Thursday

Check out the [Events Calendar](https://qgis-australia.org/events/) for more information

## Any budding radio stars doing their PhDs?
[ABC Radio Top 5 Media Residency Program](https://www.abc.net.au/listen/programs/top5/the-abc-is-seeking-australia-s-best-and-brightest-young-minds/103465016) Each year, the program puts out a call to Australia's higher  education sector and research organisations to find the TOP 5 PhD  scholars in three categories: Humanities, Science and the Arts: TOP 5 – ABC Media Residency Program — ABC listen. The  researchers-in-residence will spend two weeks working alongside the  ABC's award-winning journalists and producers, learning first-hand about  the craft of delivery through radio, television and digital platforms.
- A past mappy one was [Dr Rohan Fisher](https://www.abc.net.au/listen/programs/futuretense/people-have-to-solve-the-climate-crisis-technology-no-answer/102897170) who has worked with our friend in Fiji and focuses on Fire management in the NT.

## Newsletter Content
Do you want to contribute some content? You can provide an interest story, a report on an event or a technical instruction. Head to the [Content Contribution form](https://forms.gle/2DPXq5Y8wqnc7KhS8) to fill in your contribution. We will then contact you to run through the contribution.

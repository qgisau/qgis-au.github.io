+++
title = '010 - 24th April 2024'
date = 2024-04-24T07:07:07+01:00
draft = false
+++

### This week we pay respect to our fallen, our veterans and serving Members for Anzac Day, learn how to make a Firefly map, delve into raster tools and get involved in FOSS4G Oceania!

## From the QGIS Community
- [QGIS Community - Official Virtual Group](https://www.facebook.com/groups/qgiscommunityofficialvirtualgroup/), an official QGIS.ORG channel on facebook, has surpassed 81K members worldwide! This is another great resource to keep in your back-pocket.

## Australian Military Mappers
Going through the AWM records, I found possibly about 30 Surveyors who had lost their life whilst serving, here are two, Eric Thorpe and Ashley Birt.  
[Eric Thorpe](https://www.awm.gov.au/collection/R1694618): 1944 WW2 PNG  
[Ashley Birt](https://www.awm.gov.au/collection/R1633104): 2011 Afghanistan  

Out of interest - if you were to serve today, here are the roles available:  
**Navy:** [Hydrographic Systems Operator](https://www.adfcareers.gov.au/jobs/navy/hydrographic-surveyor)  
**Airforce:** [Intelligence Analyst -Geospatial](https://www.adfcareers.gov.au/jobs/air-force/intelligence-analyst-geospatial)  
**Army:** : [Geospatial Intelligence Analyst](https://www.adfcareers.gov.au/jobs/army/geospatial-intelligence-analyst)  
Read up on the history of the [Royal Australian Survey Corp](https://en.wikipedia.org/wiki/Royal_Australian_Survey_Corps) that mapped most of Australia and a bit of Oceania. I heard of sorties - up until the '90s -  that went to survey islands where you spent a month surveying - well one week surveying and the rest fishing. Ahh the life before computers and satellite imagery!  

## Hints and Tips
### Firefly Map
Check our Helen makes Maps tutorial on how to make Firefly maps.
<blockquote class="twitter-tweet" data-media-max-width="560"><p lang="en" dir="ltr">⚡️Create a firefly map in QGIS in 50 seconds! All you need is:<br><br>🌃 A dark base<br>🗺️ A point layer<br>👀 This video! [sound on - if you can bear my voiceover!] <a href="https://t.co/1Z3lzzpBsx">pic.twitter.com/1Z3lzzpBsx</a></p>&mdash; Helen McKenzie (@helenmakesmaps) <a href="https://twitter.com/helenmakesmaps/status/1773384707536761077?ref_src=twsrc%5Etfw">March 28, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>   

See the [Original post](https://x.com/helenmakesmaps/status/1773384707536761077) and over at [Geobserver](https://geoobserver.de/2024/04/qgis-tipp-die-gluehwuermchen-karte/?fbclid=IwZXh0bgNhZW0CMTAAAR3af2Rt-FZ55_M3Q5ugkCrn0aJfqQRovqHNCFWNKmpRyN_UNQv5ZtyyCQs_aem_AQKhBL_L7ajo2eYB1HGOAksQBkeVZDOXLZgAqAQohGyBxKe5aJQgmOgnBSEfPJ7A30LKQvB15RQXTEEr-uNB2kQl), they have already done the hard work for you and created the [QML](https://download.geoobserver.de/QGIS_Firefly_Style_v01.qml.zip).

### Working With Landsat Surface Reflectance Data in QGIS
Robert Simmon, from the USA, who specialises in visualizing satellite imagery using GDAL shows us how to [work with Landsat Surface Reflectance data in QGIS](https://medium.com/@robsimmon/working-with-landsat-surface-reflectance-data-in-qgis-13e44e68c217) by L.



## Plugins
### Orfeo ToolBox
Remote Sensors! [Orfeo ToolBox](https://www.orfeo-toolbox.org/otb-works-with-qgis-3-36/ ) has previously been packaged with QGIS but since 3.36, it will be available now as a [plugin](https://www.orfeo-toolbox.org/otb-works-with-qgis-3-36/) which you can download from the QGIS Plugin Manager. It can process high resolution optical, multispectral and radar images  at the terabyte scale. A wide variety of applications are available:  from ortho-rectification or pansharpening, all the way to  classification, SAR processing, and [much more](https://www.orfeo-toolbox.org/CookBook/Applications.html)!

***The following plugins were suggested by our helpful community to help stitch together raster data (plans) prior to georeferencing.***
### Freehand raster georeferencer
[Freehand raster georeferencer](http://gvellut.github.io/FreehandRasterGeoreferencer/) allows you to stretch/rotate raster images.
### Gimp Selection Feature Plugin
Gimp is an OS tool similar to Adobe Illustrator and interacts with QGIS quite well such as .qml and .svg creation. This plugin provides [Gimp Selection Feature Plugin](
https://github.com/lmotta/gimpselectionfeature_plugin/wiki) is great for interacting and creating a polygon using the gimp tools such as Fuzzy Select. 
*Other software options apart from GIMP include [Paint.net](https://getpaint.net/) and for image distortion [Hugin](https://hugin.sourceforge.io/) - here's a [tutorial](
https://hugin.sourceforge.io/tutorials/scans/en.shtml) for it.*

## FOSS4G SotM Oceania 2024 Hobart, 5-8th November
[Design the Logo](https://2024.foss4g-oceania.org/#/logo-competition) and get yourself free tickets to the conference and the dinner.  
The [Travel grant Program](https://docs.google.com/forms/d/1NNPSqYvYDGnbr7u6Fz8bDGfQ8m5m49gbCzBPAs9kORI/viewform?edit_requested=true), often referred to as the 'TGP' is open if you require assistance to attend.  
[Enter a presentation](https://2024.foss4g-oceania.org/#/call-for-papers) - there are 20 minute long presentations and  short 5 minute presentations called 'Lightning talks'. If you have found a cool way to do something, have an interesting project or just want to celebrate what you love about Open Source - including journeys, this is your time to shine. The Lightning Talks are a great way to either pitch a new idea or tool, or talk about your mapping hobby, or do a review on an event you attended.   
Here are some pictures to inspire you!  
 ![2018 icebreaker](/images/icebreaker2.jpg)
 ![2018 sponsors](/images/2018_sponsors.jpg)
 ![2018 talk](/images/2018_talk.jpg)
 ![2019 workshop](/images/2019_n_workshop.jpg)
 ![2019 talk](/images/2019_talk.jpg)
 ![2019 community day](/images/2019_comm_day.jpg)
 ![2023 dinner](/images/2023_dinner.JPG)

## Grant searching
Do you need funding or looking to fund a development? Use the list to see whether there are like-minded people/groups that can ban together. This is done extremely well by the local QGIS User Groups in Switzerland, Denmark and the UK to fund regional development. If you would like to have yours listed here, email the list with the details. 

Here are some current opportunities that have approached North Road. We would like to see if there is interest in the community and if anyone has a lead on grants that may help fund development.
- Open Drone Map QGIS Integration
- Bathymetric Survey QGIS Tools Opportunity, particularly for seagrass exploration.

## Newsletter Content
Finding these emails boring and want to contribute some content? You can provide an interest story, a report on an event or a technical instruction. Head to the [Content Contrbution form](https://forms.gle/2DPXq5Y8wqnc7KhS8) to fill in your contribution. We will then contact you to run through the contribution. 

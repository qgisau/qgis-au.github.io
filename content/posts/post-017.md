+++
title = '017 - 19th June 2024'
date = 2024-06-19T07:07:07+01:00
draft = false
+++
A lot has been happening recently with QGIS and OSGeo and this is a bumper issue!   
## QGIS AU news
### QGIS AU User Conference
We are looking for presenters of the following sessions:
- Ask me anything
- QGIS Server for WebGIS (keen for a presenter here)
- Create a Longplot Atlas in QGIS
Would you like to see something else presented? Let the email list know.
We would like to get a group together to help organise this so let us know if you would like to be involved. First meeting will be in August. 
### Resources tags
[Resources tags #429](https://github.com/qgis/QGIS-Django/pull/429) are coming soon for the [QGIS Hub](https://plugins.qgis.org/styles/?order_by=-upload_date&&is_gallery=true). Soon we will be able to load up and tag those styles for Australia and Oceania. 

## QGIS Project News
### QGIS Grant Program
An additional project - [QEP#248 Authentication System: allow Database storage for authentication DB](https://github.com/qgis/QGIS-Enhancement-Proposals/issues/248) has been funded thanks to donations from the community - read more [here](https://blog.qgis.org/2024/06/14/qgis-grant-programme-2024-update-no-2/).
### QGIS User Conference 
The [schedule](https://uc2024.qgis.sk/schedule/details/) is released, hopefully all will loaded onto YouTube afterwards. This one in particularly will be interesting, 
[The case of transforming attitude towards open source in public administration](https://talks.osgeo.org/qgis-uc2024/talk/NDHZX3/)
### Jupyter and QGIS
[ESA funds the consortium made up of QuantStack and Simulae Research lab to develop real-time collaboration and collaborative editing for GIS workflows in Jupyter and QGIS](https://blog.jupyter.org/jupytergis-d63b7adf9d0c)

## OSGeo News
### FOSS4G Oceania 2024
[CFP](https://2024.foss4g-oceania.org/#/call-for-papers) closes soon on 15th July. We are putting in for a morning and afterboob course.  
Have you got a talk you would like to present or something fun for a lightning talk?
### Sol Katz Awards
Call for Nominations are open for the [Sol Katz Awards](https://discourse.osgeo.org/t/sol-katz-award-for-geospatial-free-and-open-source-software-call-for-nominations/30793). The Sol Katz Award for Free and Open Source Software for Geospatial  (FOSS4G) will be given to individuals who have demonstrated leadership  in the FOSS4G community. Recipients of the award will have contributed  significantly through their activities to advance open source ideals in  the geospatial realm.
### OSGeo8
OSGeo8 is a server that holds Grass amonst other things -  was restarted this week - so hopefully there are some improvements there - [see if this impacts you](https://wiki.osgeo.org/wiki/SAC_Service_Status#osgeo_8)

## Hints and Tips
### Succession planning in QGIS 
An [article](https://qgis-australia.org/qgis/succession-planning/) by Em Hain which was spurred on by future thoughts on what to do for succession planning, especially if creating a QGIS plugin as part of an organisation. 
### QLD Data Users
There are changes coming to the qld govt topo schema, so if you are reliant on the current format, perhaps think about whether you should keep a local copy until you move over to the new changes. [Here is a list of those datasets with changes](https://spatial-qld-support.atlassian.net/wiki/spaces/SDS/pages/581140492/Topographic+data+schema+changes). The changes are still in progress. A new schema, which can be downloaded, will be finalized by July 2024.
### Working with large datasets
These are some hints drawn from the recent QGIS User list for a user who needed to generate vector tiles of a polygon shapefile of census tracts for California and QGIS kept crashing:
- Repoject the layer to EPSG: 3857 (the default projection of vector tiles) before generating the vector tiles
- Format should be a geopackage or move to PostGIS
- Spatial Index exists - Layer Properties and under Source, click Create Spatial Index.
- Simplify the tables - remove anything you don't need
### QGIS Corner Series
Felt, flagship sponsors of QGIS, have created a [QGIS Corner](https://youtube.com/playlist?list=PLulpFBGeM9D4TPdXnldfLS6iXRxsqzLob&si=xm3k_P-T-Z6CfimU) series utilising some great talents for some hints and tips QGIS.
![QGIS Corner Series](/images/qgis-core.png)
## Support Disaster relief mapping
- Flood mapping for Afhanistan, DRC and Brazil
- Landslide mapping for Enga Province, PNG
- Volcano Eruption in Kanlaon, Philipines

Check out the [HOTOSM Tasking Manager](https://tasks.hotosm.org/explore) to get started. 

## EVENTS 
 **QGIS Open Day** 28th June  
[Brisbane Geospatial Network](https://www.linkedin.com/groups/4182934/) 1st Wednesday of the Month  
[Introduction to QGIS](https://shop.adelaide.edu.au/konakart/Conferences---Events/Faculty-ECMS/NExUS-Professional-Development-Workshop%3A-Introduction-to-QGIS-2024/QGIS/2_3439.action) Course , Jack Maughan (Datarock), 4-5th July, University of Adelaide  
**Brisbane GeoRabble** 9th July, Charming Squire  
[QGIS User Conference](https://uc2024.qgis.sk/), Bratislava, Slovakia: 9-10th September  
**2024 QGIS AU User Conference**, Hobart: 4th November  
[FOSS4G SotM Oceania 2024](https://2024.foss4g-oceania.org/) Hobart: 5-8th November  
[Everything Open 2025](https://2025.everythingopen.au/), Adelaide: 20-22 January 2025  
 **2025 QGIS AU User Conference**, Norrköping Sweden: early June  
 **2025 FOSS4G Conference**, Auckland Aetearoa New Zealand: November  
 
 ***Check the [Events](https://qgis-australia.org/events/) for more information.***
 
## Newsletter Content
Finding these emails boring and want to contribute some content? You can provide an interest story, a report on an event or a technical instruction. Head to the [Content Contrbution form](https://forms.gle/2DPXq5Y8wqnc7KhS8) to fill in your contribution. We will then contact you to run through the contribution. 

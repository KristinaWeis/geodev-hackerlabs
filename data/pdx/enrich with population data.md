###Enrich with Population Data

ArcGIS Online allows you interactively GeoEnrich your data with [social demographic and business data](https://developers.arcgis.com/en/features/geo-enrichment/). You can use the [raw REST API](http://resources.arcgis.com/en/help/arcgis-rest-api/index.html#/GeoEnrichment_Service_Overview/02r30000021r000000/) but the easiest way to do accomplish this is to use the Map Viewer and the field data interactively.

In this lab you will add enrich neighborhood polygons with population data.

###Steps

1. Go to [developers.arcgis.com](http://developers.arcgis.com) and login.

2. Add the existig [Portland Neighborhoods layer]() into the Map Viewer.

3. Use `Perform Analyses > Data Enrichment` to add 2014 Population to the dataset.

 * Search for and select the `2014 Total Population (ESRI)` field

4. Now `Run Analysis`.

5. Click on the new layer and expore the new population fields added to each neighborhood.

Challenge: Explore the other enrichment fields available.
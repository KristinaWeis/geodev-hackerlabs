###View Layer Data via REST

All of your layers are [ArcGIS REST feature services](http://resources.arcgis.com/en/help/arcgis-rest-api/index.html#/Feature_Service/02r3000000z2000000/). You can explore the underlying data with the REST API or the default web page that shows the metadata and exposes some query functionality. 

###Steps

1. Go to [www.arcgis.com](http://www.arcgis.com) and login.

2. Go to `My Content`.

3. Select a feature layer.

4. Click on the url for the layer.  It should look something like this:

```
http://services.arcgis.com/uCXeTVveQzP4IIcx/arcgis/rest/services/Bike_Parking/FeatureServer/0
```

5. Explore the meta data.

6. At the bottom of the page, try the `Query` functionality.

e.g.
```
Where: 1=1
Out Fields: *
Format: HTML
```

7. Click `Query (GET)`

Challenge: Try a number of other queries and different return formats.
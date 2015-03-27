###Create Data

[ArcGIS for Developers](http://developers.arcgis.com) allows you to interactively create and publish hosted web services (feature services) to the cloud. All you need to do is specify the feature service name and fields and then save it. You can add data to the service interactively with the Map Viewer or with other ArcGIS apps e.g. ArcGIS Collector or via custom apps.  

In this lab you will create a new point feature service and add data to it.

###Steps

1. Go to [developers.arcgis.com](http://developers.arcgis.com) and login.

2. In `Hosted Data`, use `New Feature Service` to create a new dataset. 

Specify the following:

```
 * Title: PDX Points
 * Description: PDX Points
 * Type: Points
 * Tags: Portland
```

Add the following fields:
  
```
 * Name (string)
 * Type (string)
 * Date (date)
```

 NOTE: You can create as many fiends you want.

5. Choose any symbol and publish. 

6. Click `Edit in ArcGIS Online`. This should load the layer into the Map Viewer.

7. Zoom to Portland, USA.

8. Click `Edit > New Feature` and add some points to the dataset.


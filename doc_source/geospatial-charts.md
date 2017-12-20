# Using Geospatial Charts \(Maps\)<a name="geospatial-charts"></a>

Use geospatial charts to show differences in data values across a geographical map\. The map allows you to zoom in and out\. As you zoom in closer, you can see more geographical features\. The map retains the chosen zoom level and size\. 

Each circle represents a geographical location on the map chart\. This can be latitude and longitude, or geographical components such as state or city\. The size of the circles represent the magnitude of the field in the **Size** well, in relation to other values in the same field\. The color of the circles represents the values in the **Color** well\. The field in the **Color** well displays in the legend, if you choose to display one\.

Here is a sample of a map chart\. The latitude, longitude, country, state, and city are identified by a place marker icon, showing that they are a geospatial data type\. State and city are inside of a hierarchy named Geo\. Data types must be correctly configured in the data set before geospatial mapping can work\. Hierarchies are optional\. They allow QuickSight to resolve locations on the map, in the case of any ambiguities\. If the data types are correct, the mapping can work for supported geographies without hierarchies\.

For more information about setting up geospatial data types and hierarchies, see [Adding Geospatial Data](geospatial-data-prep.md)\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/quicksight/latest/user/images/geo-mapchart-sample-1.png)

Use the following table to understand the features supported by geospatial maps\.


****  

| Feature | Supported? | Comments | For More Information | 
| --- | --- | --- | --- | 
| Legend display | Yes | Displays contents of the field in the Color well | [Displaying the Visual Legend](formatting-a-visual.md#displaying-the-visual-legend) | 
| Changing the title display | Yes |  | [Displaying a Visual's Title](formatting-a-visual.md#displaying-visual-title) | 
| Changing the visual colors | Partial | You can change the color of the circles on the map, but not for individual values\. | [Changing Visual Colors in Amazon QuickSight](changing-visual-colors.md) | 
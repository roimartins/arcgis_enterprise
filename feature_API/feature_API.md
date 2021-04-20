
## The Feature service API for a layer published in ArcGIS Server can be used to query based on geometry relationships

####  POINT Geometry to be intersected 


```shell


https://citdevarcgis01.corp.cefas.co.uk/server/rest/services/Hosted/Marine_Plan_Areas_MMO/FeatureServer/0/query?where=&objectIds=&time=&geometry=%7B%0D%0A++++%22x%22%3A+2.475000000000051%2C%0D%0A++++%22y%22%3A+52.875000001000075%0D%0A+++%7D&geometryType=esriGeometryPoint&inSR=&spatialRel=esriSpatialRelIntersects&distance=&units=esriSRUnit_Foot&relationParam=&outFields=info+&returnGeometry=true&maxAllowableOffset=&geometryPrecision=&outSR=&havingClause=&gdbVersion=&historicMoment=&returnDistinctValues=false&returnIdsOnly=false&returnCountOnly=false&returnExtentOnly=false&orderByFields=&groupByFieldsForStatistics=&outStatistics=&returnZ=false&returnM=false&multipatchOption=xyFootprint&resultOffset=&resultRecordCount=&returnTrueCurves=false&returnCentroid=false&sqlFormat=none&resultType=&datumTransformation=&f=html
```

####  POLYGON (ring) Geometry to be intersected 


```shell 

https://citdevarcgis01.corp.cefas.co.uk/server/rest/services/Hosted/Marine_Plan_Areas_MMO/FeatureServer/0/query?where=&objectIds=&time=&geometry=%7B%0D%0A++++%22rings%22%3A+%5B%0D%0A+++++%5B%0D%0A++++++%5B%0D%0A+++++++2.4500000000000455%2C%0D%0A+++++++52.90000000100008%0D%0A++++++%5D%2C%0D%0A++++++%5B%0D%0A+++++++2.500000000000057%2C%0D%0A+++++++52.90000000100008%0D%0A++++++%5D%2C%0D%0A++++++%5B%0D%0A+++++++2.500000000000057%2C%0D%0A+++++++52.85000000100007%0D%0A++++++%5D%2C%0D%0A++++++%5B%0D%0A+++++++2.4500000000000455%2C%0D%0A+++++++52.85000000100007%0D%0A++++++%5D%2C%0D%0A++++++%5B%0D%0A+++++++2.4500000000000455%2C%0D%0A+++++++52.90000000100008%0D%0A++++++%5D%0D%0A+++++%5D%0D%0A++++%5D%0D%0A+++%7D&geometryType=esriGeometryPoint&inSR=&spatialRel=esriSpatialRelIntersects&distance=&units=esriSRUnit_Foot&relationParam=&outFields=info+&returnGeometry=true&maxAllowableOffset=&geometryPrecision=&outSR=&havingClause=&gdbVersion=&historicMoment=&returnDistinctValues=false&returnIdsOnly=false&returnCountOnly=false&returnExtentOnly=false&orderByFields=&groupByFieldsForStatistics=&outStatistics=&returnZ=false&returnM=false&multipatchOption=xyFootprint&resultOffset=&resultRecordCount=&returnTrueCurves=false&returnCentroid=false&sqlFormat=none&resultType=&datumTransformation=&f=html

```

# Open Urban Mapping project

Introduction
-------------
Now it's possible to digitize all buildings in the World using Computer vision and Satellite imagery. This project is started to help accelerate the routine work of digitizing of the buildings and to fill the data gaps in Openstreetmap's open data.  

## Ongoing progress
Our first target domain is Russian territory. We are going to update information on the dataset coverage and to provide some metrics on the comparison with OSM data. At the beginning it contains more than 36,5 mln buildings.

![](https://geoalert.io/img/urban/urban_coverage.png)

|Open datasets|Building heights|Geometry|Feature count|Format|Size|
|------------|----------|----------|-----------|------------|------------|
|[Far East, Russia (part1)](https://minio.aeronetlab.space/public/datasets/urban_mapping/FarEast1.zip)||Simpified | 9,579 | GeoJSON | 0.8Mb |

## Emergency Mapping contribution
The data is used for Emergency Mapping response like in [Irkutsk region, Russia, that was heavily flooded in summer 2019](https://geoalert.github.io/Irkutsk-flood/) - so we will appreciate any related contribution and data requests.

Please check for the issues or contact us directly at [hello@geoalert.io](mailto:hello@geoalert.io)

## Classification
Here is the generalized classification of buildings by most confident types we propose in the datasets. This can be extended to more classes.

<table>
  <tr>
   <td><strong>ID</strong>
   </td>
   <td><strong>CLass name</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td width="130px"><strong>Visual</strong>
   </td>
  </tr>

   <td colspan="4" >
<h2>Buildings and Construction</h2>


</td>
  </tr>
  <tr>
   <td><p style="text-align: right">
101</p>

   </td>
   <td>Residential building
   </td>
   <td>Roofs (not "footprints") of apartment multistorey buildings (shoud have at least 3+ storeys). Low floor apartment blocks in high density residential areas. 
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/101.png"/>
   </td>
  </tr>
 
  <tr>
   <td><p style="text-align: right">
102</p>

   </td>
   <td>House
   </td>
   <td>
    Private houses. Usualy corresponds to the single household.
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/102.png" />
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
103</p>

   </td>
   <td>Industrial building
   </td>
   <td>Plants, etc.
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/103.png" />
   </td>
  </tr>

  <tr>
   <td><p style="text-align: right">
105</p>

   </td>
   <td>Other non-residential buildings
   </td>
   <td>Garages, hangars, etc. - mostly small non-residential buildings
   </td>
   <td>
   </td>
  </tr>
 </table>

## License
This data is licensed under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/) which is compatible with OSM.
The input data is copyrighted by data providers but is not distributed along with the dataset. In Mapbox Terms of Service it's stated clear that 
```You may use Studio or third-party software to trace Mapbox maps solely comprised of satellite imagery ("Mapbox Satellite Imagery") and produce derivative vector datasets for non-commercial purposes and for OpenStreetMap. (https://www.mapbox.com/legal/tos/#[YmuSEapb)```

## Technical details
* Coordinate reference system - EPSG: 4326
* Data format - GeoPackage file (or GeoJSON)

## References
* [Microsoft buildings footprints](https://github.com/microsoft/USBuildingFootprints)
* [RapID - Facebook editor for Openstreetmap](https://github.com/facebookincubator/RapiD)
* Project is supported by [Skolkovo Institue of Science and Technology](https://www.skoltech.ru/en)

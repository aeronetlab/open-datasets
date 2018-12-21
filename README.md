"Open Spatial Dataset" is the joint project of Skoltech and University of Innopolis, maintained by [AeronetLab](https://aeronetlab.space/) at Skoltech.
The goal of the project is to provide research and developers community with training datasets and benchmarks to develop algorithms for Earth Observation data analysis.

Despite of increasing number of competitions in data science world and some good datasets that'd been provided for the open community (e.g. Spacenet) there is still a lack of geographical diversity and labeling data.
The main target area of "Open Spatial Dataset" is the Russian territory since there are no good datasets available for. Also it covers some parts of California for the disaster affected areas.

The labeling data is created according to thematic classification of the natural and man-made objects that have a clear interpretation either in satellite or in aerial imagery (see "markup classes").


## OSD repositories

[Emergency-mapping](https://github.com/aeronetlab/emergency-mapping)


## Markup classes

Thematic classification for obects labeling in imagery (all markup classes)

<table>
  <tr>
   <td><strong>ID</strong>
   </td>
   <td><strong>CLASS_NAME</strong>
   </td>
   <td><strong>Description</strong>
   </td>
   <td width="130px"><strong>Visual</strong>
   </td>
   <td><strong>Application domains</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
0</p>

   </td>
   <td>clutter
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Buildings and Construction</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
101</p>

   </td>
   <td>Residential building
   </td>
   <td>Roofs (not footprints!) of apartment buildings. Shoud have 5+ storeys.
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/101.png"/>
   </td>
   <td><strong>retail, real estate, urban, mapping</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
901</p>

   </td>
   <td>building shadow
   </td>
   <td>Shadows of multi-storey buildings. Should be related to appropiate building
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/901.png" />
   </td>
   <td><strong>retail, real estate, urban</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
902</p>

   </td>
   <td>building wall
   </td>
   <td>Walls of multi-storey buildings
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/902.png" />
   </td>
   <td><strong>retail, real estate, urban</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
102</p>

   </td>
   <td>House
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/102.png" />
   </td>
   <td><strong>retail, real estate, urban</strong>
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
   <td><strong>retail, urban</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
104</p>

   </td>
   <td>Commercial building
   </td>
   <td>Usualy hard to define only by imagery
   </td>
   <td>
   </td>
   <td><strong>retail, real estate, urban</strong>
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
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
106</p>

   </td>
   <td>Construction site
   </td>
   <td>The site wherer construction work is going
   </td>
   <td>
   </td>
   <td><strong>retail, construction, real estate</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
107</p>

   </td>
   <td>Construction building
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/107.png" />
   </td>
   <td><strong>construction</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
108</p>

   </td>
   <td>Pit
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>construction</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
109</p>

   </td>
   <td>Swimming Pool
   </td>
   <td>Swimming pool at the private residential area. Shoud have a relation with private house
   </td>
   <td>
   </td>
   <td><strong>retail, marketing</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
110</p>

   </td>
   <td>Religious
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Oil&Gaz</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
201</p>

   </td>
   <td>Oil storage facility
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/201.png" />
   </td>
   <td><strong>oil&gas</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
202</p>

   </td>
   <td>Oil well
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/202.png" />
   </td>
   <td><strong>oil&gas</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
203</p>

   </td>
   <td>Gas station
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/203.png" />
   </td>
   <td><strong>oil&gas, transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
204</p>

   </td>
   <td>Oil spill
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/204.png" />
   </td>
   <td><strong>oil&gas, ecology</strong>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Roads</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
301</p>

   </td>
   <td>Highway
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/301.png" />
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
302</p>

   </td>
   <td>Track
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/302.png" />
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
303</p>

   </td>
   <td>Footpath
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport, tourism</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
304</p>

   </td>
   <td>Railway
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/304.png" />
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
305</p>

   </td>
   <td>Bridge
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport, marine</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
306</p>

   </td>
   <td>Parking lot
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/306.png" />
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
308</p>

   </td>
   <td>Cross walk
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>urban, transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
307</p>

   </td>
   <td>Other road
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
309</p>

   </td>
   <td>Highway and tracks
   </td>
   <td>Union of 301 and 302 classes
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Transport</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
401</p>

   </td>
   <td>Train
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
402</p>

   </td>
   <td>Truck
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
403</p>

   </td>
   <td>Car
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
404</p>

   </td>
   <td>Vessel
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport, marine</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
405</p>

   </td>
   <td>Airplane
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
406</p>

   </td>
   <td>Other vehicle
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>transport</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
501</p>

   </td>
   <td>Dock
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>marine</strong>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
502</p>

   </td>
   <td>Container
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/502.png" />
   </td>
   <td><strong>marine, transport</strong>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Vegetation</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
601</p>

   </td>
   <td>Tree
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
602</p>

   </td>
   <td>No leaf tree
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
603</p>

   </td>
   <td>Forest
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
604</p>

   </td>
   <td>Low forest
   </td>
   <td>Low or coppice forest
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
605</p>

   </td>
   <td>Palm tree
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
606</p>

   </td>
   <td>Other tree
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
607</p>

   </td>
   <td>Shrub
   </td>
   <td>Shrubland
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
608</p>

   </td>
   <td>Plough
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
609</p>

   </td>
   <td>Сrops
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
610</p>

   </td>
   <td>Lawn
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
611</p>

   </td>
   <td>Grassland
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
612</p>

   </td>
   <td>Other low vegetation
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
613</p>

   </td>
   <td>Woodlands
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/613.png" />
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
614</p>

   </td>
   <td>TSV
   </td>
   <td>Union for 603, 604, 606, 607 and 613 classes
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Water</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
614</p>

   </td>
   <td>River
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
615</p>

   </td>
   <td>Lake
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
616</p>

   </td>
   <td>Swamp
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
617</p>

   </td>
   <td>Other water body
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
618</p>

   </td>
   <td>Stone
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
619</p>

   </td>
   <td>Clay
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
620</p>

   </td>
   <td>Sand
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
621</p>

   </td>
   <td>Other soil
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
622</p>

   </td>
   <td>Sea
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Power infrastructure</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
701</p>

   </td>
   <td>Solar panel
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
702</p>

   </td>
   <td>Power tower
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
703</p>

   </td>
   <td>Cell tower
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="5" >
<h2>Emergency and risk management</h2>


   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
801</p>

   </td>
   <td>Destroyed building
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/801.png" />
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
802</p>

   </td>
   <td>Damaged building
   </td>
   <td>
   </td>
   <td><img src="https://aeronetlab.space/img/class_img/802.png" />
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
803</p>

   </td>
   <td>Landfill
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
804</p>

   </td>
   <td>Flooded area
   </td>
   <td>Flooded residential area whrere the water poses a threat to locals
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
805</p>

   </td>
   <td>Flooded residential area
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
806</p>

   </td>
   <td>Forest loss
   </td>
   <td>Forest losse due to wildfires, loggings etc.
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
807</p>

   </td>
   <td>Forest growth
   </td>
   <td>Forest growth inverse to forest losses
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><p style="text-align: right">
808</p>

   </td>
   <td>Changes of residental buildings
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


## Credentials

<table border="0" cellpadding="10px"> <tr> <td><img src="https://aeronetlab.space/img/lab_logo.svg" width="150px"> 
</td>
<td><img src="https://aeronetlab.space/img/logo_skoltech.png" width="150px"></td>
<td><img src="https://aeronetlab.space/img/logo_innopolis.png" width="150px"></td>
</tr></table>


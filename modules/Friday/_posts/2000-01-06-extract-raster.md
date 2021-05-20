---
title: Extract raster data
published: false
---

### Extract raster values at point locations

Here we will extract information from a raster layer using the `Point sampling tool` we just installed

We're going to attach land cover data to each water beetle observation.  In the Resources section you can download a land cover image for the British Isles.  Add this to your QGIS project

1. Open your new tool `Plugins` > `Analyses` > `Point Sampling Tool`
2. Select the `Layer containing sampling points` - the locations to which you want to add the new information (e.g. *waterbeetle_combined*)
3. Select the `Layer with fields/bands to get values from` - the layer(s) containing the data you want to extract at your survey locations.  To select more than one layer, hold down the shift key
4. Specify an output file name and save as a new file, which you could display in your GIS, or use for statistical analysis


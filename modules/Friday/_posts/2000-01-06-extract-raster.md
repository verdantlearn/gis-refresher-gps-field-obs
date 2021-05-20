---
title: Extract raster data
---

### Extract raster values at point locations

Here we will extract information from a raster layer using the `Point sampling tool` we just installed.  You could follow the same process to extract information from vector layers containing polygons.  The new data you acquire could be used to symbolise your survey points differently, or as the basis for a statistical analysis outside your GIS project

We will attach **land cover** data to each water beetle observation.  In the **Resources** section above :point_up: you can download a land cover image for the British Isles.  Add this to your QGIS project

1. Open your new tool: `Plugins` > `Analyses` > `Point Sampling Tool`
2. Select the `Layer containing sampling points` - the locations to which you want to add the new information (e.g. *waterbeetle_combined*)
3. Select the `Layer with fields/bands to get values from` - the layer(s) containing the data you want to extract at your survey locations.  To select more than one layer, hold down the shift key
4. Specify a name for your `Output point vector layer` and save as a new file

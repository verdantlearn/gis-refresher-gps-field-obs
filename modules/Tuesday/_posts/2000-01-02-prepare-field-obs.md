---
title: Prepare field obs
---

## Prepare your field data
*10-30 minutes*, or more if your data need a lot of cleaning!

Today's GIS exercises are all about **add your fieldwork data** to the map.  These data are the information you have collected at each location of your field surveys.  On this page we cover how to ensure that your data are formatted correctly for use in a GIS project, and on the next page we import them into QGIS

- If you have your own survey data, follow the steps under [Use your own field observations](#yourData)
- If you're doing these exercises using the *example* dataset on water beetles, go straight to the [Use our example dataset](#exampleData) section below

### Use your own field observations
{: #yourData }

Before importing your field observations into QGIS, you need to ensure they are clean and consistent.  A good way to check for problems is to open your data in Excel and use the Filter or Pivot Table tools to examine them

1. Include a column **waypoint name**
2. Do you have missing datapoints, and are they indicated the same way throughout the dataset?  QGIS can cope with empty cells, and empty cells is the best way to, unless you also have sites that were not surveyed, in which an empty cell might be ambiguous, and you should include  
3. Check that **categorical** data are consistent i.e. species/site names or vegetation types are always spelled the same way.  Do you have the correct number of categories?
4. Check that **quantitative** data make sense.  Are there any extreme values (much lower or higher than expected) which might indicate a misplaced decimal point or typing error?
5. Check that **dates and times** are recorded in a standardised fashion e.g. yyyy-mm-dd, or hh:mm


### Use our example dataset 
{: #exampleData }

If you're working with the water beetle dataset, you can download it from the Resources section of the course above :point_up:

With all new and unfamiliar datasets, we always recommend that you look at the data to familiarise yourself with it before doing anything further, such as adding it to your GIS project or analysing it

Open the .csv file in your usual spreadsheet software (e.g. Excel) and view the column headers.  Do they make sense to you?  Do you understand what data each column contains?

<!-- Add screenshot of dataset, plus metadata on each column -->

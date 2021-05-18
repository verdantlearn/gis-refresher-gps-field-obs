---
title: Visualise categories
published: false
---

## Visualise categorical field data
*15 minutes*

Today's exercises are designed to refresh your memory of how to adjust the **symbology of vector data** in QGIS.  In other words, you'll practice displaying your field data in different ways

We'll start with visualising categorical data, also known as qualitative, thematic or nominal data

If you're working with you own field data, select a column that contains categories, either as text (site names, species, named vegetation types) or numbers (e.g. numerical code for vegetation type or observer)

If you're working with the water beetle example data, the categorical variables are the taxonomic information: *Scientific name*, *Common name* and *Family*

> 1. Open the layer properties - double-click or right-click > `Properties`)
2. Select the `Symbology` tab from the left-hand menu
3. Select `Categorized` from the dropdown menu at the top
4. Choose the column you want to symbolise from the `Value` dropdown menu; for the water beetle dataset, we'll choose *Family*
5. Click on the `Classify` button in the bottom left
6. Click `Apply` and `OK` to finish

---

- Open the layer properties - double-click or right-click > `Properties`)
<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-034.png" alt="QGIS screenshot: Open layer properties"></center>
<br>

- Select the `Symbology` tab from the left-hand menu
<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-036.png" alt="QGIS screenshot: Symbology tab"></center>
<br>

- Select `Categorized` from the dropdown menu at the top

<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-042.png" alt="QGIS screenshot: Select Categorized option"></center>

<br>

- Choose the column you want to symbolise from the `Value` dropdown menu; for the water beetle dataset, we'll choose *Family*

<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-049.png" alt="QGIS screenshot: Select Family field"></center>

<br>

- Click on the `Classify` button in the bottom left

<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-056.png" alt="QGIS screenshot: Classify values"></center>

<br>

- Click `Apply` and `OK` to finish

<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-062.png" alt="QGIS screenshot: Click OK"></center>
<br>
<center><img src="{{site.baseurl}}/img/qgis-symbol-cat-063.png" alt="QGIS screenshot: View new symbols"></center>


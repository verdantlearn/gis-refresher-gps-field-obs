---
title: Calculate a new field
published: false
---

## Calculate a new field
*10 minutes*

For the exercise on the following page, we want to visualise quantitative, or numerical, data.  The water beetle doesn't contain appropriate numerical data, so we need to **calculate a new field** first

- If you're working with *your own field data* and it already contains quantitative data such as number of individuals sighted or tree diameter, you can **omit the exercise below** and go straight to the next page
- If you're working with the *water beetle example data*, we're going to extracting year from our date field using the QGIS field calculator

> 1. Turn on the ability to edit your layer - right-click `Toggle Editing`
1. Open the attribute table in the usual way, and find the `open the field calculator (Ctrl+I)` button in the toolbar of editing buttons at the top of the Attribute table
2. Type your new field name (*Year* for the water beetle dataset) into `Output field name`
3. In the central list of variables, expand `Date and Time`
4. Scroll down the list of function and double-click on `year` to enter it into the Expression (centre-left of dialogue box)
5. In the central list of variables, expand `Fields and Values`
6. Double-click on `Date` to add it to your Expression
7. Type in a closing parenthesis `)` at the end of the `Expression` using your keyboard
8. Click `OK` to calculate the new field
9.  Note the presence of your new *Year* field in the attributes table
10. Close the attribute table and right-click `Toggle Editing` off
11. `Save` your changes when prompted

---

- Turn on the ability to edit your layer - right-click `Toggle Editing`

<center><img src="{{site.baseurl}}/img/qgis-calc-field-025.png" alt="QGIS screenshot: Toggle editing on"></center>

<br>

- Open the attribute table in the usual way, and find the `open the field calculator (Ctrl+I)` button in the top toolbar of editing buttons

<center><img src="{{site.baseurl}}/img/qgis-calc-field-047.png" alt="QGIS screenshot: Open field calculator"></center>
<br>

- Type your new field name (*Year* for the water beetle dataset) into `Output field name`

<center><img src="{{site.baseurl}}/img/qgis-calc-field-057.png" alt="QGIS screenshot: Type field name"></center>
<br>

- In the central list of variables, expand `Date and Time`

<center><img src="{{site.baseurl}}/img/qgis-calc-field-064.png" alt="QGIS screenshot: Expand Date and Time"></center>

<br>

- Scroll down the list of function and double-click on `year` to enter it into the Expression (centre-left of dialogue box)

<center><img src="{{site.baseurl}}/img/qgis-calc-field-070.png" alt="QGIS screenshot: Select year"></center>
<br>

- In the central list of variables, expand `Fields and Values`

<center><img src="{{site.baseurl}}/img/qgis-calc-field-074.png" alt="QGIS screenshot: Expand Fields and values"></center>
<br>

- Double-click on `Date` to add it to your Expression

<center><img src="{{site.baseurl}}/img/qgis-calc-field-078.png" alt="QGIS screenshot: Select Date"></center>
<br>

- Type in a closing parenthesis `)` at the end of the `Expression` using your keyboard

<center><img src="{{site.baseurl}}/img/qgis-calc-field-084.png" alt="QGIS screenshot: Close expression"></center>
<br>

- Click `OK` to calculate the new field

<center><img src="{{site.baseurl}}/img/qgis-calc-field-091.png" alt="QGIS screenshot: Click OK"></center>
<br>

- Note the presence of your new *Year* field in the attributes table

<center><img src="{{site.baseurl}}/img/qgis-calc-field-100.png" alt="QGIS screenshot: View new field"></center>
<br>

- Close the attribute table and right-click `Toggle Editing` off

<center><img src="{{site.baseurl}}/img/qgis-calc-field-111.png" alt="QGIS screenshot: Toggle editing off"></center>
<br>

- `Save` your edits when prompted
 
<center><img src="{{site.baseurl}}/img/qgis-calc-field-116.png" alt="QGIS screenshot: Save edits"></center>

<br>
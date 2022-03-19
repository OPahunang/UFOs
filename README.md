# UFOs

## Overview:

The purpose of this challenge was to develop an HTML web page with information of UFO sightings. The webpage also has a filter search function according to date, city, state, country and shape.  Once provided information you are searching, it automatically displays the data about the sightings.

 
## Results:

### Deliverable 1: Filter UFO sightings on multiple criteria

•	The list element that creates the button is removed, and there are five list elements for filtering in the index.html file. 

![delive1-list_elemenet_index.png](https://github.com/OPahunang/UFOs/blob/main/resources/delive1-list_elemenet_index.png)


•	The event listener is modified to detect changes to each filter in the app.js file.
•	The updateFilters() function saves the element, value, and the id of the filter that was changed. 
•	The filterTable() function loops through all of the filters and keeps any data that matches the filter values. 
•	The webpage filters the table correctly based on user input.

![delive1-app_modification.png](https://github.com/OPahunang/UFOs/blob/main/resources/delive1-app_modification.png)


### Deliverable 2: Description of how to perform a search, with images

Filter Search is located on the lower left-hand side of the webpage. Each search tab has an initial placeholder information as a guide for searching.

![deliv2-search.png](https://github.com/OPahunang/UFOs/blob/main/resources/deliv2-search.png)


Filter Search by Date

![deliv2-filter_by_date.png](https://github.com/OPahunang/UFOs/blob/main/resources/deliv2-filter_by_date.png)


Filter Search by City

![deliv2-filter_by_city.png](https://github.com/OPahunang/UFOs/blob/main/resources/deliv2-filter_by_city.png)


Filter Search by State

![delive2-filter_by_state.png](https://github.com/OPahunang/UFOs/blob/main/resources/delive2-filter_by_state.png)


Filter Search by Country

![delive2-filter_by_country.png](https://github.com/OPahunang/UFOs/blob/main/resources/delive2-filter_by_country.png)


Filter Search by Shape

![deliv2-filter_by_shape.png](https://github.com/OPahunang/UFOs/blob/main/resources/deliv2-filter_by_shape.png)



## Summary:

The drawback of this webpage is limited data. Example is almost all UFO sightings are only in US country and only two in other country which is in Canada.  

The two recommendations for further development:

-	Modification of the script on search filters to accept Uppercase. Example, when search by city and type benton, it will show the data but when type Benton, no information

-	Additional data or supporting information about the UFO sightings like articles or internet link     

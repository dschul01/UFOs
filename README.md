# UFOs
Utilize JavaScript and Bootstrap to develop a website containing a filterable table. 

## Overview
The purpose of this project is to develop a website containing UFO sighting data utilizing VS Code, HTML, JavaScript, and Bootstrap components.  A fully dynamic table is built using data stored in a JavaScript array allowing users to 
key in multiple filters to narrow down results of UFO sightings around the world.  Additionally, the website is customized using Bootstrap to make it a more visually appealing site.

## Results
### Performing a Search in the Website
The final project is an interactive webpage which allows users to parse UFO sightings data.  A webpage was built with HTML to view the data within a filterable dynamic table that presents the UFO sightings.  The most complex challenge of this project was creating the filterable table that allows users to filter data by date, 
city, state, country or shape.  The following steps and images walk a user on the process of using the search criteria.

This first image shows the complete table of sightings without any search criteria selected.  This entire default view will provide all sightings collected within our dataset (only a subset is shown here due to size).
![UFO_Challenge_Filter.png](https://github.com/dschul01/UFOs/blob/main/Resources/UFO_Challenge_Filter.png)

This image shows how a user may filter down the data by entering criteria within the searchable fields.  The example shows the user entering a date of "1/12/2010" within the 'Enter Date' field.  After pressing the 'Enter' key, the dataset is filtered by the specific criteria.  The user will see placeholder criteria in the searchable fields as examples of the syntax to be entered in order to narrow down the results.  
![UFO_Challenge_Filter_DateSelect.png](https://github.com/dschul01/UFOs/blob/main/Resources/UFO_Challenge_Filter_DateSelect.png)

This image is just another illustration the table may be narrowed down even further entering a value within the other searchable fields; city, state, country or shape.
![UFO_Challenge_Filter_DateStateSelect.png](https://github.com/dschul01/UFOs/blob/main/Resources/UFO_Challenge_Filter_DateStateSelect.png)

## Summary
### Design Flaw 

There are some flaws with how the challenge indicated the filters should be designed.  One main flaw to point out is the filters are built to be case-sensitive.  Users would typically enter city, states, and countries with proper upper/lower case text, but the data is stored in all lower case.  Therefore, the users may run into issues if filtering on those fields. 

### Recommendations for Improvement

I would recommend at least two changes to improve the usability of the filters.  There should be an option to input date ranges to allow more expansive search functionality.  Additionally, I would recommend allowing multiple entries to be made for the other searchable fields.  For example, allow users to enter more than one city or state in the criteria.  I believe these two improvements would be a good start to improving the overall functionality of the filters.
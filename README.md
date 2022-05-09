# UFOs

## Overview of Project
The purpose of this project was to present data about UFO sightings in an easy to read and interactive web page.  

A HTML file was created that a user can navigate to, and with the help of Bootstrap and D3, headings, text and stylings are presented to the user in an easy to read and responsive manner.

Raw data about UFO sightings was taken from a JavaScript array and converted into an HTML table, which is initially presented to the user in its entirety.  To enable the user to find specific data, filters were created in which users could type in specific items into well described fields, then the table presented would be updated based on what the input was.  To make it obvious to the user what the inputs should be, the filter boxes show an example of what can be typed in.  Lastly, if the page is refreshed, or if the "UFO Sightings" link in blue text at the top of the page is clicked, the filters are removed and the entire data set is displayed again.


## Results
The result is an easy to read and understand webpage presented to the user.  Upon initially navigating to the page, the user sees the entire data set with filters on the left side of the screen shown here:  
![UFO Sightings Homepage](/static/images/ufo_sightings_index.png)

Based on the data presented, the user can then utilize the search filters on the left hand side of the page.  For example, if the user filters on only the state of California, they would type "ca" into the State filter box.  They would then see the list of cities, and in this example, can filter further by typing "el cajon" into the City search box.  This search would yield this result:
![UFO Sightings Homepage](/static/images/ufo_sightings_state_city.png)

Another example of the search filter would be to filter on the Shape of "triangle".  This yields only the results where the UFO sighting was a triangle and the results are shown here:
![UFO Sightings Homepage](/static/images/ufo_sightings_shape.png)


## Summary
This webpage and filter set is an elegant and clean way to present data to a non-technical user.  However, even though it is easy to use, there are some drawbacks of how this is set up.  The main drawback is that the filters are free form text boxes.  If, for example, the user misspells a word, or inputs an item that is not a value in the dataset, no results will be returned.  This could cause confusion and potentially lead the user to belive there aren't any results, when in fact they just had a typo. 

Two recommendations for further development would be to:
1.  Implement drop down boxes for each of the filters so there is no room for error.  The dropdowns would only represent matching data and therefore would guarantee there could not be typo's or other filter criteria that isn't actually included in the dataset.
2.  Enhance the date filter by allowing the user to put a range of dates in, or all items before/after a specific date, rather than just a single date.  This would be a much more useful filter to allow the user to look at ranges of time, rather than just a single date.
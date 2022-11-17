# UFOs
module 12
Overview Of The Analysis:
In this project, we’re using JavaScript to create a table that organizes UFO data that is stored as a JavaScript array. This creates an interactive website that provides an extensive analysis of UFO sightings by allowing users to pull up information from a JavaScript data file using filters on the page. Users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country, and shape.

Results:
The user can use one or all five filters to check for data; they can all be activated at one time. Once the user inputs the desired search terms the user can filter the data by clicking the “filter table” button. When the user visits the html page, this is the initial page of the website they first see. By default, the table will be displaying all the available data. The user can re-initialize the page by clicking on the navigation bar at the top. By using the “Filter search” categories, the user can filter the data by day, city, state, country, and shape to narrow it down based on their interest.

Summary:
PROS:
Users can search through multiple criteria at the same time and there is no submit button needed to pull out results.
CONS:
The sensitivity of the filter option may affect the results that are being returned. For example, using lowercase to spell out a city.

The date filter does not have a calendar option so the users are not knowledgeable of exactly what period the data is from, so user might type in dates that we don’t have data for.

RECOMMENDATIONS:
Remove case-sensitivity in all the textbox search fields.

Add a calendar selection option instead of textbox field to search through dates.

Add a drop-down menu for the shape field as opposed to the textbox so users have options for what shapes to pick.

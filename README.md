# UFOs

### Project overview
The goal of this project is the make an HTML page detailing various UFO sightings. The webpage pulls from the data.js file into a table that can then be filtered based on date, city, country, shape of the UFO sighting, and state. CSS styling and bootstrap was used to style the webpage with images from NASA and contrasting text and background colors. 


### Results (HTML page walk-through)

The page has a link in the upper left corner called "UFO sightings" that can reset the table/re-load the webpage. Also included in the top of the webpage is a brief description of UFOs and opinions from UFO experts (**Fig. 1**)

**Fig. 2** shows the data table and corresponding filter options. Users can filter the data by simply inputis aning all, none or a combination of the following criteria: date, city, country, shape, and state. The table will then show only the results matching the chosen filter combination. As an example, **Fig. 3** shows the search results for sightings of circles on 1/1/2010.

### Summary
In general our HTML page provides a simple way to filter through a large amount of data related to UFO sightings. One drawback, however, is that it does not allow for parsing of the comments, which contains interesting and potentiall relevant information. For example, some comments identify the number of lights or color of lights supposedly related to the UFO. One improvement to this webpage would be to include a functionality that could search for keywords within comments. Second, a filter that could equate "us" as "USA" or not be sensitive to capitalization would allow for more inclusive search results and not be as sensitive to user input or capitalization errors (especially as they pertain to state/country abbreviations).
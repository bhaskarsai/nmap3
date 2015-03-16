# neighborhoodmap
Neighborhood map project for Udacity nanodegree

#Overview:
This project was build using a single HTML page.  All the interactions on this page were built/developed using multiple frameworks.<br /><br />
The HTML page contains a Google Map, which displays my neighborhood information on the map with highlighted markers.  The map was rendered using knockout and Jquery frameworks, while the popular plaes around my neighborhood are rendered using foursquares framework.  The page also displays weather information of my location.  The funcitionality on the map is highly interactive, by capturing user choice and display further information in wikipedia.  <br /><br />
The neighborhood project can be viewed from the following location.<br />
http://cdn.rawgit.com/bhaskarsai/nmap3/master/index.html

#version 4 Highlights - Implemented the following feedback from the instructor<br />
a) Working URL: http://cdn.rawgit.com/bhaskarsai/nmap3/master/index.html<br />
b) Hide list-view on mobile devices upon clicking a list-item<br />
c) Tweaked Global variables by bringing some of them into a method/function and checked for Google map object detection during loading of the page.<br />
d) Added google map check test page (http://cdn.rawgit.com/bhaskarsai/nmap3/master/indexbr.html)

#version 3 Highlights - Implemented typeof google object recommendation for finding google api<br />

#version 2 Highlights - Implemented Feedback from Udacity reviewer<br />
a) Re-arranged the position of Foursuare symbol for providing usability around the text field<br />
b) Added MAP ZOOM Controls at Left Center of the page<br />
c) Implemented the suggested on WIKI.  Removed from the left position and associated with the places shown on the map. Note: City information will be displayed of the place<br />
d) Added error handler for google map loading<br />
e) Search box is now enabled with Opaque dropdown box. Results are now much visible than previous version<br />
f) Upon Clicking on X in the search input, the map points will load to the default scenario. (Added validations for not loading the map to default on every click on X, however it will re-set to default when user moved away from default view)<br />
g) Clicking on X in any of pointers when moved away from default view through search, will re-set to default view (load #10 pointers/places)<br />
h) Places widget will now respond to the X button on search and individual place holders of the map.<br />
i) While re-loading map to default view, a message will be displayed beneath the text text box<br />
j) Console errors are removed through the github production URL.<br />
k) Tested in Windows 8, Google Chrome browser and IPhone 6 device.<br />

#Highlights:
a) Google Map showing my neightbood areas
		Google map loads my current area to the desktop

b) Popular locations around my neighbor hood<br >
		Loads 15 popular areas<br >
		Clicking on each place will launch new content in their respective section. (All links open in a new window)<br >
		Toggling Place-Markers between jumping animation to static image.<br >
		Active and default states of the list items, upon clicking on the list or place markers on the map<br >
		All markers open in the center of the page.<br >
		Show/Hide option for the panel window<br >
		Sorted category list in the drop-down<br ><br >

c) Weather-Information<br >
		Display current Temperature and feels like details<br >
		Clicking on the link will launch more info a new window<br >
		show/Hide option of the weather panel window<br ><br >

d) information from Wikipedia<br >
		Search wikipedia data based on the city<br >
		Open links in new wikipedia window<br >
		Show/Hide option for the wiki window<br ><br >

e) Search results<br >
		Enter a keyword, hit enter or press search<br >
		The panel window will be updated accordingly<br >
		Based on valid keywords, the search in-put will help show some results (autocomplete)<br ><br >

f) Popular categories in Drop-down for easy navigation<br >
		Drop-down in places area will be updated with alphabetical order list<br >
		Upon selecting an item, place markers will be filtered to that item<br ><br >

g) Responsive layout (works in both desktop and mobile devices)<br >
		Content renders in Desktop environemnt separately (CSS)<br >
		Content renders in mobile devices separately (CSS)<br ><br >

#Reference resources
Primary reference when I am stuck: <br />http://stackoverflow.com<br /><br />
Google Maps API: <br >https://developers.google.com/maps/documentation/javascript/reference<br ><br >
KnockoutJS:<br >http://knockoutjs.com/documentation/introduction.html<br ><br >
Foursquare API:<br >https://developer.foursquare.com/start<br ><br >
Weather Undergroud API:<br >http://www.wunderground.com/weather/api/d/docs<br ><br >
Wikipedia API:<br >http://www.mediawiki.org/wiki/API:Main_page<br ><br >
jQuery-UI: http://api.jqueryui.com/autocomplete/<br ><br >
Foursquare autocomplete plugin:<br > http://josephguadagno.net/post/2012/03/19/Foursquare-Autocomplete-jQuery-Plugin<br ><br >

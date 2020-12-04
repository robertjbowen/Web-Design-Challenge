# Web-Design-Challenge

## link:  https://robertjbowen.github.io/Web-Design-Challenge/index.html

The purpose of this challenge is to use html code to create a web interface to display data and images developed in the Python Challenge repository. The focus is on designing a consistent web design with a navigation bar, buttons, pick lists, selectable images and media query adjustments based on screen size. 


### Documents in this repository are:

* index.html - This is the web Landing Page reachable through the link above.

* WebVisualizations folder - Directory containing all of the other html files for subsequent web pages

	* tempVis.html, humidVis.html, cloudVis.html, WindVis.html - standard pages to render a view and analysis of dot plot images and analysis descriptions.

	* comparison.html - Output file for displaying all vizualizations togehter

	* WeatherData.html - Output file displaying the complete data table used in generating the plots

	* csvConverter.ipynb - python script to convert the cities.csv data file into an html format

	* Data.html - Output file for csvConverter.ipynb - base data for WeatherData.html

	* Resources folder - contains:

		* cities.csv file 

		* assets folder - contains:

			* css style sheets

			* images folder - contains images of the WebPage outputs and the plot images displyed on the pages


***
### Design concept:

## Landing Page (Home):

Topped with a navigation bar allowing navigation to any of 6 sub pages (4 visualization pages, Comparison Page, and a Data Page)

<p>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture5.png"/>
    <br>
    <em>Navigation Bar with Dropdown Menu</em>
</p>

The page uses bootstrap column (size 8) formatting to display a float image of one of the visualizations and a text description of the Python API Challenge project description and design concept is wrapped around it.

A side bar navigation is set in a second column (size 4) on the right side to allow the user to select a thumbnail image of any of the 4 visualizations. href links are assigned to each image to allow the user to directly navigate to the selected visualization page.

<p>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture6.png"/>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture7.png"/>
    <br>
    <em>Large Screen___________________________________________________________Small Screen</em>
</p>

***

## Vizualization Pages (Temperature, Humidity, Cloudiness, and Wind Speed):

Each page uses the same template and the naviagtion and side bar attributes from the landing page.

Each page displays a larger sized image of the data plot with an analysis description below. 

<p>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture8.png"/>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture9.png"/>
    <br>
    <em>Large Screen___________________________________________________________Small Screen</em>
</p>

***

## Comparison Page:

Reuses the naviagtion and side bar attributes from the landing page.

Enlarges the sidebar thumbnails to allow sideby side comparison. Images are linked using hrefs to allow direct navigation to the detailed visualization pages.


<p>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture10.png"/>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture11.png"/>
    <br>
    <em>Large Screen___________________________________________________________Small Screen</em>
</p>

***

## Data Page

Reuses the naviagtion bar attributes from the landing page.


The csv data file used to generate the plots was converted to html format and displayed as a formatted table using bootstrap table formatting in the style.css file.

<p>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture12.png"/>
    <img src="https://github.com/robertjbowen/Web-Design-Challenge/blob/main/WebVisualizations/Resources/assets/images/Picture13.png"/>
    <br>
    <em>Large Screen___________________________________________________________Small Screen</em>
</p>

***

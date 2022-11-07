# Web Visualization Dashboard
#

Data is more powerful when we share it with others! I use HTML and CSS to create a dashboard featuring the analysis as captured in the following image:


For this project, I create a website by using visualizations that were created in my Python-APIs project.
As I build this dashboard, I create individual pages for each plot and a way to navigate between them. I also build a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.
##
## Website:
For reference, see the following "Screenshots" images.
The website consist of seven pages in total, including:
### A landing page containing the following elements:
* An explanation of the project
* Links to each visualizations page. There is a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.
###
### Four visualization pages, stored in the visualizations folder, each with the following elements:
* A descriptive title and heading tag.
* The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages are stored in the assets/images folder.
* A paragraph describing the plot and its significance.
###
### A "Comparisons" page that does the following:
* Contains all of the visualizations on the same page so they can easily be compared with each other.
* Uses a Bootstrap grid for the visualizations.
* The grid is two visualizations across medium and large screens, and it is one visualization across on extra-small or small screens.
###
### A "Data" page that displays a responsive table containing the data used in the visualizations.
* The table is a Bootstrap table component.
* The data comes from exporting the .csv file as HTML or by converting it to HTML. 

###
### At the top of every page, the website must have a navigation menu with the following elements:
* It has the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.
* It contains a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.
* It provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* It is responsive (using media queries). The navigation bar is similar to the screenshots in the "Navigation Menu" section (notice the background color change).






Link: https://b0906.github.io/leaflet-challenge/Leaflet-Part-1/templates/


Deployed app : http://127.0.0.1:5500/maxtemp.html

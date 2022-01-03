# Mission-to-Mars

# Overview
To develop an appt to webscrape the following information about the planet Mars from NASA Science Mars Exploration websites:
* Latest News
* Featured Image
* Facts about the planet
* Images of the hemispheres


The mission with this project was to learn web scraping methods to extract information from the NASA Science Mars Exploration website using Chrome Developer tools to identify HTML components, Beautiful Soup/Splinter to automate a web browser and perform the scrape, MongoDB to store the data, and finally Flask to create a web application to display the data. Through the process, the goal was 

# Resources
- Data Sources: 
* [Mars Planet Science](https://www.redplanetscience.com/) 
* [Space Image](https://spaceimages-mars.com/)
* [Astropedia Search Results | GUSS Astrogeology Science Center](https://www.marshemispheres.com/)

- Software/Libraries: Visual Studio Code 1.56.0, jupyter Notebook 6.3.0, Jupyter lab 3.0.14, Flask 1.1.2, Splinter 1.26.4, Web Drive Manager, Beautiful Soup, Pymongo, MongoDB 4.4.6, Mongo DB Compass, htmlslib, lxml.

# Results: 
**Task 1
* Used Chrome Developer tools to identified HTML components, 
* Using Beautiful Soup/Splinter to automate a web browser and perform the scrape:
    - webscrapped and retrieved latest news about Mars, feature image and facts about the planet
    - scrapped full-resolution images of Mars’s hemispheres and the titles of those images.
* MongoDB to store the data,
* Flask to create a web application to display the data.

Initial App Design
<img width="1193" alt="Screen Shot 2022-01-03 at 1 13 12 AM" src="https://user-images.githubusercontent.com/75961057/147921553-f0ff7fd8-8080-4caa-a7c2-da2089c1ea53.png">
<img width="1212" alt="Screen Shot 2022-01-03 at 1 13 44 AM" src="https://user-images.githubusercontent.com/75961057/147921569-77213615-64cd-47ee-b283-195d3aec363f.png">
<img width="1223" alt="Screen Shot 2022-01-03 at 1 14 04 AM" src="https://user-images.githubusercontent.com/75961057/147921573-ecd7321e-09e8-4b60-a108-77392feca03d.png">

**Task 2**
* Changed Bootstrap 3 components to customize the view of the page:
  - Updated the color and size of the scrape button from btn btn-warning btn-xs to btn btn-default btn-lg
  - Added the hemisphere images as thumbnails in a single row by changing the grid from col-md-6 to col-md-3.

<img width="1145" alt="Screen Shot 2022-01-03 at 2 01 28 AM" src="https://user-images.githubusercontent.com/75961057/147922573-00e1d73c-307a-4be5-82cd-137f701c43a9.png">
<img width="1147" alt="Screen Shot 2022-01-03 at 2 01 49 AM" src="https://user-images.githubusercontent.com/75961057/147922582-eb7de9fc-9135-4ba2-ba5f-fc45706950fb.png">

* Used the Bootstrap 3 grid system to update the index.html file so that the website is mobile-responsive. 
* Tested the responsiveness of your website using the DevTools.

**iPad Pro**

<img width="478" alt="Screen Shot 2022-01-03 at 2 56 46 AM" src="https://user-images.githubusercontent.com/75961057/147923284-d6818b73-486f-4296-a92a-26c8cdebfd5f.png">

**Pixel 2XL**

<img width="434" alt="Screen Shot 2022-01-03 at 2 57 19 AM" src="https://user-images.githubusercontent.com/75961057/147923392-74f7199e-4a2e-4327-a245-3c9d7a18b91d.png">

<img width="440" alt="Screen Shot 2022-01-03 at 2 57 44 AM" src="https://user-images.githubusercontent.com/75961057/147923407-3e6c1a8b-1457-484d-93da-b85aeb53b783.png">

<img width="444" alt="Screen Shot 2022-01-03 at 2 58 05 AM" src="https://user-images.githubusercontent.com/75961057/147923419-a98f9fc9-356d-4051-be7b-b93d12d82c86.png">

<img width="444" alt="Screen Shot 2022-01-03 at 2 58 44 AM" src="https://user-images.githubusercontent.com/75961057/147923432-046dbb4a-83ed-45b2-b68a-a559db4999af.png">

<img width="447" alt="Screen Shot 2022-01-03 at 2 59 00 AM" src="https://user-images.githubusercontent.com/75961057/147923448-7038f362-bdd7-4da4-a6a2-87bf03ede850.png">

<img width="447" alt="Screen Shot 2022-01-03 at 2 59 16 AM" src="https://user-images.githubusercontent.com/75961057/147923463-dd673a43-86e3-49e0-a2e7-74b9b9dc039c.png">

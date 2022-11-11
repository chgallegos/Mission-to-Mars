# Mission-to-Mars
----
## Overview

The purpose of this analysis to utilize web scraping techniques in order to create a website that has the ability to scrape mars data and images. 

The analysis had 3 fundamental aspects for its completion, there were:

**1) Scrape Full-Resolution Mars Hemisphere Images and Titles**
**2) Update the Web App with Mars Hemisphere Images and Titles**
**3) Add Bootstrap 3 Components**

----
## Results

### Scrape Full-Resolution Mars Hemisphere Images and Titles

By Using BeautifulSoup and Splinter, I was able to scrape full-resolution images of Mars’s hemispheres and the titles of those images.

The first step in this process was to use devtools in order to recognize the part of the HTML code holding the image urls. Subsequently, the code to retrieve the URLS was written as the following:

![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/url-scrape.png)


### Update the Web App with Mars Hemisphere Images and Titles

Using Python and HTML knowledge, I added the code created preciously to my base code found on **scraping.py**, updated the Mongo database, and modified index.html file so the webpage contained all the information collected as well as the full-resolution image and title for each hemisphere image.

![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/app.png)
![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/html.png)

The file scraping.py is the one that contains code that retrieves the full-resolution image URL and title for each hemisphere image

![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/scraping1.png)
![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/scraping2.png)



### Add Bootstrap 3 Components

The website was designed with Bootstrap style components as to make it visually appealing and with the objective to stand out from other websites.


![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/website1.png)
![Screenshot](https://github.com/chgallegos/Mission-to-Mars/blob/main/resources/website2.png)

## Summary 

This Mission-To-Mars website/application is still currently active and scraping updated information from the website as it keeps updating. This type of application can be crucial as to automatize information requests on data that keeps evolving through time.
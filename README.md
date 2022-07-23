# Mars_Mission
Web scraping to extract most recent online data about Mars using BeautifulSoup and Splinter

# Overview of the project

The script I built is designed to scrape the most recent astronomy data about Mars from all over the web and gather it together in one location at the web page. Each time we run the script, we'll pull the newest data available. As long as the website continues to be updated with new articles, we'll have a constant influx of new information at our fingertips. That's a really useful tool for someone who wants to keep up with the updates of information. 

I used BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, stored the scraped data on a Mongo database and used a web application to display the data. 

**Used tools**
BeautifulSoup 2.2.1  
Bootstrap 4.3.1  
Chrome Driver 3.7.0  
DateTime 4.3 
Flask 1.1.2  
Flask_PyMongo 2.3.0 
html5lib 1.1  
Jupyter Notebook 10.2.2  
Mongo DB 5.0 
Numpy 1.19.3  
Pandas 1.1.4  
PyMongo 3.11.2  
Splinter 0.17.0  
webdriver-manager 3.2.2   

# Results

## Scraping Full-Resolution Mars Hemisphere Images and Titles

BeautifulSoup and Splinter were used to automate a web browser and perform a web scrape.

![img1.png](/images/img1.png) 

## Updating the Web App with Mars Hemisphere Images and Titles

MongoDB database was used to store data from the web scrape, and then a web application was created with Flask to display the data from the web scrape.
Using my Python and HTML skills, I added the code I created to my scraping.py file, updated my MongoDB database, and modified my index.html file so the webpage contains all the information I collected as well as the full-resolution image and title for each hemisphere image.

![img3.png](/images/img3.png) 
![img2.png](/images/img2.png) 


## Adding Bootstrap Components

I updated my web app to make it mobile-responsive, and added the following additional Bootstrap components: 

1. Hemisphere images added as thumbnails
2. New image appears to the header
3. "Scrape New Data" button changed
4. The title styled
5. Background color added

![img4.png](/images/img4.png)

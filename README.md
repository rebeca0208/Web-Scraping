#Mission to Mars
scraping assignment


Complete your initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

Create a Jupyter Notebook file called mission_to_mars.ipynb and use this to complete all of your scraping and analysis tasks. The following outlines what you need to scrape.
NASA Mars News

Scrape the NASA Mars News Site and collect the latest News Title and Paragraph Text. Assign the text to variables that you can reference later.
# Example:
news_title = "NASA's Next Mars Mission to Investigate Interior of Red Planet"

news_p = "Preparation of NASA's next spacecraft to Mars, InSight, has ramped up this summer, on course for launch next May from Vandenberg Air Force Base in central California -- the first interplanetary launch in history from America's West Coast."
JPL Mars Space Images - Featured Image

Visit the url for JPL Featured Space Image here.

Use splinter to navigate the site and find the image url for the current Featured Mars Image and assign the url string to a variable called featured_image_url.

Make sure to find the image url to the full size .jpg image.

Make sure to save a complete url string for this image.

# Example:
featured_image_url = 'https://www.jpl.nasa.gov/spaceimages/images/largesize/PIA16225_hires.jpg'
Mars Weather

Visit the Mars Weather twitter account here and scrape the latest Mars weather tweet from the page. Save the tweet text for the weather report as a variable called mars_weather.
# Example:
mars_weather = 'Sol 1801 (Aug 30, 2017), Sunny, high -21C/-5F, low -80C/-112F, pressure at 8.82 hPa, daylight 06:09-17:55'
Mars Facts

Visit the Mars Facts webpage here and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.

Use Pandas to convert the data to a HTML table string.

Mars Hemispheres

Visit the USGS Astrogeology site here to obtain high resolution images for each of Mar's hemispheres.

You will need to click each of the links to the hemispheres in order to find the image url to the full resolution image.

Save both the image url string for the full resolution hemisphere image, and the Hemisphere title containing the hemisphere name. Use a Python dictionary to store the data using the keys img_url and title.

Append the dictionary with the image url string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.

# Example:
hemisphere_image_urls = [
    {"title": "Valles Marineris Hemisphere", "img_url": "..."},
    {"title": "Cerberus Hemisphere", "img_url": "..."},
    {"title": "Schiaparelli Hemisphere", "img_url": "..."},
    {"title": "Syrtis Major Hemisphere", "img_url": "..."},
]

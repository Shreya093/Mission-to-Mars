# Mission-to-Mars


## Project Overview

The purpose of this project is to develop a well functioning web app for "Mission to Mars" by extracting Mars data from NASA and different other web pages. For Web Scraping the Mars data we have:
1. Used HTML/CSS elements to create a good looking web application.
2. Used BeautifulSoup and Splinter to automate a web browser and perform a web scrape.
3. Created a MongoDB database to store data from the web scrape.
4. Created a web application with Flask to display the data from the web scrape.
5. Used Bootstrap components to polish and customize our web app.
6. Used DevTools to inspect and scrape elements from web app.


## Results

### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles :

In Jupyter Notebook using BeautifulSoup, Splinter and DevTools we automated the web browser and performed web scraping for Mars Hemisphere data.

<img width="1053" alt="d1" src="https://user-images.githubusercontent.com/88418201/138967732-9f890a23-a8c9-43cc-a8d8-5fd84908b1b0.png">

### Deliverable 2: Update the Web App with Mars’s Hemisphere Images and Titles :

Next, we exported our Jupyter notebook file into a Python script. Using this script as the starting point, we started to define the scraping process using Visual Studio Code to edit our Python script. We added functions to scrape through the website(s) and loop through the HTML tags to return the information used to create a database to be stored in MongoDB.

<img width="708" alt="d2" src="https://user-images.githubusercontent.com/88418201/138968372-407e6ea1-1594-4768-becc-5e730b3dfa9c.png">

Using the database in Mongo, we create a Flask app to connect to the information and create our app routes. These routes help to display the information on the home page and will perform the scraping of new data using the codes that we wrote in the Python script.

Next, we integrate Mongo into the web app so that the data stored is updated every time the script, [Scraping.py](https://github.com/Shreya093/Mission-to-Mars/blob/main/scraping.py) is run.

After, we create an [HTML template](https://github.com/Shreya093/Mission-to-Mars/blob/main/templates/index%202.html) to customize the the web app and use Bootstrap components to enhance the HTML and CSS the file.

<img width="613" alt="Screen Shot 2021-10-26 at 3 17 49 PM" src="https://user-images.githubusercontent.com/88418201/138968960-8f3bb7eb-28fd-4333-a811-02dfdb5bbf05.png">

### Deliverable 3: Add Bootstrap 3 Components :

#### The webpage is mobile-responsive

Changed everything to col-xs, which is the smallest option. Everything will scale up from the mobile phones size to the larger desktop sizes.

#### Three additional Bootstrap 3 components are used to style the webpage [HTML template](https://github.com/Shreya093/Mission-to-Mars/blob/main/templates/index.html)

1. Added a tooltip that says Click Me!, when the user hoovers over the Scrape button.
2. Changed the background colors in the web page and formatted the table by adding some striped table pattern.
3. Changed the orientation of the hemisphere images to a single ribbon by changing the grid from col-xs-6 to col-xs-3.

<img width="613" alt="Screen Shot 2021-10-26 at 3 22 57 PM" src="https://user-images.githubusercontent.com/88418201/138969478-fb17b0e0-3d0c-4fb3-8679-349024cf16b5.png">






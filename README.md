# Web-Scrapping-Challenge
# Mission To Mars

## Overview
In this project we will be gathering information about the Climate of Mars by performing full web scrapping and data analysis.

### Aim
The aim of this project to apply full web scrapping for the mission mars by collecting data, organizing and storing data, and then visually communicating our insights.

##Resources

-Data Source :</br>
<a href="https://static.bc-edx.com/data/web/mars_news/index.html">Mars News</a>  </br>
<a href="https://static.bc-edx.com/data/web/mars_facts/temperature.html">Mars Temperature Data </a>  </br>

- Software Used :</br>
Python, Jupyter Notebook

##Analysis of Data and Results
Part 1: Scrape titles and preview text from Mars news articles.

Using Splinter, an automated browsing was used to visit the Mars News Site. Then, we extracted the HTML code with Beautiful Soup. After tht, we scrapped and extracted the tiles and preview text of the news articles and stored them in a dictionary.

Finally, we exported the data to JSON file and and have them as <a href="https://github.com/NTHub23/Web-Scrapping-Challenge/blob/main/Starter_Code_v1.2.2/marsnews.csv">Marsnews.csv</a>

Part 2: Scrape and Analyze Mars Weather Data
We used automated browsing to visit the Mars Temperature Data Site. We used Beautiful Soup to extract HTML code and then scrapped and extracted Mars Temperature table data a Pandas DataFrame. The columns extracted had the same heading as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

After extracting Mars Temperature Table Data, we used this table to analyze and visualize the data by finding answes to the following questions:

Q1. How many months exist on Mars?
Q2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
Q3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    a.  Find the average minimum daily temperature for all of the months.
    b.  Plot the results as a bar chart.
Q4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Q5. Find the average daily atmospheric pressure of all the months.
    a. Plot the results as a bar chart.
Q6. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    a. Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    b. Visually estimate the result by plotting the daily minimum temperature.

Finally, we exported the data to JSON file and and have them as <a href="https://github.com/NTHub23/Web-Scrapping-Challenge/blob/main/Starter_Code_v1.2.2/Mars_Data.csv">Mars_Data.csv</a>


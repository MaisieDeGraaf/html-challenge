# HTML Challenge

## Part 1: Mars News Analysis

### Overview

The first part of this project involves scraping data from a Mars news website to gather the latest news articles. The web scraping is performed using the Splinter and BeautifulSoup libraries in Python.

### Code Overview

The code in the Jupyter Notebook part_1_mars_news.ipynb performs the following tasks:

- Imports necessary libraries: Splinter and BeautifulSoup.

- Initiates a Chrome browser instance using Splinter.

- Visits the Mars news website and extracts the HTML content.

- Parses the HTML content using BeautifulSoup to extract news article titles and previews.

- Stores the extracted data in a list of dictionaries.

- Quits the browser instance.

## Part 2: Mars Weather Analysis

### Overview

The second part of this project involves analyzing Mars weather data. The data is scraped from a webpage using Splinter and BeautifulSoup, and then analyzed to determine average temperatures and atmospheric pressure on 
Mars.

### Code Overview

The code in the Jupyter Notebook part_2_mars_weather.ipynb performs the following tasks:

- Imports necessary libraries: Splinter, BeautifulSoup, matplotlib, and pandas.

- Initiates a Chrome browser instance using Splinter.

- Visits the Mars weather webpage and extracts the HTML content.

- Parses the HTML content using BeautifulSoup to extract temperature and pressure data.

- Stores the extracted data in a pandas DataFrame and performs data analysis.

- Generates visualizations using matplotlib to visualize average temperature and pressure trends.

- Saves the analyzed data to a CSV file.

- Quits the browser instance.

## Data Sources

The data used in this project was obtained from the following sources:

- [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html): This website provides the latest news articles related to Mars exploration.
- [Mars Weather Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html): This website provides temperature and atmospheric pressure data for Mars.

## Conclusion

The project concludes with insights drawn from the analyzed Mars weather data and with articles and information pulled from the Mars News website.

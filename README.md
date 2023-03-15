# module-11-mars-challenge


Deliverable 1: A Jupyter notebook containing code that scrapes the Mars news titles and preview text.

Part 1: Scrape Titles and Preview Text from Mars News

Opened the Jupyter Notebook and scraped the Mars News website.
Used automated browsing to visit the Mars news site Links to an external site. Inspected the page to identify which elements to scrape.
Created a Beautiful Soup object and used it to extract text elements from the website.
Extracted the titles and previewed text of the news articles that I scraped. Stored the scraping results in Python data structures.
Stored all the dictionaries in a Python list.
Printed the list in thr notebook.
Export the scraped data to a JSON file. 


Deliverable 2: A Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data.

Part 2: Scrape and Analyze Mars Weather Data

Opened the Jupyter Notebook to scrape and analyze Mars weather data.
Used automated browsing to visit the Mars Temperature Data Site Links to an external site. Inspected the page to identify which elements to scrape.
Created a Beautiful Soup object and used it to scrape the data in the HTML table. 
Assembled the scraped data into a Pandas DataFrame with the same headings as the table on the website. 

Here’s an explanation of the column headings:
id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location

Examined the data types that are currently associated with each column. Converted the data to the appropriate datetime, int, or float data types.

Analyzed the dataset by using Pandas functions to answer the following questions:
1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? Found the average minimum daily temperature for all of the months. Plotted the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? Found the average daily atmospheric pressure of all the months. Plotted the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? Considered how many days elapse on Earth in the time that Mars circles the Sun once. Visually estimated the result by plotting the daily minimum temperature.

Export the DataFrame to a CSV file.

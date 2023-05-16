# mars-scraping-challenge
Scraping titles and preview text from Mars News, then scraping and analysing Mars weather data from a given website.

part_1_mars_news.ipynb from the 'Notebooks' folder automatically browses a Mars news site and scrapes text elements such as news titles and the preview text, stores them as dictionaries in a python list, and then outputs the data as a JSON file (mars_news_articles.json) in the 'Output' folder.

part_2_mars_weather.ipynb from the 'Notebooks' folder also uses automated browsing of a Mars Temperature Data Site and scrapes the data in the HTML table using BeautifulSoup, then reassembles the table into a DataFrame, ready for Data Analysis. The data types of the DataFrame are adjusted accordingly and then the below questions are answered with accompanying visualisations as required:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?

What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
  Find the average minimum daily temperature for all of the months.
  Plot the results as a bar chart.

Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
  Find the average daily atmospheric pressure of all the months.
  Plot the results as a bar chart.

About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
  Consider how many days elapse on Earth in the time that Mars circles the Sun once.
  Visually estimate the result by plotting the daily minimum temperature.

The DataFrame is then exported to a CSV file (mars_temperature_table.csv) in the 'Output' folder.

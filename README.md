# web-scraping
module 11

## Part 1: Scrape Titles & Preview Text
Scrapes the news titles and preview text from [News - Mars Exploration Program](https://static.bc-edx.com/data/web/mars_news/index.html) with Beautiful Soup and stores in a list of dictionaries.

## Part 2: Scrape & Analyze Mars Weather Data
Scrapes data from [Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) with Beautiful Soup. Uses a for loop to hold put each row's data in a dictionary and then append it the dictionary to a list. Creates a Pandas data frame from the list of dictionaries.</br>
</br>
Analyze the data and create findings that show:
- Which month, on average has the lowest temperature and which has the highest.
- Which month, on average, has the lowest atmospheric pressure and which has the highest.
- The number of terrestrial days exist in a Martian year and the min temperature each day.
</br>
Lastly, exports the data frame to a csv file, [mars_temperature_data.csv](https://github.com/megan-oconnor/web-scraping/blob/main/data/mars_temperature_data.csv).

## Resources
data: [mars_temperature_data.csv](https://github.com/megan-oconnor/web-scraping/blob/main/data/mars_temperature_data.csv)
part 1: [part_1_mars_news.ipynb](https://github.com/megan-oconnor/web-scraping/blob/main/part_1_mars_news.ipynb)
part 2: [part_2_mars_weather.ipynb](https://github.com/megan-oconnor/web-scraping/blob/main/part_2_mars_weather.ipynb)

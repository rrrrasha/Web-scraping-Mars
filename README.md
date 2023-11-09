# Web-scraping-Mars-news-and-weather-Data 
The goal of this project was to:

Scrape titles and preview text from Mars news articles.
Scrape and analyze Mars weather data in an HTML table.
Tools and Technologies
Python
Jupyter Notebook
Beautiful Soup
Splinter
Pandas
Project Structure
Part 1: Mars News Scraping
Used automated browsing with Splinter to visit the Mars news site.
Created a Beautiful Soup object to parse the HTML content.
Extracted the titles and preview text of the news articles.
Stored the scraping results in a list of dictionaries with 'title' and 'preview' keys.
Printed the list in the Jupyter Notebook.
Optionally, stored the scraped data in a JSON file for easier sharing.
Part 2: Mars Weather Data Scraping and Analysis
Used automated browsing with Splinter to visit the Mars Temperature Data Site.
Created a Beautiful Soup object to scrape the data in the HTML table.
Assembled the scraped data into a Pandas DataFrame with appropriate column headings.
Examined and cast the data types to appropriate datetime, int, or float data types if necessary.
Analyzed the dataset to answer questions related to Martian months, days, temperature, and atmospheric pressure.
Visualized the results using bar charts and line plots.
Exported the DataFrame to a CSV file.
Conclusion
This project demonstrated the ability to effectively use web scraping techniques to collect and analyze data from Mars-related websites. The findings provide valuable insights into Martian months, days, temperature, and atmospheric pressure.

##Mars Data Analysis Part 1

#Overview:
This section of the project focuses on scraping titles and preview text from Mars news articles.

Requirements:
To run the code, ensure you have the following libraries installed:

- splinter
- beautifulsoup4

Usage
1. Clone the repository to your local machine:

git clone <repository_url>

2. Navigate to the cloned directory:

cd mars_scrape

3. Execute the Python script climate_starter.ipynb:

part_1_mars_news.ipynb

#Instructions:
1. Import Libraries: Import Splinter and BeautifulSoup libraries.
2. Visit Mars News Site: Use Splinter to visit the Mars news site.
3. Create Beautiful Soup Object: Create a Beautiful Soup object to parse the HTML.
4. Extract Text Elements: Find all news article elements and extract their text content.
5. Store in Dictionaries: Store each title and preview text pair in a Python dictionary.
6. Print Results: Print the list of dictionaries containing scraped data.

Results:
- The scraped data includes a list of dictionaries containing titles and preview texts of Mars news articles.

Mars Data Analysis Part 2

Overview:
This section of the project involves scraping and analyzing Mars weather data, which exists in a table format. The analysis includes:

- Scraping the data using Splinter and BeautifulSoup.
- Converting the scraped data into a Pandas DataFrame.
- Analyzing the dataset to answer specific questions.
- Visualizing the results using Matplotlib.

Requirements:
To run the code, ensure you have the following libraries installed:

- splinter
- beautifulsoup4
- pandas
- matplotlib

Instructions:
1. Import Libraries: Import relevant libraries including Splinter, BeautifulSoup, Matplotlib, and Pandas.
2. Visit Website: Use Splinter to visit the Mars weather data website.
3. Create Beautiful Soup Object: Create a Beautiful Soup object to parse the HTML.
4. Extract Table Data: Find the table element and extract all rows of data.
5. Convert to DataFrame: Create a Pandas DataFrame using the extracted data.
6. Convert Data Types: Change data types for analysis (e.g., datetime, integers, floats).
7. Analyze Data: Use Pandas functions to answer specific questions about the dataset.
8. Visualize Results: Plot relevant data using Matplotlib.
9. Export to CSV: Write the analyzed data to a CSV file for further use.

Results:
- The analysis provides insights into Martian weather data, including the number of months on Mars, Martian days' worth of data, average low temperature by month, coldest and hottest months, average pressure by Martian month, and the number of terrestrial days in a Martian year.

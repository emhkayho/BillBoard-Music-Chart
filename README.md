# BillBoard-Music-Chart
![Screenshot 2023-07-29 033413](https://github.com/emhkayho/BillBoard-Music-Chart/assets/96947147/75a352e3-c00a-4a00-8277-64a44354c673)

---
# Billboard Music Chart Web Scraper

This Python script allows you to scrape music chart data from Billboard.com. The script is designed to extract essential information from the Billboard Hot 200 chart, including the song name, artist, last week's position, peak position, and number of weeks on the chart.

## Requirements

Before running the script, ensure you have the necessary Python libraries installed:

- requests: Used to make HTTP requests and retrieve the web page content.
- BeautifulSoup (bs4): Used for parsing the HTML content of the web page and extracting specific data.
- pandas: Used to organize and manipulate the scraped data.

You can install these libraries using pip with the following command:

```
pip install requests beautifulsoup4 pandas
```

## How to Use

1. Clone the repository or download the script to your local machine.
2. Open the script in your preferred Python environment or text editor.
3. Run the script, and it will fetch the data from the Billboard Hot 100 chart by default.

## Understanding the Code

1. **Importing Useful Libraries:** The script begins by importing the necessary libraries, including requests, BeautifulSoup, and pandas, to enable web scraping and data manipulation.

2. **Analyzing the Website Code:** The script examines the HTML structure of the Billboard Hot 100 chart webpage to identify the elements that contain the desired information. This step is crucial for understanding where to find the song name, artist, peak position, and other relevant details.

3. **Web Scraping the Data:** Using the identified HTML elements and class names, the script employs BeautifulSoup to extract the required data from the webpage. It locates the `<div>` and `<li>` elements containing the music details and then uses appropriate methods to retrieve the song name, artist, last week's position, peak position, and week on the chart.

4. **Extracting the Table using Pandas:** After successfully scraping the data, the script organizes it into a tabular format using the pandas library. The scraped information is stored in a list of lists, and pandas is utilized to create a DataFrame from this data, making it easy to view and manipulate.

## Precautions for Web Scraping

When using web scraping tools. Make sure to adhere to the website's terms of service and respect their rate-limiting policies to avoid overwhelming their servers with too many requests. Always review the website's robots.txt file to check for any specific rules related to web scraping.

## Saving the Scraped Data

After successfully scraping and organizing the chart data, the script saves it as a CSV (Comma-Separated Values) file. The CSV file provides a convenient way to store the data for further analysis or visualization in other tools.
🎵📈

---

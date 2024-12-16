# data-collection-challenge

Hello!

This is a repository for the Data Collection Challenge for the UofM Data Analytics Bootcamp Course.

This focus of this project was to scrape data from a website concerning various kinds of information and data about the planet Mars.
For the first script file, we were tasked with:
  - Using an automated browser to visit the News section of the website and scraping the data
  - Extract the title and preview text for all the news articles on the main page
  - Store said title and preview texts retrieved in a Python list
  - Print the list in the notebook (Jupyter Notebook was used to write/edit these scripts)

For the second script file, we were tasked with:
  - Use an automated browser to visit the Mars Data Temperature section of the website and scrape the data within
  - Load the data and column headers into a Pandas dataframe
  - Change the data types of multiple different columns
  - Find how many different months exist on Mars
  - Find how many Martian days worth of data exist within the dataset
  - Find the average minimum daily temperature for all Martian months, and plot the results in a bar chart
  - Find the average daily atmosphering pressure for all Martian months, and plot the results in a bar chart
  - Estimate how many terrestrial (Earth) days exist in a Martian year by plotting the daily minimum temperature for each daily observation
  - Perform a written analysis for each of those chart topics
  - Export the data in the dataframe to a CSV file

Instructions for using the scripts are as follows:
  - Download repository files
  - Open one of the files (or both if you so desire) in Jupyter Notebook
  - Run the individual cells (or the full script) at your discretion

I hope the results and analysis found here prove to be insightful and helpful!

Some references were used during the creation of these scripts:
Got help from the XPert Learning Assistant AI to write a function to strip the tags from the scraped mars temperature data. Here's the first prompt I used:
im working with BeautifulSoup to scrape a mars temperature data table and get all the rows of data. i have successfully grabbed all the data but it is returning it in this format: <td>2</td>. how do i remove the "<td>" and "</td>"?

Referenced code from this article for help with my function to convert the datatypes of the mars_Df dataframe:
https://sparkbyexamples.com/pandas/pandas-convert-column-to-int/

Referenced the Pandas sort_values() function documentation for writing code that sorts the average minimum temperature bar graph data:
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html

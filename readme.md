# Mars Web Scraping and Data Analysis

This repository contains the solutions for the Module 11 Challenge involving web scraping and data analysis tasks related to Mars news articles and Mars weather data.

## Deliverable 1: Scrape Titles and Preview Text from Mars News

### Overview

In this part of the challenge, we utilize web scraping techniques to extract titles and preview text from [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html). We then organize the extracted information into structured data.

### Instructions

1. Automated browsing is used to visit the Mars News Website, and the page is inspected to identify the relevant elements to scrape.

2. A Beautiful Soup object is created to parse the HTML content of the website and extract the desired text elements.

3. Titles and preview text of news articles are extracted and stored as dictionary pairs in a Python list.


## Deliverable 2: Scrape and Analyze Mars Weather Data

### Overview

In this section of the challenge, we perform web scraping to acquire Mars weather data from the [Mars Temperature Data Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html). The extracted data is analyzed using Pandas and visualized using Matplotlib to answer various questions about Martian weather.

### Instructions

1. Automated browsing is employed to visit the Mars Temperature Data Website, and the page is inspected to identify the relevant elements to scrape.

2. A Beautiful Soup object is created to parse the HTML content of the website and extract data from the HTML table.

3. The scraped data is structured into a Pandas DataFrame, including column headings from the table.

4. Data types are examined and converted to appropriate types using Pandas methods.

5. The dataset is analyzed by answering specific questions about Martian weather trends, such as the number of months, days' worth of data, coldest and warmest months, average atmospheric pressure, and the length of a Martian year.

6. The results are visualized using Matplotlib, and the DataFrame is exported to a CSV file named `mars_weather.csv` located in the Output folder.

### Analysis Results

- How many months exist on Mars? There are 12 months on Mars.

- How many Martian days' worth of data are there? There are 1867 Martian days' worth of data in this dataset.

#### Average Low Temperature by Month

![low_avg_plot](https://github.com/RahiemBrooks/Web_Scraping-Challenge/assets/135518113/0c04cdad-2504-422e-ba57-03bcebb2f451)


Month 3 is the coldest month on Mars with an average temperature of -83.31 Celsius, while Month 8 is the hottest with an average temperature of -68.38 Celsius.

#### Average Atmospheric Pressure by Month

![pressure_avg_plot](https://github.com/RahiemBrooks/Web_Scraping-Challenge/assets/135518113/7df8dbf2-1057-4fa9-a357-e350584182c9)


Month 6 has the lowest atmospheric pressure on Mars (745.05 hPa), while Month 9 has the highest (913.31 hPa).

#### Martian Year Length

![days_plot](https://github.com/RahiemBrooks/Web_Scraping-Challenge/assets/135518113/8a8d1e7e-07a3-4b5d-80bd-ef41e06f805f)


The distance from peak to peak in the plot indicates that a year on Mars is about 682 Earth days, which is close to the confirmed value of 687 Earth days.

## Conclusion

The solutions provided in this repository demonstrate effective web scraping techniques using libraries like Splinter and Beautiful Soup, as well as data analysis using Pandas and visualization using Matplotlib. By extracting and analyzing information from Mars news articles and weather data, we gain insights into the latest updates and climatic conditions on the Red Planet.


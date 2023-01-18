# Mars_Challenge

## Background

I'm now ready to take on a full web-scraping and data analysis project. I have learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. I have also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, I have strengthened the same core skills that I had been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating my insights.


## Resources 
- Data Source: </br>
<a href="https://static.bc-edx.com/data/web/mars_news/index.html">Mars News</a>  </br>
<a href="https://static.bc-edx.com/data/web/mars_facts/temperature.html">Mars Temperature Data</a>  </br>
- Software: Python 3.7.13, Jupyter Notebook. 

## Analysis of Data and Results
**1. Scrape Titles and Preview Text from Mars News** </br>

I used the automated browsing to visit the Mars news site Links to an external site. Inspected the page to identify which elements to scrape. Next I created a Beautiful Soup object and used it to extract text elements from the website. After, I extracted the titles and preview text of the news articles that I scraped. 

I storeed each title-and-preview pair in a Python dictionary and, gave each dictionary two keys: title and preview. 
</br>

Finally, I exported the data to JSON file and saved them as <a href="https://github.com/HJandu/Mars_Challenge/blob/main/mars.csv">mars.csv</a>

</br>

To see the full code written in this part check <a href="https://github.com/HJandu/Mars_Challenge/blob/main/part_1_mars_news.ipynb">mars_data_challenge_part_1.ipynb</a>
</br>

**2. Scrape and Analyze Mars Weather Data** </br>
I more or less followed the above steps to scrape elements. 
After creating a DataFrame, I anaylsed and created visualisations to answer the following questions: 

- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
![Screen Shot 2023-01-18 at 23 41 05](https://user-images.githubusercontent.com/116304118/213319730-d03eacfd-c24c-4905-a11e-f0cc74e67be0.png)

- Which months have the lowest and the highest atmospheric pressure on Mars? 

![Screen Shot 2023-01-18 at 23 41 19](https://user-images.githubusercontent.com/116304118/213319709-ece1c11b-b289-4977-a775-21475b561181.png)

- About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

</br>
Finally, the last step was to export our data as <a href="https://github.com/HJandu/Mars_Challenge/blob/main/Temp_table_mars.csv">mars_table.csv</a>

</br>

To see the full code written to do this part check <a href="https://github.com/HJandu/Mars_Challenge/blob/main/part_2_mars_weather.ipynb">mars_data_challenge_part_2.ipynb</a>

</br>



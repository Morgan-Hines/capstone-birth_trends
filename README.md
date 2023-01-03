# Birth Trends in America: A Profile of Women Giving Birth?

## Table of Contents
* [Motivation](#Motivation)
* [Data Questions](#Data-Questions)
* [Data Sources and Tools](#Data-Sources-and-Tools)
* [The Process](#The-Process)


## Motivation
<details>
  <summary> I've seen several articles regarding the declining birth rates in America, each generation blaming  another for contributing the most to the downward trend. As childless millennial, it made me wonder what type of women in my generation were actually having children. Was there a certain factor that seemed to connect them, or certain trends that could be found among them?
  I decided to look at 3 elements to see if I could create a profile of sorts for the women giving birth. The first element I looked at was age. I was curious to see if there has been a shift in the ages of women having children. The second element I dove into was racial demographics of women giving birth. And the third element was level of education.
</details>

## Data Questions
1. What age group of women is birthing children the most?
2. What is the racial demographic of women who had children in 2016-2020?
3. What level of education have women having children typically obtained?

## Data Sources and Tools
#### Data Sources
* [www.cdc.gov](https://www.cdc.gov/nchs/data_access/VitalStatsOnline.htm)
* [wonder.cdc.gov](https://wonder.cdc.gov/natality-current.html)
* [census.gov/data](https://data.census.gov/)
* [www.gapminder.org](https://www.gapminder.org/data/)


#### Technology Tools
* Python
  * [Jupyter Notebooks](https://jupyter.org/)
  * [pandas](https://pandas.pydata.org/)
* [Tableau](https://www.tableau.com/)


## The Process
<details>
  <summary>Acquiring the data</summary>
Finding the data was a journey in it's own right. While looking through the CDC's data I stumbled upon some huge data sets early on in my search that included a lot of information for each birth that took place in the U.S. Each year had over 3 million rows. I wasn't sure this was what I was looking for but knew that there was such good information provided I didn't want to pass it up. Pulling in this data provided a challenge because it was so large. The data was in a different format and I had to decipher which lines/characters corresponded with each column. But this challenge meant I was able to pull straight into Python only the columns I wanted which slimmed down my data set a little.
I then moved onto finding some really good social indicators (level of educational attainment, racial demographics, and poverty) data from the census. I knew this would be important to have to answer the questions I set out to. This data wasn't as cumbersome as the CDC data but did need some cleaning.
The last set of data I found on gapminder wasn't everything I hoped it would be but did provide me with a lot of good information to create my birth rate map. And I was able to pull what I needed from it.
</details>

<details>
  <summary>Cleaning and organizing the data</summary>
Organizing the CDC data was important because it was such a large data set. I was able to pull what I needed in order to aggregate the data, which then allowed me to get a better picture of what I was working with.
Cleaning the census data was also very important, after pulling it in I realized that there were several strings that needed to be organized and transposed in order to get a cohesive table to work with.
</details>

<details>
  <summary>Loading data to Tableau, building dashboards</summary>
I initially created visualizations in Python and put them in a PowerPoint but decided to create a Tableau story instead. I felt Tableau would provide a cleaner more uniform presentation. So what I did to pivot was pull the tables I created for the Python graphs and pulled them directly into Tableau. This created some issues such as the data not connecting but I was able to resolve most of them.
</details>

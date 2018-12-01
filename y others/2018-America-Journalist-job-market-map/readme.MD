#  America-Journalist-job-market-map
This is an example of [choropleth](https://en.wikipedia.org/wiki/Choropleth_map). It's a report about the condition of the employment market for journalists in the U.S.
In this map, the key data is the number of opening positions in each state of the U.S. In addition, this map recognise the states with their abbreviations(VA, NY...). 
![](newchoropleth.png)

The tools and process:
- Get the data from `0 jobs.csv`
- Use `pandas` to manipulate the location data from `0 jobs.csv` into `US-States.csv` to code the states of the U.S into their abbreviations
- Use `list.count()` to categorise the jobs into different states
- Use `plotly` to visualize the map

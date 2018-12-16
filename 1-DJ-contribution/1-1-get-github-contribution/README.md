# Assignment 1 -- Data collection and ideation
## Indroduction
### Topic
  - The data journalists' information and their contributions on Github from 2008 to 2018
### Data source
  - http://jplusplus.github.io/global-directory/
### Data fields (type, sample data); 
  - ```name``` - String. e.g. ```Justin Myers```
  - ```institution``` - String. e.g. ```The Associated Press```
  - ```city``` - String. e.g. ```United States, Brooklyn (US-VA)```
  - ```github adress``` - String. e.g. ```http://github.com/myersjustinc```
  - ```github contributions``` - Float. e.g. ```1.0,0.0,12.0,3.0...```
  - The result is in [Result.csv](https://github.com/FLYSTEPHEN/python-data-assignments/blob/master/assignment1/Result.csv)
  - The codes is in [scrape-data-journalist-directory-and-output-github-contributions.ipynb](https://github.com/FLYSTEPHEN/python-data-assignments/blob/master/assignment1/scrape-data-journalist-directory-and-output-github-contributions.ipynb)
### Data volume
  - 217 rows × 4 columns + 3963 rows × 81 columns
  - 217 data journalists's information, including their names, institutions, cities, github adress 
  - Github contributions on an everyday level from 2008 of 81 data journalists who have a github account
### License
  - CC 4.0
### obstacles and solutions
  - [x] from http://jplusplus.github.io/global-directory/ we cannot use ```requests``` to get its script directly so we used the dynamic way. Afterwards we come back to the static way since there is no need to change pages during scraping and it is much quicker than dynamic.
### Future issues
  - [ ] We can analyze the pattern of their contributions by time. 
  - [ ] we can also do the analysis by geography, since we have collect their cities. We can use geopy API to solve it.


## Mission list
Deadline: **Nov 9, 2018 (Fri)**
- [x] Collect your **original** data by one of the following two ways:
- Scraping static website (requests + beautiful soup)
- Scraping a dynamic website (selenium/ splinter)
### Requirement:
- [x] The dataset needs to contain mordirectory.ipynbe than **100** entries and more than **5** fields.
- [x] In the `README.md` file, give information about your dataset, so people can quickly understand the content without looking into your CSV file. You can include those sections: 1) topic ; 2) data source; 3) data fields (type, sample data); 4) data volume; 5) **license**.
### Bonus: Enrich your dataset
enrich your dataset:
- [ ] You can download data set from [gov open data portals](https://data.gov.hk/en/), [research institutes](https://ourworldindata.org/), or [any collection](https://github.com/awesomedata/awesome-public-datasets) that you can verify. You don't have to actually download the data in this bonus question, because some dataset is too large to be put onto GitHub repo. Simply give pointers to the database you are considering and briefly describe how they can be incorporated into the dataset you just scraped or how they can assist your articulation.
- [ ] You can get some related data via [HTTP based API](https://earthquake.usgs.gov/fdsnws/event/1/). Please tell us what is the API, give a few (truncated) sample responses, and discuss how that data can potentially help your data-driven report.


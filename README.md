# WEB-SCRAPING-WIKIPEDIA-PAGE-MAKING-DISNEY-MOVIES-DATASET
This repository contains files for Web-Scraping Wikipedia page and making a dateset with Disney Movies.

## About the Project

For this project I performed scraping of Wikipedia pages for Disney movies to create a Disney Movies dataset. From the data availale on wikipedia such as `Title`, `Directed by`, `Produced by`, `Written by`, `Narrated by`,  `Music by`, `Cinematography`, `Edited by`, `Production company`, `Distributed by`, `Release date`, `Running time`, `Country`, `Language` I have created a structured dataset which can be used for further analysis. Also, I have used OMDb API to get `imdb`, `metascore`, `rotten_tomatoes` data which is combined with the dcapped data. The final data is stored as CSV.

### Prerequisite packages and software
* Python
* Numpy
* urllib
* Jupyter Notebook
* Beautiful Soup,bs4
* Requests
* Pickle
* Pandas

### Data Collection
* Scraped Disney Movie data from Wikipedia here
* Collected additional data from OMDB API for every title and attached to the data.

### Task Overiew
* Task 1: Scrape info box from Toy Story 3 Wiki page and save in python dictionary.
* Task 2: Scrape info box for all Disney movies and save in list of python dictionaries.
* Task 3: Clean the data!
  - Strip out all references
  - Split up long strings
  - Convert 'Running time' field to integer
  - Convert 'Budget' and 'Box office' fields to floats
  - Convert dates to datetime objects
  - Save data using Pickle
* Task 4: Attach IMDb, Rotten Tomatoes, Metascores to dataset using OMDb API.
* Task 5: Save final dataset as JSON and CSV files.
* 
### Data Cleaning in detail
* Cleaned data using Python and Regex
* Parsed out the main monetary values of different formats from Budget and Box-Office columns using several regexes together.
* Cleaned other columns like Running time and Imdb-rating and then converted their data-types to numeric.




# Movie Recommendation System—Data Sourcing

   ### CONTENTS
**[The Challenge](#the-challenge)**<br>
**[Starter Code](#starter-code)**<br>
**[Challenge Checklist](#challenge-checklist)**<br>
**[API Keys](#api-keys)**<br>
**[Running the Program](#running-the-program)**<br>

## The Challenge

Prepare data for a movie recommendation system which will help users find movie reviews and related movies. Utilizing APIs the data will be sourced from two public databases: [The New York Times](https://www.nytimes.com/), and [The Movie Database](https://www.themoviedb.org/). The extracted data will be merged and prepared for natural language processing (NLP).

## Starter Code

The starter code for this challenge consists of three files.  

1. A comma-separated values (CSV) file that provides sample output of the final process. This file will not be part of the uploaded content as it is for review only.
2. A sample environment file which provides the syntax for adding API keys to be used to source the data.
3. A Jupyter notebook (.ipynb) file that prompts for the expected code. It includes code to import all necessary python packages, read in the API keys, and set variables for access to data, and other bits and pieces. It also includes a preview of expected output for each cell.

## Challenge Checklist

### Part 1: Access the New York Times API

- [x] Access 20 pages of movie reviews from The New York Times
- [x] Preview JSON data
- [x] Convert data to Pandas DataFrame
- [x] Extract title data
- [x] Convert keywords column list to string
- [x] Create title list

### Part 2: Access the Movie Database API

- [x] Obtain list of movie titles from The Movie Database
- [x] Preview JSON data
- [x] Convert data to Pandas DataFrame

### Part 3: Merge and Clean the Data for Export

- [x] Merge both data sets
- [x] Fix column data
- [x] Drop irrelevant data
- [x] Delete duplication and re-index
- [x] Export final data to CSV

## API Keys

To run this program one will need their own API keys from [The New York Times](https://developer.nytimes.com/accounts/create), and [The Movie Database](https://www.themoviedb.org/signup). These keys would be saved in a .env file in the following format.

```
NYT_API_KEY="ENTER YOUR KEY HERE"
TMDB_API_KEY="ENTER YOUR KEY HERE"
```

## Running the Program

The program folder contains the completed Jupyter notebook which can be run cell by cell from and results displayed in Jupyter, Jupyter Lab, or VS code with Jupyter extensions.

```
retrieve_movie_data.ipynb
```

The outputs for cells in the notebook are saved with the file (just in case viewer does not have API keys to step through the notebook). The notebook cells may be re-run from top to bottom. Outputs may resemble those displayed in the original starter code. However, one step in the process where I diverged created more accurate results throughout the rest.

Additionally the final output will be stored in the output folder as a CSV file:

```
./output/collected_data.csv
```

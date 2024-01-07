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

- [ ] Access 20 pages of movie reviews from The New York Times
- [ ] Preview JSON data
- [ ] Convert data to Pandas DataFrame
- [ ] Extract title data
- [ ] Convert keywords column list to string
- [ ] Create title list

### Part 2: Access the Movie Database API

- [ ] Obtain list of movie titles from The Movie Database
- [ ] Preview JSON data
- [ ] Convert data to Pandas DataFrame

### Part 3: Merge and Clean the Data for Export

- [ ] Merge both data sets
- [ ] Fix column data
- [ ] Drop irrelevant data
- [ ] Delete duplication and re-index
- [ ] Export final data to CSV

## API Keys

To run this program one will need their own API keys from [The New York Times](https://developer.nytimes.com/accounts/create), and [The Movie Database](https://www.themoviedb.org/signup).  These keys would be saved in a .env file in the following format.

```
NYT_API_KEY="ENTER YOUR KEY HERE"
TMDB_API_KEY="ENTER YOUR KEY HERE"
```

## Running the Program

The program folder contains the completed Jupyter notebook which can be run cell by cell from and results displayed in Jupyter, Jupyter Lab, or VS code with Jupyter extensions.

```
retrieve_movie_data.ipynb
```

The outputs for all cells in the notebook may not be cleared (just in case viewer does not have API keys to step through the notebook). The notebook cells may be re-run from top to bottom. Outputs may resemble those displayed in the original starter code—give or take depending on how static the data source is.

Additionally the final output will be stored in the output folder as a CSV file:

```
./output/collected_data.csv
```

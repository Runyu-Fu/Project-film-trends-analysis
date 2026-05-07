# A Data Driven Study of Disney Films in Film Industry

## Overview

This project explores how Disney films have changed over time and how they compare with broader global film trends. I focused on Disney because it is one of the most influential companies in the entertainment industry, and I wanted to better understand how its genres, audience ratings, popularity, and storytelling style have evolved.

The project mainly looks at three questions:

1. How have Disney movie genres changed over time?
2. How have audience ratings and popularity changed compared with global movies?
3. How are runtime, genre, IMDb rating, awards, and Metascore related?

## Datasets

I used two public datasets from Kaggle:

- **Disney Movies & Shows Dataset**
  - Includes Disney titles, release years, genres, IMDb ratings, Metascore, awards, runtime, and plot descriptions.

- **IMDb Top 1000 Movies Dataset**
  - Used as a comparison dataset for global film trends.
  - Includes movie titles, release years, genres, IMDb ratings, votes, Metascore, runtime, and overview text.

## Methods

In this project, I used Python to clean, organize, and analyze the data. The main steps included:

- Cleaning release year, runtime, IMDb rating, Metascore, vote count, and award columns
- Splitting multi-genre entries so each genre could be analyzed separately
- Creating visualizations to compare Disney and global film trends over time
- Using sentiment-related text features from movie descriptions and overviews
- Comparing relationships between IMDb rating, Metascore, runtime, genre, and awards
- Applying basic statistical analysis and correlation testing

## Main Findings

The analysis shows that Disney films became much more diverse after 2000. Earlier Disney productions were more concentrated in family, comedy, and animation, while later films expanded into action, adventure, fantasy, thriller, and other genres.

Audience engagement, measured by IMDb votes, increased for both Disney and global films, especially after the 1980s and 1990s. However, Disney’s growth happened on a smaller scale compared with the global movie dataset.

Disney ratings also showed more fluctuation over time, while global movie ratings stayed relatively stable. In the text analysis, Disney plot descriptions showed stronger emotional variation, which fits Disney’s brand style of family-oriented and emotionally expressive storytelling.

Overall, Disney follows some broader film industry trends, but it still keeps its own brand identity, especially around family, fantasy, and emotional storytelling.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- plotly
- scipy
- TextBlob
- NLTK
- spaCy
- Jupyter Notebook

## Project Structure

```text
.
├── README.md
├── project_final.pdf
├── disney_plus_shows.csv
├── imdb_top_1000.csv
└── plots/

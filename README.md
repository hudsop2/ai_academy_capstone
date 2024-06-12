# ai_academy_capstone
Repository for final group project/capstone for Deloitte's AI Academy

# Data Dictionary:
- Joined together movies.csv, movies_2.csv, and movies_3.csv using Movie Title and Release Date year
### Columns of Data Loaded into Classification and Regression Modeling Notebooks
- **month_released**: Integer. Month of the year the movie was released.
- **rated**: String. What the movie is rated (R, PG, etc.)
- **genre**: String. Movie genre (Drama, Comedy, etc.)
- **runtime_minutes**: Double. Movie runtime length in minutes.
- **belongs_to_collection**: Boolean. Whether or not movie belongs to a collection of movies or not. (Ex: Toy Story Movies)
- **production_budget_usd**: Integer. Budget to produce the movie in US Dollars ($).
- **domestic_gross_usd**: Integer. Gross Domestic box office revenue of the movie in US Dollars ($).
- **worldwide_gross_usd**: Integer. Gross Worldwide box office revenue of the movie in US Dollars ($).
- **imdb_score**: Float. IMDb Score of the movie listed. IMDb is an online database of information related to film and other forms of media.
- **dir_____**: Boolean. 27 columns that list whether or not the director also contributed to listed role in creation of the movie. Roles include: Producer, Stunts, Composer, etc.
- **non_dom_gross_usd**: Integer. Gross non-domestic box office reveneue of the movie in US Dollars ($).
- **title_length**: Integer. Character length of the movie title.
- **worlwide_roi**: Double. Return on investment at a global scale based on production budget and worldwide gross US Dollars ($).
- **domestic_roi**: Double. Return on investment at a domestic scale based on production budget and domestic gross US Dollars ($).
- **non_dom_roi**: Double. Return on investment non-domestically based on production budget and non-domestic gross US Dollars ($).
- **success_level_ww**: Boolean. Whether or not the movie makes it's production budget back in revenue or not.
  

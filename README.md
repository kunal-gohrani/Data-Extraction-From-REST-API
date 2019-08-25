# Movies-Data-Extraction-from-REST-API
This project helps us extract data of 200 top rated movies from https://api.themoviedb.org/3/movie/top_rated?api_key=8265bd1679663a7ea12ac168da84d2e8&language=en-US&page=1 REST api link. The given link returns a JSON string and contains only 20 movies in each page. Iterating page by page, I have been able to extract data of 200 movies with information about each movie such as release date, popularity, average votes, summary of movie. 

## Technologies used:
- Python
- Pandas
- Requests
- JSON
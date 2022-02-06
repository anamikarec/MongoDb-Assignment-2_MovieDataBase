##### create a mock movies table in sequel and mongodb which has 500 documents which has following columns/fields

- id
- movie_name
- movie_genre
- production_year ( between 1990 to 2020)
- budget ( 9000 to 20000)
##### I want queries for the following in both mysql and mongo all queries should only return movie_name and production_year

- 1. find all movies which are equal to movie_name
- 2. find all movies which are not equal to movie_name
- 3. find all movies greater than and greater than equal to a budget
- 4. find all movies less than and less than equal to a budget
- 5. find all movies that are produced after 2000 with budget greater than 10000
- 6. find all movies that are produced after 2000 or budget greater than 10000
- 7. find all movies that are neither produced after 2000 nor with budget greater than 10000.
- 8. find all movies that are not produced in 2000 or they do not have budget of 10000
- 9. find all movies that were produced from 2000 to 2010.
- 10. Sort all movies descending based on the production year and if the year is same then alphabetically for their movie_names
- 11. in query 10 skip the first 10 entries and fetch the next 5
- 12. remove movie genre from the first 10 movies in query 10.
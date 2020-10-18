# SQL-
this is my practice repository
SELECT DISTINCT year from population_years;

SELECT population FROM population_years
ORDER BY country = 'Gabon' DESC
LIMIT 3;

SELECT country FROM population_years
WHERE year = 2005
ORDER BY population ASC
LIMIT 10;

SELECT country FROM population_years
 WHERE population > 100 AND year = 2010;

 
SELECT DISTINCT country FROM population_years
WHERE country LIKE '%Islands%';
 
SELECT population, year FROM population_years
 WHERE country = 'Indonesia' 
 AND year BETWEEN 2000 AND 2011
 ORDER BY year asc;

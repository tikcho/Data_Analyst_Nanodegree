-- Find city
SELECT * FROM city_list WHERE country LIKE 'Georgia'
-- Check data for the city
SELECT * FROM city_data WHERE city LIKE 'Tbilisi'

-- Save data for global avg
SELECT * FROM global_data

-- Save data for tbilisi avg
SELECT year, avg_temp FROM city_data WHERE city='Tbilisi'

-- Join tables and ssave data for city and global avg
SELECT global_data.year, global_data.avg_temp as globavg, city_data.avg_temp as cityavg 
FROM global_data 
JOIN city_data 
ON global_data.year=city_data.year 
WHERE city='Tbilisi'

# Weather Observation Station 5

## 1. Problem

[Problem page](https://www.hackerrank.com/challenges/weather-observation-station-5/problem)

## 2. Solution

```sql
SELECT CITY, LENGTH(CITY) FROM STATION
ORDER BY LENGTH(CITY), CITY
LIMIT 1;

SELECT CITY, LENGTH(CITY) FROM STATION
ORDER BY LENGTH(CITY) DESC, CITY
LIMIT 1;
```

# Weather Observation Station 6

## 1. Problem

[Problem page](https://www.hackerrank.com/challenges/weather-observation-station-6/problem)

## 2. Solution

```sql
SELECT DISTINCT CITY FROM STATION 
WHERE 
LEFT(CITY, 1) IN ('a', 'e', 'i', 'o', 'u');
```

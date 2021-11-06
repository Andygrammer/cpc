# Weather Observation Station 7

## 1. Problem

[Problem page](https://www.hackerrank.com/challenges/weather-observation-station-7/problem)

## 2. Solution

```sql
SELECT DISTINCT CITY FROM STATION
WHERE
RIGHT(CITY, 1) IN ('a', 'e', 'i', 'o', 'u');
```

# Weather Observation Station 4

## 1. Problem

[Problem page](https://www.hackerrank.com/challenges/weather-observation-station-4/problem)

## 2. Solution

```sql
SELECT COUNT(CITY) - COUNT(DISTINCT(CITY)) FROM STATION;
```

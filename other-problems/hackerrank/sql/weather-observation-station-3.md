# Weather Observation Station 3

## 1. Problem

[Problem page](https://www.hackerrank.com/challenges/weather-observation-station-3/problem)

## 2. Solution

```sql
SELECT DISTINCT CITY FROM STATION WHERE MOD(ID, 2) = 0;
```

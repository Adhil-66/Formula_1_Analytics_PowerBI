# DAX Measures -- Formula 1 Analytics



## 1. Total Points

``` dax
-- Total Points =
SUM(driver_standings[total_points])
```

## 2. Total Wins

``` dax
-- Total Wins =
SUM(driver_standings[wins])
```

## 3. Total Podiums

``` dax
-- Total Podiums =
SUM(driver_standings[podiums_est])
```

## 4. world championships

``` dax
-- World Championships =
SUM(driver_standings[is_world_champion])
```



# Beverage Sales Prediction 


This is Project / Exercises of creation of sales prediction of bevarage based on the "store5.csv" 

# EDA 

below table are the preview of the sales data , we only filtered data only "Beverage" 

| id    | date    | date       |store_nbr| family                    | sales       | onpromotion | dcoilwtico |
|-------|---------|------------|--------|----------------------------|-------------|------------|-------|
| 0     | 1452    | 2013-01-01 | 5      | AUTOMOTIVE                 | 0.000       | 0          | NaN   |
| 1     | 1453    | 2013-01-01 | 5      | BABY CARE                  | 0.000       | 0          | NaN   |
| 2     | 1454    | 2013-01-01 | 5      | BEAUTY                     | 0.000       | 0          | NaN   |
| 3     | 1455    | 2013-01-01 | 5      | BEVERAGES                  | 0.000       | 0          | NaN   |
| 4     | 1456    | 2013-01-01 | 5      | BOOKS                      | 0.000       | 0          | NaN   |
| ...   | ...     | ...        | ...    | ...                        | ...         | ...        | ...   |
| 55567 | 3000586 | 2017-08-15 | 5      | POULTRY                    | 241.011     | 1          | 47.57 |
| 55568 | 3000587 | 2017-08-15 | 5      | PREPARED FOODS             | 52.121      | 0          | 47.57 |
| 55569 | 3000588 | 2017-08-15 | 5      | PRODUCE                    | 1357.823    | 4          | 47.57 |
| 55570 | 3000589 | 2017-08-15 | 5      | SCHOOL AND OFFICE SUPPLIES | 0.000       | 0          | 47.57 |
| 55571 | 3000590 | 2017-08-15 | 5      | SEAFOOD                    | 9.669       | 0          | 47.57 |


Top 5 of the data are below 

```
                  sales
family                 
GROCERY I  5.262682e+06
BEVERAGES  2.533831e+06
CLEANING   1.667748e+06
PRODUCE    1.653582e+06
DAIRY      8.712830e+05
```

Below are the steps taken added 

- Filtered to Beverages
- Changing datatype Date 
- Add missing date
- Add calender atribute (Year , Month , Holiday and weekend Flag etc)
- Scaling (Sales , dcoilwtico)
- Backfill and interpolate (dcoilwtico)
- Adding Rolling Mean





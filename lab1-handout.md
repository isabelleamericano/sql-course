# Stuctured Query Language, Pt. 1

## Learning Objectives:
- What is SQL?
- Why do we need to know it?
- How do we use it?

## Setup

##### 1. go to the class directory
``cd ~/gasql``

##### 2. import our sample database - the cities, countries, and languages of the world
``./sqlite3 world.sqlite``

##### 3. view all available tables
``.tables``

##### 4. view the country table schema
``.schema country``

##### 5. more tips

**To get out of a line continuation:** ```;```

**To exit SQLite:** ```.quit```


## Selecting

###### select everything from this table
```
SELECT * 
FROM country;
```

###### select just certain columns
```
SELECT code,name,continent,population 
FROM country;
```

###### find one row, based on a country code
```
SELECT code,name,continent,population 
FROM country 
WHERE code='ARG';
```

###### find any rows that are similar
```
SELECT code,name,continent,population 
FROM country 
WHERE code LIKE 'AR%';
```

###### find all countries where there's a population of at least 100 million people
```
SELECT code,name,continent,population 
FROM country 
WHERE population >= 100000000;
```


###### find only European countries whose population is more than 40 million
```
SELECT code,name,continent,population 
FROM country 
WHERE continent='Europe' AND population > 40000000;
```

###### sort those countries by population, from most to least
```
SELECT code,name,continent,population 
FROM country 
WHERE continent='Europe' AND population > 40000000 
ORDER BY population DESC;
```

_Special thanks to Micah Rich, GA Los Angeles!_

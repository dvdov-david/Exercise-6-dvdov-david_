# Exercise 6: Data analysis with Pandas II (10 points)

In this week's exercise we will continue developing our skills using Pandas to analyze climate data.

The aim of this exercise is to analyze historical weather data and **weather anomalies**. In Problem 1 you read in a tricky data file and explore it's contents. In problem 2, you will convert and aggregate the data from daily temperatures in Fahrenheit, to monthly average temperatures in Celsius. In Problem 3, you will finally analyze weather anomalies by conparing monthly average temperatures to a long-term average.

If you are uncertain about **the style of your code**, take a look at the **[PEP 8 - Style guide for Python code](https://www.python.org/dev/peps/pep-0008/)**.

After making your changes to the notebook, you will need to upload it to GitHub.

- **Exercise 6 is due by the start of the next lesson (9:15 am, 14 October 2020)**.
- Don't forget to check out the [hints for this week's exercise](https://geo-python-site.readthedocs.io/en/latest/lessons/L6/exercise-6.html#exercise-6-hints) if you're having trouble.
- Scores on this exercise are out of **10 points (Problems 1-3)**. Problem 4 is optional.

## Before you start

### Clone the Exercise 6 repository

- Make sure you cloned your own repository (repository name contains your GitHub username). 
- After solving the problems, remember to commit your changes and push them to GitHub. 
- Remember also to answer all written questions in the exercise, in addition to the programming tasks.

### Input data

For problems 1-3 in this exercise we will be using historical climate data from the Helsinki-Vantaa airport station.
For these problems, we have daily observations obtained from the [NOAA Global Historical Climatology Network](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND).
The file was downloaded using the "Custom GHCN-Daily Text" output format, including following attributes:

| Attribute                | Description                      |
|--------------------------|----------------------------------|
| `STATION`                | Unique ID of the weather station |
| `ELEVATION`              | Elevation of the station         |
| `LATITUDE` , `LONGITUDE` | Coordinates of the station       |
| `DATE`                   | Date of the measurement          |
| `PRCP`                   | Precipitation                    |
| `TAVG`                   | Average temperature              |
| `TMAX`                   | Maximum temperature              |
| `TMIN`                   | Minimum temperature              |

The file for this problem is exactly as available from the NOAA website. You can take a [look of the data](data/1091402.txt).

**Note**: once again that temperatures in this dataset are given in degrees Fahrenheit.

Additional information about the data format can be found in the [hints for Exercise 6](https://geo-python-site.readthedocs.io/en/latest/lessons/L6/exercise-6.html#exercise-6-hints).

## Getting started

Always remove these two lines when starting to work on an exercise:
```
# REPLACE THE ERROR BELOW WITH YOUR OWN CODE
raise NotImplementedError()
```
This error will tell us if you have not even started to solve the problem when checking the exercises :)

## Problems

**Note**: Problems 1-3 are all in one notebook.

- [Problems 1-3: Analysing Helsinki climate data](Exercise-6-problems-1-3.ipynb)
- [Problem 4: Analysing Sodankyla climate data (optional)](Exercise-6-problem-4.ipynb)
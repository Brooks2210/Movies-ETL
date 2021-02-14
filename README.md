# MoviesETL
The purpose of this project was to learn the basics of EXTRACT, TRANSFORM, and LOAD. The data used was from both .csv files and JSON data.

## Initial Steps:
The first steps was to pull the data into jupyter notebooks and create panda files. After the data was loaded, a plan needed to be made to determine which data could be used, transformed, or deleted.

## Badly damaged data was fixed by:

Filling in missing data by
  -substituting data from another source,
  -interpolating between existing data points, or
  -extrapolating from existing data

Standardizing units of measure (e.g., monetary values stored in multiple currencies)

Consolidating data from multiple columns

### fixing data in the wrong form

  Reshape the data
  Convert data types
  Parse text data to the correct format
  Split columns
 
 Finally data frames were merged and uploaded in Postgres and viewed using pgAdmin to make sure everything loaded properly

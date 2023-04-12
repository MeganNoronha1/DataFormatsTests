# DataFormatsTests

Notebooks to test different dataformats storing pseudo experiment data.

## I/O speed tests

### Write speed (average of 100)
- As a function of # of rows (5 columns worth, 2e3 - 1e6 points)

### Read (average of 100):
- Metadata read (how long to access one scan’s metadate)
- Column read (how long to access two columns [but check by column])

### Data efficiency
- Storage size as function of rows for 5 columns
- Storing meta experiments in one file vs many (as a function of n experiments)


### Possible solutions
- <span style='color:black'> JSON </span>
- <span style='color:green'> NetCDF </span> and <span style='color:lime'> NetCDF with compression </span>
- <span style='color:magenta'> Parquet </span> and <span style='color:hotpink'> Fast Parquet</span>
- <span style='color:red'> ORC </span>
- <span style='color:blue'> Avro </span>
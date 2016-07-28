[WIP]

Pandas DataFrame analogues in H2OFrame (in the Python API)

#### Create a toy dataframe
```
# from a list of tuples
testframe = h2o.H2OFrame([(1,2,3), (4,5,6), (7,8,9)])

# with strings/categoricals
duckframe = h2o.H2OFrame([('Mallard', 1.10, 89), ('Long-tailed duck', 0.74, 71), ('Northern shoveler', 0.60, 76)])
duckframe.col_names = ['Species', 'Weight_kg', 'Wingspan_cm']
```

#### Read from csv/tsv

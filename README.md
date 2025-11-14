# circuitydatabase
Source for the Circuity Database designed to be distributed through PyPI.

# Installation instructions
```
python3 -m pip install circuitydatabase
```

# Running circuity from the command-line
```
% circuity --csv-path example/directory/data_file.csv --query 'justin age'
```

# Developer instructions
## Publishing new versions

```
twine upload dist/*
```

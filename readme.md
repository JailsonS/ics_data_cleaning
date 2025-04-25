This repository contains scripts for inspecting and standardizing count values across different units.

### Requirements

- python 3.9^

### Folder strucutre
```
project
│   readme.md
|   01_std_units.ipynb
|   ...
│   requirements.txt - requirements
└───data
|       dataset_carnes_v2.parquet
|       rules_v8.json
```

### create virtual env
`python -m venv ./venv `

### activate virtual env
- windows
    `. venv/Scripts/activate` <br>
- linux
    `. venv/bin/activate` <br>

## Install requirements
`pip install -r requirements.txt`

### Note

Follow the instructions above to run the dataset conversion pipeline. Ensure that all required inputs are available, <br>
including the Parquet file and the rules dictionary (rules.json).
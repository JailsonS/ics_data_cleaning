This is a short script to clean beef dataset

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

Follow the above instructions to run the pipeline of conversion dataset, make sure that all inputs are <br>
available i.e. parquet file, dictionary of rules (rules.json)
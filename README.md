# Instructions

## Install

With tool of your choice. e.g. venv and pip

- `python -m venv venv`
- `source venv/bin/activate`
- `pip install .`
- `athome-generator --help`

## Run Generator

```
usage: athome-generator [-h] [-d DATA_DIR] [-p]

Generate Commands for Robocup@Home

options:
  -h, --help            show this help message and exit
  -d DATA_DIR, --data-dir DATA_DIR
                        directory where the data is read from
  -p, --print-config    print parsed data and exit
```

Run the generator for the given DATA_DIR
- `athome-generator -d DATA_DIR`

For an example layout check out the: [CompetitionTemplate](https://github.com/RoboCupAtHome/CompetitionTemplate)




[README_Assignment5.md](https://github.com/user-attachments/files/35167619/README_Assignment5.md)
# CSA08 Assignment 5 — City Air Quality Monitoring

## Student

* Name: Selva Raghaav S
* Register number: 1914260028

Repository: https://github.com/raaghav10-hue/CSA-08-1914260028-Assignment5

Environment

* Python version: \[Run `python --version`]
* Libraries: \[List actual libraries and versions]
* Install: `python -m pip install -r requirements.txt` (if requirements are present)

## Structure

```text
TaskA1/       source inspection, schema and queries
TaskA2/       cleaning and normalization design
TaskA3/       analysis and visualization design
TaskA4/       debugging and profiling plan
TaskA5/       complaint sentiment, summary and chatbot
TaskB1/       cleaning pipeline, fixtures, SQLite and charts
TaskB2/       adversarial data and parameterized SQL
TaskB3/       benchmarks and profiling
TaskB4/       final scale decision and evaluation
requirements.txt
README.md
```

## Run commands and results

Update filenames and notes to match the committed programs and actual runs.

|Task|Command|Result note|
|-|-|-|
|B1 Cleaning|`python TaskB1/clean\_pipeline.py`|\[Record accepted/rejected rows and output files]|
|B2 SQL tests|`python TaskB2/sql\_tests.py`|\[Record malformed-input and injection-safe query results]|
|B3 Benchmarks|`python TaskB3/benchmark.py`|\[Record timings for 1, 12 and 120 stations]|
|B4 Evaluation|`python TaskB4/evaluate.py`|\[Record complaint agreement and index timings]|

## Data and reproducibility

Keep source CSVs or deterministic data-generation scripts, rejected-row logs, cleaned outputs, the SQLite creation/import script, generated charts, benchmark output and execution screenshots in the matching task folders. Record machine/runtime details with timing results. Do not report measurements until they have been run.

## Dependencies

Python standard library modules used: csv, sqlite3, statistics, re, logging, timeit, cProfile. Add exact third-party package versions such as pandas and matplotlib to `requirements.txt` if used.


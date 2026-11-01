# CS50P Python Exercises

This repository contains my exercises and small examples from working through [CS50's Introduction to Programming with Python (CS50P)](https://cs50.harvard.edu/python/). I’m keeping it as a record of what I’ve learned through self-directed practice.

These are learning exercises rather than a single application. The files are organized by the course section or topic they relate to, and some are intentionally small demonstrations of one concept.

## What’s here

| File | What it practices |
| --- | --- |
| `CS50P0.py` | Functions, input, and squaring a number |
| `CS50P1.py` | `match` statements and conditional logic |
| `CS50P2.py` | Loops and printing a square |
| `CS50P3.py` | Command-line arguments, JSON, and requesting song results from the iTunes Search API |
| `CS50P4.py` | Functions, default arguments, and a greeting |
| `CS50P5.py` | Pytest tests for the greeting function |
| `CS50P6.py` | Writing rows to a CSV file |
| `CS50P7.py` | Regular expressions and extracting a username from a URL |
| `CS50P8.py` | Classes and class methods |
| `CS50P8vault.py` | Operator overloading with a `Vault` class |
| `CS50P8wizard.py` | Class inheritance |
| `names_CS50P6.csv` | Example CSV data |

## Requirements

- Python 3.10 or later
- `requests` for the iTunes API example
- `pytest` to run the tests

Install the packages used by those examples with:

```bash
python -m pip install requests pytest
```

## Running the examples

Run commands from the repository folder. For example:

```bash
python CS50P0.py
python CS50P7.py
```

The API example accepts a search term as a command-line argument:

```bash
python CS50P3.py coldplay
```

Run the tests with:

```bash
python -m pytest
```

Some examples prompt for input. The CSV exercise appends entries to `names_CS50P6.csv`, so running it changes that file.

## Learning notes

I’m using this repository to track my progress and keep the code I write while learning Python. The exercises may be simple or incomplete by design; the focus is on practicing concepts and improving over time.

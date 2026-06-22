# Template Repo for Python Scripts

> Default template for the publication/release of python scripts

## Requirements

- Python 3.7+

## Setup

1. Clone the repo
1. Rename config.py.example to config.py
1. Create any necessary tokens
1. Populate config.py

## Usage

```bash
python script.py
```

## Changes and Release

Increment the package.json version, using SEMVER when commiting new changes to the script.
The GitHub action will  create a new release using the last commit message as the release note.

## Notes

> Script specific details goes here

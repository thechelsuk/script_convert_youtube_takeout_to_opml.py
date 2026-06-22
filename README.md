# Convert YouTube Takeout CSV to OPML File

> Script to convert YouTube Takeout CSV data into an OPML file for easier subscription management.

## Requirements

- Python 3.7+

## Setup

1. Clone the repo
1. Rename config.py.example to config.py
1. Populate config.py

## Usage

```bash
python script.py
```

## Changes and Release

Increment the package.json version, using SEMVER when committing new changes to the script.
The GitHub action will  create a new release using the last commit message as the release note.

## Notes

> Export the CSV file from Google's Takeout service, and place it in the same directory as the script.
> The script will read the CSV file and generate an OPML file that can be imported into feed readers or other applications that support OPML format. converting channels to their RSS feed urls.
> Entries are put into a folder named "YouTube" in the OPML file. You can change this in the config.py file, but this offers separation from the other feeds you may have in your feed reader.

## ExophaseExport

This script makes it easy to grab all your data from Exophase. Just log in through the browser it opens, it’ll find your player ID on its own, then download everything and save it as JSON and Excel files for you.

## Requirements

    Python 3.8 or higher

    Playwright (for browser automation)

    pandas (for Excel export)
    
    openpyxl (Excel file engine)
## Installation

1.Download the script.

2.(Recommended) Сreate a virtual environment:

## Linux
    python3 -m venv venv
    source venv/bin/activate 
## Windows
    py -3 -m venv venv
    \venv\Scripts\Activate.ps1
3.Install dependencies:

    pip install playwright pandas openpyxl

4.Install browser binaries for Playwright:

    playwright install
After run .py and folow instruction 
## NOTE: Keep browser window open until the script finishes. 

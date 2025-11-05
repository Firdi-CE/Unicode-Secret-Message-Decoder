Google Doc Secret Message Decoder
This is a Python utility that fetches a publicly published Google Doc, parses a table of 2D coordinates and Unicode characters, and renders the resulting 2D graphic in the console. It's designed to decode "secret messages" hidden in this specific data format.

Features
Web Fetching: Reads data directly from a public Google Doc URL.

HTML Parsing: Uses BeautifulSoup to find and parse the data table.

2D Grid Rendering: Correctly interprets a Cartesian coordinate system (where y=0 is the bottom row) and builds a 2D grid.

Console Output: Prints the final graphic directly to your terminal.

Requirements
Python 3.x

requests library

beautifulsoup4 library

Installation
You can install the necessary libraries using pip:

Bash

pip install requests beautifulsoup4
Usage
Save the code as a Python file (e.g., decoder.py).

Import and call the print_google_doc_grid() function, or simply include your function call at the end of the script.

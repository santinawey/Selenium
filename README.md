# Selenium
Automated PDF Download 

## Description

This project is a demonstration of web scraping and file download using Selenium and Python. It utilizes the Selenium library to navigate to a specific website, extract the download URL for a file, and then uses the Requests library to download the file to a specified location on your local machine.

## Requirements

To run this project, you need to have the following installed:

- Python [3.10.11]
- Selenium [4.10.0]
- ChromeDriver [114.0.5735.90]
- Requests [2.31.0]

## Usage

1. Make sure you have the ChromeDriver executable in your PATH or specify its path in the script.
2. Open the Python script and update the following variables:
   - `path`: Path to the ChromeDriver executable (if not in PATH).
   - `download_path`: Path where you want the file to be downloaded.
3. Run the script: `python script.py`
4. The script will open a Chrome browser, navigate to the specified website, extract the download URL, and download the file to the specified location.
5. Once the file is downloaded, you will see a success message in the terminal.

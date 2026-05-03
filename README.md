# ITPM-IT23633018

# IT3040 Assignment 1 - Transliteration Accuracy Testing

This project automates test execution for the PixelSuite Chat Sinhala transliteration tool using Playwright and Python.

## Requirements

- Python 3.11 or above
- Google Chrome / Playwright Chromium
- Playwright
- openpyxl

## Install dependencies

pip install -U pip
pip install playwright openpyxl
python -m playwright install

## Run tests

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --header-row 1 --url "https://www.pixelssuite.com/chat-translator" --wait-ms 8000 --type-delay-ms 100 --slow-mo-ms 500 --save-every 1

## Output

The script reads the Singlish input and expected Sinhala output from the Excel file, runs the test cases on the website, and records the actual output and test status in the Excel file.

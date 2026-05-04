# IT3040 Assignment 1 – Transliteration Accuracy Testing

## Objective
To evaluate the accuracy of Singlish to Sinhala transliteration using automated testing.

## Tools Used
- Python
- Playwright
- Excel

## Setup Instructions
py -m pip install playwright openpyxl
py -m playwright install

## Execution Command
py test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Description
This repository contains 50 negative test cases covering all 24 Singlish input types. The tests were automated using Playwright and results were recorded in Excel.

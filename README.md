# test_automation_ui

Playwright automation script for IT3040 Assignment 1 — Functional and Usability Testing of pixelssuite.com

## What This Tests
Automated test to verify the image preview functionality of the Image Format Conversion feature at:
https://www.pixelssuite.com/convert-to-png

Uploads a PNG file and checks whether a preview image is displayed on the page.

## Project Structure
- image_preview_test.py — Main Playwright test script
- sample.png — Sample PNG file used for testing
- execution_results.csv — Recorded test execution results
- results/ — Folder containing screenshots from test runs

## Requirements
- Python 3.11 or 3.12
- Google Chrome (recommended)

## Installation

Step 1 — Install Python dependencies:
pip install playwright openpyxl

Step 2 — Install Playwright browsers:
playwright install

## How to Run

Step 1 — Navigate to the project folder in Command Prompt:
cd /d D:\test_automation_ui

Step 2 — Run the test:
python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Expected Output
After running, check:
- execution_results.csv — should contain one row with status PASS
- results/preview_pass.png — screenshot of the browser during the test

## Test Result
- File tested: sample.png (PNG format)
- Preview detected: True
- Status: PASS

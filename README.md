# IT23413474 – IT3040 Assignment 1

## Project: Automated Testing for Singlish to Sinhala Transliteration System

## GitHub Repository
https://github.com/dayanwishwanathr/it23413474-it3040-assignment-1

## Prerequisites
- Python 3.11/3.12
- Install dependencies: `pip install -r IT23413474_requirements.txt`
- Install browsers: `playwright install`

## How to Run
Open your terminal or command prompt and navigate to the project directory:

```bash
cd "\IT23413474\IT23413474_test_automation"
```

Once inside the directory, execute the automation script to run the tests:

```Bash
python IT23413474_test_automation.py --excel "IT23413474_Assignment 1 - Test cases.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

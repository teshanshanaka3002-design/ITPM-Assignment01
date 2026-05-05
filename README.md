# IT3040 – Assignment 1 /IT23706682 (Option 1)

## 📌 Project Overview

This project evaluates the accuracy of a Singlish-to-Sinhala transliteration system using automated testing.

The system under test:
https://www.pixelssuite.com/chat-translator

##  What was done

* Identified 50 negative test cases where the system fails
* Covered all 24 Singlish input types
* Automated testing using Playwright
* Recorded outputs and results in Excel

## ⚙️ Setup Instructions

### 1. Install dependencies

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

### 2. Run the test script

```bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```


## 📁 Project Structure

```
test_automation/
 ├── test_automation.py
 ├── Assignment 1 - Test cases.xlsx
 ├── (other files)
```

##  Note - important

* Script should be run only once before adding additional columns
* Excel file should not be modified before execution

---

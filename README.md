# ITPM-Assignment-01-Test-Automation

## Student Information
- Student Name: Thilakarathna A.G.I.D
- Student ID: IT23681842  
- Group: Y3.S1.WD.IT.02.01  

---

## Project Description

In this project, a real-world web system was tested using automated testing.

The selected system:
https://www.pixelssuite.com/chat-translator

This system converts **Singlish input into Sinhala output**.

A total of **50 test cases** were created to identify failing scenarios.  
Automation was implemented using **Python and Playwright**.

---

## Project Files

- `test_automation.py` → Automation script  
- `IT23681842-Assignment 1 - Test cases.xlsx` → Test cases  
- `README.md` → Project instructions  

---


## Technologies Used

- Python  
- Playwright  
- openpyxl  
- Microsoft Excel  

---

## Prerequisites

Make sure the following are installed:

- Python 3.11 or above  
- Google Chrome browser  

---

## Added Dependencies

- playwright  
- openpyxl  

---

## How to Setup the Project

### 1. Clone the repository

```bash

Open a new terminal

Navigate to the project folder
cd IT23681842

Install dependencies
pip install -U pip
pip install playwright openpyxl

Install Playwright browsers
playwright install

How to Run the Tests

⚠️ IMPORTANT:

Close the Excel file before running
Ensure a stable internet connection

Run the following command:
python test_automation.py --excel "test_automation/IT23681842-Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

What the Automation Script Does

Opens the Chat Translator website
Reads Singlish inputs from Excel
Enters inputs into the system
Captures Sinhala output
Compares Expected vs Actual output
Updates Excel with PASS / FAIL results
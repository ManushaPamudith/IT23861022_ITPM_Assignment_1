# IT3040 – Assignment 1

## Automated Testing of Singlish to Sinhala Translator

---

## 👤 Student Details

* **Name:** PUSHPAKUMARA G.K.M.P
* **Registration Number:** IT23861022
* **Module:** IT3040 – IT Project Management 

---

## 📌 Project Overview

This assignment focuses on identifying failures in a Singlish to Sinhala chat translator system.

A total of **50 negative test cases** were created where the system fails to correctly convert Singlish input into Sinhala output.

Automation was performed using the provided **Playwright Python script (`test_automation.py`)**.

---

## 🎯 Objectives

* Identify incorrect translations (FAIL scenarios)
* Cover all **24 Singlish input types** (Appendix 1)
* Include **at least 2 test cases per type**
* Automate testing using Playwright

---

## 🧪 Test Case Details

* **Total Test Cases:** 50
* **Type:** Negative (FAIL cases only)
* **Format:** Excel file

Each test case includes:

* Input (Singlish)
* Expected Output (Correct Sinhala)
* Actual Output (System result)
* Status (PASS / FAIL)
* Singlish Input Type
* Evidence / Rationale

---

## ⚙️ Technologies Used

* Python 3
* Playwright
* OpenPyXL
* Microsoft Excel

---

## 🚀 How to Run the Automation Script

### 🔹 Step 1: Install dependencies

Open terminal and run:

* pip install playwright openpyxl 

* playwright install

---

### 🔹 Step 2: Run the script

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

---

### 🔹 Step 3: Output

* The script will:

  * Read inputs from Excel
  * Run tests on the translator
  * Write:

    * Actual Output
    * PASS / FAIL status

---



## 🔗 GitHub Repository

https://github.com/ManushaPamudith/IT23861022_ITPM_Assignment_1.git

---

## ⚠️ Important Notes

* Only **FAIL test cases** are included
* All **24 input types are covered**
* At least **2 cases per type**
* No examples copied from Appendix 1 or 2
* Provided automation script is used without modification

---

## ✅ Conclusion

This project demonstrates the limitations of the translator system using structured test cases and automation.

---

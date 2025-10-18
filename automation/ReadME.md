# Automation Testing (Katalon)

## Overview
This folder contains automated test scripts developed using **Katalon Studio 10.1.1 for validating key workflows of the selected web application — [https://www.saucedemo.com/](https://www.saucedemo.com/).

### Objective
To automate essential functional flows to ensure the stability of critical user journeys during regression testing.

---

## Test Scenarios Automated

1. **Login Test**
   - Validate user login with valid credentials.
   - Verify error message for invalid credentials.

2. **Add to Cart Test**
   - Log in with valid credentials.
   - Add a product to the cart.
   - Verify the product appears in the cart summary page.

---

## Tools & Environment
- **Automation Tool:** Katalon Studio 10.1.1 
- **Language:** Groovy  
- **Operating System:** Windows 11  
- **Browser:** Chrome  

---

## How to Run the Tests
1. Open Katalon Studio and import this project folder.  
2. Configure test data if needed (under `Data Files`).  
3. Select the test suite and click **Run** (choose browser: Chrome).  
4. View execution results in the **Log Viewer** and **Reports** tabs.

---

## Expected Results
- Login flow completes successfully and lands on the Products page.
- Add to Cart flow correctly displays selected items in the cart.
- Failed login attempts show a proper validation message.

---

## Author
**Muhammad Tauqeer**  
Senior QA Automation & Manual Engineer – AKSA-SDS

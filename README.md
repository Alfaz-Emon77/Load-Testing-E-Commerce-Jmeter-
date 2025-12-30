# Load-Testing-E-Commerce-Jmeter-


## Project Overview
This project demonstrates **Load Testing using Apache JMeter** for an **e-commerce website flow** (login/search/add-to-cart) as a **portfolio/demo project**.

⚠️ **Disclaimer:**  
This test is **NOT for live e-commerce websites like Daraz.com**.  
All scripts are designed for **educational/demo purposes** using a local or mock environment.

---

## Tools & Technologies
- Apache JMeter
- CSV Data Set Config
- HTTP Request Sampler
- View Results Tree
- Summary Report Listener

---

## Test Scenario
- Multiple users simulate browsing, login, and adding products to cart
- Data-driven testing using CSV
- Load applied via Thread Group

---

## CSV Example
```csv
username,password
testuser1,123456
testuser2,abcdef
testuser3,qwerty

# 🚀 Performance & Load Testing Project

This project demonstrates performance and load testing using:
- 🧪 **Postman** – for API functional testing
- 📈 **Apache JMeter** – for simulating concurrent user load and evaluating performance

## 📌 Project Goal

To test the performance and stability of the public API at [ReqRes](https://reqres.in) by simulating multiple users using JMeter and validating endpoints with Postman.

## 🔧 Tools Used

| Tool     | Use                            |
|----------|--------------------------------|
| Postman  | API functional testing         |
| JMeter   | Load/performance testing       |

## ✅ Tested API Scenarios

| Endpoint                        | Method | Purpose               |
|---------------------------------|--------|------------------------|
| `/api/users?page=2`            | GET    | List users             |
| `/api/users`                   | POST   | Create a new user      |

## 🔁 JMeter Test Plan

- Simulated **10 users**, looped twice
- Tested GET and POST endpoints
- Monitored:
  - Average response time
  - Error %
  - Throughput

## 📊 Sample Results

![Summary Report](./screenshots/summary-report.png)

- Avg response time: ~303 ms
- Error rate: 0%
- API handled simulated load successfully

## 📂 Files Included

- `jmeter_test_plan.jmx` – JMeter load test file
- `postman_collection.json` – API test requests
- `screenshots/` –  summary report images
- `screenshots/` –  graph result images
- `screenshots/` –  view result tree images

---

> Created by Augustin Aldrin KJ  
> 📧 augustin.aldrin@example.com  
> 🌐 [LinkedIn](https://linkedin.com/in/augustin-aldrin-kj-617361259) | [GitHub](https://github.com/aldrinkj)

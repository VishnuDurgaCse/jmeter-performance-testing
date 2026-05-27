# ⚡ JMeter Performance Testing

Performance and load testing using Apache JMeter on reqres.in REST API simulating 50 concurrent virtual users

---

## 🛠️ Tools Used

![JMeter](https://img.shields.io/badge/Apache%20JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📌 What This Project Covers

- ✅ Load testing with 50 concurrent virtual users
- ✅ API performance measurement — response time, throughput
- ✅ Error rate validation
- ✅ Real-world API testing on reqres.in
- ✅ Command line test execution

---

## ⚙️ Test Configuration

| Parameter | Value |
|---|---|
| Tool | Apache JMeter 5.6.3 |
| Target API | https://reqres.in/api/users |
| Method | GET |
| Virtual Users | 50 |
| Ramp-up Period | 10 seconds |
| Loop Count | 1 |

---

## 📊 Test Results

| Metric | Value |
|---|---|
| Total Requests | 50 |
| Average Response Time | 685 ms |
| Min Response Time | 191 ms |
| Max Response Time | 1169 ms |
| Throughput | 36.8 requests/sec |
| Error Rate | 0.00% |

---

## 📸 Test Execution Screenshot

![Command Line Results](command_line_results.png)

---

## ▶️ How to Run

Prerequisites
- Java JDK 21
- Apache JMeter 5.6.3

Run from command line

jmeter -n -t reqres-load-test.jmx -l results.jtl

Open in JMeter GUI
Double click jmeter.bat and open reqres-load-test.jmx

---

## 🔑 Key Concepts Covered

- ✅ Thread Group — simulating concurrent users
- ✅ HTTP Request Sampler — API endpoint testing
- ✅ HTTP Header Manager — API key authentication
- ✅ Summary Report — performance metrics
- ✅ View Results Tree — individual request results
- ✅ Response Time Graph — visual performance analysis

---

## 💡 Test Analysis

- All 50 requests completed successfully with 0% error rate
- Average response time of 685ms is within acceptable range
- Max response time of 1169ms shows occasional latency spikes
- Throughput of 36.8 requests per second confirms stable API performance

---

## 👩‍💻 Author

Vishnu Durga S

GitHub: https://github.com/VishnuDurgaCse

Email: vishnudurgacs@gmail.com

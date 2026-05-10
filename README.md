# Restful Booker API Performance Testing

## Project Overview

This project contains performance testing scripts for the **Restful Booker API** using Apache JMeter. The goal of this project is to evaluate API performance, response time, throughput, and stability under load.

## Tools & Technologies

* **Apache JMeter** – Performance testing tool
* **Restful Booker API** – Test target API
* **CSV Data Set Config** – Dynamic test data handling
* **Assertions** – Response validation
* **Pre-Processors & Post-Processors** – Dynamic variable extraction and data management
* **Command Line Execution (CLI)** – Test execution via terminal
* **HTML Dashboard Report** – Result analysis and reporting

## Test Scenarios

* Create Booking API load testing
* Response validation with assertions
* Dynamic data extraction and reuse
* Concurrent user simulation
* Performance metrics analysis

## Project Structure

```bash
├── TestPlan.jmx          # JMeter test script
├── data/                 # Test data files (if any)
├── reports/              # Generated HTML reports
├── results/              # JTL result files
└── README.md             # Project documentation
```

## How to Run

### Run via JMeter GUI

1. Open Apache JMeter
2. Load the `.jmx` file
3. Configure test data if needed
4. Run the test

### Run via Command Line

```bash
jmeter -n -t TestPlan.jmx -l results/result.jtl -e -o reports/
```

## Performance Metrics Covered

* Response Time
* Throughput
* Error Rate
* APDEX Score
* Requests per Second

## Sample Report

Generated JMeter HTML Dashboard Report for performance analysis.

## Learning Outcomes

* API Performance Testing
* Load & Stress Testing
* Dynamic Data Handling in JMeter
* Assertions & Validation
* Report Generation & Analysis

<img width="1883" height="939" alt="restfulBookerJmeter" src="https://github.com/user-attachments/assets/c845ca62-b3fc-4f43-b78b-44014bfe8bfe" />
<img width="1914" height="919" alt="report2" src="https://github.com/user-attachments/assets/27bfe3de-a6d4-4981-a375-756aef85b445" />



## Author

**Tahsin Ahmmed**
Software Quality Assurance (SQA) Engineer

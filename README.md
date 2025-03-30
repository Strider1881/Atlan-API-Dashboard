
# Atlan API Observability Dashboard
This repository contains the solution for the Atlan Platform Internship Challenge 2025 - Observability. The goal of this project is to improve debugging efficiency by implementing observability solutions that track key metrics, monitor system performance, and provide actionable insights.

## 📋 Project Overview
- The goal of this project is to enhance observability for Atlan's API ecosystem by:

- Monitoring critical API performance metrics (response times, error rates, throughput).

- Implementing a structured logging strategy.

- Designing a shared dashboard for tracking system health.

- Reducing repetitive debugging tasks through automation.

This solution is designed to address inefficiencies in debugging workflows and improve response times for identifying and resolving issues.

## 🛠️ Features

#API Performance Metrics:

  - Tracks response times (p50, p90, p99), request rates, and error rates.

  - Identifies slow endpoints and high-error-rate APIs.

#Database Monitoring:

- Monitors query execution time, throughput, and cache hit/miss ratios.

#System Resource Utilization:

- Tracks CPU usage, memory consumption, disk I/O, and network latency.

#Request Tracing:

- Follows requests across services to pinpoint bottlenecks.

#Error Detection & Alerts:

- Categorizes errors (e.g., 500 Database Timeout, 503 Service Unavailable) and triggers alerts for abnormal patterns.

#📊 Dashboard Preview
The project includes a sample dashboard showcasing real-time metrics:

|Metric                 |	Description                             |
|-----------------------|-----------------------------------------|
|Response Time	Tracks  | latency across endpoints                |
|Error Rate	            | Monitors failure percentages            |
|CPU & Memory Usage    	| Displays resource consumption           |

#Sample Dashboard Screenshot:
![Dashboard Example](docs/dashboard

#📂Repository Structure

📂 Atlan-API-Observability-Dashboard. <br>
├── 📂 docs <br>
│   ├── observability.pdf        # Explanatory document with design decisions <br>
│   ├── ATLAN-Internship-Challenge.pdf # Detailed challenge description<br>
│   ├── dashboard_image.png      # Sample dashboard screenshot<br>
├── 📂 assets<br>
│   └── Atlan-API-Observability-Dashboard.html # Dashboard implementation (HTML)<br>
├── README.md                    # Project documentation (this file)<br>


#🚀 Getting Started
#Prerequisites
To view or extend the project:

-Open Atlan-API-Observability-Dashboard.html in any modern web browser.

-Optionally, use monitoring tools like Grafana or Kibana for additional insights.

#Installation & Usage

Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/Strider1881/Atlan-API-Observability-Dashboard.git
cd Atlan-API-Observability-Dashboard
```


#Open the dashboard:<br>

- Navigate to assets/Atlan-API-Observability-Dashboard.html.<br>

- Open the file in your preferred browser to view the sample dashboard.

#Review documentation:

- Explore docs/observability.pdf for an explanation of the design decisions.

- Refer to ATLAN-Internship-Challenge.pdf for challenge details.

#🖥️ **Key Components**

#**Observability Framework: OpenTelemetry**
The solution uses OpenTelemetry as a framework for collecting metrics, logs, and traces across services. This ensures compatibility with various monitoring tools while providing comprehensive system insights.

**Key Metrics Tracked**

-API Metrics: Response times (p50/p90/p99), request rates, error rates.

-Database Metrics: Query execution time, cache hit/miss ratio.

-System Metrics: CPU/memory usage, disk I/O.

**Logging Strategy**
Logs are categorized into three groups:

-**Logs Kept**: API request details (method, endpoint, response time), database query logs.

-**Logs Removed**: Redundant debug logs or repetitive success messages.

-**Logs Added**: Correlation IDs for tracing requests across services.

**📈 Improvements Achieved**

|   Metric	                       |        Before Solution         |                After Solution   |
|----------------------------------|--------------------------------|---------------------------------|
| Debugging Time	                 |    ~4.5 hours	                |             ~35 minutes         |
| Senior Engineer Involvement	     | 80% of issues	                |           25% of issues         |
| User-reported Problems	         |      90%	                      |                 25%             |

These improvements have significantly reduced debugging time and enhanced team productivity.

#**🌟 Future Enhancements**
-Automate alert thresholds using anomaly detection algorithms.

-Expand monitoring coverage to include mobile app performance.

-Integrate machine learning models for predictive analytics.

#**📄 Deliverables**
**-****Dashboard Implementation**: HTML File

**-Documentation:**

     **-**Explanatory Document

      **-**Challenge Description

**-Dashboard Screenshot:** Sample Dashboard

**🤝 Contributing**
Contributions are welcome! Please fork the repository and submit a pull request with detailed explanations of your changes.

**📧 Contact**
For queries or feedback, please reach out at gsroop2306@gmail.com .


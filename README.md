# 🚀 Production Monitoring Stack on AWS

## 📌 Overview

A production-ready monitoring solution deployed on AWS EC2 using Docker Compose. This project provides real-time monitoring and visualization of Linux server metrics using Prometheus, Grafana, and Node Exporter.

---

## 🏗️ Architecture

```
                AWS EC2 (Amazon Linux 2023)
                        │
                     Docker
                        │
        ┌───────────────┼───────────────┐
        │               │               │
 Prometheus      Node Exporter      Grafana
        │               │
        └────── Scrapes Metrics ───────┘
```

---

## 🚀 Technologies Used

- AWS EC2
- Amazon Linux 2023
- Docker
- Docker Compose
- Prometheus
- Grafana
- Node Exporter
- Git
- GitHub

---

## ✨ Features

- Real-time infrastructure monitoring
- CPU monitoring
- Memory monitoring
- Disk usage monitoring
- Network monitoring
- Docker-based deployment
- Prometheus metrics collection
- Grafana dashboards

---

## 📂 Project Structure

```
production-monitoring-stack
├── docker-compose.yml
├── prometheus
│   └── prometheus.yml
├── grafana
├── screenshots
└── README.md
```

---

## ▶️ Deployment

```bash
git clone https://github.com/satya7705/production-monitoring-stack.git

cd production-monitoring-stack

docker-compose up -d
```

---

## 📊 Monitoring Endpoints

Grafana

```
http://<EC2_PUBLIC_IP>:3000
```

Prometheus

```
http://<EC2_PUBLIC_IP>:9090
```

---

## 👨‍💻 Author

**Venkata Satya Narayana Nunna**

- Site Reliability Engineer
- DevOps Engineer

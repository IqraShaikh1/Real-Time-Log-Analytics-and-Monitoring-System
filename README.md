# Real-Time Log Analysis Platform

## **Project Overview**

This project is a **Real-Time Log Analysis Platform** designed to simulate enterprise-grade log monitoring and analytics. It is optimized for **Windows environments with low-spec machines**, using lightweight technologies while maintaining **core big data concepts**.  

The system generates synthetic application logs, ingests them into **MongoDB** and **HDFS**, processes the logs for analytics, and visualizes them in a **real-time dashboard**.  

---

## **Key Features**

- Continuous log generation simulating multiple services and error levels.  
- Real-time log ingestion into **MongoDB** (hot storage) and **HDFS** (cold storage).  
- Log processing using **Python + Pandas** for analytics.  
- Real-time visualization via **Streamlit dashboard**.  
- Generates JSON-based analytical reports.  
- Supports multi-service, multi-level log analysis including response times, error detection, and service activity.  

---

## **Architecture**
![Project Architecture](./images/diagram.png)

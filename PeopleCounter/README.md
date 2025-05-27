# 👥 People Counter: Edge-Cloud-iOS Computer Vision System

## 📘 Background

This project explores a scalable computer vision system for counting people entering and exiting a space. Designed for edge deployment (Raspberry Pi + iPhone), it integrates real-time detection with cloud-based monitoring and analytics. The goal is to create a lightweight, robust solution that can provide actionable footfall insights for physical spaces like gyms, cafes, or small shops.

It also serves as an end-to-end application of my experience in computer vision, edge computing, and MLOps.

---

## 🏗️ System Architecture

<img src="PeopleCounterSystemArchitecture.png" alt="System Architecture Diagram" width="600"/>

**Overview:**
- **Raspberry Pi** for edge-based people detection
- **MQTT** for lightweight message queuing between devices and backend
- **FastAPI** for serving real-time detection data and device communication
- **Docker** to containerise services for modularity and portability
- **Prometheus + Grafana** to monitor system/application metrics and visualise performance
- **AWS (ECR, ECS, EFS, DynamoDB)** to host scalable backend infrastructure
- **Swift** for delivery via iOS app

---

## 🌍 Real-World Application

This system is aimed at real environments with limited resources and minimal IT overhead. Potential use cases:
- Counting footfall in gyms to track peak times
- Monitoring entrances to manage occupancy limits
- Informing staffing or advertising decisions based on customer flow

---

## 🚧 Status

> 🔨 **In Progress**: Currently finishing the CI/CD pipeline for a single-camera prototype. Multi-camera system planned for the next version.

---

## 🙏 Acknowledgements

Placeholder.


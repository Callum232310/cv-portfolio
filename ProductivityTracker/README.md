
# 🧠 Productivity Tracker: Pose & Activity Monitoring System

## 📘 Background

This project explores an embedded computer vision system for tracking human posture and activity using pose estimation and time series modelling simultaneously. Built for NVIDIA Jetson devices, it aims to infer in C++ for maximum performance and minimal resource usage.

The goal is to prototype a system that can monitor productivity via visual and key/mouse input behaviours, which would be ideal for personal or industrial-scale productivity tracking of people working from home.

It also serves as a deep-dive into C++ CV deployment, real-time deployment, CUDA GPU inference optimisation and embedded constraints.

---

## 🏗️ System Architecture

<img src="ProductivityTrackerSystemArchitecture.png" alt="System Architecture Diagram" width="600"/>

**Overview:**
- **NVIDIA Jetson** for edge-based data collection
- **Pose Estimator** for pose estimation
- **Gaze Estimator** for gaze estimation
- **Time Series Model** for key/mouse log data classification
- **Stream Processor** for aggregating and processing user behaviour
- **PC Agent** for capturing key/mouse logs
- **FastAPI** for serving behaviour data and device communication
- **Docker** for containerising services for modularity and portability
- **Prometheus + Grafana** for monitoring system/application metrics and visualising performance

---

## 🌍 Real-World Application

This system is intended to validate and enhance productivity in a variety of desk-based environments, especially remote work settings. By tracking posture, activity, and input behaviour locally, it can provide actionable insights without intrusive monitoring. Potential applications include:

- Validating WFH/office productivity via behaviour analysis
- Supporting individuals with personal productivity monitoring
- Enhancing ergonomics and awareness in professional environments

---

## 🚧 Status

> 🧪 **Prototyping**: System architecture and project goals defined. C++ CUDA/GPU optimisation research underway.

---

## 🙏 Acknowledgements

Placeholder.

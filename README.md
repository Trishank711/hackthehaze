<p align="center">
  <img src="https://raw.githubusercontent.com/saadeghi/files/main/dark-github-banner.png" width="90%" />
</p>

<h1 align="center">🌫️ HackTheHaze</h1>

<p align="center">
  <b>Delhi Region Ward-Wise AQI Monitoring System</b><br>
  Micro-Level Air Quality Intelligence for Smarter Cities
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success" />
  <img src="https://img.shields.io/badge/Domain-Environmental%20Monitoring-blue" />
  <img src="https://img.shields.io/badge/Data-AQI-orange" />
</p>

---

## 🌍 Project Overview
<img src="https://images.unsplash.com/photo-1603784558471-29d1a15d7b89?auto=format&fit=crop&w=1200&q=80" width="70%" />

**HackTheHaze** is a data-driven air quality monitoring project focused on **ward-wise AQI analysis across Delhi**.  
Instead of relying on city-wide averages, the system captures **localized pollution trends**, enabling better decision-making.

The project is designed with **scalability and analytics-readiness** in mind, making it suitable for:
- Smart city infrastructure
- Health risk assessment
- ML-based pollution prediction

---

## 🎯 Problem Statement
<img src="https://images.unsplash.com/photo-1604537529428-15bcbeecfe4d?auto=format&fit=crop&w=1200&q=80" width="65%" />

- Delhi’s AQI varies significantly across neighborhoods  
- Centralized AQI values hide **local pollution hotspots**
- Citizens and authorities lack **ward-level visibility**

**HackTheHaze addresses this gap** by providing granular AQI insights where they matter most.

---

## ⚙️ Technology Stack
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="42"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" height="42"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" height="42"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" height="42"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" height="42"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" height="42"/>
</p>

**Why this stack?**
- Python + Flask for rapid backend development
- MongoDB for flexible AQI time-series storage
- Web stack for lightweight visualization and dashboards

---

## 🧠 Core Capabilities
<img src="https://images.unsplash.com/photo-1581091012184-5c7cce3d8d0b?auto=format&fit=crop&w=1200&q=80" width="65%" />

- 📍 Ward-wise AQI aggregation
- ⏱️ Near real-time AQI updates
- 🗄️ Historical AQI data archiving
- 📊 Analytics-ready structured datasets
- 🔌 Designed for API & sensor extensibility

---

## 🛰️ System Architecture
<img src="https://images.unsplash.com/photo-1555949963-aa79dcee981c?auto=format&fit=crop&w=1200&q=80" width="65%" />

```text
AQI Sensors / Public APIs
            ↓
Data Collection & Validation
            ↓
MongoDB (Ward-wise Storage)
            ↓
Processing & Aggregation
            ↓
Visualization & Analytics Layer

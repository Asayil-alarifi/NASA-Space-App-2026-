# NASA-Space-App-2026-
# https://aero-shield-sentinel--aldaridari.replit.app/
#<div align="center">

# 🚀 Aero Shield Sentinel

### AI-Powered Early Fire Detection System for Spacecraft

[🌐 Live Demo](https://aero-shield-sentinel--aldaridari.replit.app) · [💻 GitHub](https://github.com/Nourahlafi)

![Status](https://img.shields.io/badge/Status-Early%20Prototype-orange)
![Dashboard](https://img.shields.io/badge/Dashboard-Streamlit-red)
![Data](https://img.shields.io/badge/Data-NASA%20PSI--102-blue)

</div>

Aero Shield Sentinel is an AI-assisted early fire detection and risk prediction prototype designed to improve fire safety inside spacecraft.

The project combines environmental sensors, NASA experimental combustion data, and data analysis to identify early indicators of potential fire risks and support timely intervention before they escalate.

---

## 💡 Project Overview

Fire detection in spacecraft presents unique challenges, especially in microgravity environments, where flames and smoke behave differently than on Earth.

Our solution explores an intelligent monitoring system that aims to:

- Monitor environmental temperature and humidity.
- Analyze combustion-related temperature and particle measurements.
- Identify abnormal environmental patterns.
- Predict potential fire risks using AI-assisted analysis.
- Generate early warnings to support preventive action.

---

## 🛰️ NASA Experimental Data

The project uses experimental datasets associated with NASA's Physical Sciences Informatics (PSI) program.

**Experimental Reference:** `PSI-102`

We prepared and analyzed three datasets:

| Dataset | Records |
|---|---|
| DBP | 602 |
| Silicone | 806 |
| Combined Dataset | 1,408 |

The combined dataset includes a `material` column to distinguish between the two experimental materials.

### Key Parameters

| Parameter | Description |
|---|---|
| `GasPlumeTemperature (DegC)` | Gas plume temperature |
| `DustTrakA (MgPerM3)` | Particle concentration measurements |
| `DustTrakB (MgPerM3)` | Additional particle concentration measurements |
| `PTrak (PtPerCC)` | Particle number concentration |

These measurements help us investigate the relationship between temperature changes and particle behavior during combustion experiments.

---

## 🔧 Hardware Components

The prototype is designed around environmental monitoring components:

- Temperature sensor.
- Humidity sensor.
- Gas sensor.
- Microcontroller for sensor data acquisition.

Physical sensor readings are collected separately from NASA's experimental datasets, which are used for analytical development.

---

## 🧠 AI & Data Analysis

The project explores AI-assisted analysis to identify patterns that may indicate potential fire hazards.

The analysis focuses on:

- Temperature variations.
- Particle concentration patterns.
- Experimental material comparisons.
- Abnormal environmental readings.

Our goal is to develop a predictive model capable of identifying potential fire risks and generating early warnings.

---

## ⚙️ System Workflow

1. **Data Collection:** Collect readings from connected environmental sensors.
2. **Data Processing:** Prepare NASA PSI-102 experimental datasets.
3. **Data Analysis:** Examine temperature and particle patterns.
4. **Risk Assessment:** Identify abnormal readings.
5. **Early Warning:** Display potential risk indicators through the monitoring dashboard.

---

## 📊 Dashboard

The project includes a Streamlit-based dashboard for data visualization and monitoring.

It provides:

- Temperature data visualization.
- Particle measurement analysis.
- Comparison between experimental materials.
- Analytical summaries.
- Risk indicators.

---

## 🎯 Project Objectives

- Improve early fire-risk detection in spacecraft.
- Explore AI-assisted fire prediction.
- Study combustion behavior in microgravity-related research.
- Support timely responses to potential fire incidents.
- Contribute to safer future space missions.

---

## 🚧 Current Development Stage

Aero Shield Sentinel is currently an early-stage prototype.

It combines experimental NASA datasets, environmental monitoring sensors, data analysis, and a dashboard interface.

Further development, model validation, and hardware testing are required before operational deployment.

---

## 🔮 Future Development

- Complete environmental sensor integration.
- Develop and validate a dedicated machine learning model.
- Improve real-time monitoring and alerts.
- Explore automated response mechanisms.
- Conduct additional testing under simulated spacecraft conditions.

---

## 👥 Team OUJ

Developed by Team OUJ, a multidisciplinary student team combining expertise in information technology, business administration, and physics.

### Team Members

| Member | Field |
|---|---|
| Sama Ghanem | Business Administration |
| Asayil Faisal Alarifi | Information Technology |
| [Nourah Lafi Basheer](https://github.com/Nourahlafi) | Information Technology |
| Manar Omar Ali | Information Technology |
| Wejdan Khalil Ghanem | Physics |
| Sumou Aziz Ibrahim Alanazi | Physics |

---

## 🔗 Project Links

- 🌐 [Live Demo – Aero Shield Sentinel](https://aero-shield-sentinel--aldaridari.replit.app)
- 💻 [GitHub – Nourah Lafi](https://github.com/Nourahlafi)

---

## ⚠️ Disclaimer

Aero Shield Sentinel is an independent student prototype inspired by NASA research. It is not an official NASA project and has not been certified for spacecraft operation or emergency fire suppression.

---

<div align="center">

**Team OUJ**

*Detect Early. Respond Smarter. Protect Beyond Earth.*

</div>

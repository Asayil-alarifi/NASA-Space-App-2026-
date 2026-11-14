# NASA-Space-App-2026-
# https://aero-shield-sentinel--aldaridari.replit.app/
#🚀 Aero Shield Sentinel
AI-Powered Early Fire Detection System for Spacecraft
Aero Shield Sentinel is an early-stage AI-assisted fire monitoring and prediction system designed to improve fire safety inside spacecraft.
The project aims to detect early indicators of potential fire incidents by monitoring environmental conditions, analyzing temperature variations, and studying experimental combustion data from NASA. The goal is to identify potential risks and generate early warnings before a fire escalates.
💡 Project Idea
Fire detection inside spacecraft presents unique challenges, particularly in microgravity environments, where flames and smoke behave differently than on Earth.
Aero Shield Sentinel addresses this challenge through a prototype that combines environmental sensors, NASA experimental data, and AI-assisted analysis.
The system focuses on:
Monitoring temperature and humidity.
Analyzing combustion-related temperature and particle measurements.
Identifying abnormal environmental patterns.
Predicting potential fire risks.
Generating early warnings to support timely intervention.
🛰️ NASA Experimental Data – PSI-102
Our project uses experimental datasets associated with NASA's Physical Sciences Informatics (PSI) program.
The PSI-102 experiment serves as the scientific reference for our data analysis.
We prepared three CSV datasets:
Dataset| Number of Records
DBP| 602
Silicone| 806
Combined Dataset| 1,408
The combined dataset includes a "material" column to distinguish between the two experimental materials.
Key Data Parameters
Parameter| Description
"GasPlumeTemperature(DegC)"| Gas plume temperature in Celsius
"DustTrakA(MgPerM3)"| Particle concentration measurements
"DustTrakB(MgPerM3)"| Additional particle concentration measurements
"PTrak(PtPerCC)"| Particle number concentration
These measurements help us study temperature changes and particle behavior associated with combustion experiments.
🔧 Hardware Components
The physical prototype is designed around environmental monitoring components:
Temperature sensor.
Humidity sensor.
Gas sensor.
Microcontroller for collecting sensor readings.
The physical sensors monitor the environment, while NASA experimental datasets are used separately for analytical development.
🧠 AI & Data Analysis
The project explores an AI-assisted approach to identifying potential fire risks.
The analytical process focuses on:
Temperature variations.
Particle concentration patterns.
Differences between DBP and Silicone experimental data.
Abnormal readings that may indicate emerging risks.
The ultimate objective is to develop a predictive model that can identify potential fire hazards and provide early warnings.
⚙️ System Workflow
Data Collection: Collect environmental readings from connected sensors.
Data Processing: Prepare and analyze NASA PSI-102 experimental datasets.
Data Analysis: Examine temperature and particle patterns.
Risk Assessment: Identify abnormal readings and potential warning conditions.
Alert Generation: Present risk indicators through the monitoring interface.
📊 Monitoring Dashboard
The project includes a Streamlit-based dashboard designed to visualize experimental data and monitoring results.
Key features include:
Temperature visualization.
Particle measurement analysis.
Comparison between experimental materials.
Data-driven risk indicators.
Analytical summaries.
🎯 Project Objectives
Improve early fire-risk detection in spacecraft.
Explore AI-assisted fire prediction.
Study combustion-related temperature and particle behavior.
Support timely responses to potential fire incidents.
Contribute to safer future space missions.
🚧 Current Development Stage
Aero Shield Sentinel is currently an early-stage prototype.
The project combines NASA experimental datasets, environmental sensor integration, data analysis, and a monitoring dashboard.
Further development, model validation, and hardware testing are required before the system can be considered an operational spacecraft fire-safety solution.
🔮 Future Development
Complete integration of all environmental sensors.

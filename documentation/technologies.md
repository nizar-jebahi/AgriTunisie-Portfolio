# AgriTunisie — Technologies and Technical Stack

## Overview

AgriTunisie is built using a combination of web development frameworks, backend technologies, Artificial Intelligence models, and IoT hardware.

The selected technologies support the development of an integrated platform for agricultural monitoring and intelligent decision support.

## 1. Frontend Development

| Technology | Technical Role |
|---|---|
| Angular | Component-based frontend development and application structure |
| Ionic | Cross-platform user interface and mobile-oriented experience |

The frontend provides the user-facing interface through which agricultural information and platform functionalities are accessed.

## 2. Backend Development

| Technology | Technical Role |
|---|---|
| Python | Backend and AI development |
| FastAPI | REST API development and communication between system components |

The backend handles application requests and provides the communication layer between the frontend, AI components, and connected devices.

## 3. Artificial Intelligence and Machine Learning

| Technology | Technical Role |
|---|---|
| YOLOv8 | Plant disease detection from images |
| EfficientNetB0 | Plant disease image classification |
| XGBoost | Irrigation-related prediction |
| RAG | Retrieval-based agricultural question answering |

These technologies provide the intelligent analysis capabilities of the platform.

## 4. Internet of Things (IoT)

| Component | Technical Role |
|---|---|
| Raspberry Pi 4B | Main IoT device for sensor data acquisition |
| DHT11 | Temperature and air humidity measurement |
| BH1750 | Light intensity measurement |
| Capacitive Soil Moisture Sensor | Soil moisture measurement |
| MCP3008 | Analog-to-digital conversion for the soil moisture sensor |

The IoT subsystem collects environmental and soil measurements and transmits the collected data to the backend through Wi-Fi.

## 5. Database

**MongoDB**

MongoDB is used as the database technology for storing application data.

## 6. System Communication

The platform combines several communication paths:

- The Angular/Ionic frontend communicates with the FastAPI backend through HTTP requests.
- The Raspberry Pi sends sensor measurements to the backend through Wi-Fi using HTTP POST requests.
- The backend connects application services with the AI components and database.

## 7. Technical Architecture

The overall technology stack follows a modular architecture in which frontend development, backend services, AI processing, IoT data acquisition, and data storage work together.

---

*This document describes the technologies used in the AgriTunisie project. It is intended for technical presentation and documentation; implementation source code and private project assets are not included in this repository.*

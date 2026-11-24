# AgriTunisie — Artificial Intelligence Components

## Overview

AgriTunisie integrates several Artificial Intelligence approaches to support agricultural monitoring, plant disease identification, and intelligent irrigation decision-making.

The AI layer combines computer vision, machine learning, and Retrieval-Augmented Generation (RAG) to provide data-driven agricultural assistance.

## 1. Computer Vision — Plant Disease Detection

**Model:** YOLOv8

YOLOv8 is integrated into the platform for image-based plant disease detection. It processes images of plant leaves to identify and localize potential disease symptoms.

**Primary objective:**
- Detect visible disease symptoms in plant images.
- Support early identification of potential plant health issues.
- Provide visual analysis as part of the agricultural monitoring workflow.

## 2. Deep Learning — Plant Disease Classification

**Model:** EfficientNetB0

EfficientNetB0 is used as a deep learning image-classification model to analyze plant images and identify disease categories.

**Primary objective:**
- Extract relevant visual features from plant images.
- Classify images into the model's supported disease categories.
- Complement the platform's computer vision capabilities.

## 3. Predictive Machine Learning — Intelligent Irrigation

**Model:** XGBoost

XGBoost is applied to irrigation-related prediction using environmental and soil measurements.

**Input features:**
- Soil moisture
- Temperature
- Air humidity

**Primary objective:**
- Analyze environmental conditions.
- Generate irrigation-related predictions.
- Support more informed water-management decisions.

## 4. Retrieval-Augmented Generation — Agricultural Assistant

**Approach:** Retrieval-Augmented Generation (RAG)

AgriTunisie incorporates a RAG-based conversational assistant designed to provide users with contextually relevant agricultural information.

The approach combines information retrieval with language generation to produce responses grounded in the available agricultural knowledge base.

**Primary objective:**
- Retrieve relevant agricultural information.
- Answer user questions through a conversational interface.
- Make agricultural knowledge more accessible to farmers.

## AI Architecture and Integration

The AI components contribute to different functions within the AgriTunisie ecosystem:

| Component | Technology | Application |
|---|---|---|
| Disease detection | YOLOv8 | Computer vision |
| Disease classification | EfficientNetB0 | Deep learning |
| Irrigation prediction | XGBoost | Predictive machine learning |
| Agricultural assistant | RAG | Knowledge retrieval and generation |

These components are integrated into the broader platform alongside the backend services, frontend application, and IoT monitoring system.

## Project Scope

The AI layer is designed to support the broader objectives of AgriTunisie:

- Improving access to plant health information.
- Supporting data-driven irrigation decisions.
- Connecting agricultural data with intelligent software solutions.
- Contributing to more informed and efficient agricultural practices.

---

**Development note:** This repository is a public project presentation. Source code, trained model weights, private datasets, and internal implementation details are intentionally excluded.

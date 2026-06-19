# Rollball Video Analytics Research Results

## Overview

This repository presents the results and outputs of my research work on AI-powered video analytics for Rollball.

The project focuses on applying Computer Vision, Pose Estimation, and Sports Analytics techniques to analyze player actions, classify shot outcomes, and generate performance metrics from Rollball video data.

This work resulted in the research paper:

**"AI-Powered Video Analytics Framework for Rollball Goal Detection and Tournament Automation"**

Accepted and presented at **IEEE IC2PCT 2026**.

---

## Research Objectives

* Establish a foundation for analytics-driven development of Rollball.
* Create a custom annotated dataset for Rollball video analysis.
* Detect and classify shot outcomes including Goal, Save, and Miss.
* Develop Rollball-specific performance metrics.
* Explore the use of Computer Vision for player performance evaluation.

---

## Methodology

The analytical pipeline combines:

* YOLOv8 Object Detection
* MediaPipe Pose Estimation
* Ball Trajectory Analysis
* Outcome Classification
* Performance Metric Generation

Pipeline:

Video Input

↓

Object Detection

↓

Player Tracking

↓

Pose Estimation

↓

Trajectory Analysis

↓

Outcome Classification

↓

Metric Computation

---

## Proposed Performance Metrics

### Goal Detection Accuracy (GDA)

Measures shot outcome detection accuracy.

### Save Reaction Index (SRI)

Measures goalkeeper reaction capability.

### Motion Smoothness Index (MSI)

Measures movement fluidity and control.

### Trajectory Deviation Score (TDS)

Measures shot trajectory consistency and accuracy.

---

## Sample Results

Example analytical output:

* Goal Detection Accuracy (GDA): 1.00
* Save Reaction Index (SRI): 0.7356
* Motion Smoothness Index (Shooter): 0.4558
* Motion Smoothness Index (Goalkeeper): 0.4235
* Trajectory Deviation Score (TDS): 0.0612
* Outcome Classification: Save

---

## Technology Stack

* Python
* YOLOv8
* OpenCV
* MediaPipe
* PyTorch
* NumPy
* Matplotlib

---

## Repository Contents

This repository contains:

* Research outputs
* Experimental results
* Screenshots
* Performance metrics
* Architecture diagrams
* Demonstration materials

---

## Note

This repository is intended to showcase research outcomes and experimental results.

Source code is not publicly available due to project ownership and collaboration requirements.

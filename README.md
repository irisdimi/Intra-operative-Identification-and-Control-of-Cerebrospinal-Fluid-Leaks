# Intra-operative Identification and Control of Cerebrospinal Fluid Leaks

This repository contains the final major project report for ENGF1112 Group 27.

## Project Overview

This project proposes a compact robotic surgical assistant for the intra-operative identification and control of cerebrospinal fluid (CSF) leaks. The system combines real-time sensing, machine learning, probabilistic modelling, and robotic intervention to improve detection and treatment of CSF leaks during high-risk neurosurgical and spinal procedures.

## Problem

Cerebrospinal fluid leaks can occur during procedures such as spinal fusions, craniotomies, laminectomies, and skull-base surgeries. If missed during surgery, CSF leaks can lead to complications including infection, meningitis, intracranial hypotension, revision surgery, longer hospital stays, and higher healthcare costs.

## Proposed System

The proposed robotic assistant uses a multi-sensor detection system, including:

- Near-infrared spectroscopy
- Shortwave infrared imaging
- Fluorescent dye tracking
- Endoscopic visual recognition
- Capacitive and impedance moisture sensors
- ECG monitoring
- Blood pressure monitoring
- Transcranial Doppler ultrasound
- Temperature monitoring

The system analyses sensor data in real time and alerts the surgeon when a possible CSF leak is detected.

## Intervention Methods

Depending on the type of leak, the robot may support:

- Medical glue delivery
- Epidural blood patching
- Catheter-delivered liquid embolic agents
- Surgeon-approved robotic actuation

All robotic intervention requires surgeon approval.

## System Modelling

The project includes:

- Probabilistic modelling of CSF leak type and location
- Patient-specific risk mapping
- Real-time anomaly detection
- Closed-loop PID control modelling for cranial arterial velocity
- Human-in-the-loop robotic control architecture

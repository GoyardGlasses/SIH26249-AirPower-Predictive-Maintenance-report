# SIH 2026 — Air Power: Predictive Maintenance & Fleet Availability

## Problem Statement

**SIH26249 — Air Power: Predictive Maintenance & Fleet Availability**

Aircraft availability is affected not only by component failures, but also by
spare availability, maintenance manpower, facility capacity, maintenance
windows, operational demand and other sustainment constraints.

This repository documents the research, analysis and proposed technical
solution developed for the Smart India Hackathon 2026 problem statement.

---

## Core Thesis

> **DO NOT OPTIMIZE FAILURE PROBABILITY.  
> OPTIMIZE FLEET AVAILABILITY.**

The proposed solution acts as an intelligence and decision-support layer
above existing aircraft health, maintenance, logistics and operational systems.

---

## Research Scope

The research covers:

- Aircraft health monitoring
- Predictive maintenance
- Remaining Useful Life (RUL)
- Aircraft maintenance processes
- High-tempo / wartime maintenance
- Spare-part availability
- Maintenance manpower
- Maintenance facilities
- Aircraft utilisation
- Fleet availability
- AI/ML for predictive maintenance
- Maintenance optimization
- Digital twins
- Data integration
- Security and military constraints
- Validation and evaluation

---

## International Benchmarking

The research compares maintenance and sustainment approaches across:

- 🇮🇳 India
- 🇺🇸 United States Air Force
- 🇫🇷 French Air & Space Force
- 🇩🇪 German Air Force / Bundeswehr

---

## Research Framework

A structured **315-question research framework** was used to investigate:

1. Understanding the actual problem
2. High-tempo / wartime operations
3. Existing aircraft-health systems
4. Aircraft data
5. Maintenance records
6. Maintenance hierarchy
7. Predictive maintenance
8. Remaining Useful Life
9. Spares
10. Maintenance manpower
11. Maintenance facilities
12. Aircraft utilisation
13. Fleet availability
14. Decision-making
15. Integration
16. Security / military constraints
17. IoT / hardware
18. Digital twin
19. Validation
20. The biggest questions for the actual SIH solution

---

## Proposed Solution

### AI-Powered Fleet Maintenance Intelligence

The proposed platform combines:

**Aircraft Health + Flight/Usage + Maintenance History + Spares + Manpower + Facilities + Operational Demand**

to:

**Detect → Predict → Understand → Assess → Optimize → Simulate → Act → Learn**

---

## Key Intelligence Capabilities

### 1. Fleet Availability Intelligence
Predicts the operational impact of aircraft/component degradation.

### 2. Resource-Aware Maintenance Optimization
Considers:

- Spare availability
- Technician skills
- Facility capacity
- Tooling
- Lead time
- Maintenance windows
- Operational demand

### 3. Degradation Fingerprint Learning
Identifies patterns of degradation before conventional thresholds are reached.

### 4. Failure Propagation Intelligence
Models how component degradation can create secondary maintenance consequences.

### 5. Cross-Aircraft Transfer Learning
Uses relevant patterns from similar aircraft/components when local failure history is limited.

### 6. What-If Availability Simulation
Compares alternative maintenance actions before execution.

---

## Technical Architecture

### Data Layer

- PostgreSQL
- InfluxDB
- Apache Kafka

### AI / ML

- Python
- LSTM
- XGBoost / LightGBM
- RUL prediction
- Anomaly detection
- Failure-risk prediction

### Optimization

- OR-Tools
- Constraint-aware maintenance optimization

### Decision Layer

- FastAPI
- Node.js
- JEV / LAYA

### Frontend

- React
- TypeScript
- Tailwind CSS

### Deployment

- Docker
- Nginx
- Controlled on-premise / secure deployment

---

## Core Decision Example

The system should answer:

> **Aircraft A is predicted to experience degradation. What should we do to keep the maximum number of aircraft available?**

Instead of simply generating a failure alert, the system evaluates:

- Failure risk
- RUL and uncertainty
- Mission priority
- Spare availability
- Spare location
- Time-to-usable-part
- Technician availability
- Facility capacity
- Maintenance window
- Fleet impact

It then compares feasible maintenance actions and recommends the option that maximizes expected fleet availability.

---

## Research Report

📄 [Full Research Report](Research/SIH26249_AirPower_Full_Research_Report.pdf)

📝 [Editable Research Report](Research/SIH26249_AirPower_Full_Research_Report.docx)

---

## Team

**Team:** TESTERS  
**Team ID:** 184916  
**Hackathon:** Smart India Hackathon 2026  
**Problem Statement:** SIH26249

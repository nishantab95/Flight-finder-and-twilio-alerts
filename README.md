# 🚀 Flight Finder & Real-Time Price Alert System

## 📌 Project Summary

A **production-style API integration system** built using Python that monitors flight prices in real time and triggers automated alerts when prices drop below predefined thresholds.

This project demonstrates **end-to-end system integration**, including external APIs, data processing pipelines, and event-driven notification systems — aligning with real-world fintech and backend integration roles.

---

## 🎯 Key Highlights (ATS Optimized)

* ✔️ REST API Integration (Amadeus Flight API)
* ✔️ JSON Data Processing & Transformation
* ✔️ Multi-System Integration (Twilio + Google Sheets)
* ✔️ Automated Notification System
* ✔️ Error Handling & Debugging Logic
* ✔️ Modular Python Architecture
* ✔️ Real-World Backend Workflow Simulation

---

## 🧠 Problem Statement

Tracking flight prices manually is inefficient and unreliable. Users often miss the best deals due to lack of automation.

---

## 💡 Solution

Designed an automated system that:

* Fetches live flight data via API
* Processes and analyzes pricing
* Compares against user-defined thresholds
* Sends real-time alerts via SMS

---

## 🏗️ System Architecture

```
Amadeus API → JSON Response → Python Processing Layer → Price Evaluation
                                      ↓
                              Google Sheets (Data Storage)
                                      ↓
                               Twilio API (SMS Alerts)
```

---

## ⚙️ Tech Stack

| Category    | Technologies                        |
| ----------- | ----------------------------------- |
| Language    | Python                              |
| APIs        | REST APIs (Amadeus, Twilio, Sheety) |
| Data Format | JSON                                |
| Tools       | Postman (API Testing)               |
| Storage     | Google Sheets (via Sheety API)      |

---

## 🔄 Workflow Explanation

1. Fetch flight data using Amadeus API
2. Receive structured JSON response
3. Extract and clean relevant fields
4. Compare prices against predefined thresholds
5. Store/update flight data in Google Sheets
6. Trigger SMS alerts using Twilio API

---

## ⚡ Features

* 🔹 Multi-API Integration Pipeline
* 🔹 Real-Time Price Monitoring
* 🔹 Automated SMS Notification System
* 🔹 Data Persistence via Google Sheets
* 🔹 Clean & Modular Code Structure

---

## 🧪 Error Handling & Debugging

* Implemented response validation before processing
* Handled API failures using status code checks
* Managed missing or inconsistent data safely
* Added debugging steps to trace API and data flow issues

---

## 📈 Real-World Relevance

This project simulates real-world systems used in:

* Fintech API integrations
* Payment and notification systems
* Backend automation pipelines
* Data exchange between distributed systems

---

## 🚀 Future Enhancements

* Add retry mechanism for failed API calls
* Implement logging system for production debugging
* Build dashboard for flight tracking visualization
* Extend support for multiple users and routes

---

## 💼 Recruiter Note

This project demonstrates strong foundational skills in:

* API integrations
* System design thinking
* Debugging and problem-solving
* Backend data workflows

---

## 📌 Author

**Nishant Bilagi**
Aspiring Backend / API Integration Engineer | Transitioning into AI/ML

---

## ⭐ Final Note

This project reflects my focus on building **real-world, scalable systems** by integrating multiple services and ensuring smooth data flow — a critical requirement in modern backend and fintech applications.

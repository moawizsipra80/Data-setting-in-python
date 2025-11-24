# Data Setting in Python
# Lahore Smart City - Traffic & Safety Analytics Assignment

**Assignment Date:** November 24, 2025  
**Student Level:** Beginner

---

## 📝 Assignment Overview

In this assignment, we analyze raw traffic logs from Lahore Smart City using Python code.  
Each step includes easy-to-understand code and clear explanations so that even beginners can follow and understand the solutions.

---

## 📦 Data Sample

*(Insert the sample dataset code here)*

---

## 🚦 Core Questions & Solutions

### Q1: Data Parsing

Each log string was split into fields (zone, speed, vehicle, etc.) and converted into a dictionary.  
This made further analysis much easier, as each log was stored as a structured record.

---

### Q2: Average Speed per Zone

Calculated the average speed for each zone by grouping speeds and dividing by the number of vehicles in each zone.

---

### Q3: Peak Hour

Extracted the hour from each log's `time` field and counted occurrences to determine which hour had the most traffic entries.

---

### Q4: Vehicles with Speed > 80

Identified and listed all vehicles with a speed greater than 80.

---

### Q5: Violations Count

Collected all the violations into a list and used a dictionary (or Python's `Counter`) to calculate how often each violation type occurred.

---

### Q6: Safety Index per Zone

- Each zone starts with 100 points.
- For each helmet violation: subtract 10 points.
- For each overspeed violation: subtract 20 points.
- For each congested status: subtract 10 points.
- Safety Categories:  
  - 80+ points: "Safe"  
  - 50–79: "Moderate"  
  - Below 50: "Risky"

---

### Q7: Vehicle Category Summary

Summarized each vehicle type (Car, Bike, Bus, Truck) with:
- Count (number of logs)
- Average speed
- Total violations

---

### Q8: High-Congestion Zones

Marked zones as high-congestion if they had at least one log with `status == "Congested"`.

---

### Q9: Time Window Classification

Mapped the `time` (hours) from each log into time windows:
- "Morning"
- "Afternoon"
- "Evening"
- "Night"

---

### Q10: Final Zone-Level Report

For each zone, a summary report was printed:
- Number of vehicles
- Average speed
- Total violations
- Most common vehicle type
- Safety category

---

## ✍️ Author

- **Student Name:** Muhammad Moawiz Sipra  
- **Submission Date:** November 24, 2025

---

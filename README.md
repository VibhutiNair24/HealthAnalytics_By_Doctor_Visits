# 🏥 Healthcare Analytics — Doctor Visits Analysis

An end-to-end data analytics project exploring socio-demographic, economic, and health-related drivers of doctor visits using patient health survey data.

---

## 📌 Project Overview
Healthcare utilization patterns are critical for resource allocation and policy design. This project analyzes a dataset of **1,849 patient records** across 13 attributes to identify what factors drive patients to consult a doctor.

### Key Objectives
1. Perform statistical profiling on patient health utilization.
2. Uncover non-linear relationships between socio-demographic factors and healthcare access.
3. Identify top feature differentiators between visitors (1+ visits) and non-visitors (0 visits).

---

## 🛠️ Tech Stack
* **Language:** Python 3.9
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Tools:** Jupyter Notebook, Git, GitHub

---

## 📊 Key Findings
* **Zero-Inflation:** Over 55% of patients reported 0 doctor visits in the 2-week period, indicating a strong right-skewed count distribution.
* **Top Predictors:** `illness` (number of recent illnesses) and `reduced` (days of reduced activity) are the strongest individual predictors of doctor visits.
* **Age & Gender Trajectory:** Females exhibit higher mean visit rates during reproductive/mid-life years (ages 32–52), whereas male visit rates increase in senior cohorts (62–72).
* **Policy Impact:** Patients receiving low-income free government insurance (`freepoor`) showed higher utilization rates, demonstrating the efficacy of safety-net coverage.

---

## 📁 Repository Structure

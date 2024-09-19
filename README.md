# Healthcare Appointment No-Show Analysis

## Table of Contents
- [Overview](#overview)
- [Dataset Information](#dataset-information)
- [Objective](#objective)
- [Key Findings](#key-findings)
- [Project Structure](#project-structure)
- [Steps to Run the Project](#steps-to-run-the-project)
  - [1. Install Dependencies](#1-install-dependencies)
  - [2. Running the Analysis](#2-running-the-analysis)
  - [3. Dataset Cleaning](#3-dataset-cleaning)
  - [4. Visualizations](#4-visualizations)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)

---

## Overview
This project performs exploratory data analysis (EDA) on a healthcare dataset that records patient appointment attendance (no-shows) along with demographic and health-related factors. The analysis aims to uncover patterns that can help reduce missed appointments and improve healthcare efficiency.

---

## Dataset Information
The dataset contains information on patient appointments, demographic details, and medical history. Key columns in the dataset include:

- **PatientId**: Unique identifier for each patient.
- **AppointmentID**: Unique identifier for each appointment.
- **Gender**: Patient's gender.
- **ScheduledDay**: Date and time when the appointment was scheduled.
- **AppointmentDay**: Date of the actual appointment.
- **Age**: Patient's age.
- **Neighbourhood**: Area of residence.
- **Scholarship**: Indicates if the patient is enrolled in a welfare program.
- **Hipertension**, **Diabetes**, **Alcoholism**, **Handcap**: Medical conditions.
- **SMS_received**: Indicates if the patient received an SMS reminder.
- **No-show**: Whether the patient missed the appointment ("Yes" = No-show, "No" = Attended).

---

## Objective
The primary goal of this project is to:
1. Analyze the factors that contribute to patients missing their scheduled appointments.
2. Explore the influence of demographic, medical, and notification (SMS) data on no-show rates.
3. Generate actionable insights that can help reduce no-show rates in healthcare systems.

---

## Key Findings

### 1. **Neighbourhood Effect**:
   - Patients from certain neighborhoods show varying no-show rates, with some areas consistently having higher rates.

### 2. **Day of the Week**:
   - Appointments scheduled later in the week (especially Fridays) tend to have higher no-show rates.

### 3. **Age Group Patterns**:
   - Younger patients (0-20 years old) are more likely to miss their appointments, whereas older age groups (50-70 years old) show lower no-show rates.

### 4. **Time Gap between Scheduling and Appointment**:
   - A longer time gap between scheduling and the actual appointment date leads to a higher chance of missing the appointment.

### 5. **Financial Aid (Scholarship)**:
   - Patients enrolled in the financial aid program tend to miss more appointments, suggesting potential socioeconomic barriers.

### 6. **Health Conditions**:
   - Patients with chronic conditions such as hypertension and diabetes have lower no-show rates, whereas patients with alcoholism and disabilities tend to miss more appointments.

### 7. **Impact of SMS Notifications**:
   - SMS reminders help reduce no-show rates, but many patients still miss appointments even after receiving a reminder.

---



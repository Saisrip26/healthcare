# Healthcare Appointment No-Show Analysis

## Table of Contents
- [Overview](#overview)
- [Dataset Information](#dataset-information)
- [Objective](#objective)
- [Key Findings](#key-findings)
- [Business Insights Summary](#business-insights-summary)

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

## Business Insights Summary

### 1. **Neighbourhood Influence**:
   - Certain neighborhoods have significantly higher appointment volumes. For example, patients from some neighborhoods (like "JARDIM CAMBURI") tend to have higher attendance, while others experience more no-shows. Targeting specific areas for follow-up reminders or personalized communication could reduce no-show rates.

### 2. **Day of the Week**:
   - No-shows tend to be more common towards the end of the week (especially Fridays). Hospitals might consider adjusting scheduling practices, such as offering flexible time slots or sending reminders earlier in the week.

### 3. **Scheduling and Appointment Time Gap**:
   - The larger the time gap between scheduling and the appointment, the more likely a patient is to miss the appointment. Scheduling closer to the appointment date or implementing follow-up systems for long-gap appointments could help mitigate this.

### 4. **Age Group**:
   - Younger patients (ages 0-10 and 11-20) are more likely to miss their appointments compared to older groups. Appointment policies for younger patients (such as rescheduling flexibility or frequent reminders) could help reduce no-shows.

### 5. **Scholarship (Financial Aid)**:
   - Patients who receive financial aid (under a scholarship) tend to miss more appointments. Offering additional support, like transportation assistance or better access to scheduling options, could benefit these patients.

### 6. **Health Condition Impact**:
   - **Hypertension and Diabetes**: Patients with these conditions tend to have lower no-show rates, likely due to the need for regular monitoring.
   - **Alcoholism and Handicap**: These conditions show a slightly higher no-show rate, indicating that additional support may be necessary for these groups.

### 7. **SMS Notifications**:
   - SMS reminders appear to have some effect on reducing no-shows, but a significant number of patients still miss appointments even after receiving reminders. Combining SMS with other strategies (like phone calls or automated rescheduling systems) could yield better results.

### 8. **Correlation Insights**:
   - The correlation heatmap shows low correlations between most health conditions and no-show rates, meaning that no single health factor has a dominating impact. However, there is a slight positive correlation between receiving an SMS and reduced no-shows.




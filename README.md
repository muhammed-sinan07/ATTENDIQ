# AttendIQ – Smart Attendance & Risk Predictor

AttendIQ is a smart student attendance dashboard.

It helps students track attendance, predict academic risk, and make informed decisions before falling below the minimum attendance requirement.

## Problem Statement

Many colleges require students to maintain a minimum attendance percentage (typically 75%) to be eligible for exams.

Students often miscalculate attendance and realize too late that they are below the required threshold.

AttendIQ solves this by acting as a smart attendance advisor.

---

## Features

### Core Features
- Add multiple subjects
- Track attendance percentage per subject
- Automatic risk classification:
  - 🟢 Safe
  - 🟡 At Risk
  - 🔴 Critical
- Calculate classes needed to recover attendance
- Predict how many classes can be safely skipped
- Overall attendance health dashboard
- Real-time alerts for critical subjects

### Advanced Features
- Circular / semester minimum attendance mode
- Custom attendance threshold support
- Duty leave prediction assistance
- Impossible attendance detection
- Export downloadable attendance report
- Interactive dashboard analytics
- Local browser storage persistence

---

## Tech Stack

Frontend:
- HTML5
- CSS3
- Vanilla JavaScript

Storage:
- Browser LocalStorage

Deployment:
- Vercel 
---

## Project Structure

```bash
AttendIQ/
│
├── index.html
└── README.m

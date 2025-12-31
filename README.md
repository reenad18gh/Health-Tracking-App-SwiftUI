# Health Tracking App – SwiftUI Prototype

A SwiftUI-based health tracking mobile application prototype focused on clean architecture, accessibility, and scalable user flows.

This project demonstrates how UI design, product thinking, and SwiftUI implementation come together to form a clear and maintainable iOS application.

---

## Project Overview

This app is designed to support daily health tracking through a simple and structured experience.  
The concept targets a broad audience, including patients with chronic conditions, elderly users, and individuals interested in everyday health monitoring.

The primary goal of this project is to showcase:
- State-driven SwiftUI architecture
- Reusable UI components
- Accessibility-first design decisions
- Clear, real-world user journeys
- Clean and maintainable project structure

---

## Interactive Presentation

The full product vision, problem definition, user flows, and design decisions are explained in the presentation below:

👉 **View the full presentation**  
https://www.canva.com/design/DAG8Z4-Vcuw/FIEXcm2TUjw4n_uATYCWbg/view

The presentation covers:
- Problem statement
- Target users and personas
- User journey and app flow
- Core features and MVP scope
- Design direction and accessibility considerations
- Development timeline
- Future enhancements

---

## App Overview & Screens

A visual overview of the application UI and all major screens is available here:

👉 **View app screens overview**  
https://www.canva.com/design/DAG8gAkLFsc/fm0fPj7o733K3dl8ekz5ag/view

This overview includes:
- Authentication screens (Login, Sign Up, Forgot Password)
- Medical history input
- Symptom logging flow
- Daily reminder setup
- Health reports and timeline selection

---

## Key Technical Highlights

### State-Driven UI
- Centralized state management for reports and timelines
- Predictable UI updates driven by state changes
- Clear separation between UI and state logic

### Reusable Components
- Shared headers, cards, buttons, typography, and progress indicators
- Consistent design system applied across all screens
- Improved maintainability and scalability

### NavigationStack Architecture
- Linear and scalable user flow
- Clear navigation hierarchy
- Easy to extend with additional screens

### Accessibility-Focused Design
- Large, readable typography
- High-contrast dark mode
- Clear visual hierarchy
- Minimal cognitive load for non-technical users

---

## Features Implemented

- Authentication flow
  - Login
  - Sign Up
  - Forgot Password
- Medical history management
- Daily symptom logging with severity levels
- Daily reminder configuration
- Health reports with dynamic timelines
- Report settings with live state updates
- Dark mode UI with green accent theme

---

## User Flow

Login  
→ Sign Up  
→ Medical History  
→ Symptom Logging  
→ Daily Reminder  
→ Health Report  
→ Report Settings

Each step is designed to be simple, focused, and easy to follow.

---

## Tech Stack

- SwiftUI
- iOS 17+
- Xcode
- NavigationStack
- MVVM-style state management
- Custom design system

---

## Project Structure

Health-Tracking-App-SwiftUI/
│
├── App/
│ └── HealthApp/
│ ├── Health_AppApp.swift
│ ├── AppState.swift
│ ├── UIComponents.swift
│ ├── LoginView.swift
│ ├── ForgotPasswordView.swift
│ ├── ContentView.swift
│ ├── MedicalHistoryView.swift
│ ├── SymptomLoggingView.swift
│ ├── DailyReminderView.swift
│ ├── HealthReportView.swift
│ └── ReportSettingsView.swift
│
├── README.md
└── LICENSE

---

## Project Status

This project is a UI and functional prototype.  
No backend services or authentication providers are integrated.

---

## Author

Rinad Mohammed Alghamdi  
UI Concept & iOS Development  
© 2025

---

## Notice

This repository is shared for portfolio and educational purposes only.  
Design and source code are not licensed for commercial use without prior permission.

# RandWise

A modern Android budgeting and expense management application built with Kotlin, MVVM Architecture, Room Database, Navigation Components, ViewBinding, and Material Design 3.

RandWise helps users track expenses, manage budgets, monitor savings goals, analyze spending habits, and build healthier financial behaviours through powerful analytics and achievement-based motivation. The application is designed with a premium fintech-inspired user experience and operates completely offline, ensuring users retain full ownership of their financial data.

---

## Features

### Authentication & User Management

* User Registration
* Secure Login
* Logout Functionality
* Remember Me Support
* Session Persistence
* Multi-User Support
* User-Specific Financial Records
* Input Validation

### Dashboard

* Personalized Welcome Card
* Budget Overview
* Budget Remaining Indicator
* Monthly Spending Summary
* Recent Expenses Feed
* Budget Health Score
* Quick Actions
* Analytics Preview

### Expense Management

* Add Expenses
* Edit Expenses
* Delete Expenses
* Receipt Attachments
* Receipt Preview
* Date & Time Selection
* Category Assignment
* Expense Notes
* Transaction History
* Input Validation

### Category Management

* Create Categories
* Edit Categories
* Delete Categories
* Custom Category Colors
* Category Icons
* Category Spending Limits
* Category Statistics

### Goals & Savings Tracking

* Monthly Budget Goals
* Savings Goals
* Category Spending Targets
* Progress Tracking
* Goal Completion Monitoring
* Budget Health Evaluation

### Analytics & Insights

* Pie Charts
* Bar Charts
* Line Charts
* Spending Distribution Analysis
* Monthly Spending Trends
* Category Trend Analysis
* Budget Performance Tracking
* Financial Insights
* Empty-State Analytics Handling

### Achievement System

* First Expense
* 7-Day Streak
* 30-Day Streak
* 100 Expenses
* Receipt Collector
* Budget Master
* Savings Star
* Category Champion
* Achievement Progress Tracking
* Unlock History

### Settings

* Profile Management
* Theme Preferences
* Data Export
* Data Reset
* Application Information

---

## Highlights

* Offline-First Design
* Multi-User Support
* Budget Health Score
* Receipt Management
* Advanced Financial Analytics
* Achievement & Gamification System
* Category Spending Limits
* Savings Goal Tracking
* Local Data Ownership
* Premium Fintech User Experience
* Safe Empty-State Handling
* Modern Android Development Practices

---

## Technology Stack

### Language

* Kotlin

### UI

* XML Layouts
* ViewBinding
* Material Design 3

### Architecture

* MVVM (Model-View-ViewModel)
* Repository Pattern
* LiveData

### Navigation

* Navigation Component
* Safe Args

### Database

* Room Database
* DAO Pattern
* Type Converters

### Charts

* MPAndroidChart

### Testing

* Unit Testing
* UI Testing
* Database Testing
* Repository Testing
* Navigation Testing

---

## Architecture

RandWise follows the MVVM architectural pattern to ensure maintainability, scalability, and separation of concerns.

```text
UI (Activities / Fragments)
            │
            ▼
       ViewModels
            │
            ▼
      Repositories
            │
            ▼
      Room Database
            │
     DAOs & Entities
```

### Core Layers

#### Presentation Layer

Responsible for:

* User Interface
* Navigation
* User Interaction

#### Business Logic Layer

Responsible for:

* ViewModels
* State Management
* Validation
* Data Processing

#### Data Layer

Responsible for:

* Repositories
* Room Database
* DAOs
* Local Persistence

---

## Database Structure

The application stores data locally using Room Database.

### Entities

| Entity        | Purpose                            |
| ------------- | ---------------------------------- |
| User          | Stores account information         |
| Expense       | Stores expense transactions        |
| Category      | Stores spending categories         |
| BudgetGoal    | Stores savings and budgeting goals |
| CategoryLimit | Stores category spending limits    |
| Achievement   | Stores achievement progress        |
| UserSession   | Stores login session information   |
| Settings      | Stores user preferences            |

---

## Project Structure

```text
com.randwise.app

├── data
│   ├── model
│   ├── dao
│   └── database
│
├── repository
│
├── viewmodel
│
├── ui
│   ├── auth
│   ├── dashboard
│   ├── expenses
│   ├── analytics
│   ├── categories
│   ├── goals
│   ├── achievements
│   └── settings
│
├── navigation
│
└── utils
```

---

## Offline Functionality

RandWise is designed to function entirely without internet access.

All core features are available offline, including:

* Authentication
* Expense Tracking
* Receipt Storage
* Budget Management
* Goal Tracking
* Analytics
* Achievements
* Category Management
* Settings

All information is stored locally on the user's device using Room Database.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/RandWise.git
```

### Open the Project

1. Open Android Studio
2. Select **Open Existing Project**
3. Navigate to the RandWise project folder
4. Allow Gradle Sync to complete

### Run the Application

1. Connect an Android device or start an emulator
2. Click **Run**
3. Select the target device
4. Launch the application

---

## Building the APK

### Debug APK

```text
Build
→ Build APK(s)
```

### Signed Release APK

```text
Build
→ Generate Signed Bundle / APK
```

### Install Using ADB

```bash
adb install app-debug.apk
```

---

## Testing

The project includes:

* Unit Tests
* Database Tests
* Repository Tests
* Navigation Tests
* UI Tests

Testing is used to ensure application reliability, data integrity, and feature stability.

---

## Future Enhancements

Planned future improvements include:

* Cloud Backup & Synchronization
* Biometric Authentication
* AI-Powered Spending Insights
* Smart Budget Recommendations
* PDF Report Generation
* Recurring Transaction Support
* Shared Family Budgets
* Cross-Device Synchronization
* Banking Integration

---

## Why RandWise?

RandWise was built to demonstrate modern Android development practices while solving real-world budgeting challenges. The application combines a clean architecture, offline-first functionality, advanced analytics, goal tracking, and gamification into a single financial management platform designed to provide a professional fintech experience.

---

## License

All rights reserved.

This project is provided for educational, portfolio, and demonstration purposes.

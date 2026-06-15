# RandWise

A modern Android budgeting and expense management application built using Kotlin, MVVM Architecture, Room Database, and Material Design 3.

## Overview

RandWise is a premium personal finance application designed to help users manage expenses, monitor spending habits, achieve savings goals, and improve budgeting discipline.

Unlike traditional student budgeting projects, RandWise focuses on a polished fintech-inspired experience with intuitive navigation, modern analytics, achievement systems, and offline-first functionality.

---

## Features

### User Authentication

* User Registration
* Secure Login
* Session Persistence
* Remember Me Functionality
* Multi-User Support

### Dashboard

* Personalized Welcome Card
* Monthly Budget Overview
* Budget Remaining Indicator
* Spending Summary
* Quick Actions
* Recent Expenses
* Budget Health Score
* Analytics Preview

### Expense Management

* Add Expenses
* Edit Expenses
* Delete Expenses
* Receipt Attachments
* Category Assignment
* Date & Time Tracking
* Validation Handling

### Categories

* Create Categories
* Edit Categories
* Delete Categories
* Custom Spending Limits
* Category Statistics
* Visual Category Identification

### Analytics

* Pie Charts
* Line Charts
* Bar Charts
* Spending Trends
* Budget Trends
* Category Performance Analysis

### Goals

* Monthly Budget Goals
* Savings Targets
* Category Spending Limits
* Progress Tracking
* Budget Health Monitoring

### Achievements

* First Expense
* 7-Day Streak
* 30-Day Streak
* Budget Master
* Savings Star
* Category Champion
* Receipt Collector

### Settings

* User Profile
* Theme Management
* Data Export
* Data Reset
* Application Information

---

## Technology Stack

### Frontend

* Kotlin
* XML Layouts
* Material Design 3
* ViewBinding

### Architecture

* MVVM
* Repository Pattern
* LiveData
* Navigation Component

### Database

* Room Database
* DAO Pattern
* Type Converters

### Charts

* MPAndroidChart

---

## Architecture

MVVM Architecture

UI Layer
→ ViewModels
→ Repository Layer
→ Room Database

Benefits:

* Separation of Concerns
* Easier Testing
* Scalability
* Maintainability

---

## Database Entities

* User
* Expense
* Category
* BudgetGoal
* CategoryLimit
* Achievement
* UserSession
* Settings

---

## Application Modules

* Authentication
* Dashboard
* Expense Management
* Analytics
* Categories
* Goals
* Achievements
* Settings

---

## Offline First

RandWise is designed to work completely offline.

Features available without internet:

* User Authentication
* Expense Tracking
* Analytics
* Budget Goals
* Achievement Tracking
* Reporting

---

## Screenshots

Add screenshots here after application completion.

---

## Installation

### Clone Repository

git clone https://github.com/your-repository/RandWise.git

### Open Project

Open Android Studio

Select:
Open Existing Project

Choose:
RandWise

### Build

Build → Make Project

### Run

Run → Run App

---

## Requirements

* Android Studio Hedgehog or newer
* Android SDK 24+
* Android Device or Emulator
* Gradle 8+

---

## Future Enhancements

* Cloud Synchronization
* Biometric Authentication
* AI Spending Insights
* PDF Reports
* Recurring Transactions
* Shared Family Budgets
* Banking Integration

---

## License

Educational and Portfolio Use.

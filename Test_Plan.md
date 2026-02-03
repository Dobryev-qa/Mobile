# Test Plan  
## Homebody Challenge (iOS Mobile App)

**Version:** 1.0  
**Test Plan Date:** 20.01.2025  

---

## 1. Introduction

Homebody Challenge is a mobile fitness application for iOS devices, primarily targeting iPhone users running **iOS 18 and above**.

The application is developed using **Flutter (Dart)** and follows an **offline-first** approach with local data storage.

### Main Features
- Monthly fitness challenges  
- Custom challenge creation (Quick Start and Pro modes)  
- Workout tracking and progress monitoring  
- Profile with statistics  
- Local notifications  
- Offline usage support  

The current version (**1.0**) represents an **MVP release**.

---

## 2. Test Objectives

- Verify that core application functionality works according to user stories and acceptance criteria  
- Ensure main user flows work end-to-end without critical defects  
- Validate application behavior in offline mode  
- Identify functional, usability, and lifecycle-related issues  
- Assess basic performance characteristics (launch time, UI responsiveness)  

---

## 3. Test Types

- Manual functional testing  
- Smoke testing  
- Sanity testing  
- Regression testing (basic)  
- Exploratory testing  
- Basic performance testing  

**Automation testing:** Not included

---

## 4. Scope of Testing

### In Scope

#### Functional Testing
- App installation, deletion, and reinstallation  
- Application launch and lifecycle (background / foreground / cold start)  
- Dashboard functionality  
- Monthly challenge flow  
- Featured and custom challenges  
- Custom challenge creation (Quick Start and Pro modes)  
- Workout flow and timer  
- Progress tracking and statistics  
- Notifications (enable, schedule, receive, open app from notification)  
- Offline mode behavior  

#### Non-Functional Testing
- UI/UX usability checks  
- Application launch time  
- Basic localization verification  

---

### Out of Scope

- Backend and API testing (application is offline-first)  
- Cloud synchronization  
- Real payment processing (mock paywall only)  
- Analytics and CI/CD pipelines  

---

## 5. Test Environment

- **Platform:** iOS  
- **Real Device:** iPhone 11 (iOS 18.4)  
- **Simulator:** iPhone 17 (iOS 26.1)  
- **Network Conditions:**  
  - Online  
  - Offline  
  - Airplane mode  

---

## 6. Entry Criteria

- Application build is installed successfully  
- Core functionality is implemented  
- No known blocker preventing app launch  

---

## 7. Exit Criteria

- No blocker or critical defects remain open  
- Core user flows are tested end-to-end  
- Known issues are documented  
- Planned test cases are executed  

---

## 8. Risks and Mitigation

### Risks
- Limited real device and iOS version coverage  
- Platform-specific issues on newer iOS versions  
- Time constraints reducing overall test coverage  

### Mitigation
- Focus on critical user flows  
- Prioritize real device testing  
- Exploratory testing for high-risk areas  

---

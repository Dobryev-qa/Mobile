#  Mobile App – Functional Test Cases

This document contains functional test cases for the **HomeBody Challenge** mobile application.  

---

##  Test Case List

- [TC-01: App Launch & Cold Start](#tc-01-app-launch--cold-start)
- [TC-02: Monthly Challenge Acceptance](#tc-02-monthly-challenge-acceptance)
- [TC-03: Create Custom Challenge – Quick Start](#tc-03-create-custom-challenge--quick-start)
- [TC-04: Delete Active Challenge via Swipe](#tc-04-delete-active-challenge-via-swipe)
- [TC-05: Workout Reminder Notifications](#tc-05-workout-reminder-notifications)
- [TC-06: App Background → Foreground](#tc-06-app-background--foreground)

---

## TC-01: App Launch & Cold Start

**Type:** Functional  

### Test Steps
1. Tap the app icon on the device
2. Observe the application launch process

### Expected Result
- Application launches successfully
- Launch screen is displayed
- App navigates to the Home screen
- Application does not crash

---

## TC-02: Monthly Challenge Acceptance

**Type:** Functional  

### Preconditions
- User is on the Home / Dashboard screen
- Monthly Challenge is available
- Monthly Challenge is not yet active

### Test Steps
1. Open the application
2. Locate the **Monthly Challenge** section
3. Tap **Start Challenge**

### Expected Result
- Monthly Challenge becomes active
- User is navigated to the Active / Workout screen
- Monthly Challenge is added to Active Challenges
- Duplicate challenge is not created

---

## TC-03: Create Custom Challenge – Quick Start

**Type:** Functional  

### Preconditions
- Application is launched
- User is on the Home screen

### Test Steps
1. Navigate to the **Create Challenge** screen
2. Select **Quick Start** mode
3. Configure basic challenge settings
4. Confirm challenge creation

### Expected Result
- Custom challenge is successfully created
- Challenge appears in **My Challenges**
- Created challenge data is saved correctly

---

## TC-04: Delete Active Challenge via Swipe

**Type:** Functional  

### Preconditions
- At least one active challenge exists
- User is on the **Active** screen

### Test Steps
1. Navigate to the **Active** screen
2. Swipe left or right on an active challenge
3. Confirm deletion

### Expected Result
- Selected challenge is removed from Active Challenges
- Application does not crash
- Screen updates correctly without black screen

---

## TC-05: Workout Reminder Notifications

**Type:** Functional  

### Preconditions
- Notifications are disabled

### Test Steps
1. Open the application
2. Navigate to **Profile**
3. Enable workout notifications
4. Allow notification permission
5. Set a reminder time
6. Wait for the scheduled time

### Expected Result
- System notification permission is requested
- Notifications are enabled
- Workout reminder notification is delivered at scheduled time
- Tapping notification opens the app to the relevant workout screen

---

## TC-06: App Background → Foreground

**Type:** Functional  

### Test Steps
1. Open the application
2. Send the app to background
3. Return the app to foreground

### Expected Result
- Application resumes successfully
- User remains on the previous screen
- App does not crash
- Application state is preserved

# Acceptance Criteria

## US-02 – Monthly Challenge

### AC-01: Monthly challenge is displayed on Dashboard
Given the user opens the app  
When the Dashboard screen is displayed  
Then the Monthly Challenge section is visible

### AC-02: User can accept the monthly challenge
Given the Monthly Challenge is displayed  
When the user taps the "Accept Challenge" button  
Then the challenge becomes active and the Workout screen is opened

### AC-03: Monthly challenge is not duplicated
Given the Monthly Challenge is already active  
When the user taps the "Accept Challenge" button again  
Then no new challenge is created

### AC-04: User continues today’s workout
Given the Monthly Challenge is active and today’s workout is not completed  
When the user opens the Workout screen  
Then exercises for the current day are displayed

---

## US-04 – Create Custom Challenge

### AC-01: Create Challenge screen can be opened
Given the app is open  
When the user navigates to the Create Challenge screen  
Then the Create Challenge screen is displayed

### AC-02: User can choose challenge creation mode
Given the user is on the Create Challenge screen  
When the screen is displayed  
Then the user can choose between "Quick Start" and "Pro" modes

---

## US-05 – Quick Start Challenge Creation

### AC-01: User can start Quick Start flow
Given the user is on the Create Challenge screen  
When the user selects "Quick Start"  
Then the Quick Start flow is opened

### AC-02: User can configure basic settings
Given the user is in the Quick Start flow  
When the user selects challenge settings  
Then the selected settings are applied

### AC-03: User can create a challenge using Quick Start
Given the user completes the Quick Start flow  
When the user confirms challenge creation  
Then a new challenge is created and added to "My Challenges"

---

## US-10 – Notifications

### AC-01: App requests notification permission
Given notifications are disabled  
When the user enables notifications in app settings  
Then the system permission request is shown

### AC-02: Notifications are enabled
Given the permission request is shown  
When the user allows notifications  
Then notifications are enabled in the app

### AC-03: User can set notification time
Given notifications are enabled  
When the user selects a reminder time  
Then the selected time is saved

### AC-04: Notification is delivered
Given a reminder time is set  
When the scheduled time is reached  
Then a workout notification is delivered

### AC-05: Notification is not duplicated
Given today’s notification was already delivered  
When the app remains active or inactive  
Then the notification is not sent again

### AC-06: App opens from notification
Given a workout notification is shown  
When the user taps the notification  
Then the app opens and navigates to the workout screen

# Bug Report – BUG-001

## Summary
App crashes on relaunch after being fully closed.

---

## Project Information
- **Project:** Homebody Challenge  
- **Platform:** iOS (Mobile)  


---

## Environment
- **Device:** iPhone 11  
- **OS Version:** iOS 18.4  
- **Build Type:** Debug 

---

## Preconditions
- Application is installed on the device
- Application was launched successfully at least once

---

## Steps to Reproduce
1. Launch the application
2. Close the application
3. Open the app switcher
4. Swipe up to fully close the application
5. Tap the app icon on the Home screen to launch the app again

---

## Expected Result
- App opens normally
- App remains visible on the screen

---

## Actual Result
- App starts launch animation
- App crashes immediately during launch
- App does not appear on the screen
- App is not visible in the app switcher after the crash

---

## Severity
**Critical**

---

## Priority
**High**

---

## Logs
- No crash logs or error messages are shown in the console

## Evidence
![Bug 001 – App crash on relaunch](https://raw.githubusercontent.com/Dobryev-qa/Mobile/main/Bugs_Evidence/bug_001.gif)
---
# Bug Report – Bug_002

## Summary
Black screen after deleting an active challenge via swipe

---

## Project Information
**Project:** Homebody Challenge (Mobile App)  
**Component:** Active Challenges Screen  
**Platform:** iOS (Mobile)

---

## Environment
- **Device:** iPhone 11  
- **OS:** iOS 18.4  
- **Build:** Debug  

---

## Preconditions
- At least one active challenge exists  
- User is logged into the app 
- User is on the **Active** screen  

---

## Steps to Reproduce
1. Open the application  
2. Navigate to the **Active** screen  
3. Swipe left or right on an active challenge  
4. Confirm challenge deletion  

---

## Expected Result
- Selected challenge is removed from the Active Challenges list  
- Active screen updates correctly  
- Application continues to work normally  
- No visual issues appear  

---

## Actual Result
- Screen turns completely black after swipe deletion  
- Application becomes unresponsive  
- User cannot continue using the app without restarting it  

---

## Severity
**Critical**

---

## Priority
**High**

---

## Evidence
![Bug 002 – App crash on relaunch](https://raw.githubusercontent.com/Dobryev-qa/Mobile/main/Bugs_Evidence/Bug_002.gif)

# CS-360-Module-Eight - Weight-Tracking App

## Overview
The **Weight-Tracking App** is an Android application designed to help users track their daily weight, set personalized goal weights, and receive motivational notifications upon achieving their targets. The main purpose of this project was to create a **user-centered mobile application** that combines functionality, simplicity, and motivation for everyday use. This app demonstrates key skills in **mobile app development**, **database management**, and **UI/UX design** within Android Studio.

---

## App Requirements and Goals
The goal of the app is to support users who want a simple and effective way to monitor weight changes without unnecessary complexity. It addresses the need for accessible progress tracking by providing:
- **Daily Weight Input and History View**
- **Goal Weight Entry**
- **Automatic Notifications** upon goal achievement  
- **Secure Login and Account Creation**

By focusing on minimalism and efficiency, the app eliminates distractions and allows users to stay focused on their fitness goals.

---

## User Interface and Design Approach
To create a **user-centered experience**, the app was built with an intuitive layout and clear navigation. The core screens include:
- **Login/Register Screen:** For secure account management.  
- **Dashboard Screen:** To display past entries, input new weights, and track progress.  
- **Goal Screen:** For goal-setting and automatic notifications when goals are reached.  

The design emphasizes clarity through readable typography, clean input fields, and responsive layouts. Buttons and labels are easily accessible, ensuring the app can be comfortably used on various screen sizes. This user-first design ensures engagement and ease of use, contributing to a positive user experience.

---

## Coding Approach and Strategies
The coding process followed an **iterative and modular approach**. Development began with database implementation (using **SQLite**) to store user, goal, and weight data. Afterward, each UI component was connected to backend functions through event listeners and data bindings.  
Key strategies included:
- Breaking development into small, testable modules.  
- Applying **Android best practices** for Activity lifecycle management.  
- Maintaining clean, reusable code for scalability.  

These strategies promote better debugging, maintainability, and adaptability for future enhancements.

---

## Testing and Debugging
The app underwent multiple testing stages using the **Android Emulator** and on-device testing.  
Key tests included:
- **Database Operations:** Ensuring accurate storage and retrieval of weight and goal data.  
- **UI Interactions:** Verifying button responsiveness and layout consistency.  
- **Notification Testing:** Confirming that goal notifications trigger correctly.  
- **Permission Handling:** Ensuring SMS permissions were requested only when necessary.  

Testing was crucial to verifying that the app’s features worked reliably across Android versions. This process revealed minor issues with permission handling and manifest configurations, which were successfully resolved by refining `AndroidManifest.xml` attributes and logic validation.

---

## Challenges and Innovations
One of the biggest challenges was ensuring the app remained compatible with the latest Android versions, particularly regarding permissions (such as `SEND_SMS`) and exported activities. I overcame this by studying recent Android documentation and updating the manifest to meet security requirements.  
Another innovation was integrating a **goal-based notification system** that automatically sends motivational alerts when users reach their target weight—an enhancement that adds real-world value and engagement to the app.

---

## Demonstration of Knowledge and Skills
This project highlights my ability to combine **mobile development**, **UI/UX design**, and **database integration** into a cohesive product.  
In particular:
- The **DatabaseHelper** class showcases structured data management.  
- The **DashboardActivity** demonstrates my ability to handle event-driven programming and SMS integration.  
- The final app illustrates my understanding of **user-centered design principles** and **software engineering best practices**.  

Through this project, I demonstrated technical proficiency, creativity, and the ability to deliver a functional, well-designed mobile app from concept to completion.

---


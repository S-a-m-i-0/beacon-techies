# Event Management Application

## Overview
The Event Management Application is an Android-based platform designed to provide a **fair, transparent, and accessible event registration experience**. Rather than relying on first-come-first-served sign-ups, the app uses a **lottery-based waiting list system** to ensure equal opportunities for all participants.

The application supports multiple user roles—**Entrant, Organizer, and Admin**—each with role-specific permissions. Real-time updates, QR code integration, and cloud-based data management are powered by Firebase.

---

## 🎥 Demo Video
A complete walkthrough of the app’s features is available here:  
https://drive.google.com/file/d/156Mpkwj-IH8tMCLBpqfOBlLRKLpZoo8e/view

---

## 📸 Screenshots
- Dashboard Overview  
- Event Details Page  

---

## ✨ Features

### ✅ Entrant Features
- Join or leave an event waiting list  
- Receive notifications for lottery results  
- Automatically re-enter the lottery if a selected participant declines  
- Upload, update, or remove profile pictures  
- Optional geolocation-based event sign-up  
- Scan QR codes to view event details instantly  
- Automatic login using device authentication (no username or password required)

### 🎟️ Organizer Features
- Create, edit, and manage events  
- Generate unique QR codes for event registration  
- View and manage entrant waiting lists  
- Track registration locations on a map  
- Run a fair and random lottery to select participants  
- Upload and manage event posters  
- Send notifications to entrants and selected participants  

### 🔧 Admin Features
- Remove events, user profiles, and QR code data  
- Browse all events, profiles, and uploaded images  
- Monitor system activity  
- Remove facilities or content that violate platform policies  

---

## 🛠️ Technology Stack
- **Programming Language:** Java  
- **Development Environment:** Android Studio  
- **Authentication:** Firebase Authentication  
- **Database:** Firebase Firestore  
- **Cloud Storage:** Firebase Storage  
- **Testing:** JUnit, Espresso  
- **Build Tool:** Gradle  

---

## 🚀 Installation & Setup

### Prerequisites
- Android Studio installed  
- A configured Firebase project  

### Setup Instructions
- Clone the repository:
   ```bash
   git clone https://github.com/yourusername/event-lottery-app.git
   cd event-lottery-app
   fter cloning the repository, complete the following steps to run the project:

- Open the project in **Android Studio**

- Connect **Firebase**:
  - Navigate to **Tools > Firebase**
  - Follow the Firebase integration instructions
  - Download and add the `google-services.json` file from the Firebase Console to the project

- Sync **Gradle** and build the project

- Run the app on an **Android emulator** or a **physical Android device**

## 📖 Usage Guide

### Getting Started
When launching the app for the first time, users are authenticated using **Firebase Authentication**.  
Based on their role, users are granted access as **Entrants**, **Organizers**, or **Admins**, each with different permissions and features.

No traditional username or password is required; authentication is handled securely through device-based login.

---

### 👤 Entrants
Entrants are regular users who wish to participate in events.

Entrants can:
- Browse a list of available events
- Scan QR codes to instantly view event details
- Join or leave an event’s waiting list
- Receive notifications about lottery selection results
- Automatically re-enter the lottery if a selected participant declines
- Upload, update, or remove profile pictures
- Optionally register for events using geolocation-based verification

---

### 🎟️ Organizers
Organizers are responsible for creating and managing events.

Organizers can:
- Create, edit, and publish events
- Generate unique QR codes for event registration
- View and manage waiting lists of interested entrants
- Conduct fair lottery draws to select participants
- Upload and manage event posters and descriptions
- Track entrant registration locations using a map view
- Send notifications to entrants and selected participants

---

### 🔧 Admins
Admins oversee the platform to ensure fairness and policy compliance.

Admins can:
- View and manage all events and user profiles
- Remove events, users, or uploaded images when necessary
- Delete QR code data and event facilities that violate policies
- Monitor overall application activity to ensure fair usage

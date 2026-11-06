# 🛕 TempleEase – Smart Temple Management & Visitor Assistance App

**TempleEase** is an Android application designed to improve the temple visiting experience through smart crowd monitoring, parking availability tracking, route recommendations, real-time alerts, and visitor assistance.

The application helps pilgrims make informed decisions, avoid crowded areas, find suitable parking spaces, and navigate temple premises more efficiently. It also provides administrative features to manage temple information and visitor safety.

## ✨ Key Features

### 1. Live Crowd Monitoring
- Displays crowd levels at different temple gates.
- Categorizes crowd density as LOW, MEDIUM, and HIGH.
- Shows estimated waiting times.
- Fetches crowd status updates from Firebase Firestore.

### 2. Smart Route Recommendations
- Recommends suitable temple entrances based on crowd conditions.
- Ranks available gates according to crowd density and estimated waiting time.
- Helps visitors choose less crowded routes.

### 3. Interactive Temple Map
- Displays temple locations and gate markers.
- Uses OpenStreetMap for map visualization.
- Shows crowd information associated with different gates.

### 4. Parking Availability
- Displays available parking zones.
- Shows the number of available parking slots.
- Helps visitors identify suitable parking areas.

### 5. Emergency SOS Assistance
- Provides an emergency SOS feature.
- Allows emergency alerts to be submitted to the backend.
- Supports improved communication with temple administration.

### 6. Smart Alerts & Notifications
- Displays important temple announcements.
- Provides crowd and parking-related alerts.
- Helps visitors stay informed about important updates.

### 7. AI-Style Chat Assistant
- Includes an interactive FAQ-based chatbot.
- Answers questions related to crowd status, parking, routes, darshan timings, prasadam, and emergencies.
- Provides quick assistance through a conversational interface.

### 8. User Authentication & Role Management
- User registration and login.
- Firebase Authentication integration.
- Separate visitor and administrator navigation flows.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Kotlin |
| UI Development | Jetpack Compose |
| Architecture | MVVM |
| Backend | Firebase |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore |
| Maps | OpenStreetMap (OSMDroid) |
| Navigation | Jetpack Navigation Compose |
| Local Storage | DataStore Preferences |
| Asynchronous Programming | Kotlin Coroutines and Flow |
| Development Environment | Android Studio |
| Build System | Gradle |

## 🏗️ Application Architecture

TempleEase follows the Model-View-ViewModel (MVVM) architecture.

- **Model:** Represents application data such as users, crowd status, parking status, alerts, and messages.
- **View:** Jetpack Compose screens that display information and handle user interactions.
- **ViewModel:** Manages UI state and coordinates communication between the UI and repositories.
- **Repository:** Handles data operations involving Firebase Firestore and application logic.

## 📱 Main Application Modules

- Home Dashboard
- Crowd Monitoring
- Interactive Map
- Route Recommendations
- Parking Management
- Alerts
- Chat Assistant
- User Profile
- Authentication
- Emergency SOS

## 🚀 Getting Started

### Prerequisites

- Android Studio
- Android SDK
- Kotlin support
- JDK 11 or compatible Gradle JDK
- Firebase project
- Android device or emulator

### Installation

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/TempleEase.git
```

**Step 2: Open the project**

Open the cloned project in Android Studio.

**Step 3: Configure Firebase**

1. Create a Firebase project.
2. Register your Android application using its package name.
3. Enable Firebase Authentication.
4. Set up Cloud Firestore.
5. Download your Firebase configuration file.
6. Place `google-services.json` in the Android app module directory.

**Step 4: Configure Firestore**

Create the collections required by the application:

- `users`
- `crowd_status`
- `parking`
- `alerts`
- `sos_alerts`

Configure appropriate Firestore security rules before deployment.

**Step 5: Build and Run**

Sync the Gradle project, build the application, and run it on an Android emulator or physical device.

## 🌍 Real-World Applications

TempleEase can be useful for:

- Large temples experiencing heavy visitor traffic.
- Festivals and special religious occasions.
- Crowd management and visitor safety.
- Efficient parking management.
- Reducing congestion at temple entrances.
- Improving the overall pilgrimage experience.

## 🔮 Future Enhancements

- AI-powered crowd prediction using historical visitor data.
- Real-time GPS-based navigation.
- Live parking sensor integration.
- Multilingual voice assistance.
- Push notifications using Firebase Cloud Messaging.
- QR-based darshan booking and queue management.
- Advanced analytics dashboard for temple administrators.
- Integration with CCTV-based crowd detection systems.

## 🎯 Project Objective

The primary objective of TempleEase is to combine mobile technology, cloud-based services, and intelligent visitor assistance to create a safer, smarter, and more organised temple environment.

**TempleEase – Making Every Temple Visit Easier, Safer, and Smarter.**

## 👩‍💻 Project Information

- **Project Name:** TempleEase
- **Platform:** Android
- **Domain:** Smart Tourism / Smart Temple Management
- **Project Type:** Mobile Application
- **Primary Language:** Kotlin



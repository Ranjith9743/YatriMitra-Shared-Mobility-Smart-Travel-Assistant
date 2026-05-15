# 🚖 YatriMitra – Shared Mobility & Smart Travel Assistant

## 📌 Project Overview
**YatriMitra** is an Android-based Shared Mobility application developed to simplify daily commuting through smart ride booking, route assistance, emergency safety, and travel utility services.  

The application focuses on providing users with a safer, more efficient, and user-friendly transportation experience by integrating essential mobility features into one platform.

---

# 🎯 Problem Statement
Urban commuters often face multiple challenges such as:
- Difficulty in finding affordable rides
- Lack of integrated route guidance
- Safety concerns during travel
- Emergency support limitations
- Fuel/petrol station accessibility issues

**YatriMitra** addresses these issues by offering a unified smart mobility solution.

---

# 🚀 Key Features

## 👤 User Authentication
- User Registration
- Login System
- Profile Management
- Secure local data handling

---

## 🚗 Ride Booking
- Book shared rides
- Select source & destination
- Ride details interface
- User-friendly booking flow

---

## 🗺️ Route Navigation
- Route planning UI
- Travel path guidance
- Navigation-ready architecture

---

## ⛽ Nearby Petrol Pumps
- Petrol pump finder interface
- Fuel assistance for travelers

---

## 🚨 Emergency Safety
- Emergency contact support
- Safety-first architecture
- Quick-access assistance module

---

## 📊 Dashboard
- Centralized navigation
- User controls
- Easy feature access

---

# 🛠️ Tech Stack

## Frontend:
- **Kotlin**
- **Jetpack Compose**
- **Material Design**

## Architecture:
- **MVVM (Model-View-ViewModel)**
- **Repository Pattern**
- **Hilt Dependency Injection**

## Database:
- **Room Database**

## Future Scope:
- Firebase Authentication
- Firestore Cloud Database
- Google Maps API
- Real-Time GPS Tracking
- Payment Gateway Integration

---

# 🏗️ Project Structure

```plaintext
YatriMitraSharedMobilityApp/
│
├── app/
│   ├── src/main/java/com/example/yatrimitra/
│   │   ├── ui/                # Screens & UI Components
│   │   ├── viewmodel/         # ViewModels
│   │   ├── repository/        # Data handling
│   │   ├── database/          # Room DB
│   │   ├── navigation/        # Navigation setup
│   │   └── di/                # Hilt Dependency Injection
│   │
│   ├── res/                   # Resources
│   └── AndroidManifest.xml
│
├── build.gradle
├── settings.gradle
└── README.md

# CoolRoute - Cool Route Finding App 🚴‍♂️🌳

---

**Original Repository:** [CoolRoute GitHub Repo](https://github.com/wenhao111-gps/CoolRoute)

---

[![Kotlin](https://img.shields.io/badge/Kotlin-FF5722?style=for-the-badge\&logo=kotlin\&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge\&logo=android\&logoColor=white)](https://developer.android.com/)
[![Industry Project](https://img.shields.io/badge/Industry-Project-blue?style=for-the-badge)]()
[![CO₂ Saved](https://img.shields.io/badge/CO₂_Saved-🌿-green?style=for-the-badge)]()

---

**CoolRoute** is an Android application built with Kotlin and Jetpack Compose that helps users find **cool, shaded routes** for walking, cycling, or other outdoor activities. The app prioritizes routes with optimal shade, comfort, and environmental benefits, helping users stay cool while tracking **CO₂ savings** and building a **virtual forest**.

---

## Overview

CoolRoute is designed for pedestrians and cyclists in Melbourne, Australia. Unlike traditional navigation apps, it focuses on **shade, comfort, and sustainability** rather than just shortest distance. Users can explore the city safely while monitoring their environmental impact and earning badges for sustainable travel.

---

## Key Features 🌟

* **Shaded & Comfortable Route Finding:** Select routes with optimal shade and pedestrian/cyclist comfort.
* **Urban Heat Island Index:** Visualize heat intensity across Melbourne to avoid hot spots.
* **Tree Canopy Coverage:** Explore canopy density across different suburbs in Melbourne to plan cooler, greener routes.
* **CO₂ Savings Tracker:** Track carbon emissions avoided by walking or cycling.
* **Food Carbon Footprint Calculator:** Estimate the CO₂ impact of your dietary choices.
* **AI-Based Carbon Reduction Tips:** Receive personalized suggestions to reduce carbon emissions in daily life, including food and travel.
* **Virtual Forest:** Earn virtual trees as you travel, representing your environmental contribution.
* **Progress Badges:** Gamified rewards for sustainable commuting milestones.
* **Interactive Maps:** Full-screen Google Maps with route polylines, highlighting most shaded, fastest, and scenic options.
* **Modern UI:** Built with **Jetpack Compose** and **Material 3**, featuring floating search bars, bottom sheets, and smooth navigation.

---

## Technical Implementation 🛠

### Dependencies

* **Google Maps SDK** – For map display and interaction
* **Maps Compose** – Integration with Jetpack Compose
* **Jetpack Compose** – Modern Android UI toolkit
* **Material 3** – Design system components

### Architecture

* **UI Layer:** Jetpack Compose components
* **State Management:** Local state using `remember` and `mutableStateOf`
* **Navigation:** Screen-based navigation between Home, Map, and Community

### Key Components

* `HomePage.kt` — Main screen with map and search functionality
* `SearchBar.kt` — Floating card with origin/destination inputs
* `RouteBottomSheet.kt` — Bottom sheet displaying available routes
* `RouteCard.kt` — Individual route information card
* `BottomNavigationBar.kt` — Navigation between app sections

---

## Setup and Running ⚡

### Prerequisites

* Android Studio (latest version)
* Android SDK 24+
* Google Maps API key

### Running the App

1. Open the project in Android Studio
2. Sync Gradle files
3. Run the app on an emulator or physical device

---

## Current Status ✅

* UI Implementation Complete: All required UI components implemented
* Google Maps Integration: Full-screen map centered around Melbourne
* Search Functionality: Origin/destination input with swap capability
* Route Display: Mock routes with polylines and selection
* Material 3 Design: Modern, clean UI following Material Design principles
* Navigation: Bottom navigation bar with proper routing

---

## Next Steps (Backend Integration)

* Implement actual **route calculation algorithms**
* Add **real-time location services**
* Integrate with mapping APIs for route data
* Add **user preferences and route history**
* Implement **actual navigation functionality**

---

## Screenshots 📱

<img width="1043" height="2048" alt="image" src="https://github.com/user-attachments/assets/4073832e-edcb-423d-b3e8-b7c9bbc3f64f" />
<img width="1062" height="2048" alt="image" src="https://github.com/user-attachments/assets/a38caf28-7286-49df-ab78-334ae8c14c1d" />
<img width="1080" height="1976" alt="image" src="https://github.com/user-attachments/assets/378eb392-d030-4eb7-b607-c66eeed71cd0" />
<img width="1056" height="2048" alt="image" src="https://github.com/user-attachments/assets/814bab56-5ce7-4002-8732-bea44f7762f6" />
<img width="1059" height="2048" alt="image" src="https://github.com/user-attachments/assets/08765aeb-fcbe-44f9-9bad-c2c119f27d46" />
<img width="1064" height="2048" alt="image" src="https://github.com/user-attachments/assets/c2aae022-897b-450c-94a4-7ec406e1b5b2" />
<img width="1054" height="2048" alt="image" src="https://github.com/user-attachments/assets/dc34136a-c77d-4426-a3c8-889ff93f74bf" />

---

## License 📄

This project is **proprietary** as part of an industry assignment. The README is public to showcase the project without exposing private source code.

---

## Acknowledgements 🙏

* Melbourne open GIS datasets
* Google Maps API
* AI carbon emission datasets
* Industry mentors and project collaborators

```
```

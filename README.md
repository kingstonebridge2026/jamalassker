# Car Zone 🚗 | Enterprise-Grade Flutter Marketplace

A high-performance, cross-platform mobile application for car enthusiasts and dealers. Built with a focus on **Clean Architecture** and **Scalable State Management**, this project demonstrates industry-standard development practices for the modern mobile ecosystem.

## 🏗️ Architectural Overview
This project implements a hybrid of **Clean Architecture** and **MVVM** to ensure a strict separation of concerns, making the codebase highly testable and maintainable.

- **Presentation Layer:** Managed via `flutter_bloc` for predictable state transitions and reactive UI updates.
- **Domain Layer:** Contains pure business logic and entity definitions (Plain Old Dart Objects).
- **Data Layer:** Handles data retrieval from **Firebase (Firestore)** and external REST APIs using **Dio**, with a repository pattern to abstract data sources.



[Image of Clean Architecture Diagram]


## 🛠️ Tech Stack & Key Features
- **State Management:** `flutter_bloc` (Cubit) for lightweight, efficient state handling.
- **Networking:** `Dio` with custom interceptors for secure API communication.
- **Backend-as-a-Service:** Full **Firebase** integration (Auth, Firestore, Cloud Messaging).
- **Security:** Secure local storage via `get_storage` and robust JWT-based authentication flows.
- **Localization:** Multi-language support using `easy_localization` (currently supporting Arabic/English).
- **UI/UX:** Custom-built components for a consistent design language, utilizing `google_fonts` and `font_awesome_flutter`.

## 🚀 Key Engineering Highlights
- **Platform Interoperability:** Custom logic for native device features like image picking and URL launching.
- **Dependency Management:** Modular folder structure (`lib/core`, `lib/features`) designed for team scalability.
- **Notifications:** Integrated **Firebase Cloud Messaging (FCM)** with local notification fallback for high user engagement.

## 🏁 Getting Started

### Prerequisites
- Flutter SDK: `^3.8.1`
- A Firebase project setup (Google Services files required).

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/car_zone.git](https://github.com/yourusername/car_zone.git)

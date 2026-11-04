# EV Finder & Queue Management

A mobile application that helps electric vehicle (EV) drivers to find nearby charging stations and reserve charging slots in advance, while giving station administrators a real-time view of reservations.

---

## Tech Stack

| Layer        | Technology            |
|--------------|-----------------------|
| Frontend     | Flutter               |
| Backend      | Firebase              |
| Maps & Location | Google Maps API    |

---

## Features

### User
- **Find charging stations** – Browse and locate nearby EV charging stations on an interactive map.
- **Reserve a charging slot** – Book an available time slot at a chosen station to avoid waiting in queues.

### Admin
- **Real-time reservation view** – Monitor incoming and active reservations as they happen.
- **Manage station details** – Add, update and maintain charging station information.

---

## Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install)
- A [Firebase](https://console.firebase.google.com/) project
- A [Google Maps API key](https://developers.google.com/maps/documentation/android-sdk/get-api-key)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ThisaruUmandi/Electric-Vehicle-Finder-and-Queue-Management.git
   cd Electric-Vehicle-Finder-and-Queue-Management
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a Firebase project and register your Android/iOS app.
   - Add `google-services.json` to `android/app/` and/or `GoogleService-Info.plist` to `ios/Runner/`.

4. **Add your Google Maps API key**
   - **Android:** add the key to `android/app/src/main/AndroidManifest.xml`
     ```xml
     <meta-data
         android:name="com.google.android.geo.API_KEY"
         android:value="YOUR_API_KEY"/>
     ```
   - **iOS:** add the key in `ios/Runner/AppDelegate.swift`
     ```swift
     GMSServices.provideAPIKey("YOUR_API_KEY")
     ```

5. **Run the app**
   ```bash
   flutter run
   ```

---

## Contributing

Contributions, issues and feature requests are welcome. Feel free to open an issue or submit a pull request.

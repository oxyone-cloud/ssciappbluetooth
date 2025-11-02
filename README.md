# 📱 SSCIAPPBLUETOOTH



## 🌐 Overview
**SSCIAppBluetooth** is a fully functional Flutter mobile application designed for smart refrigeration monitoring and control.  
Developed by **Benhamamouch Othman**, the app connects via Bluetooth and synchronizes real-time data with Firebase.

## 🚀 Features
- Bluetooth connectivity for IoT devices  
- Real-time data synchronization with **Firebase**  
- Flutter-based mobile interface  
- Designed for industrial refrigeration systems  
- Operational and tested with real hardware  

## 🧱 Tech Stack
- Flutter / Dart  
- Firebase  
- Bluetooth API  

## ⚙️ Architecture
SSCIAppBluetooth/
│
├── android/                     # Android platform-specific code
├── ios/                         # iOS platform-specific code
├── build/                       # Auto-generated build files (ignored by Git)
│
├── lib/                         # Main Flutter source code
│   ├── main.dart                 # Application entry point
│   │
│   ├── core/                     # Core services and utilities
│   │   ├── bluetooth_service.dart   # Manages Bluetooth communication
│   │   ├── firebase_service.dart    # Handles Firebase data sync
│   │   ├── data_parser.dart         # Converts sensor data formats
│   │   └── logger.dart              # Custom logs and debug tools
│   │
│   ├── models/                   # Data models
│   │   ├── device_model.dart       # Represents connected devices
│   │   └── sensor_data.dart        # Represents incoming sensor values
│   │
│   ├── screens/                  # App screens (UI)
│   │   ├── home_screen.dart        # Dashboard for connected devices
│   │   ├── device_list_screen.dart # Scanning and pairing interface
│   │   ├── data_screen.dart        # Real-time sensor data view
│   │   └── settings_screen.dart    # Configuration and preferences
│   │
│   ├── widgets/                  # Reusable UI components
│   │   ├── device_card.dart
│   │   ├── bluetooth_button.dart
│   │   └── data_chart.dart
│   │
│   ├── utils/                    # Helper functions
│   │   ├── constants.dart
│   │   ├── theme.dart
│   │   └── validators.dart
│   │
│   └── routes.dart               # Defines navigation routes
│
├── assets/                      # App images, icons, and fonts
│   ├── icons/
│   ├── images/
│   └── fonts/
│
├── test/                        # Unit and widget tests
│   ├── bluetooth_test.dart
│   └── firebase_test.dart
│
├── pubspec.yaml                 # Flutter dependencies and project metadata
├── README.md                    # Project documentation
├── .gitignore                   # Files ignored by Git
└── LICENSE                      # MIT license file

## 📜 License
Released under the **MIT License**.  
Open for modification and integration with credit to the author.

## 👤 Author
**Benhamamouch Othman (Oxy-One)**  
Founder & CEO of **SSCI Solution of Cold**  
🔗 [LinkedIn](https://www.linkedin.com/in/benhamamouch-othman)  
🌍 [Official Website](https://oxyone-cloud.github.io/Benhamamouch-web)

# DiaTransIosApp

DiaTransIosApp is an iOS application designed to provide translation services, focusing on dialects. This application is developed using SwiftUI and integrates various features for real-time translation.

## Features

- Real-time voice translation
- Support for multiple dialects
- Easy-to-use interface
- Customizable language options

## Requirements

- iOS 14.0 or later
- Xcode 12.0 or later
- Swift 5.0 or later

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/jsun96225/DiaTransIosApp.git
DiaTransIosApp/
├── DiaTrans.xcodeproj         # Xcode project file
├── DiaTrans/
│   ├── Models/                # Data models
│   ├── Views/                 # SwiftUI views
│   │   ├── ConversationView.swift
│   │   ├── CustomTabBarView.swift
│   │   ├── ContentView.swift
│   │   ├── RecordView.swift
│   │   ├── HistoryView.swift
│   │   ├── UserView.swift
│   ├── Controllers/           # View controllers
│   ├── Services/              # API and other services
│   ├── Resources/             # Assets and other resources
│   └── DiaTransApp.swift      # App entry point
├── Podfile                    # CocoaPods dependencies
└── README.md                  # Project README file

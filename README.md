DIALD

DIALD is a social iOS app designed for go-getters to set and share real-time proof of progress with friends. Combining goal tracking with dual-camera capture, DIALD transforms your daily achievements into authentic social moments—motivating yourself and your circle.

🚀 Key Features

Dual-Camera Capture: Snap simultaneous front/back photos or 2‑second looping videos to document goals as you complete them.

Accountability Feed: Post updates to your friend circles, view real-time Firestore-powered stories, and react to each other’s achievements.

Daily Goals & Streaks: Set up to 3 goals per day, track completion, and maintain streak badges to stay on track.

Group Circles & Leaderboards: Create or join circles, compare progress on group leaderboards, and nudge friends for accountability.

Explore & Search: Discover peers, groups, and trending public circles; send join requests or invite links.

Profiles & Customization: Personalize profiles with bios, progress feed, goal stats, and music status—styled for both light & dark modes.

Animations & Polish: Confetti celebrations, smooth haptic feedback, and subtle motion for an ultra‑clean, premium feel.

🛠️ Tech Stack

Language & Framework: Swift 5, SwiftUI

Backend: Firebase Firestore, Firebase Auth, Firebase Storage

Animations: Framer Motion concepts via SwiftUI animation APIs

Icons & Imagery: SF Symbols, dual-camera preview

CI/CD: GitHub Actions for build & test; TestFlight for beta distribution

📥 Installation & Setup

Clone the repo

git clone https://github.com/your-org/diald.git
cd diald

Install Dependencies

Ensure Xcode 14+ is installed.

Run pod install (if using CocoaPods) or open with Swift Package Manager.

Firebase Configuration

Create a Firebase project and enable Firestore, Auth, and Storage.

Download GoogleService-Info.plist and add it to the Xcode project root.

Update Bundle Identifier to match your Firebase settings.

Run the App

Select the Diald scheme, choose a simulator or device, and press Run.

📂 Project Structure

Diald/
├── App/                  # App entry point & environment setup
├── Models/               # Data models (User, Post, Group, Goal)
├── ViewModels/           # MVVM logic & Firestore listeners
├── Views/                # SwiftUI views (Home, Profile, GroupDetail)
├── Components/           # Reusable UI components (Cards, Modals)
├── Services/             # Networking & Firebase wrappers
├── Resources/            # Assets, Localization files, Fonts
└── Utilities/            # Helpers, Extensions, Animations

🤝 Contributing

Fork the repo.

Create a feature branch: git checkout -b feature/YourFeature.

Commit your changes: git commit -m "Add awesome feature".

Push to the branch: git push origin feature/YourFeature.

Open a pull request—ensure all tests pass and code is linted.

Please follow the existing code style, include tests for new logic, and describe your changes clearly.

📝 License

This project is licensed under the MIT License. See LICENSE for details.

"Social media that actually makes you better. Feel the push, share the proof, and get DIALD.

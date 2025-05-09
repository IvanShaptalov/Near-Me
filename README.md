✈️ Near Me — MVVM, Combine, Swift Concurrency, CI/CD

A production-ready travel planning app built with a modern tech stack. The project showcases clean architecture, reactive programming, and full CI/CD integration.

⸻

🔧 1. CI/CD & Automation
    •    Integrated with Bitrise: automated builds, testing, and deployment from GitHub.
    •    Configured Fastlane for streamlined workflows: build, test, and TestFlight deployment.
    •    Continuous integration with XCTest in the pipeline.

⸻

🧠 2. Architecture & Async
    •    MVVM architecture with a clear separation between View, ViewModel, and Service layers.
    •    Utilizes Combine for reactive bindings using @Published, Publisher, sink.
    •    Implements Swift Concurrency with async/await in UseCase and network layers.

⸻

🖼️ 3. User Interface
    •    Built entirely in UIKit with SnapKit for declarative Auto Layout.
    •    Storyboards removed. Manual setup via SceneDelegate and code-based UI.
    •    Responsive layout adaptable to all device sizes.

⸻

📊 4. Analytics & Backend
    •    Integrated Firebase Analytics to track screens and custom events.
    •    Connected Adjust for advanced mobile marketing analytics and attribution.
    •    Deployed Cloud Functions for dynamic content (e.g., trip recommendations), secured with auth tokens.

⸻

🧪 5. Testing
    •    Unit tests for ViewModels using XCTest.
    •    UI tests for user flows: scrolling, navigation, and input.
    •    Full test suite included in the Bitrise workflow.

⸻

🌍 App Overview

An iOS app for planning personalized trips with:
    •    📍 Route planning with landmarks and destinations
    •    🌦️ Real-time weather integration
    •    💡 Smart suggestions based on travel type (adventure, city tour, beach)
    •    📈 Analytics-powered user behavior insights

⸻

🚀 Tech Stack
    •    UIKit + SnapKit
    •    MVVM Architecture
    •    Combine + Swift Concurrency
    •    Firebase (Analytics & Cloud Functions)
    •    Adjust
    •    Bitrise + Fastlane
    •    XCTest (Unit & UI)

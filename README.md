A modern Android application for managing library books and student records using Jetpack Compose, Room database, and ML Kit for QR/barcode scanning.

Features
Book Management: Browse, add, and view detailed information about books in the library.
QR/Barcode Scanner: Easily process book transactions by scanning QR codes or barcodes using the built-in scanner powered by CameraX and Google ML Kit.
Student Records: Maintain a list of students and track their borrowing history.
Transaction History: View a complete history of book scans and assignments.
Leaderboard: Track and rank students based on their reading or borrowing activity.
Modern UI: Built entirely with Jetpack Compose following Material Design 3 guidelines.
Tech Stack
Language: Kotlin
UI Framework: Jetpack Compose
Architecture: MVVM (Model-View-ViewModel)
Database: Room for local persistence
Scanning: Google ML Kit Barcode Scanning & CameraX
Navigation: Navigation Compose
Image Loading: Coil
Dependency Injection: (Standard ViewModel pattern used)
Getting Started
Clone the repository.
Open the project in Android Studio (Ladybug or newer recommended).
Sync Gradle and run the app on an Android device or emulator (API 26+).
Project Structure
ui/screens/: Contains all the Compose screens (Home, Scanner, History, Students, etc.).
viewmodel/: Contains LibraryViewModel for managing UI state and data operations.
data/: (Implied) Room database entities, DAOs, and repository.
ui/theme/: Material 3 theme configuration.

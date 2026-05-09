NarynDrive
NarynDrive is a peer-to-peer rideshare and delivery platform designed specifically for Naryn, Kyrgyzstan. The project aims to digitalize local transport and logistics by providing real-time tracking and monitoring capabilities.

🛠 Tech Stack
Frontend: Flutter (Dart)

Backend: Java with Spring Boot

Database: PostgreSQL & Dockerized environments

APIs: Google Maps SDK for Android

Communication: STOMP WebSockets for live tracking

🚀 Current Progress
The mobile development phase has successfully reached the following milestones:

Environment Configuration: Fully established the Flutter development environment, including Android SDK toolchain integration and Developer Mode permissions for Windows symlink support.

Maps Integration: Successfully integrated the google_maps_flutter package and configured the Google Cloud Console with secure API keys and SHA-1 fingerprints.

Live Rendering: The application successfully launches on an Android Emulator, rendering a high-fidelity map centered on Naryn City (41.4285, 75.9912).

Backend Foundation: The Spring Boot backend is already equipped with STOMP WebSocket functionality to handle future live-tracking data streams.

📦 Prerequisites & Setup
Flutter SDK: Ensure Flutter is installed and added to your system PATH.

Android SDK: Android Studio must be installed to provide the necessary build tools and emulators.

API Key: A valid Google Maps API key must be placed in android/app/src/main/AndroidManifest.xml.

Bash
# Clean the project and fetch dependencies
flutter clean
flutter pub get

# Run the application
flutter run
🗺 Roadmap
[ ] User Location: Implement the geolocator package to display the user's live position on the map.

[ ] Live Markers: Integrate backend WebSocket data to display real-time driver and delivery vehicle positions as markers.

[ ] UI Overlay: Build the cross-platform mobile interface for ride requests and delivery tracking.

[ ] Authentication: Link the mobile frontend with existing backend security protocols.

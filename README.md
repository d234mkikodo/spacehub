# Flutter Social Media App

**Demo:** [https://flutter-social-livesteam.web.app/](https://flutter-social-livesteam.web.app/)

This repository contains the documentation and design concepts for a modern social media application built with **Flutter**. The application is designed to provide a seamless experience across Web and Mobile platforms.

## ✨ Features

*   **Authentication**: Secure login and social sign-in integration.
*   **Social Feed**: Interactive feed with categories and responsive layout (Sidebar for Desktop, Drawer for Mobile).
*   **Live Streaming**: Dedicated interface for watching streams with real-time chat and video controls.
*   **Search**: Global search functionality.

## 🛠️ How It Was Built

This application was developed using the following process:

### 1. Project Setup & Architecture
*   Initialized a new Flutter project.
*   Structured the project by features (`auth`, `feed`, `stream`, `search`) to ensure scalability.
*   Configured the app to run on both Android and Web platforms.

### 2. UI/UX Design
*   **Theme**: Defined a global app theme using `ThemeData` to ensure consistent colors and typography (Google Fonts).
*   **Responsive Design**: Implemented `LayoutBuilder` and screen width checks to dynamically switch between Desktop (Sidebar) and Mobile (Drawer) layouts.
*   **Components**: Created reusable widgets for Post Cards, Live Stream Cards, and Buttons to maintain design consistency.

### 3. Feature Implementation

#### Authentication
*   Designed a Login Page with form validation.
*   Prepared the structure for integrating Firebase Auth or other providers.

#### Social Feed
*   Built a scrollable list view to display posts.
*   Implemented a category filter system.
*   Added a responsive sidebar/drawer for navigation.

#### Live Streaming
*   Developed a `LiveStreamPage` with a video player placeholder.
*   Added an overlay for live chat and interaction buttons (Like, Share).
*   Ensured the layout adjusts correctly for full-screen viewing.

### 4. Deployment
*   Built the web version using `flutter build web`.
*   Deployed the application to Firebase Hosting for high performance and global availability.

---
*Note: This repository serves as a documentation and demo overview. The source code is not included.*

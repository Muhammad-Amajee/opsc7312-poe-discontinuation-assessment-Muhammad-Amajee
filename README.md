Event Buddy App

Name: Muhammad

Surname: Amajee

Student Number: ST10117234

GitHub Repo Link: 

OneDrive Project Link: 

Youtube Video Link: https://youtu.be/61CBP3WYmlQ

EventBuddy - Event Management App

Table of Contents

Features
Getting Started
App Demonstration
Usage
REST API
Testing
Design Considerations
Contributing
Documentation
Publishing
Submission
Contact Information
Features

Single Sign-On (SSO) Allows users to register and log in via a secure SSO service, providing easy access and enhanced security. Biometric Authentication Implements fingerprint or facial recognition for secure user authentication.

User Settings

Users can update personal settings, including preferences related to notifications, language, and themes.

REST API Integration

Connects to a REST API managing event data in a backend database, supporting real-time data retrieval and updating.

Offline Mode with Sync

Allows users to perform actions offline with synchronization capabilities once reconnected.

Real-time Notifications

Implements a push notification system for real-time updates and alerts.

Multi-language Support

Supports at least 2 South African languages.

Automated Testing & GitHub Actions

Automated build and test processes ensure continuous integration and quality, utilizing GitHub Actions to automate testing workflows.

App Icon and Final Image Assets

Features a user-friendly app icon and final image assets for a professional appearance.

User-Defined Features:

➢ Customizable Event Reminders: Users will have the ability to set reminders for events at customizable intervals, ensuring they never miss an important moment.

➢ Cross-Platform Syncing: EventBuddy will offer seamless syncing across multiple devices, ensuring users can access their event data wherever they go

Getting Started

Prerequisites

Android Studio
Kotlin
Git
API Hosting (e.g., Firebase, AWS)
Installation

Clone the Repository: git clone https://github.com/VCDN-2024/opsc7312-part-2-Muhammad-Amajee.git

Open in Android Studio: Launch Android Studio and open the project folder.

Set Up Dependencies: Sync the project with Gradle to download the required dependencies.

Run the App: Use a physical Android device to run the app and test its functionalities.

App Demonstration A comprehensive demo video showcases the app's working features, including:

Registering and logging in via SSO.
Implementing biometric authentication.
Changing user settings.
Connecting to the REST API and managing data.
Offline mode with synchronization.
Real-time notifications.
Multi-language support.
Usage

Registration & Login

Navigate to the login screen to sign in via SSO or use biometric authentication.

Settings Management

Update user preferences in the settings menu.

Events

View, create, and manage events synced with the REST API. Perform actions offline with automatic synchronization.

REST API

The REST API handles:

Event Data: CRUD operations for event-related information (create, read, update, delete).
User Data: Management of user profiles and settings.
Testing

Automated tests are integrated via GitHub Actions to ensure key functionalities work across different environments:

Unit Tests
Integration Tests
Design Considerations

User Interface: Ease of use with input validation and error handling.
Scalability: Modular architecture allows for future updates.
Security: User data is securely managed via SSO and biometric authentication.
Contributing

If you'd like to contribute, open a pull request or file an issue. All contributions are welcome!

Event Buddy Release Notes

Version 1.0.0 - Initial Release

Release Date: November 4, 2024

Overview The initial release of Event Buddy introduces a comprehensive event management application with key features that enhance user experience, security, and accessibility. This release allows users to manage event-related tasks, receive real-time updates, and personalize their settings through a user-friendly interface.

Features

User Authentication

Single Sign-On (SSO): Secure user registration and login with SSO support for streamlined access.
Biometric Authentication: Optional fingerprint and facial recognition provide an additional layer of security.
Settings Management

Allows users to modify their preferences, including notification settings and language selection.
Event Management and Tracking

Users can view, track, and manage events using a connected REST API, which synchronizes data with a central database.
Offline Mode with Synchronization

Users can access and update event information while offline, with automatic synchronization when back online.
Real-Time Notifications

Push notifications provide timely alerts for updates, reminders, and important announcements related to the user's events.
Multi-Language Support

Available in multiple South African languages to support a wider range of users.
User-Defined Features:

➢ Customizable Event Reminders: Users will have the ability to set reminders for events at customizable intervals, ensuring they never miss an important moment.

➢ Cross-Platform Syncing: EventBuddy will offer seamless syncing across multiple devices, ensuring users can access their event data wherever they go

Improvements

Enhanced UI/UX
User-friendly interface with consistent design, intuitive navigation, and visual elements for ease of use.
Error Handling
Improved error handling ensures smooth operation and prevents crashes due to invalid input or connectivity issues.
Technical Enhancements

GitHub Actions Integration
Automated CI/CD pipeline set up with GitHub Actions for continuous integration and automated testing.
REST API and Database Setup
REST API connects seamlessly to a database for secure and efficient data handling.
Logging
Logging implemented for tracking key app events and debugging.
Known Issues

Occasional Delays in Notification Delivery
Notifications may experience minor delays due to server sync times.
Limited Multi-Language Support
Initial release includes two South African languages; additional languages will be added in future releases.
Next Steps For future versions, we plan to:

Expand multi-language support to more South African languages.
Add event-sharing functionality for easier collaboration.
Improve offline sync times and optimize server connections for real-time updates.
These release notes outline the initial release features, improvements, technical details, known issues, and planned updates. Contact developer if you’d like more details on any section!

Contact Information

Developer: Muhammad Amajee

Email: ST10117234@vcconnect.edu.za

# EventBuddy - Event Management App

## Author Information
**Name:** Muhammad Amajee  
**Student Number:** ST10117234  

## Project Links
- **GitHub Repository:** [Click Here To Open Repo](https://github.com/Muhammad-Amajee/opsc7312-poe-discontinuation-assessment-Muhammad-Amajee)
- **OneDrive:** [Click Here To Download Project Files](https://onedrive.live.com/?cid=6E2099341517F389&id=6E2099341517F389%21sea0e69d1e12547fcaf6e917bf6dfd447&parId=root&o=OneUp)
- **YouTube Video Demonstration:** [Click Here To View Demo Video](https://youtu.be/61CBP3WYmlQ)

---

## Table of Contents
1. [Features](#features)
2. [Getting Started](#getting-started)
3. [App Demonstration](#app-demonstration)
4. [Usage](#usage)
5. [REST API](#rest-api)
6. [Testing](#testing)
7. [Design Considerations](#design-considerations)
8. [Contributing](#contributing)
9. [Release Notes](#release-notes)
10. [Known Issues](#known-issues)
11. [Future Improvements](#future-improvements)
12. [Contact Information](#contact-information)

---

## Features
Single Sign-On (SSO)
> Allows users to register and log in via a secure SSO service, providing easy access and enhanced security.

Biometric Authentication 
> Implements fingerprint or facial recognition for secure user authentication.

User Settings
> Users can update personal settings, including preferences related to notifications, language, and themes.

REST API Integration
> Connects to a REST API managing event data in a backend database, supporting real-time data retrieval and updating.

Offline Mode with Sync
> Allows users to perform actions offline with synchronization capabilities once reconnected.

Real-time Notifications
> Implements a push notification system for real-time updates and alerts.

Multi-language Support
> Supports at least 2 South African languages.

Automated Testing & GitHub Actions
> Automated build and test processes ensure continuous integration and quality, utilizing GitHub Actions to automate testing workflows.

App Icon and Final Image Assets
> Features a user-friendly app icon and final image assets for a professional appearance.

---

## User-Defined Features

Customizable Event Reminders
> Users will have the ability to set reminders for events at customizable intervals, ensuring they never miss an important moment.

Cross-Platform Syncing
> EventBuddy will offer seamless syncing across multiple devices, ensuring users can access their event data wherever they go.

---

## Getting Started

### Prerequisites
- Android Studio
- Kotlin
- Git
- API Hosting (e.g., Firebase, AWS)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Muhammad-Amajee/opsc7312-poe-discontinuation-assessment-Muhammad-Amajee.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle to install dependencies.
4. Run the app on a physical or virtual Android device.

---

## App Demonstration
A comprehensive demo video is available showcasing:
- User authentication (SSO & Biometric Login)
- Settings configuration
- Event creation & management
- REST API integration
- Offline mode with sync
- Real-time notifications
- Multi-language support

[Click Here To Watch The Demo](https://youtu.be/61CBP3WYmlQ)

---

## Usage
### Registration & Login
- Sign in via SSO or biometric authentication.

### Settings Management
- Update notification, theme, and language preferences.

### Event Management
- Create, edit, and delete events with REST API integration.
- Perform actions offline with automatic sync upon reconnection.

---

## REST API
Handles:
- **Event Data:** CRUD operations for event management.
- **User Data:** Profile settings and authentication management.

---

## Testing
Automated testing using GitHub Actions:
- **Unit Tests**
- **Integration Tests**

---

## Design Considerations
- **User Interface:** Intuitive and user-friendly design.
- **Scalability:** Modular architecture for future enhancements.
- **Security:** Secure authentication via SSO and biometric authentication.

---

## Contributing
Contributions are welcome! Open a pull request or send an email.

---

## Release Notes

### Version 1.0.0 - Initial Release (November 4, 2024)

## Overview
The initial release of Event Buddy introduces a comprehensive event management application with key features that enhance user experience, security, and accessibility. This release allows users to manage event-related tasks, receive real-time updates, and personalize their settings through a user-friendly interface.

## Features
1. User Authentication 
   - Single Sign-On (SSO): Secure user registration and login with SSO support for streamlined access.
   - Biometric Authentication: Optional fingerprint and facial recognition provide an additional layer of security.

2. Settings Management 
   - Allows users to modify their preferences, including notification settings and language selection.

3. Event Management and Tracking  
   - Users can view, track, and manage events using a connected REST API, which synchronizes data with a central database.

4. Offline Mode with Synchronization  
   - Users can access and update event information while offline, with automatic synchronization when back online.

5. Real-Time Notifications 
   - Push notifications provide timely alerts for updates, reminders, and important announcements related to the user's events.

6. Multi-Language Support 
   - Available in multiple South African languages to support a wider range of users.

---

## User-Defined Features

1. Customizable Event Reminders
   - Users will have the ability to set reminders for events at customizable intervals, ensuring they never miss an important moment.

2. Cross-Platform Syncing
   - EventBuddy will offer seamless syncing across multiple devices, ensuring users can access their event data wherever they go

---

## Improvements
> Enhanced UI/UX 
   - User-friendly interface with consistent design, intuitive navigation, and visual elements for ease of use.

Error Handling 
   - Improved error handling ensures smooth operation and prevents crashes due to invalid input or connectivity issues.

---

## Technical Enhancements
GitHub Actions Integration
   - Automated CI/CD pipeline set up with GitHub Actions for continuous integration and automated testing.

REST API and Database Setup
   - REST API connects seamlessly to a database for secure and efficient data handling.

Logging  
   - Logging implemented for tracking key app events and debugging.

---

## Known Issues
Occasional Delays in Notification Delivery  
   - Notifications may experience minor delays due to server sync times.

Limited Multi-Language Support  
   - Initial release includes two South African languages; additional languages will be added in future releases.

---

## Next Steps
For future versions, we plan to:
1. Expand multi-language support to more South African languages.
2. Add event-sharing functionality for easier collaboration.
3. Improve offline sync times and optimize server connections for real-time updates.
   
These release notes outline the initial release features, improvements, technical details, known issues, and planned updates. Contact developer if you’d like more details on any section!

---

## Contact Information
**Developer:** Muhammad Amajee  
**Email:** ST10117234@vcconnect.edu.za


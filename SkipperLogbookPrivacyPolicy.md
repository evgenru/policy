# Privacy Policy — Skipper Logbook

*Last updated: April 26, 2026*

## 1. Introduction

This Privacy Policy describes how Skipper Logbook ("we", "our", or "the app") collects, uses, and shares information when you use our mobile application.

By using Skipper Logbook, you agree to the collection and use of information in accordance with this policy.

## 2. Information We Collect

### 2.1 Account Information
When you sign up for an account, we collect:
- Email address (via Firebase Authentication)
- Profile display name (if you choose to provide one)
- Google account ID (if you sign in with Google)

### 2.2 Location Data
- **Precise GPS location**: We collect precise GPS coordinates when you actively record a sailing track or log an entry. This happens only when the app is in the foreground and tracking is enabled.
- **Background location**: With your explicit permission, we may collect location data in the background to continue tracking your position even when the app is not visible on screen. This is required for continuous voyage logging and anchor alarm functionality.
- **Location is never collected when tracking is disabled.**

### 2.3 Sailing Log Data
We store the data you enter into the app, including:
- Log entries (date, time, position, course, speed, weather conditions, engine hours, fuel level, and other nautical observations)
- Waypoints and routes
- GPS track records (recorded positions with timestamps)
- Sailboat information (vessel name, dimensions, engine details)
- Crew member names
- Engine log entries
- Service records and notes
- Equipment inventory
- Anchor alarm settings
- Seasonal log summaries
- MOB (Man Overboard) records

### 2.4 Automatically Collected Data
- Device model and operating system version (for crash reporting via Firebase Crashlytics)
- App usage statistics (via Firebase Analytics, anonymized)
- Crash logs and error reports

## 3. How We Use Your Information

We use the collected information exclusively for:
- Providing the yacht logbook functionality (recording, storing, and displaying your sailing data)
- Synchronizing your data across devices via Firebase Firestore
- Authenticating your account
- Improving app stability through crash reporting
- Sending location-based notifications (anchor alarm, waypoint arrival) — only if enabled

We **do not** use your data for advertising, marketing, or profiling.

## 4. Data Storage and Synchronization

### 4.1 Local Storage
All your logbook data is stored locally on your device using a local database (SQLDelight) and file-based storage. The app functions with full core features even without an internet connection.

### 4.2 Cloud Synchronization
When you sign in, your data is synchronized with Firebase Firestore (Google Cloud Platform, servers in the United States). This enables:
- Data backup to the cloud
- Synchronization across multiple devices

You can disable cloud synchronization at any time in the app settings.

## 5. Third-Party Services

We use the following third-party services:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Firebase (Google)** | Authentication, Firestore database, Crashlytics, Analytics | Email, device info, crash logs, app data |
| **MapLibre** | Map rendering | GPS position (processed locally) |

Firebase operates under Google's Privacy Policy: https://policies.google.com/privacy

## 6. Data Security

We implement appropriate security measures:
- All data transmitted to Firebase is encrypted in transit via HTTPS/TLS
- Firebase Firestore data is encrypted at rest
- Authentication is handled by Firebase Auth with industry-standard OAuth 2.0
- GPS location data is never transmitted to any server other than Firebase

## 7. Your Rights and Choices

You have the right to:
- **Access** your data within the app at any time
- **Export** your data via GPX/KML export functionality
- **Delete** individual log entries or entire logs from within the app
- **Delete your account** and all associated data by contacting us
- **Disable cloud sync** to keep data only on your device
- **Revoke location permissions** at any time via system settings (some features may be limited)
- **Request full data deletion** from our servers by email

## 8. Data Retention

We retain your data for as long as your account is active. If you delete your account, we delete all associated data from Firebase servers within 30 days. Locally stored data must be deleted by uninstalling the app or clearing app data from system settings.

## 9. Children's Privacy

This app is not intended for children under 13. We do not knowingly collect data from children.

## 10. Changes to This Policy

We may update this Privacy Policy. We will notify you of changes by posting the new policy in the app and updating the "Last updated" date.

## 11. Contact

For questions, data access, or deletion requests:

- **Email**: petrodox@gmail.com

## 12. Consent

By using Skipper Logbook, you consent to this Privacy Policy. If you do not agree, please discontinue use of the app.

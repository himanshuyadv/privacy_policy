# Privacy Policy

**Effective Date:** October 14, 2026
**App Name:** Power Button
**Package Name:** `com.powerbuttonxml`
**Developer:** Himanshu / Power Button XML

---

## 1. Introduction
Welcome to **Power Button** ("we", "our", or "us"). We are committed to protecting your privacy and ensuring that your personal information is handled in a safe and responsible manner.

This Privacy Policy explains how our Android application (`com.powerbuttonxml`) collects, uses, discloses, and safeguards your information when you use our app. Please read this privacy policy carefully. If you do not agree with the terms of this privacy policy, please do not use the application.

---

## 2. Information We Collect
We respect your privacy and design our app to collect the minimum amount of data necessary to provide and improve our core functionality.

### A. Non-Personal Information & Diagnostics
- **Crash Reports & Diagnostics:** We use **Firebase Crashlytics** to collect anonymous crash reports, stack traces, and app performance data when the app encounters an error. This helps us diagnose bugs and improve app stability.
- **Analytics:** We use **Google Analytics for Firebase** to collect anonymous usage statistics (such as app session duration and feature interaction frequency) to understand how users interact with the app.

### B. Advertising Data (Google AdMob)
Our app displays advertisements provided by **Google AdMob**. AdMob may collect and use certain data to serve relevant ads, including:
- Advertising ID (AD_ID)
- IP address
- Device and network information
- Ad interaction data

In compliance with regional regulations (such as GDPR and CCPA), we use the **Google User Messaging Platform (UMP)** SDK to obtain user consent for personalized ads where required.

### C. What We Do NOT Collect
We do **NOT** collect:
- Personally Identifiable Information (PII) such as your name, email address, phone number, or physical address.
- Sensitive user data, passwords, financial information, or contacts.
- Photos, media, audio recordings, or location data.

---

## 3. Use of Accessibility Service
**Power Button** uses the Android **Accessibility Service API** (`AccessibilityService`) strictly to provide its core functionality.

- **Purpose:** The Accessibility Service is used solely to detect power button actions and device state changes to perform custom user-configured actions (such as turning off the screen, opening the power menu, or adjusting volume).
- **Data Privacy & Accessibility Compliance:**
  - We **never** use the Accessibility Service to collect, store, or share any personal or sensitive user data.
  - We **never** monitor user input, capture keystrokes, read sensitive text on screen, or bypass any Android privacy controls.
  - The accessibility features operate entirely on your device and are governed strictly by your explicit configuration within the app.

---

## 4. Permissions Explained
Our app requests certain Android permissions to function correctly:
- `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_SPECIAL_USE`: Required to keep the background service active so it can reliably listen for button presses and user commands.
- `RECEIVE_BOOT_COMPLETED`: Allows the app to restart its service automatically when your device reboots.
- `WAKE_LOCK`: Keeps the CPU running when necessary to process power button actions.
- `POST_NOTIFICATIONS`: Allows us to display status/foreground service notifications required by Android.
- `AD_ID`: Used by Google AdMob for advertising and analytics.

---

## 5. Third-Party Services
We integrate reputable third-party services that may collect information in accordance with their own privacy policies:
- **Google AdMob & UMP:** [Google Privacy Policy](https://policies.google.com/privacy)
- **Firebase Crashlytics & Analytics:** [Firebase Privacy Policy](https://firebase.google.com/support/privacy)

---

## 6. Children's Privacy
Our app is not directed to children under the age of 13 (or higher depending on local jurisdiction). We do not knowingly collect personal information from children. If you believe we have inadvertently collected information from a child, please contact us so we can promptly remove it.

---

## 7. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated effective date. You are advised to review this Privacy Policy periodically for any changes.

---

## 8. Contact Us
If you have any questions, concerns, or suggestions regarding this Privacy Policy or our privacy practices, please contact us at:

- **Developer / Support Email:** support@powerbuttonxml.com *(or your contact email)*
- **App Package Name:** `com.powerbuttonxml`

# Privacy Policy

**Last Updated: June 6, 2026**

This Privacy Policy explains how the developer ("we", "us", or "our") collects, uses, manages, and protects your information when you use the MichiLog application (the "App").

---

## 1. Information We Collect and How We Collect It

The App collects the following information to provide, improve our services, and deliver advertisements.

### 1.1 Account Information
When you create an account and sign in, we collect and authenticate the following information (using Supabase Auth):
* Email address, password
* Display name, email address, and provider-specific identifiers when using social sign-in (e.g., Apple, Google)

### 1.2 Location Information (GPS Data)
To provide the App's core feature, "recording and mapping your touring/driving routes," we collect location data:
* **Background Location**: Once you start recording a trip, the App continuously collects your location data (latitude, longitude, altitude, speed, and timestamp) even when the App is in the background or your device is locked.
* We do not collect background location data when trip recording is inactive or stopped.

### 1.3 User Content
We collect data you voluntarily enter or upload to customize your trip logs:
* Route logs (path coordinates)
* Title, notes, dates, and times
* Photos/images uploaded to the trip log (stored in Firebase Storage, etc.)

### 1.4 Ad and Analytics Information
The App utilizes external SDKs for ad delivery (Google AdMob) and crash analysis/performance monitoring, which may automatically collect:
* **Device Identifiers**: Advertising ID (IDFA / AAID), IP address
* **Usage & Error Logs**: Crash reports (Firebase Crashlytics), device model name, OS version, and basic in-app interaction events

On iOS, we request tracking permission via the App Tracking Transparency (ATT) framework. If you decline, the App will still function but will show non-personalized ads.

---

## 2. Use of Information

We use the collected information only for the following purposes:

* Account authentication and management
* Providing background location tracking and trip route mapping
* Synchronizing local offline data with our cloud servers (PowerSync / Supabase)
* Storing and displaying photos attached to your trip logs
* Delivering and optimizing advertisements
* Analyzing crash logs, improving App performance, and responding to support inquiries

---

## 3. Sharing and Third-Party Disclosure

We do not disclose or sell your personal information to third parties, except in the following cases:

* **Service Providers**: We use trusted third-party services to host our backend infrastructure and provide services. These providers process information in accordance with their own privacy policies:
  * [Supabase](https://supabase.com/privacy) (Authentication & Database)
  * [PowerSync](https://www.powersync.com/privacy-policy) (Data Synchronization)
  * [Google Firebase / Storage / Crashlytics](https://firebase.google.com/support/privacy) (File Storage & Analytics)
  * [Google AdMob](https://policies.google.com/privacy) (Ad Delivery)
* **Legal Requirements**: When required by law, regulations, or legal processes to disclose information.

---

## 4. Data Security and Retention

* Your data is stored on secure cloud servers managed by Supabase and Google Firebase.
* All communications between the App and the servers are encrypted using HTTPS/TLS.
* You can delete your account and all associated personal data at any time via the settings menu in the App.

---

## 5. Children's Privacy

The App does not knowingly collect personal information from children under the age of 13. If we discover that a child under 13 has provided us with personal information, we will immediately delete it from our servers.

---

## 6. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When changes are made, we will update the "Last Updated" date at the top of this page.

---

## 7. Contact Us

If you have any questions or inquiries regarding this Privacy Policy or our data practices, please contact us at:

* **Email**: k.lifetime.app+michilog-support@gmail.com

---
*This Privacy Policy was originally written in Japanese.*

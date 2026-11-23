# Privacy Policy for LoopCalm

**Last Updated:** November 23, 2026  
**Effective Date:** November 23, 2026  
**Application Name:** LoopCalm (LoopCalm: Anti Stress Puzzle)  
**Package Name / App ID:** `com.playsphere.loopcalm`  
**Developer / Publisher:** PlaySphere  
**Contact Email:** [allgames9e@gmail.com](mailto:allgames9e@gmail.com)  

---

## 1. Introduction & Overview

Welcome to **LoopCalm** ("we," "our," "us," or the "Game"). We respect your privacy and are committed to protecting any information associated with your use of our mobile and web application.

This Privacy Policy explains in complete detail what information we collect, how it is used, how it is stored, your privacy rights, and the measures we take to ensure your data remains safe and confidential. 

LoopCalm is designed as a mindful, relaxing, offline-first puzzle experience. Our fundamental privacy principle is simple: **we do not collect, request, or store any Personally Identifiable Information (PII) such as your real name, physical address, email address, phone number, contacts, microphone, camera, or precise GPS location.**

By downloading, installing, accessing, or playing LoopCalm, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with this policy, please do not use the application.

---

## 2. Information We Collect and Process

We divide the data handled by LoopCalm into three clear categories:

### A. Data Stored Locally on Your Device (Client-Side Storage)
To deliver a smooth and uninterrupted gaming experience, certain gameplay states and preferences are stored exclusively on your device using HTML5 LocalStorage and device storage:
- **Game Progress & Levels:** Solved puzzles count, current level index, and completed loops in both **Loop Mode** (closed loops) and **Void Mode** (disconnected lines).
- **Player Preferences:** Sound effects volume, ambient soundtrack toggles, active harmonic sound styles (e.g., Zen Tibetan, Crystal Kalimba, Ethereal Bell), and preferred color palettes/themes.
- **Achievements & Stars:** In-game star count and completion metrics.
- **Anonymous Device ID:** A randomly generated, pseudonymous UUID string (`loopcalm_device_id`) generated locally upon the first launch. This identifier contains no hardware identifiers (such as IMEI or MAC address) and serves exclusively to distinguish anonymous leaderboard entries.

*Note: All local gameplay data remains on your device and is erased if you choose "Reset Progress" within the game or clear the application cache/data in your Android system settings.*

### B. Information Processed by Cloud Services (Leaderboard & Remote Config)
If your device is connected to the internet, our cloud backend (powered by Supabase) may process:
- **Leaderboard Records:**
  - Player Nickname: A custom display name chosen voluntarily by the player (we strictly advise players not to use real names or personal identifiers).
  - Score & Progress: Star count, total puzzles solved, and current level.
  - Anonymous Device UUID: Used to associate the score with your session without identifying you personally.
  - Timestamp: The date and time of score submission.
- **Remote Configuration:** Periodic checks to fetch game configurations, announcements, and policy updates (such as "How to Play" tutorials or updated support links).

### C. Information Collected Automatically by Third Parties (Advertisements & Technical Diagnostics)
When using the app with an active internet connection, third-party advertising partners (Google AdMob) and diagnostic services may automatically collect standard mobile device data, including:
- **Advertising Identifiers:** Google Advertising ID (AAID / GAID) on Android devices.
- **Device & Technical Data:** Device manufacturer, hardware model, operating system version, screen resolution, carrier, and general language settings.
- **Network Information:** Coarse location data inferred from your IP address (e.g., country or region level, never precise GPS coordinates).
- **Ad Interaction Data:** Number of ads displayed, ad impressions, clicks, video completion rates, and crash or performance diagnostics.

---

## 3. What We DO NOT Collect (Zero-PII Guarantee)

We believe in radical data minimization. LoopCalm explicitly **DOES NOT**:
- ❌ Require account registration, passwords, or social media logins (Google Sign-In, Facebook, Apple ID).
- ❌ Request or access your phone contacts, address book, or call logs.
- ❌ Access your camera, microphone, or audio recording hardware.
- ❌ Access your photo gallery, media files, or internal document storage (beyond sandboxed app cache).
- ❌ Track or request your precise GPS or Bluetooth geolocation.
- ❌ Collect payment or financial information (the game does not process direct payments or credit cards).
- ❌ Read hardware biometric data or permanent hardware serial numbers (IMEI, MEID, or MAC addresses).

---

## 4. Permissions Requested & Justification

LoopCalm requires only the minimal permissions necessary for core functionality and ad delivery. These are declared in the Android Manifest:

| Permission | Technical Name | Purpose & Justification |
| :--- | :--- | :--- |
| **Internet Access** | `android.permission.INTERNET` | Required to communicate with cloud servers for global leaderboard rankings, remote game policy updates, and displaying advertisements via Google AdMob. |
| **Network State** | `android.permission.ACCESS_NETWORK_STATE` | Allows the application to detect whether an active Wi-Fi or cellular connection exists before attempting network operations, preventing crashes and saving battery life. |

*No high-risk, sensitive, or runtime permissions (such as Location, Camera, Contacts, or Storage) are requested.*

---

## 5. Third-Party Services & SDK Integrations

We partner with industry-standard third-party service providers who assist in app distribution, cloud synchronization, and ad monetization. These providers have their own privacy policies governing their collection and handling of data:

### 1. Google AdMob (Google LLC)
- **Role:** Displaying in-game banner ads, interstitial transitions, rewarded ads, and app open ads.
- **Data Processed:** Google Advertising ID (AAID), IP address (for regional routing and fraud prevention), device specifications, and ad performance logs.
- **Ad Personalization:** Depending on your jurisdiction and consent choices, ads may be personalized (interest-based) or non-personalized (contextual).
- **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Google Ad Technologies:** [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
- **Google Partners Policy:** [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)

### 2. Supabase (Supabase, Inc.)
- **Role:** Cloud database provider for leaderboard scores and remote game configuration policies.
- **Data Processed:** Anonymous player nickname, game score, level count, anonymous device UUID, and timestamp.
- **Security:** Communications are encrypted via TLS/HTTPS, and data is protected by strict database Row-Level Security (RLS) policies.
- **Supabase Privacy Policy:** [https://supabase.com/privacy](https://supabase.com/privacy)

### 3. Google Play Services (Google LLC)
- **Role:** Providing base Android OS runtime services, app integrity, and updates.
- **Google Play Services Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

## 6. Children's Privacy (COPPA & Family Policy Compliance)

LoopCalm is an all-ages, family-friendly casual geometric puzzle game.

- **COPPA (Children’s Online Privacy Protection Act):** We strictly adhere to COPPA guidelines. We do not knowingly collect, solicit, or maintain personal information from children under the age of 13 (or under 16 in the European Union).
- **No PII Requested:** The game does not require personal details or account creation.
- **Parental Inquiries & Deletion:** If you are a parent or legal guardian and believe that your child has submitted any information (e.g., a leaderboard nickname) or you wish to request deletion of any pseudonymous record, please contact us immediately at [allgames9e@gmail.com](mailto:allgames9e@gmail.com). Upon verification, we will promptly delete the data from our active databases.

---

## 7. Legal Bases for Data Processing (GDPR / UK GDPR Compliance)

If you are a resident of the European Economic Area (EEA) or the United Kingdom, our processing of your pseudonymous data is governed by the following legal bases under the General Data Protection Regulation (GDPR):
1. **Legitimate Interests:** Processing anonymous device identifiers, gameplay scores, and basic telemetry is necessary for our legitimate interests in maintaining, securing, optimizing, and operating the game.
2. **Consent:** Where required by law (such as for personalized advertising and the access of identifiers on your device), we rely on your explicit consent obtained via the User Messaging Platform (UMP) or Google consent dialogs. You may withdraw or adjust your consent at any time through your Android device settings.

### Your GDPR Rights:
Under GDPR, you have the right to:
- **Access:** Request confirmation of whether we hold data related to your anonymous device ID.
- **Rectification:** Request correction of inaccurate information.
- **Erasure ("Right to be Forgotten"):** Request the deletion of your leaderboard entries and associated pseudonymous identifier.
- **Restriction of Processing:** Request limitation of data processing under certain conditions.
- **Data Portability:** Request a copy of your score data in a machine-readable format.
- **Object / Withdraw Consent:** Opt-out of personalized advertisements at any time.

To exercise any of these rights, contact our Data Protection representative at [allgames9e@gmail.com](mailto:allgames9e@gmail.com).

---

## 8. California Consumer Privacy Rights (CCPA / CPRA Compliance)

If you are a California resident, the California Consumer Privacy Act (CCPA) as amended by the California Privacy Rights Act (CPRA) grants you specific rights:
- **Right to Know / Access:** You have the right to request information regarding the categories and specific pieces of personal information collected, the sources, and the business purpose for collection.
- **Right to Delete:** You have the right to request deletion of personal information collected from you.
- **Right to Opt-Out of Sale or Sharing:** We do not sell personal information for monetary value. However, the sharing of advertising identifiers with third-party ad networks (like Google AdMob) for cross-context behavioral advertising may be considered a "sale" or "share" under California law. You can opt out at any time by configuring your device settings (see Section 10).
- **Right to Non-Discrimination:** We will not discriminate against you (e.g., by denying access to gameplay or charging different rates) for exercising your CCPA rights.

---

## 9. Data Retention and Security

### Data Retention:
- **Local Device Data:** Retained until you manually uninstall the game, clear application storage, or tap "Reset Progress" in the settings drawer.
- **Cloud Leaderboard Data:** Anonymous scores and nicknames are retained for as long as the leaderboard feature is active. Inactive records may be purged periodically.
- **Ad Analytics Logs:** Maintained by Google AdMob according to their standard data retention schedules (typically aggregated and anonymized within 9 to 18 months).

### Security Measures:
We implement standard security safeguards to protect data:
- All data transmission between the app and backend services uses industry-standard Transport Layer Security (TLS/HTTPS).
- Supabase database access is restricted using secure API keys and Row-Level Security (RLS) policies.
- No sensitive user credentials or unencrypted secrets are stored on the client.

*Please note: While we follow commercially accepted standards to protect data, no method of transmission over the internet or electronic storage is 100% secure.*

---

## 10. Managing Your Privacy & Opt-Out Options

You maintain full control over your data while playing LoopCalm:

### A. Resetting or Deleting In-Game Data
1. Open **LoopCalm**.
2. Tap the **Settings** icon on the top right.
3. Scroll down and tap **Reset Progress**. Confirm your choice to permanently erase all locally stored levels, stars, and theme unlocks.
4. Alternatively, open your phone's **Android Settings > Apps > LoopCalm > Storage > Clear Storage / Clear Cache**.

### B. Opting Out of Personalized Advertisements
You can prevent Google AdMob and ad networks from serving interest-based ads by disabling ad personalization on your Android device:
1. Open your Android device **Settings**.
2. Navigate to **Google > All Services > Ads** (or **Privacy > Ads** depending on your OS version).
3. Tap **Reset Advertising ID** or select **Delete Advertising ID**.
4. Enable **Opt out of Ads Personalization** (if available on your Android version).
*Note: You will still see advertisements in the game, but they will be contextual rather than tailored to your interests.*

### C. Requesting Leaderboard Record Removal
To request the complete deletion of your nickname, score, or device UUID from our cloud leaderboard:
- Email us at: [allgames9e@gmail.com](mailto:allgames9e@gmail.com)
- Subject: `Data Deletion Request - LoopCalm`
- Provide your in-game player nickname and approximate date/score or your `loopcalm_device_id` (accessible via app settings/logs). We will fulfill verified requests within 30 days.

---

## 11. Google Play Data Safety Summary

For full transparency, here is how LoopCalm maps to the **Google Play Data Safety Form**:

| Data Type | Collected? | Shared? | Purpose | Optional / Required |
| :--- | :--- | :--- | :--- | :--- |
| **Name / Email / Phone / Address** | **No** | **No** | N/A | N/A |
| **Precise Location** | **No** | **No** | N/A | N/A |
| **Coarse Location (City/Country level)** | Inferred via IP by AdMob | Yes (with AdMob) | Advertising & Fraud Prevention | Automatic |
| **User IDs (Anonymous Device UUID)** | Yes | Yes (Leaderboard & Cloud sync) | App Functionality & Analytics | Optional / Gameplay |
| **Device or other IDs (Advertising ID / AAID)** | Yes | Yes (with Google AdMob) | Advertising, Monetization, Analytics | Automatic / Manageable via Android settings |
| **App Performance & Crash Logs** | Diagnostic telemetry | Yes (Diagnostics) | App Functionality & Bug Fixing | Automatic |
| **Financial / Payment Information** | **No** | **No** | N/A | N/A |
| **Photos / Videos / Files** | **No** | **No** | N/A | N/A |

- **Data Encrypted in Transit:** Yes (HTTPS / TLS 1.3)
- **Data Deletion Mechanism Provided:** Yes (via in-app reset and developer email contact)

---

## 12. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect changes in our operational practices, new features, or updated legal requirements. Any modifications will be posted directly within this document with a refreshed "Last Updated" date at the top.

We encourage you to review this Privacy Policy periodically. Substantial changes will be highlighted through in-game notices or updated remote policy alerts.

---

## 13. Contact Information & Support

If you have any questions, suggestions, legal concerns, or data deletion requests regarding this Privacy Policy or our practices, please contact our dedicated support team:

- **Official Support & Privacy Email:** [allgames9e@gmail.com](mailto:allgames9e@gmail.com)
- **Developer / Publisher:** PlaySphere
- **Response Commitment:** We aim to respond to all inquiries and privacy requests within 24 to 48 business hours.

---
*By enjoying LoopCalm, you entrust us with creating a peaceful, relaxing experience. We honor that trust by keeping your personal data completely private and protected.*

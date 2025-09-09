# Privacy-Policy
KidNotifier Parental App

Privacy policy ( KidNotifier App) 



KidNotifier is a dual-mode parental control application designed to help parents monitor notifications received on their child’s device. 

This Privacy Policy explains what information we collect from both Child and Parent versions of the app, how it is used, and the rights you have as a user.

Your privacy is very important to us. This application, KidNotifier Parental App, is designed to help parents stay informed about their child’s phone activity with full consent and transparency. This Privacy Policy explains how we collect, use, and protect your information.

Information We Collect

This app may collect the following data from the child’s device, only after explicit permission:

Type of Data Description

Notification Content App name, title, message content (e.g. WhatsApp, Instagram)

App List Installed app names (for filter control)

Purpose of Data Collection

We collect data for the following purposes:

To enable real-time notification sharing with the parent

To help parents understand their child’s phone usage patterns

To support features like app filters, battery status, network connection status. 

We do not collect personal files, media, or passwords.


Data Security

All data is transmitted over secure SSL (HTTPS).

Data is stored in Firebase Realtime Database, protected by Google-grade security.

No third-party sharing, sale, or misuse of data is allowed.

Users (child & parent) both may delete their data anytime from within the app.


User Consent

The app explicitly asks for user consent before uploading any data.

Only parents who know the child’s Unique ID (UID) can access their data.

The child can stop sharing or delete data anytime by using the In App "Delete Data" Botton
 
All permissions are declared and used in accordance with Google Play policies.

We Do NOT:

Spy on users silently

Record audio/video

Access personal media or passwords

Sell or share data with advertisers, 

Data Retention & Deletion

Data is retained only as long as required for the parent to view it.

Parents or children can delete all data by clicking “Delete Data” inside the app.


Children’s Privacy

This app is intended to be used by parents only, with the child’s informed consent.
We do not market to or collect data directly from children under 13 without guardian permission.


( CHILD MODE ) 

Information We Collect

The child Mode collects the following data:

App name and package name that generated the notification

Notification title and message content

Timestamp of the notification

We generate a random unique sync ID (UID) on the child’s device to organize notification data in Firebase. This UID is not linked to any user login or device ID. It is created locally and used solely for syncing with the parent device.We do not collect phone numbers, contact lists, email addresses, precise location, media files, or other personal identifiers.

2.Why We Collect This

Information this data is collected for parental monitoring purposes only, allowing parents to view and analyze the types of notifications the child receives.

3. How Data Is Stored


All data is securely stored in Firebase Realtime Database and is accessible only to the parent who enters or scans the matching UID. We do not store data on third-party servers.


4. Permissions Required

To function correctly, the child app requuests:

Notification Access – to read incoming notifications

Internet Access – to sync data to Firebase

the device's battery status and internet connectivity. 


Battery Optimization Exclusion – to ensure the service is not interrupted by the operating system

Note: We do not use these permissions for background tracking or unrelated activity.

Installed Apps Information

"KidNotifier app collects a list of installed applications (including system apps) only for the purpose of allowing the user to select which apps' notifications to monitor. This data is not shared with third parties and is only used locally or stored securely on Firebase under the user’s control."

What We Collect

App Name

Package Name

App Icon


This data is used to help you filter or manage apps within the app’s features (e.g., notification filters ).

We do not share this data with any third-party services or advertisers. All data remains on your device or is stored securely if synced with your own linked Firebase ID.

2. Purpose of Collection:

The installed apps data is collected for the following purposes:

To allow users to choose which apps' notifications they want to sync.

To help parents monitor notifications from specific apps.

To personalize your in-app experience.

3. User Consent:

We ask for your explicit permission before accessing app usage data or installed apps information. You can revoke this permission at any time from your device settings.

4. Data Storage:

This data is stored locally on your device and optionally synced to Firebase only under the user’s own unique ID. No data is sold or misused.

5. Data Sharing:

We do not share your installed apps list or any personal data with any third-party services.

5. Data Retention

Notification data is retained only as long as needed for monitoring. Parents can request deletion of data at any time via in-app settings or by contacting support.

6. Parental Consent

This app is intended to be installed on a child’s device with full parental knowledge and consent. It does not function independently or without linking to a parent device.


( PARENT MODE ) 

Information We Collect

The parent Mode does not collect any personal data from the parent device.

2. How It Works

The app reads synced notification data from Firebase using the UID provided by the child device. This information is presented in a structured and readable format.

3. Local Storage

For convenience, the parent app temporarily stores notification data locally using a local key-value system (e.g., TinyDB). This data is not shared and exists only to improve loading speed.


4. Permissions

Required Internet Access – to read synced data from Firebase


In parent mode, if the same app (e.g., WhatsApp) is installed on the parent's device, the app icon is fetched locally and shown alongside synced notifications. This icon is used only for display purposes and is not collected, stored, or transmitted.


Security & Data Sharing

All communication between devices and Firebase is encrypted using secure protocols.We do not share data with third parties, advertisers, or analytics services.Only authorized parents (those with the correct UID) can access the child’s data.

"To support core functionalities and enhance the experience, KidNotifier App uses the following SDKs and libraries"

(These services are governed by their own privacy policies) 

(Firebase Realtime Database)

 Purpose: Sync and store child device data (notifications, battery, status, etc.)


Data Stored: Notification title, content, time, app name, Battery info, online info, UID-based linkage

Privacy: Data is only accessible to the linked parent account and encrypted during transfer Firebase


(Firebase Authentication)

Purpose: Secure login for parent users using Google Sign-In

Data Used: Email address, display name (used to identify parent)


Privacy: No passwords are stored by us; authentication is handled by Firebase/Google---

(Google Play Billing Library)

Purpose: To enable secure subscription payments for Parent Mode

Data Used: No direct access to financial info. Billing is handled via Google Play

(Glide Image Library)

Purpose: Efficient image loading and caching (e.g., profile pictures, icons)


Privacy: Does not collect personal data


KidNotifier does NOT use any advertising SDK, analytics trackers, or third-party data collection tools.All SDK used are strictly for app functionality and security purposes


We use Firebase SDK only for secure authentication and real-time data syncing. We do not use Firebase Analytics or advertising-related features.You can learn more about Firebase’s privacy Also. 

Device Information Accessed

(Child Mode Only) To support parental insights, we may also access Battery percentage Online/offline status This information is used strictly for parental awareness and is never shared with third parties.


Data Deletion & User Rights


1. Connected Parent Details 
 The child can view the name and email address of the currently connected parent in the Child Dashboard.

2. Disconnect Anytime

If the child no longer wants to share notification data, they can disconnect the parent at any time by tapping the "Disconnect"

3. App Notification Control

The child has full control over which apps’ notifications are shared.From the dashboard, the child can select specific apps whose notifications should be visible to the parent.

4. View and management
 permissions in the Child Dashboard Section

5. Delete data Anytime

Parents or children can delete all data by clicking “Delete Data” inside the app.

Contact Us If you have any questions, concerns, or wish to request data removal, please contact us:Email: kidnotifier@gmail.com

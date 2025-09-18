# Privacy Policy for JotPad

**Last Updated: September 18, 2024**

Welcome to JotPad. This Privacy Policy explains how JotPad (“we,” “our,” or “us”) collects, uses, and protects your information when you use our Progressive Web App (PWA) and Chrome Extension. Your privacy is our top priority, and this policy is designed to be transparent and easy to understand.

By using JotPad, you agree to the collection and use of information in accordance with this policy.

---

### 1. Guiding Principles

Our privacy practices are built on these core principles:

*   **You Own Your Data**: Your notes, settings, and personal information are yours. We claim no ownership over them.
*   **Data Stays Local First**: By default, all your note content and application settings are stored directly on your device.
*   **Transparency**: We are upfront about what data we handle and why.
*   **No Selling of Data**: We will never sell, rent, or share your personal information or note content with third-party advertisers.

---

### 2. Information We Collect

We collect different types of information depending on the features you use.

#### a) Information You Provide & Store Locally

*   **Note Content & Folders**: The primary data JotPad handles is the content of your notes and the folder structure you create. By default, this is stored exclusively on your device using your browser's local IndexedDB storage. We do not have access to this data.
*   **Application Settings**: Your preferences (e.g., theme, font size) are also stored locally on your device using `localStorage`.

#### b) Information for Optional Features

If you choose to use features that require an internet connection, we handle the following:

*   **Google Account Information (Optional Login)**: If you sign in with Google, we use **Firebase Authentication**. Through this service, we receive your basic Google profile information, including:
    *   Your name
    *   Your email address
    *   Your profile picture URL
    This information is used solely for identifying you within the app and displaying your profile.

*   **Google Drive Data (Optional Sync)**: If you enable Google Drive sync, the application stores a data file (`jotpad_data.json`) containing your notes and folders in your personal Google Drive account. This file is placed in either:
    *   A private **"App Data Folder"** visible only to JotPad (default).
    *   A visible folder named **"Jotpad Noted"** if you choose this option in settings.
    We do not have access to your Google Drive account or any files outside of what JotPad creates. All operations are performed directly between your browser and Google's servers.

*   **Shared Note Content (Optional Sharing)**: If you use the "Share Note" feature, a copy of the specific note you choose to share is sent to our Firebase Firestore database to generate a public, time-limited link. This temporary copy is automatically deleted after 7 days.

---

### 3. How We Use Information

The data we handle is used exclusively to provide and improve JotPad's functionality.

*   **To Provide Core Functionality**: Your locally stored notes and settings are used to make the app work offline and persist your data between sessions.
*   **To Enable Authentication**: Your Google account information is used to log you in, secure your Pro status, and display your user profile.
*   **To Enable Cloud Sync**: The Google Drive integration allows you to back up, restore, and sync your notes across your own devices.
*   **To Enable Note Sharing**: The Firebase Firestore integration is used only to facilitate the temporary sharing of a specific note when you initiate it.

---

### 4. Chrome Extension Permissions Explained

JotPad requests the following permissions for the Chrome Extension. Here is why we need them:

*   `sidePanel`: This is the core permission that allows JotPad to open as a notepad in the browser's side panel, which is the main feature of the extension.
*   `storage`: This permission is used to store your notes and settings locally on your device, ensuring your data persists.

---

### 5. Third-Party Services

We rely on trusted third-party services to provide optional features. We do not share your data with them beyond what is necessary for their services to function.

*   **Firebase (by Google)**: We use Firebase for two optional features:
    *   **Firebase Authentication**: To manage Google Sign-In.
    *   **Firebase Firestore**: To temporarily store a copy of a note when you use the "Share Note" feature.
    You can review [Google's Privacy Policy](https://policies.google.com/privacy) for more information on how they handle data.

*   **Google Drive API**: This is used for the optional note synchronization feature. The API is called directly from your browser to your Google Drive account.

---

### 6. Data Security

We are committed to protecting your information.

*   **Local Data**: Your data stored on-device is as secure as the browser and operating system you are using.
*   **App Lock & Encryption**: Our "App Lock" and "Protected Note" features use the **WebAuthn standard** and **AES-GCM encryption**. This means your encryption keys are derived from your device's secure hardware (like a TPM chip or secure enclave). We never see or store these keys.
*   **Data in Transit**: All communication with Google services (Firebase, Google Drive) is encrypted using industry-standard Transport Layer Security (TLS).

---

### 7. User Rights and Data Control

You are in full control of your data.

*   **Access and Deletion**: You can view, edit, and delete any of your notes or folders directly within the app at any time. Using the "Delete All Notes" function in settings will permanently wipe all note data from your device.
*   **Revoking Authentication**: You can sign out of your Google account at any time from the user profile menu. This will disassociate your account from the app.
*   **Revoking Sync Permissions**: You can disconnect from Google Drive in the app's settings. You can also revoke JotPad's access permissions at any time from your [Google Account security page](https://myaccount.google.com/permissions).
*   **Uninstalling**: Uninstalling the Chrome Extension or clearing the site data for the PWA will permanently delete all locally stored notes and settings. This action is irreversible.

---

### 8. Children’s Privacy

JotPad is not intended for or directed at children under the age of 13. We do not knowingly collect any personal information from children. If you believe we have inadvertently collected such information, please contact us so we can promptly remove it.

---

### 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the “Last Updated” date at the top. We encourage you to review this Privacy Policy periodically for any changes.

---

### 10. Contact Us

If you have any questions or concerns about this Privacy Policy, please do not hesitate to contact us at:

**vortexim@proton.me** 

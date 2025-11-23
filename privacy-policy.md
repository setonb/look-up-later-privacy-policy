# Privacy Policy for Look Up Later

**Last Updated: November 22, 2025**

## Overview

Look Up Later ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how the Look Up Later iOS application handles information.

## Data Collection

### What We Collect

Look Up Later collects and processes the following data **locally on your device only**:

1. **Voice Recordings**
   - Purpose: To transcribe your task descriptions
   - Storage: Temporarily processed for transcription, then discarded
   - Access: Never leaves your device, never sent to our servers

2. **Task Data**
   - Purpose: To store your tasks and manage your to-do list
   - Storage: Locally on your device using SwiftData
   - Contents: Task text, estimated duration, creation date, completion status, dismissal timestamps
   - Access: Remains on your device only

3. **User Preferences**
   - Purpose: To remember your settings (e.g., Obsidian vault configuration)
   - Storage: Locally in UserDefaults on your device
   - Access: Never transmitted externally

### What We Don't Collect

- ❌ Personal identifying information (name, email, phone number)
- ❌ Location data
- ❌ Device identifiers for tracking
- ❌ Usage analytics or crash reports
- ❌ Advertising identifiers

## How Your Data is Used

All data processing happens **entirely on your device**:

- **Speech Recognition**: Uses Apple's on-device speech recognition APIs to convert your voice to text
- **Task Storage**: All tasks are stored in your iPhone's local database using SwiftData
- **AI Processing**: Duration estimation uses on-device machine learning models

**We have no servers. We cannot access your data. Your data never leaves your device.**

## Third-Party Services

Look Up Later uses the following Apple system services:

1. **Speech Recognition** (iOS framework)
   - Provider: Apple Inc.
   - Purpose: Convert voice recordings to text
   - Privacy: Processes on-device or via Apple's privacy-preserving servers
   - Learn more: [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

2. **SwiftData** (iOS framework)
   - Provider: Apple Inc.
   - Purpose: Local data storage
   - Privacy: All data stays on your device

### Optional Integration

**Obsidian**
- If you choose to enable Obsidian integration, the app can create notes in your Obsidian vault
- This uses URL schemes to communicate with the Obsidian app
- Configuration (vault name, folder path) is stored locally on your device
- We do not access or transmit any Obsidian data

## Data Sharing

**We do not share your data with anyone.** Period.

Your task data, voice recordings, and preferences remain exclusively on your device. We have no ability to access, transmit, or share this information.

## Data Security

- All data is protected by iOS system security and your device's biometric authentication
- Data is automatically included in your iPhone backups (encrypted if you use encrypted backups)
- If you delete the app, all data is permanently removed from your device

## Your Rights

You have complete control over your data:

- **Access**: View all your tasks within the app
- **Modify**: Edit or update any task at any time
- **Delete**: Delete individual tasks or all data by deleting the app
- **Export**: Task data remains on your device; you may back it up via iCloud/iTunes

## Children's Privacy

Look Up Later does not knowingly collect information from children under 13. The app does not collect personal information from any users. Parents may allow children to use the app, and all data will remain on the child's device.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted to this page with an updated "Last Updated" date. Continued use of the app after changes constitutes acceptance of the updated policy.

## Permissions Requested

Look Up Later requests the following iOS permissions:

1. **Microphone Access**
   - Purpose: To record your voice when creating tasks via speech
   - When: Only when you actively tap the record button or use Siri shortcuts
   - Data handling: Audio is transcribed on-device and then discarded

2. **Speech Recognition**
   - Purpose: To convert your voice recordings into text
   - When: During or immediately after voice recording
   - Data handling: Processed by Apple's speech recognition (on-device or privacy-preserving servers)

You can revoke these permissions at any time in iOS Settings → Look Up Later.

## API Usage Declarations

As required by Apple's privacy manifest requirements, Look Up Later uses:

- **UserDefaults** (Reason: CA92.1) - To store user preferences and settings locally
- **File Timestamp APIs** (Reason: C617.1) - To manage task creation and modification dates

## Contact Information

Look Up Later is developed by **Seton Brown**.

For privacy questions or concerns:
- Email: [setonb@gmail.com](mailto:setonb@gmail.com)
- GitHub: https://github.com/setonb

## Legal Basis

This app operates under Apple's standard App Store terms and conditions. By downloading and using Look Up Later, you agree to this Privacy Policy and Apple's terms.

## International Users

Look Up Later is available worldwide. All data processing occurs on your device, regardless of your location. No data crosses borders because no data is transmitted.

## California Privacy Rights (CCPA)

Under the California Consumer Privacy Act:
- We do not sell personal information
- We do not collect personal information for commercial purposes
- All data remains on your device

## European Privacy Rights (GDPR)

Under the General Data Protection Regulation:
- Legal basis for processing: Legitimate interest (providing app functionality)
- Data controller: Seton Brown
- Data processor: None (all processing is on-device)
- Right to erasure: Delete the app to remove all data
- Data portability: Not applicable (data never leaves your device)

---

**Summary**: Look Up Later is a privacy-first application. Your tasks, voice recordings, and preferences never leave your device. We have no servers, no analytics, and no way to access your information. Your data is yours alone.


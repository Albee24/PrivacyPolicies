# Privacy Policy for ChapterChat

**Effective date: November 14, 2026**

ChapterChat ("we," "us," or "our") is a spoiler-safe book club companion app available on Android and the companion web app. This Privacy Policy explains what information ChapterChat collects, how it is stored and used, and when it may be processed by third-party services.

---

## Information ChapterChat Collects

When you use ChapterChat, we collect and process information necessary to provide our spoiler-safe book club and discussion features:
- **Account Information**: When you sign in using Google Sign-In (via Firebase Authentication or Credential Manager), we collect your Google account name, email address, and profile details.
- **User Profiles**: Information you explicitly provide in your profile, such as your display username, bio, favorite genres, and profile avatar (stored as a compressed image thumbnail).
- **Book Club & Discussion Data**: Information about books you create or join, chapter discussions, comments, and timestamps. Uploaded book cover photos are compressed on-device into lightweight image thumbnails stored directly in your book club records.
- **Notification Subscriptions**: Device tokens and thread subscriptions used to deliver push notifications and unread activity alerts when replies are posted in your watched book threads.

---

## How Information is Stored and Used

- **Cloud Firestore & Firebase Authentication**: ChapterChat uses Google Firebase as its cloud backend. Your account data, book discussions, chapter comments, and member profiles are securely stored in a dedicated Cloud Firestore database.
- **Local Storage & Cache**: Temporary logs, session states, and cached data may be stored on your device to ensure smooth offline and online operation.
- **Images**: Book covers and avatars are compressed client-side into lightweight Base64 thumbnails stored within Firestore documents. We do not use external cloud storage buckets (such as Firebase Storage) for media files.

---

## Network and Third-Party Services

ChapterChat connects to essential online backend services provided by **Google Firebase**:
- **Firebase Authentication**: Secures user sign-in and identity verification.
- **Cloud Firestore**: Powers real-time book club synchronization and chapter-isolated comment feeds.
- **Firebase Cloud Messaging (FCM)**: Delivers push notifications for new comment replies on your watched threads.
- **Google AdMob / AdSense**: Displays banner advertisements within the app and web app.

These third-party services process standard connection information, such as your device's IP address and request metadata, in accordance with Google's privacy policies.

---

## Sharing and Third Parties

We do not sell, trade, or rent your personal information to third parties. 

Data sharing is strictly limited to:
1. Essential cloud infrastructure services (Google Firebase) required for user authentication, database synchronization, and push notifications.
2. Ad networks (Google AdMob / AdSense) for displaying advertisements.
3. Other book club members within the context of shared public or private book discussions (e.g., your username and comments are visible to members of the clubs you join).

---

## Retention and Deletion

- **Account & Content Data**: Your profile, book clubs, and comments remain stored in Cloud Firestore for as long as your account is active or until you delete them, close a book club, or request account deletion.
- **Closing Books / Deleting Comments**: When you close a book or delete comments, the data is removed from the active database in accordance with our repository rules and batch deletion caps.
- **Uninstalling**: Uninstalling the mobile app or web app removes local cache, but your cloud-backed account and club data remain stored securely in Firebase until explicitly deleted or closed.

---

## Children’s Privacy

ChapterChat is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us so we can promptly remove it.

---

## Security

We use industry-standard security practices provided by Firebase Authentication and Cloud Firestore security rules to protect your data. However, no method of electronic transmission or storage is 100% secure. Please keep your account credentials safe and avoid sharing sensitive personal information.

---

## Changes to This Policy

We may update this Privacy Policy from time to time to reflect changes in our app, data practices, or legal requirements. The updated policy will be published at this location with a revised effective date. We encourage you to review it periodically.

---

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at:
- **Email**: support@accappdev.com *(or your designated contact email)*

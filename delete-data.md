---
title: Delete Your Data
permalink: /delete-data/
---

# Delete your data — Math Flow (Stepsum)

**App:** Math Flow (Google Play package `com.twiner.math`), to be renamed Stepsum
**Developer:** Team Sunbee · team.sunbee@gmail.com

The app has no accounts, so there is nothing to log in to. There are two kinds of data, and each is removed differently.

## 1. Data on your device (quiz history, settings)

You remove it yourself. No request is needed.

- **Quiz history only:** open the app → Settings → **Reset All Data** → Reset.
- **Everything, including settings and unlocked levels:** uninstall the app, or clear its storage in Android Settings → Apps → Math Flow → Storage → Clear storage.

If Android backup is on for your device, also delete the app's backup in your Google account (Google One / Backup settings). The app cannot do this for you.

## 2. Analytics and crash data held by Firebase

Request it by email.

1. Send an email to **team.sunbee@gmail.com** with the subject `Data deletion request`.
2. Include the approximate date you last used the app and, if you can, your device model. There is no account to identify you, so this helps us match your app instance.
3. We submit a deletion request to Firebase for the app-instance ID tied to your installation. Firebase completes it within 30 days, and we confirm by reply when it is done.

Uninstalling the app also resets the app-instance ID, so no new data is linked to the old one.

## What is deleted and what is kept

| Data | After your request |
|---|---|
| Usage events (sessions, problems answered, screens viewed, settings changed) tied to your app instance | Deleted |
| Crash reports tied to your installation | Deleted |
| Device model, OS version, app version, country-level location attached to the above | Deleted with them |
| Aggregated statistics that no longer identify any app instance (for example, average time per problem across all users) | Kept — they cannot be traced back to you |

Nothing else is held about you. We do not keep your email after the request is closed.

Full details: [Privacy Policy](/privacy/).

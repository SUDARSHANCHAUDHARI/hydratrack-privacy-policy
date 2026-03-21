# HydraTrack — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

HydraTrack is a hydration tracking app for Android. It helps you log daily water intake, set hydration goals, and optionally sync data with Google Fit. All hydration data is stored locally on your device.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Water intake logs (amount, time, date) | Core hydration tracking | Room database on your device |
| Daily hydration goals and settings | Personalisation | DataStore on your device |
| App preferences | Personalisation | DataStore on your device |

### Google Fit Integration (Optional)

If you choose to connect Google Fit, HydraTrack syncs your hydration logs to your Google Fit account. This requires Google Sign-In.

- **Data synced:** Hydration log entries (amount, timestamp)
- **Processed by:** Google Fit API and Google Play Services
- **Google's privacy policy:** https://policies.google.com/privacy

You can disconnect Google Fit at any time in the App settings. Disconnecting stops future syncing but does not delete data already in Google Fit.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Track and display daily water intake | Local hydration logs |
| Send hydration reminder notifications | Local WorkManager schedules |
| Sync with Google Fit (if connected) | Hydration data sent to Google Fit API |

---

## Data Storage and Security

- **Hydration data:** Stored in a Room database in the App's private directory
- **No Sudarshan Tech Labs cloud storage:** We operate no backend server
- **Android sandbox:** Data is protected by Android's application sandboxing

## Data Retention

| Data | Retention |
|---|---|
| Local hydration data | Until you delete it or uninstall the App |
| Google Fit data (if synced) | Managed by Google Fit — delete via Google Fit settings |

---

## Data Sharing

We do not sell your data. Data is shared only with Google Fit if you choose to connect it.

---

## Permissions Explained

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Send hydration reminder notifications |
| `SCHEDULE_EXACT_ALARM` | Schedule precise reminder alarms |
| `WAKE_LOCK` | Ensure reminders trigger on time |
| `VIBRATE` | Haptic feedback for reminders |
| `INTERNET` | Required for Google Fit API sync and Google Sign-In |
| `ACCESS_NETWORK_STATE` | Check connectivity before syncing with Google Fit |

---

## Your Rights and Controls

- **Delete hydration logs:** Use the delete function in the App
- **Disconnect Google Fit:** Go to App Settings > Connections > Disconnect Google Fit
- **Delete all local data:** Uninstall or go to Android Settings > Apps > HydraTrack > Storage > Clear Data

---

## Children's Privacy

HydraTrack is not directed at children under 13. We do not knowingly collect personal information from children.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes via:

- In-app notification
- Updated policy date on this page

Continued use of HydraTrack after changes become effective constitutes your acceptance of the updated policy.

---

## Contact Us

For privacy questions, data access requests, or account deletion:

- **Email:** sudarshantechlabs@gmail.com
- **Developer:** sunny.sudarshan@gmail.com
- **Website:** https://sudarshantechlabs.com
- **Response Time:** Within 48 hours

---

## GDPR Rights (EU Users)

If you are in the European Economic Area, you have the right to:

- **Access** — Request a copy of your personal data
- **Rectification** — Correct inaccurate data
- **Erasure** — Request deletion of your data
- **Restrict Processing** — Limit how we use your data
- **Data Portability** — Receive your data in a portable format
- **Object** — Object to certain types of processing

To exercise these rights, contact us at the details above.

---

## Play Store Data Safety Summary

| Data type | Collected | Shared | Purpose |
|---|---|---|---|
| Hydration logs | Local only | Google Fit (optional, if connected) | Fitness tracking |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-03-21

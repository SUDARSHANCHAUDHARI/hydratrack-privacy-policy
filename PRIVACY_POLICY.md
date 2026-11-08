# HydraTrack — Privacy Policy

**Effective Date:** 2026-03-21
**Last Updated:** 2026-11-08
**Version:** 1.0.0

Published by **Sudarshan Tech Labs** | https://sudarshantechlabs.com | sudarshantechlabs@gmail.com

---

HydraTrack is a hydration tracking app for Android. It helps you log daily water intake and set hydration goals. All data is stored locally on your device, and the App has no internet access.

---

## Data Collection

### Data Stored Locally on Your Device

| Data | Purpose | Storage |
|---|---|---|
| Water intake logs (amount, time, date) | Core hydration tracking | Room database on your device |
| Daily hydration goals and settings | Personalisation | DataStore on your device |
| App preferences | Personalisation | DataStore on your device |

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Track and display daily water intake | Local hydration logs |
| Send hydration reminder notifications | Local WorkManager schedules |

---

## Data Storage and Security

- **Hydration data:** Stored in a Room database in the App's private directory
- **No Sudarshan Tech Labs cloud storage:** We operate no backend server
- **Android sandbox:** Data is protected by Android's application sandboxing

## Data Retention

| Data | Retention |
|---|---|
| Local hydration data | Until you delete it or uninstall the App |

---

## Data Sharing

We do not sell or share your data. It never leaves your device.

---

## Permissions Explained

The App itself asks for three permissions:

| Permission | Why It Is Needed |
|---|---|
| `POST_NOTIFICATIONS` | Send hydration reminder notifications |
| `WAKE_LOCK` | Ensure reminders trigger on time |
| `VIBRATE` | Haptic feedback for reminders |

### Permissions added by Android libraries

The finished app carries five more, declared by the Android libraries it is built on rather than by the App's own code. They still appear in the permission list you see on the Play Store, so they are listed here for completeness:

| Permission | Comes from | What it does |
|---|---|---|
| `ACCESS_NETWORK_STATE` | WorkManager | Lets a library check whether a network exists. It does **not** grant network access, and without `INTERNET` nothing can be sent |
| `RECEIVE_BOOT_COMPLETED` | WorkManager | Re-registers your scheduled reminders after the device restarts |
| `FOREGROUND_SERVICE`, `BIND_JOB_SERVICE` | WorkManager | How Android runs scheduled background work |
| `DUMP` | a build-time library | Diagnostic permission. Android grants it only to system apps, so it has no effect here |

**`INTERNET` is absent from the finished app**, verified against the merged manifest rather than the App's own file alone. That is what makes the statement at the top of this policy — that the App has no internet access — true of the build you install.

---

## Your Rights and Controls

- **Delete hydration logs:** Use the delete function in the App
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
| Hydration logs | No (on-device only) | No | Hydration tracking |

---

---

**This privacy policy complies with:**
- Google Play Store requirements
- GDPR (General Data Protection Regulation)
- CCPA (California Consumer Privacy Act)

**Last reviewed:** 2026-11-08

---

This is the published policy, served at https://sudarshanchaudhari.github.io/hydratrack-privacy-policy/ from the `main` branch of this repository. `index.html` carries the same content for the web and must be updated alongside this file. The copy in the [HydraTrack app repository](https://github.com/SUDARSHANCHAUDHARI/HydraTrack/blob/main/PRIVACY_POLICY.md) is kept identical.

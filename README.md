# Privacy Policy — HydraTrack

**Effective Date:** 2026-03-21
**Last Updated:** 2026-03-21

This Privacy Policy describes how **SudarshanTechLabs** ("we", "us", or "our") handles your information when you use the **HydraTrack** Android application (the "App").

---

## 1. Data We Collect

HydraTrack collects only the minimum data necessary to provide its features:

| Data | Purpose | Storage |
|------|---------|---------|
| Daily water intake logs | Track hydration progress | Local device only |
| Body weight | Calculate personalized daily goal | Local device only |
| Activity level | Calculate personalized daily goal | Local device only |
| Notification preferences | Deliver hydration reminders | Local device only |
| Weather data (Premium) | Adjust daily goal based on temperature | Fetched from OpenWeatherMap API; not stored |

**We do not collect:**
- Name, email address, or any personally identifiable information
- Location data
- Device identifiers (IMEI, advertising ID, etc.)
- Usage analytics or crash reports (unless explicitly added in a future version)

---

## 2. How We Use Your Data

All data listed above is used solely to provide the features of the App:

- Water intake logs are used to display your progress and statistics
- Weight and activity level are used to calculate your personalized daily hydration goal
- Notification preferences are used to schedule hydration reminders
- Weather data (Premium only) is fetched in real time to adjust your daily goal on hot days — it is never stored or sent to our servers

---

## 3. Data Sharing with Third Parties

We do not sell, trade, or transfer your personal data to any third party.

The following limited exceptions apply:

**Google Fit (Premium feature — opt-in only)**
If you enable Google Fit sync in the App settings, your water intake data will be written to your Google Fit account. This is entirely optional and controlled by you. Google's Privacy Policy applies to data stored in Google Fit: [https://policies.google.com/privacy](https://policies.google.com/privacy)

**OpenWeatherMap API (Premium feature)**
When weather-based goal adjustment is active, the App sends your approximate city-level location (not GPS coordinates) to OpenWeatherMap to retrieve the current temperature. No personal data is included in this request. OpenWeatherMap's Privacy Policy: [https://openweathermap.org/privacy-policy](https://openweathermap.org/privacy-policy)

---

## 4. Data Storage & Security

- All personal data (intake logs, weight, activity level) is stored **exclusively on your device** using Android Room database and DataStore.
- No data is transmitted to SudarshanTechLabs servers.
- We do not operate any backend servers for this application.
- Data security is provided by Android's built-in application sandboxing.
- You can delete all App data at any time via Android Settings → Apps → HydraTrack → Clear Data.

---

## 5. Children's Privacy

HydraTrack is not directed to children under the age of 13. We do not knowingly collect any personal information from children under 13. If you believe a child under 13 has provided data through the App, please contact us at the email below and we will take appropriate action.

---

## 6. Permissions

The App requests the following Android permissions:

| Permission | Reason |
|-----------|--------|
| `POST_NOTIFICATIONS` | Send hydration reminder notifications (Android 13+) |
| `SCHEDULE_EXACT_ALARM` | Schedule reminders at specific times |
| `WAKE_LOCK` | Ensure reminders fire even when device is in standby |
| `VIBRATE` | Vibrate on reminder notifications |
| `INTERNET` | Fetch weather data (Premium feature only) |
| `ACCESS_NETWORK_STATE` | Check connectivity before weather API calls |

No permissions are used beyond their stated purpose.

---

## 7. Data Retention

Data remains on your device until you:
- Clear App data via Android Settings
- Uninstall the App
- Manually delete logs within the App

We do not retain copies of your data on any external server.

---

## 8. Your Rights

You have full control over your data:
- **Access:** All your data is visible within the App
- **Deletion:** Clear App data via Android Settings → Apps → HydraTrack → Clear Data, or uninstall the App
- **Portability:** Premium users can export data to CSV from the Settings screen

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this document and notify users via an in-app notice on the next App launch.

Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions or concerns about this Privacy Policy, please contact us:

**SudarshanTechLabs**
Bangkok, Bangkok, Thailand
Email: [sudarshantechlabs@gmail.com](mailto:sudarshantechlabs@gmail.com)

---

*This privacy policy was written for HydraTrack by SudarshanTechLabs.*

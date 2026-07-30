# Privacy Policy — Oramat

**Last updated: 31 July 2026**

Oramat is a plant care app. This policy explains what data the app handles, why, and what you can do about it.

The short version: Oramat has no accounts, no ads, no analytics and no trackers. It never asks for your name, email or phone number. Your photos never leave your phone.

---

## Who is responsible

.Turpal Papaev, Belgium
Contact: **support@oramat.app**

For the purposes of the GDPR, I am the data controller for the data described below.

---

## What the app stores

### On your phone only

- Your plants: names, locations, plant type, watering interval, moisture threshold
- Your watering history
- **Photos you add to a plant.** These stay in the app's private storage on your device. They are never uploaded anywhere.
- Your chosen language

If you uninstall the app, all of this is deleted from your phone.

### On Google servers (Firebase)

So that your plants survive a reinstall, a copy of your plant data — everything in the list above **except your photos** — is stored in Firebase Realtime Database, hosted in Belgium (europe-west1).

To do this without asking you to create an account, the app uses **Firebase Anonymous Authentication**. This generates a random ID for your device. It is not linked to your name, email, Google account, or any other identifier. I cannot tell who you are from it, and I cannot contact you.

If you enable notifications, a Firebase Cloud Messaging token for your device is also stored, so the app can send you a watering reminder.

### Sensor data (only if you use one)

Oramat can optionally read from a soil moisture sensor. If you connect one, its readings — soil moisture, battery level, and the time it last reported — are stored under the sensor's code in the same database.

**Please note:** sensor readings are stored under the sensor's own code rather than under your anonymous ID, and any signed-in user of the app who knew that code could read them. Do not use a sensor code that identifies you personally. This is a known limitation of the current version and I intend to tighten it.

---

## What the app does NOT do

- No advertising, and no advertising identifiers
- No analytics, tracking, or usage measurement
- No selling or sharing of data with third parties
- No location tracking
- No access to contacts, calendar, microphone, or files beyond the photo you pick yourself
- No account, no email address, no name, no phone number

---

## Permissions the app asks for

- **Photos / storage** — only when you choose to add a photo of a plant, and only for the photo you select
- **Notifications** — only to remind you to water a plant

You can refuse either. The app works without both.

---

## Who else can see the data

**Google** (Firebase), acting as my processor, stores the data described above on servers in Belgium. Google's own privacy terms apply to their handling of it: https://firebase.google.com/support/privacy

Nobody else has access. I do not share, sell, or transfer data to anyone.

---

## How long it is kept

Your data stays in Firebase until it is deleted.

Because accounts are anonymous, **there is no way to recover your data if you uninstall the app or reset your device** — the anonymous ID is lost with it. This is the trade-off for not requiring you to sign up. Please don't rely on Oramat as your only record of anything you care about.

---

## Your rights

Under the GDPR you have the right to access, correct, delete, or export your data, to restrict or object to processing, and to complain to a supervisory authority.

**In practice, deletion is the easy one:** uninstalling the app deletes everything stored on your phone. To also delete the cloud backup, use the "Delete my data" option in the app's settings, or email **support@oramat.app**.

The honest limitation: because the app has no accounts, **I cannot identify which stored data is yours** unless you tell me your anonymous ID (shown in the app's settings). Without it I have no way to find, export, or delete your specific record, and no way to verify a request is really yours. This is a deliberate privacy trade-off — I hold less about you, but I also can't look you up.

If you are unhappy with how your data is handled, you can complain to the Belgian Data Protection Authority (Gegevensbeschermingsautoriteit / Autorité de protection des données): https://www.gegevensbeschermingsautoriteit.be

---

## Children

Oramat is not directed at children under 13 and does not knowingly collect data from them. It asks for no personal information from anyone.

---

## Changes to this policy

If this policy changes, the date at the top will change and the new version will be posted at this address. Material changes will also be noted in the app's release notes.

---

## Contact

**support@oramat.app**

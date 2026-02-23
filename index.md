# Fi7Note – Privacy Policy

_Last updated: 23 February 2026_

Thank you for using **Fi7Note** (“the App”, “we”, “us”, “our”).
This Privacy Policy explains what data Fi7Note processes, how it is used, and what choices you have.

Fi7Note is a fitness logging app with free-text workout input and on-device parsing.

---

## 1. Overview

- Fi7Note does **not require a separate Fi7Note account**.
- Your workout and profile data are primarily stored **locally on your device**.
- We do **not** run a general cloud sync for your workout history.
- Certain actions (such as sending feedback by email, and optional markup-feedback transmissions if enabled in your build) can transmit data off-device.

---

## 2. Data processed locally on your device

Fi7Note stores data in local app storage (Capacitor Preferences) and, for some technical features, localStorage.

### 2.1 Workout data
When you log workouts, the app stores data such as:

- your free-text workout input,
- parsed exercises, sets, reps, weights, distance/time/speed metrics,
- exercise notes,
- optional session timestamps/duration,
- optional span/markup overrides used in review mode.

### 2.2 Profile and app settings
The app stores profile/settings data such as:

- language,
- unit preferences (e.g., kg/lb, km/mi, min/h:mm),
- training goal settings (e.g., active days per week),
- onboarding/tutorial state,
- UI preferences.

### 2.3 Draft and editor state
To prevent data loss, Fi7Note may store temporary draft content, including:

- current unsaved text,
- review/editor state (including temporary spans and session edit values).

### 2.4 Exercise catalog and muscle overrides
Fi7Note may store locally:

- your local exercise-catalog entries (encountered/created exercise records),
- locally persisted muscle-label overrides for exercises.

### 2.5 In-app review prompt state
Fi7Note stores local state for in-app rating prompts (e.g., prompt shown/dismissed timestamps and counts).

---

## 3. Data sent off-device

### 3.1 Email feedback (user-initiated)
If you use the feedback button, Fi7Note opens your email app with a prefilled recipient:

- `materialize.thoughts@gmail.com`

If you send the email, we receive the information you include (email address, message content, attachments if any).
We use this only to handle your request and respond.

### 3.2 Optional markup feedback endpoint (feature-dependent)
Fi7Note includes a markup-feedback module. If this module is enabled and used in your app flow, feedback payloads can be sent to:

- `https://guide-cloud.de/mat-tools-backend/api/markup-feedback`

Such payloads may include:

- `rawText` and `cleanedText`,
- model spans and user-corrected spans,
- optional muscle-correction structures (model vs. user labels),
- optional session metadata (start/end/duration),
- technical metadata (e.g., source, app build, platform),
- optional local correlation ID (`clientEntryId`).

If sending fails, payloads may be queued locally and retried later.

### 3.3 Google Play / platform services
On Android release builds, model asset packs may be delivered via Google Play infrastructure (Play Asset Delivery).
This is a platform distribution mechanism and may involve standard Google Play service processing.

---

## 4. Subscriptions and purchases

Fi7Note is subscription-based. Access requires an active subscription purchased via **Google Play**.

- Billing, payment processing, and subscription account handling are performed by Google Play.
- We do not receive your full payment card details.
- The app only uses purchase/subscription status information provided by Google Play to determine access.

For details, see Google’s terms and privacy policy.

---

## 5. Advertising and analytics

Based on the current Fi7Note codebase configuration:

- no third-party ad SDK is integrated,
- no third-party analytics/crash-reporting SDK is integrated.

If this changes in future versions, this policy will be updated.

---

## 6. Data retention and deletion

### 6.1 Local app data
Local workout/profile/settings/draft data remains on your device until you delete it by:

- removing entries in the app (where available),
- clearing app storage in device settings,
- uninstalling the app.

### 6.2 Email feedback data
Emails you send to us are retained in our mailbox until no longer needed, unless legal obligations require longer retention.
You can request deletion via email.

### 6.3 Markup-feedback records (if used)
If markup-feedback submissions are enabled and sent, server-side records are retained for product-quality/debug purposes until deletion is requested or operationally no longer required.

---

## 7. Children’s privacy

Fi7Note is not directed to children.
If you believe a child has sent personal data to us (e.g., via email), contact us and we will take reasonable deletion steps.

---

## 8. Security

- Local data protection also depends on your device security (screen lock, OS protections).
- Network requests use HTTPS.
- On Android, Fi7Note uses a restrictive network security configuration for the configured backend domain.

No method of transmission or storage is 100% secure.

---

## 9. Your rights and choices

Depending on your jurisdiction, you may have rights to access, correction, deletion, or objection regarding personal data we process.
Because Fi7Note is largely local-first, many controls are directly available on your device (clear data/uninstall).

For requests regarding server-side or email data, contact us.

---

## 10. Changes to this policy

We may update this Privacy Policy from time to time.
Material changes will be reflected by updating the “Last updated” date above.

---

## 11. Contact

If you have questions about this Privacy Policy or Fi7Note, contact:

**Email:** materialize.thoughts@gmail.com

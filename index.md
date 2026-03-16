# Fi7Note – Privacy Policy

_Last updated: 16 March 2026_

Thank you for using **Fi7Note** (“the App”, “we”, “us”, “our”).
This Privacy Policy explains what data Fi7Note processes, how it is used, and what choices you have.

Fi7Note is a fitness logging app with free-text workout input and primarily on-device parsing and storage.

---

## 1. Overview

- Fi7Note does **not require a separate Fi7Note account**.
- Your workout, profile, and app settings data are primarily stored **locally on your device**.
- We do **not** run a general cloud sync for your workout history.
- Certain user-initiated actions can transmit data off-device, such as sending feedback by email or saving review corrections that are submitted as product-quality feedback.

---

## 2. Data processed locally on your device

Fi7Note stores data in local app storage (Capacitor Preferences) and, for some technical features, localStorage.

### 2.1 Workout data

When you log workouts, the app stores data such as:

- your free-text workout input,
- parsed exercises, sets, reps, weights, distance/time/speed metrics,
- exercise notes,
- optional session timestamps and duration,
- optional span/markup overrides used in review mode.

### 2.2 Profile and app settings

The app stores profile/settings data such as:

- language,
- unit preferences (e.g. kg/lb, km/mi, min/h:mm),
- training goal settings (e.g. active days per week),
- onboarding/tutorial state,
- UI preferences.

### 2.3 Draft and editor state

To help prevent data loss, Fi7Note may store temporary draft content, including:

- current unsaved text,
- review/editor state (including temporary spans and session edit values).

### 2.4 Exercise catalog and muscle overrides

Fi7Note may store locally:

- your local exercise-catalog entries (encountered or created exercise records),
- locally persisted muscle-label overrides for exercises.

### 2.5 In-app review prompt state

Fi7Note stores local state for in-app rating prompts (for example, prompt shown/dismissed timestamps and counts).

---

## 3. Data sent off-device

### 3.1 Email feedback (user-initiated)

If you use the feedback button, Fi7Note opens your email app with a prefilled recipient:

- `materialize.thoughts@gmail.com`

If you send the email, we receive the information you include, such as your email address, message content, and any attachments you choose to send.
We use this only to handle your request and respond.

### 3.2 Review correction / markup feedback

When you save parser or review corrections in Fi7Note, the app may send product-quality feedback to:

- `https://guide-cloud.de/mat-tools-backend/api/markup-feedback`

Because Fi7Note is a fitness logging app, these submissions may contain **health and fitness information** and other user-provided workout content, including:

- `rawText` and `cleanedText`,
- model spans and user-corrected spans,
- optional muscle-correction structures (model vs. user labels),
- optional session metadata (start, end, duration),
- technical metadata (such as source, app build, and platform),
- an optional local correlation ID (`clientEntryId`).

We use these records to improve parsing quality, investigate issues, and review model behavior.
If sending fails, payloads may be queued locally and retried later.

### 3.3 Google Play / platform services

On Android release builds, model asset packs may be delivered via Google Play infrastructure (Play Asset Delivery).
This is a platform distribution mechanism and may involve standard Google Play service processing.

---

## 4. Future subscriptions and purchases

Fi7Note may offer optional subscriptions or other in-app purchases in future versions through **Google Play**.

If and when this becomes available:

- billing, payment processing, and subscription management will be handled by Google Play,
- we will not receive your full payment card details,
- the app may use purchase or subscription status information provided by Google Play to unlock paid features.

This Privacy Policy will be updated when subscriptions or purchases are live in the app.

---

## 5. Advertising and analytics

Based on the current Fi7Note codebase configuration:

- no third-party ad SDK is integrated,
- no third-party analytics or crash-reporting SDK is integrated.

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

### 6.3 Review correction / markup-feedback records

If review-correction feedback is submitted, server-side records are retained for product-quality and debugging purposes until deletion is requested or operationally no longer required.

---

## 7. Children’s privacy

Fi7Note is not directed to children.
If you believe a child has sent personal data to us (for example, via email or review feedback), contact us and we will take reasonable deletion steps.

---

## 8. Security

- Local data protection also depends on your device security (screen lock, OS protections).
- Network requests use HTTPS.
- On Android, Fi7Note uses a restrictive network security configuration for the configured backend domain.

No method of transmission or storage is 100% secure.

---

## 9. Your rights and choices

Depending on your jurisdiction, you may have rights to access, correction, deletion, or objection regarding personal data we process.
Because Fi7Note is largely local-first, many controls are directly available on your device (for example, clear data or uninstall).

For requests regarding server-side or email data, contact us.

---

## 10. Changes to this policy

We may update this Privacy Policy from time to time.
Material changes will be reflected by updating the “Last updated” date above.

---

## 11. Contact

If you have questions about this Privacy Policy or Fi7Note, contact:

**Email:** materialize.thoughts@gmail.com

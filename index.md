# Fi7Note App Privacy Policy

**Effective date:** August 7, 2026

## 1. Scope

This App Privacy Policy applies to the Fi7Note mobile application for Android ("Fi7Note", "app", "we", "us", or "our").

This Policy covers the Fi7Note app itself. It does **not** by itself govern the public website at `materialize-thoughts.com`, which is covered separately by the website Privacy Policy.

## 2. Controller

The controller for the processing described in this App Privacy Policy is:

**Pascal Schönfeld**  
Materialize Thoughts  
Marrensberg 9  
24944 Flensburg  
Germany  
Email: materialize.thoughts@gmail.com

## 3. What Fi7Note Is

Fi7Note is a local-first Android fitness journaling app built for fast workout capture.

Its core flow is:

1. you type workout notes in natural free text,
2. the app processes that text on your device,
3. the app shows a structured result for review,
4. you can check, adjust, and save the workout, and
5. you can later use history and progress views to revisit saved training data.

Fi7Note is **not** a social fitness network, does **not** require a separate Fi7Note account for its core use, and does **not** provide general cloud sync for workout history as a core product feature.

## 4. Our Privacy Approach

Fi7Note is designed around a local-first model.

That means, by default:

- workout text you enter,
- parsed workout structure,
- saved workout history,
- profile settings,
- onboarding state, and
- similar core app content

are primarily stored and processed on your device.

We do **not** operate Fi7Note as a cloud-first workout logging service.

We do **not** sell personal data.

We do **not** use your workout history as part of a public social feed.

We do **not** use your workout text, exercise names, weights, repetitions, notes, training history, or personal fitness details for advertising profiles.

Fi7Note may use optional, consent-based usage analytics through Firebase / Google Analytics for Firebase. This analytics is disabled unless you actively allow it in the app, and you can change your choice later in Profile.

Separately from optional Firebase analytics, production versions of Fi7Note may send a very limited set of predefined, aggregate usage counters to a Fi7Note-operated endpoint hosted on Cloudflare infrastructure. These counters are designed only to measure coarse product and funnel stages, do not create a Fi7Note user profile, and operate independently of the Firebase analytics consent setting.

Fi7Note does not include third-party advertising SDKs or third-party crash-reporting SDKs in the current app codebase.

## 5. Categories of Data We Process

Depending on how you use Fi7Note, we may process the following categories of data.

### 5.1 Data you enter in the app

This may include:

- workout text and notes,
- exercise names,
- sets, reps, weight, units,
- distance, time, speed, pace,
- workout-related comments,
- saved training entries,
- goals, preferences, and related settings.

Because workout entries and related notes may reveal fitness- or health-related information, some jurisdictions may treat parts of this information as sensitive or special-category personal data.

This workout content is used for the app functionality you choose to use. It is not sent to Firebase / Google Analytics.

### 5.2 Data created or stored by the app on your device

This may include:

- structured workout records derived from your text input,
- exercise mappings and related review data,
- app settings,
- onboarding completion state,
- unit preferences,
- local app state needed for normal operation.

### 5.3 Subscription and purchase-related data

If you purchase Fi7Note through Google Play, we may process limited purchase- or entitlement-related information made available to us or to the app as needed to:

- determine whether paid access should be enabled,
- verify whether a subscription or purchase is active,
- apply trial or paid access rules,
- handle support issues related to access status,
- respond to billing-related questions where relevant.

We do **not** receive your full payment card details from Google Play.

Google Play handles billing, payment processing, taxes, renewals, cancellations, refunds, billing disputes, and store-level purchase management under Google’s applicable terms, policies, and infrastructure.

### 5.4 Optional usage analytics

If you actively allow analytics in the app, Fi7Note may send limited usage analytics to Firebase / Google Analytics for Firebase.

These analytics events are abstract product, funnel, and share-flow events. They may include, for example:

- onboarding started, completed, or skipped,
- paywall viewed,
- plan type selected, such as trial, monthly, yearly, or lifetime,
- checkout started, purchase completed, or purchase cancelled,
- first workout started,
- workout saved,
- review screen opened or confirmed,
- history or progress screen opened,
- progress detail opened,
- smart suggestion seen or used,
- Share Studio opened,
- share export started or completed,
- native share sheet opened,
- share flow completed or cancelled where technically measurable.

Analytics parameters are limited to abstract values such as:

- app language,
- source screen or flow,
- selected unit type,
- plan type,
- share component type,
- share format,
- generic success, failure, or cancellation reasons,
- boolean states such as whether recognized items existed.

Fi7Note does **not** send the following to Firebase / Google Analytics:

- workout free text,
- exercise names,
- weights,
- repetitions,
- notes,
- concrete workout history,
- concrete muscle distribution per user,
- personal fitness details,
- share recipients,
- names of other apps you share to,
- screenshots or exported share images.

Firebase / Google Analytics may process technical identifiers and operational metadata necessary for analytics, such as an app instance identifier or Firebase installation identifier, device and app information, app lifecycle information, approximate location derived from IP address, and related analytics metadata.

We use this optional analytics to understand and improve onboarding, paywall quality, purchase flow quality, sharing/export quality, and general product reliability. If Firebase / Google Analytics is linked with Google Ads, these abstract events may also be used for campaign and conversion measurement. We do not use Fi7Note workout content for ad targeting.

Analytics is off until you choose to allow it. If you decline analytics, Fi7Note continues to work normally. You can later enable or disable analytics in Profile.

### 5.5 Minimal aggregate usage counters

Separately from Firebase / Google Analytics, production versions of Fi7Note may send a small number of predefined event counters to a Fi7Note-operated endpoint hosted using Cloudflare Workers and Cloudflare D1.

These counters are used only to understand coarse product and funnel performance, for example whether app sessions reach stages such as:

- app start,
- onboarding start, individual onboarding stages, and onboarding completion,
- first workout start and review,
- first, second, or third successfully saved workout,
- paywall view or plan selection,
- checkout start, cancellation, failure, or purchase completion.

For such a counter request, Fi7Note sends only:

- a predefined event name, and
- the Fi7Note app version.

Fi7Note does **not** include any of the following in the counter payload:

- workout text,
- exercise names, weights, repetitions, notes, or concrete workout history,
- names, email addresses, or account identifiers,
- Fi7Note user IDs,
- installation IDs,
- Firebase installation or app-instance identifiers,
- advertising IDs,
- Android IDs or other device identifiers,
- session IDs,
- device model or Android version,
- exact client-side timestamps,
- share recipients or exported share content.

The counter endpoint determines the calendar day server-side and updates an aggregate count for the combination of day, event, and app version. The Fi7Note D1 counter database does not store a per-user or per-installation event history and is not designed to identify whether two counter requests came from the same person or device.

As with any internet connection, Cloudflare necessarily receives network information such as the source IP address while routing and processing the HTTPS request. Fi7Note does not include the IP address as an event parameter and does not store it in the D1 counter database. Cloudflare may process limited network and security metadata as necessary to provide and protect its infrastructure.

The D1 database used for these aggregate counters is configured with Cloudflare's **EU jurisdiction**, which restricts where that D1 database runs and stores its persisted database data to the European Union.

This minimal counter system is technically and organizationally separate from Firebase / Google Analytics. It does not use Firebase identifiers, is not linked to Firebase user or analytics profiles, and continues to operate even if you do not consent to optional Firebase / Google Analytics. It is not used to create advertising profiles or to target advertising to individual users.

### 5.6 Review corrections and product-quality feedback

Fi7Note includes review and correction flows to help you check and fix recognized workout data.

If you choose to share review corrections, product-quality feedback, or support information, we may process the information you choose to submit or explicitly allow for that purpose.

Depending on the specific flow, this may include:

- correction context,
- your message,
- screenshots you choose to send,
- logs or technical context you choose to send or explicitly trigger,
- app version, device information, or error context relevant to the issue you reported.

Such submissions are optional and are not required for normal use of the core app.

Where Fi7Note provides a setting for automatic review-correction sharing, you can change that setting in Profile.

### 5.7 Technical and operational data

We may process limited technical information where necessary to provide, secure, or troubleshoot the app, such as:

- app version,
- Android version,
- device model,
- language setting,
- purchase entitlement status,
- technical error context,
- operational metadata necessary for app functionality or support.

We do not use this as a basis for a third-party advertising profile.

## 6. How We Use Personal Data

We use personal data only as necessary for purposes such as:

- providing Fi7Note’s core workout journaling functionality,
- processing and structuring workout text on-device,
- saving and displaying your workout history and progress,
- enabling app setup and normal operation,
- maintaining app security, stability, and integrity,
- determining paid access entitlement where applicable,
- responding to support requests,
- reviewing user-initiated quality feedback,
- improving parsing quality where you choose to share correction feedback,
- measuring product quality and detailed funnel performance where you allow optional Firebase analytics,
- measuring coarse aggregate product and funnel performance through the minimal counter system described above,
- measuring campaign or conversion performance where optional analytics is enabled and configured for that purpose,
- complying with legal obligations,
- enforcing our terms and protecting our rights.

We do **not** sell personal data.

We do **not** use your workout history as part of a public social feed.

We do **not** send your workout text, exercise names, weights, repetitions, notes, concrete training history, or personal fitness details to Firebase / Google Analytics or to the minimal aggregate counter system.

## 7. Legal Bases

Where EU, EEA, UK, or similar data protection law applies, we process personal data on one or more of the following legal bases, depending on the context:

- **performance of a contract** or steps taken at your request before entering into a contract,
- **legitimate interests** in operating, securing, improving, and supporting Fi7Note,
- **compliance with legal obligations**,
- **consent**, where consent is required.

Optional Firebase / Google Analytics usage analytics is based on your consent. You can withdraw this consent later in Profile.

Where the transmission of network information in connection with the minimal aggregate counter constitutes processing of personal data, we rely on our legitimate interests in operating and improving Fi7Note and understanding basic product and funnel performance. The counter is deliberately data-minimized: it uses no persistent user, installation, advertising, Firebase, or device identifier and does not create individual usage profiles.

Where workout-related input or related information is regarded as sensitive or special-category personal data under applicable law, we process it only to the extent necessary for the specific functionality you actively use and on an applicable legal basis and additional condition under that law, including your explicit choice to enter and use such information in the app where required.

## 8. On-Device Processing and Local Storage

A central characteristic of Fi7Note is that the app’s core parsing and storage model is local-first.

In ordinary use, workout text and the resulting structured workout data are processed on your device rather than being sent to us as part of a general cloud logging workflow.

Your saved app data may remain on your device unless:

- you edit or delete it,
- you clear app storage,
- you uninstall the app,
- your device, operating system, or platform removes app data or cached components,
- you voluntarily send information to us through a support, feedback, or correction-sharing flow,
- you enable optional Firebase analytics, which sends only abstract usage events and technical analytics metadata as described above,
- or the app sends the minimal aggregate usage counters described in Section 5.5.

Downloaded or cached app assets, including model-related or platform-managed artifacts, may be managed differently from your user-created workout history.

## 9. Google Play Billing, Trial, and Access

Fi7Note is offered through Google Play.

Depending on the offer shown to the user in Google Play, Fi7Note may be available through:

- a monthly subscription,
- a yearly subscription,
- and/or a one-time Lifetime Access purchase.

An eligible subscription offer may include a free trial, including a 14-day free trial where offered in Google Play.

Unless cancelled before the trial ends, the selected subscription converts into a paid subscription and renews automatically according to the billing interval shown in Google Play until cancelled.

Lifetime Access is a one-time purchase and does not auto-renew.

Billing, payment processing, taxes, renewals, cancellations, refunds, billing disputes, and store-level purchase management are handled by Google Play under Google’s applicable terms, policies, and infrastructure.

Deleting the app does not by itself cancel a subscription.

## 10. Firebase Analytics Consent, Withdrawal, and Aggregate Counters

Firebase / Google Analytics usage analytics is disabled unless you actively allow it.

During onboarding, Fi7Note asks whether you want to continue with analytics or without analytics. You can use Fi7Note either way.

If you allow analytics, Fi7Note may send the limited abstract events described in this Policy from that point forward.

If you decline analytics, Fi7Note does not send analytics events to Firebase / Google Analytics, and the app continues to work normally.

You can change your analytics choice later in Profile.

If you turn analytics off later, Fi7Note stops sending future analytics events. The app also asks the Firebase Analytics SDK to disable analytics consent and reset analytics data where technically available. However, data that has already been processed into aggregated analytics reports may not always be removable from all historical reports.

Fi7Note does not send a separate Firebase analytics event simply saying that you granted or denied analytics consent.

The analytics consent setting described in this section controls Firebase / Google Analytics. It does **not** control the minimal aggregate counter system described in Section 5.5. Those counters operate independently and may therefore be sent whether you allow or decline optional Firebase analytics. The counter system does not use Firebase identifiers and does not create an individual user or installation profile.

## 11. When Data May Leave the Device

Fi7Note is not designed to continuously transmit workout history to us as part of a general cloud-sync model.

Data may leave the device only in limited situations such as:

- when this is necessary for Google Play purchase or entitlement handling,
- when the app sends the minimal aggregate usage counters described in Section 5.5,
- when you allow optional Firebase / Google Analytics usage analytics,
- when you contact us by email,
- when you voluntarily submit a support request,
- when you voluntarily send product-quality feedback,
- when you choose to share review corrections or related quality context,
- when disclosure is required by law,
- or where limited off-device processing is otherwise necessary for a specific feature you intentionally use.

Even when you do not allow optional Firebase analytics or use support/correction-sharing features, the minimal aggregate counters described in Section 5.5 may still leave the device. Your workout content and concrete workout history remain local unless another specific feature described in this Policy causes them to be transmitted.

## 12. Sharing and Disclosures

We do not share personal data with third parties for their own independent advertising purposes.

We may disclose or make data available only where necessary to:

- Google Play and related Google services involved in billing, entitlement, app distribution, or platform operations,
- Cloudflare, as an infrastructure and processing provider for the minimal aggregate counter endpoint and D1 database,
- Firebase / Google Analytics, if you allow optional analytics,
- Google Ads, if Firebase / Google Analytics is linked for campaign or conversion measurement,
- hosting, infrastructure, support, communications, or storage providers acting on our behalf,
- professional advisers where reasonably necessary,
- legal, regulatory, judicial, or public authorities where required by law,
- successors or counterparties in a merger, acquisition, restructuring, or similar transaction, subject to applicable law.

Where third-party service providers process data for us, they do so only under appropriate contractual or legal controls, where required.

Fi7Note does not send share recipients or the names of other apps you share to as part of its analytics events.

## 13. International Transfers

If personal data is processed by service providers or platform providers outside your country, including outside the European Economic Area or the United Kingdom, such data may be transferred internationally.

Where required by applicable law, we rely on an adequacy decision, standard contractual clauses, or another valid transfer mechanism.

Google services, including Google Play, Firebase, Google Analytics, and Google Ads, may involve processing in countries outside your country of residence, subject to Google’s applicable terms, policies, and transfer mechanisms.

Cloudflare is a global infrastructure provider headquartered in the United States. Cloudflare may process network traffic and related service data through its global network. Cloudflare states that, where it acts as a processor, it processes customer and end-user content on behalf of its customers under its applicable data processing terms. The D1 database used by Fi7Note for the aggregate counters is configured with an EU jurisdiction, so the persisted D1 database is restricted to running and storing its database data within the European Union. This jurisdiction setting does not mean that all Worker request processing is necessarily limited to the EU. Where an international transfer requires a transfer mechanism, Cloudflare's applicable contractual and legal transfer safeguards may apply.

Cloudflare privacy information is available at: https://www.cloudflare.com/policies/privacy/

## 14. Retention

We retain personal data only for as long as necessary for the purposes described in this Policy.

In general:

- **local workout history and settings** remain on your device until changed, deleted, or removed by you, or until device/platform behavior removes them,
- **purchase and entitlement information** is retained as long as reasonably necessary for access control, accounting, dispute handling, legal compliance, and support,
- **support, feedback, and correction submissions** are retained as long as needed to handle the issue, improve the product, document the matter, and comply with legal obligations,
- **email correspondence** is retained as long as reasonably necessary for the communication and related legal or operational purposes,
- **technical support logs or diagnostic materials** are retained only as long as needed for the relevant support, quality, security, or compliance purpose,
- **Firebase / Google Analytics data** is retained according to the relevant Firebase / Google Analytics settings and Google’s applicable policies,
- **minimal aggregate counter data** is stored as aggregate daily counts by event and app version for as long as reasonably necessary to compare product and funnel performance over time. These counter records do not contain a Fi7Note user ID, installation ID, Firebase ID, advertising ID, Android ID, session ID, or workout content. Cloudflare may retain limited service, security, or operational metadata according to its applicable service configuration, legal obligations, and policies.

Retention periods may be longer where required or permitted by law.

## 15. Security

We take reasonable technical and organizational measures to protect personal data against unauthorized access, loss, misuse, alteration, or disclosure.

However, no method of electronic storage, transmission, or device security is completely risk-free. You are also responsible for securing your device, operating-system access, backups, and local environment.

Where data is transmitted off-device as part of a support, purchase, feedback, correction-sharing, optional analytics, or aggregate-counter process, we use reasonable safeguards appropriate to the nature of that transmission. Counter requests are transmitted over HTTPS. Fi7Note’s D1 counter database is configured for EU jurisdiction and Cloudflare D1 encrypts stored database data at rest and data in transit within its service infrastructure.

## 16. Accuracy and User Review

Fi7Note is built to handle messy, real-world workout input, but parsing results may still require review.

You are responsible for checking and correcting workout entries, values, units, notes, and structured results before relying on them.

Fi7Note is a journaling and tracking tool only. It is not medical advice, diagnosis, treatment, coaching, or emergency guidance.

## 17. Your Rights

Depending on your jurisdiction, you may have rights including:

- access to personal data,
- rectification of inaccurate data,
- erasure,
- restriction of processing,
- objection to processing,
- data portability,
- withdrawal of consent where processing is based on consent,
- and the right to lodge a complaint with a competent supervisory authority.

Because Fi7Note is primarily local-first and does not require a general Fi7Note account for core use, some rights may need to be exercised directly on your device where the relevant data is stored only locally.

You can withdraw optional Firebase / Google Analytics consent in the app’s Profile settings. This setting does not disable the minimal aggregate counters described in Section 5.5.

For privacy-related requests, contact: materialize.thoughts@gmail.com

## 18. Children

Fi7Note is not directed to children under the minimum age required by applicable law in their jurisdiction.

We do not knowingly seek to collect personal data from children through Fi7Note. If you believe a child has provided personal data inappropriately, contact us.

## 19. Changes to this Policy

We may update this App Privacy Policy from time to time.

If we do, we will publish the updated version and update the effective date above. Material changes may also be reflected through the app, the website, the app store listing, or another appropriate channel where required.

## 20. Contact

For privacy-related questions, requests, or complaints, contact:

**Pascal Schönfeld**  
Materialize Thoughts  
Marrensberg 9  
24944 Flensburg  
Germany  
Email: materialize.thoughts@gmail.com

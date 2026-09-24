# Privacy Policy — Sistr

Last Updated: 2026/9/25

## 1. Acceptance of Terms

Sistr ("Sistr", "we", "us", or "our") is committed to protecting your privacy. This Privacy Policy applies to Sistr and its various versions and is part of our Terms of Service. By accessing or using our Application, you acknowledge and fully understand this Privacy Policy and freely consent to the practices described here.

Sistr is a Bible app for women: retold Bible stories, daily affirmations, verses and devotionals. We have designed the app, and this policy, around collecting as little information as possible. **None of the data collected by this app is linked to your identity.**

## 2. Data We Collect

We collect the following categories of data, none of which is linked to your identity:

### User Content

**First Name** — Used for App Functionality, stored on-device (declared as "Name" on the App Store)

The app asks for a first name so greetings and stories feel personal. You may leave it empty or use any name you like. The name is stored only on the device, in standard iOS user preferences. It **is included in the story request sent to the AI provider that writes story text** so the reflection and prayer can address you, and it **is included in the narration text sent to the text-to-speech provider** so the narrator can pronounce it. It is not sent to the AI provider that paints illustrations, and no other identifying metadata is attached to any request.

**Date of Birth, Seasons of Life and Story Requests** — Used for App Functionality

You may enter your date of birth and pick the seasons of life you are in (for example motherhood, healing, a new faith). The date of birth is stored only on the device; only your **age in whole years** is sent to the AI provider so stories fit your stage of life — **the date itself is never transmitted**. When you ask for a story for what you are facing, you choose from a fixed list of themes; the chosen theme and your seasons are sent so the story can speak into them. There is no free text field. Story length is sent as a preference. None of this is linked to your identity.

### Identifiers

**Anonymous Device ID** — Used for App Functionality, Analytics, and Other Purposes

An anonymous device identifier is collected to ensure secure and reliable AI service routing, to manage your subscription, and to count app usage in aggregate. This identifier is not linked to your personal identity and is not used for advertising or cross-app tracking.

### Purchases

**Purchase History** — Used for App Functionality, and Analytics

If you make an in-app purchase, transaction data is processed by Apple and RevenueCat to manage the subscription. This data is used to provide access to premium features and to analyze purchasing trends in aggregate. RevenueCat may also receive Apple's anonymous ad attribution token, which tells us whether the app was found through an Apple Search Ads campaign; it contains no personal information.

### Usage Data

**Product Interaction** — Used for Analytics

We collect anonymous data about how the app is used (for example which screens are opened and which features are used) through Firebase Analytics. This helps us understand how the app is used and improve it. It is not linked to your identity and is not used for advertising.

### Diagnostics

**Crash Data and Performance Data** — Used for App Functionality

Crash reports and basic diagnostic information (for example error logs) are collected through Firebase Crashlytics to help us find and fix issues that affect the app's stability.

### Other Data

**Other Data Types** — Used for App Functionality, Analytics, and Other Purposes

Anonymous service data, including IP address, is collected by our AI routing proxy to ensure secure AI service delivery, and your age in whole years travels with a story request as described in Section 3. This data is not linked to your identity.

## 3. How AI Story Generation Works

This section describes in detail how Sistr processes story generation.

### What is sent to our AI provider for story text?

When a story is generated, the following is sent to our AI provider (OpenRouter, Inc., via the AIProxy routing service):

- Your first name, if you gave one, so the reflection and prayer can address you.
- Your age in whole years, if you gave a date of birth — **not** the date itself.
- The seasons of life you picked and, for a story for today, the theme you chose from the list.
- Your story length preference and whether the reflection should include a modern day picture.
- The Bible passage or Holy Path story the telling is based on.

### What is sent to our text-to-speech provider for narration?

When narration audio is generated, the finished story text, which may contain your first name in the reflection and prayer so the narrator can pronounce it, is sent to our TTS provider (ElevenLabs, via AIProxy) together with the voice you chose. The TTS provider receives only the text and voice settings; no other identifying metadata is attached.

### What is sent to our AI provider for illustrations?

Image prompts are written by the text AI and describe the scenes of the story. They are not meant to contain your name and carry no other information about you.

### Is any of this data retained?

No. Generated stories, illustrations and audio are returned to the device for local reading, playback and your story library. Our AI and TTS providers process the request and return the result; we do not maintain copies of prompts, generated stories, images or audio on our own servers.

### Consent

Before the first story request, the app asks for your explicit consent to send the data above to our AI providers. You can withdraw it at any time by deleting your data from Settings, which also resets the consent.

### Summary

| Question | Answer |
|----------|--------|
| Is my first name sent to the text AI? | Yes, if you gave one, so the reflection and prayer can address you. |
| Is my first name sent to the illustration AI? | No. Image prompts describe scenes only. |
| Is my first name sent to the text-to-speech AI? | Yes, inside the story text so it can be voiced. No other identifying metadata is attached. |
| Is my date of birth sent? | No. Only your age in whole years. |
| Can I type free text into a story request? | No. You choose from a fixed list of themes. |
| Are stories stored on your servers? | No. They live only on the device. |
| Is any usage activity tracked? | Anonymous, aggregate usage and crash data only, through Firebase. No advertising, no cross-app tracking. |

## 4. Daily Reminders and Widgets

If you turn on the daily reminder, the app schedules a local notification on your device with the day's affirmation. Nothing is sent to us or to any push notification service; the schedule and its content are computed on the device. The Home Screen and Lock Screen widgets read the day's affirmation, verse and your progress from a small file the app writes on the device. Widgets make no network requests.

## 5. Children's Privacy

Sistr is intended for adults and is not directed at children under 9. We do not knowingly collect personal information from children. If you believe a child has provided data through the app, please contact us at tunahanaktay.apps@gmail.com and we will delete it immediately.

## 6. Third-Party Services

We use the following third-party services:

- **OpenRouter, Inc.** — AI-powered story text and illustration generation. Receives only the prompts described in Section 3. Privacy policy: https://openrouter.ai/privacy
- **ElevenLabs, Inc.** — AI-powered narration. Receives the finished story text and the voice settings. No other identifying metadata is attached. Privacy policy: https://elevenlabs.io/privacy
- **AIProxy** — Secure AI service routing in front of OpenRouter and ElevenLabs. Uses an anonymous stable device identifier and collects IP address for security purposes. Privacy policy: https://www.aiproxy.com/privacy
- **RevenueCat** — Subscription and purchase management. Collects device identifiers, purchase history and Apple's anonymous ad attribution token to manage entitlements. Privacy policy: https://www.revenuecat.com/privacy
- **Firebase (Google)** — Analytics (anonymous, aggregate usage), Crashlytics (crash and diagnostic reports) and Remote Config (operational configuration such as force-update and maintenance-mode notices). Keyed by an anonymous Firebase Installation ID. **No advertising.** Privacy policy: https://policies.google.com/privacy
- **Apple In-App Purchases** — Secure transaction handling under Apple's privacy policy.

These services process data only to the extent required for their core functions. None of the data collected is linked to your personal identity.

## 7. Data Retention

- **First name, date of birth, seasons and story preferences:** Stored only on the device, in standard iOS user preferences. Removed when you delete your data from Settings or delete the app.
- **Generated stories, illustrations and audio:** Stored only on the device, in the app's local story library. Removed when you delete a story, delete your data from Settings, or delete the app.
- **Holy Path progress, streak and the reminder schedule:** Stored only on the device. Removed when you delete your data from Settings or delete the app.
- **Prompts sent to AI providers:** Not retained by us. Subject to the AI providers' own retention policies, which do not link the prompts to your identity.
- **Analytics and crash data:** Retained by Firebase according to Google's retention policies, keyed by an anonymous installation identifier.
- **Purchase information:** Managed by Apple and RevenueCat under their respective privacy and retention policies.
- **No user data is linked to your personal identity.**

## 8. Data Security

- All data transmission between the device, our services, and third-party providers is encrypted.
- Story generation is fully automated with no human access to prompts or outputs.
- No employee has access to your content unless you explicitly request support.
- We do not collect, store, analyze, or share photos, biometric or facial data.
- We apply appropriate technical and organizational measures to protect your data. While no system can guarantee 100% security, we continuously work to safeguard your information.

## 9. Your Rights

You have the right to:

- Understand what data is collected and how it is used (this Privacy Policy).
- Review the third-party services we use (Section 6).
- Delete everything the app keeps about you at any time from Settings → Delete my data, which removes your name, date of birth, seasons, stories, progress and streak from the device and resets your AI consent. Your subscription is not affected.
- Delete the app from the device, which removes all locally stored data.
- Contact us with questions or requests, including requests under the GDPR or the CCPA.

## 10. International Transfers

Some AI processing, analytics and crash diagnostics may occur on cloud servers located outside your country, including in the United States. All processing is done under secure, GDPR-compliant infrastructure.

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The updated version will be posted here with a revised "Last Updated" date. Continued use of the Application constitutes acceptance of the updated terms.

## 12. Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact us:

Email: tunahanaktay.apps@gmail.com

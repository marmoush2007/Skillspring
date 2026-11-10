# SkillSpring — Combined V1–V5 prototype

## Included
- V1: Responsive learning dashboard, lesson search and categories.
- V2: Local learner profile and saved progress.
- V3: 12 lessons, 7 rotating daily practice prompts, progress and streak tracking.
- V4: Free/Plus preview, premium lesson gating demo, printable informal completion certificate.
- V5: PWA manifest, service worker cache, app icon and installability metadata.

## Run it
For a quick preview, open `index.html` in a browser. For PWA installation and offline caching, serve this folder over HTTPS (or localhost); service workers do not work from a `file://` URL. A static host can serve these files.

## Important limitations
This is a front-end prototype. Profiles and learning progress are stored only in the current browser/device. There is no real secure authentication, cloud sync, administrator dashboard, payment processing, subscription verification, or accredited certificate service. The Plus toggle is a no-charge demo only. Do not enter sensitive information. Before real users or sales, add a secure backend, privacy policy, data deletion/export, age-appropriate safeguards, verified payment provider integration, server-side entitlement checks, and security testing.

## Android / Google Play
This package is a PWA source bundle, not an Android APK or signed Android App Bundle (.aab). To publish on Google Play, an adult account owner/developer must create and verify the Play Console account, build/package the app as an Android app, complete store listing and policy declarations, test it, and submit it for review. New personal Play Console accounts are subject to Google's closed-testing requirement (currently 12 opted-in testers for 14 continuous days before applying for production access). Check current official Play Console requirements before submission.

## Suggested next production tasks
1. Deploy this PWA on HTTPS.
2. Build backend authentication and database.
3. Integrate a compliant payment provider only after business/legal review.
4. Add privacy policy, terms, support contact, and content review.
5. Package an Android release and test on multiple devices.

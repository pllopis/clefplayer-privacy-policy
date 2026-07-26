# clefPlayer Privacy Policy

Last updated: July 26, 2026

clefPlayer is a piano-learning app. The app itself does not require an account and does not transmit personal data to its own servers — the app has no servers. The only data that leaves your device is processed by the third-party SDKs listed below, in order to serve ads, validate purchases, and fetch feature flags.

## What the app stores locally on your device

These never leave your device unless you uninstall the app (in which case they are deleted):

- The start timestamp of your 7-day free trial (so the app knows when it expires).
- MIDI files you upload for practice.
- App settings (selected MIDI devices, score layout, tempo, hand mode, etc.).
- Sight-reading practice history (last 5 sessions per scale).

## Third-party SDKs and what they process

### Google Mobile Ads (AdMob)

Used to show banner and interstitial ads to free-tier users who have chosen the ad-supported option after their trial expires. AdMob may collect:

- A resettable device identifier and IP address (used to serve ads and prevent fraud).
- IDFA, **only if you grant App Tracking Transparency permission** when prompted. If you deny, only non-personalized ads are used.
- Coarse, non-precise location derived from IP address.
- Aggregate ad-performance metrics.

Google's privacy policy: https://policies.google.com/privacy

### Google UserMessagingPlatform (UMP)

Used to request GDPR consent from users in the European Economic Area, the United Kingdom, and Switzerland before loading ads. Stores your consent choice on your device. Subject to Google's privacy policy (above).

### Firebase Remote Config (operated by Google)

Used to fetch feature flags (for example, whether the ad-supported tier is enabled). Transmits a resettable app instance identifier and IP address. **Firebase Analytics is disabled** in this app — no events, screens, or user behavior are sent to Firebase.

### RevenueCat

Handles in-app purchases and restores. Transmits an anonymous app user ID and Apple-receipt data to validate that a purchase is legitimate and to restore it on a new device. Payment itself is processed by Apple's App Store; RevenueCat does not see or store your payment instrument. RevenueCat privacy policy: https://www.revenuecat.com/privacy

## App Tracking Transparency

On first launch, the app will ask for permission to track. If you grant it, AdMob may use IDFA to serve more relevant ads. If you deny, the app continues to work fully — only the ads are non-personalized. Tracking permission can be changed any time in iOS Settings → clefPlayer → Allow Tracking.

## Choices and controls

- **Tracking:** iOS Settings → clefPlayer → Allow Tracking. Or reset all advertising identifiers at iOS Settings → Privacy & Security → Tracking.
- **Ads:** Remove all ads with a one-time purchase from inside the app.
- **Consent (EEA/UK/CH):** Re-open the consent form any time from the app's settings if available, or by reinstalling the app.
- **Local data:** Uninstalling the app deletes all locally stored data listed above.
- **AdMob personalization:** Google Ads settings at https://adssettings.google.com.

## Data retention

- Locally stored data is kept until the app is uninstalled.
- AdMob and Firebase retain data according to their own published retention policies (linked above).
- RevenueCat retains purchase records for the lifetime of the app's account with them, as required for restore and fraud prevention.

## Children

The app is not directed at children under 13 (US COPPA) or under 16 (GDPR-K). No personal data is knowingly collected from children. AdMob is configured to not serve interest-based ads to users where age is unknown.

## Security

The app does not transmit personal data over unencrypted connections. All SDK network calls use HTTPS.

## Changes

This policy may be updated. The "Last updated" date at the top will reflect the most recent change.

## Contact

For support, contact pablollopis@protonmail.com

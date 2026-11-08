# Privacy Policy for OpenSound

**Last Updated:** November 8, 2026  
**Effective Date:** November 8, 2026

## 1. Overview
OpenSound is a 100% free, open-source soundboard application built with user privacy as its core principle. OpenSound operates entirely offline and does not collect, transmit, store, track, or share any personal information, usage metrics, or telemetry.

## 2. Information We Do NOT Collect
- **Zero Personal Data:** We do not collect names, email addresses, phone numbers, location data, IP addresses, or device identifiers.
- **Zero Analytics & Tracking:** OpenSound contains no analytics libraries (e.g., Google Analytics, Firebase), no crash reporting SDKs, no tracking pixels, and no behavioral monitoring.
- **Zero Advertising:** There are no advertisements, ad networks, or commercial tracking services embedded in OpenSound.
- **Zero Cloud Storage:** OpenSound does not host user accounts or sync data to external servers. All custom soundboards, presets, and audio recordings exist exclusively on your local device.

## 3. Device Permissions & How They Are Used
OpenSound requests only the minimum permissions necessary to deliver local user-initiated features. No data accessed via these permissions ever leaves your device:

- **Camera (`android.permission.CAMERA`):**  
  Used exclusively when you open the in-app QR scanner to scan soundboard presets shared by another device. Camera feed processing happens entirely in volatile memory via local ZXing decoding. No images, video frames, or metadata are ever captured, saved, or uploaded.
- **Microphone (`android.permission.RECORD_AUDIO`):**  
  Used exclusively when you record a custom sound for a tile. The recording is saved strictly to your local storage or app sandbox. Audio data is never transmitted across any network.
- **Near-Field Communication (`android.permission.NFC`):**  
  Used for peer-to-peer sound sharing via Android Host Card Emulation (HCE) when you explicitly choose to beam a sound to another device via NFC.
- **Storage (`READ_EXTERNAL_STORAGE` / `WRITE_EXTERNAL_STORAGE`):**  
  Used solely to allow you to import custom sound files (WAV, MP3, OGG) from your device and export soundpacks to your device storage.
- **Vibration (`android.permission.VIBRATE`):**  
  Used solely to provide tactile haptic feedback when tapping tiles.

## 4. Third-Party Services & Links
OpenSound does not integrate with any third-party APIs, web services, or data brokers. If the app displays a link to an external website (such as the project source code on GitHub), your interaction with that website is governed by that third party's privacy policy.

## 5. Children's Privacy
Because OpenSound collects no personal data whatsoever, it is fully compliant with COPPA (Children's Online Privacy Protection Act) and GDPR-K. OpenSound does not knowingly collect or solicit any information from children under 13 (or any age).

## 6. Open Source Transparency
OpenSound is published as free and open-source software. You are encouraged to inspect, audit, and compile the full source code yourself to independently verify all privacy and security claims.

## 7. Changes to This Policy
Because OpenSound does not collect data or maintain user contact information, any updates to this policy will be published directly to the project GitHub repository.

## 8. Contact
If you have any questions or feedback regarding this Privacy Policy, please open an issue on the project GitHub repository.
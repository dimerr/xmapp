---
layout: default
title: Privacy Policy
permalink: /privacy/
---

**Effective date:** 10 November 2026  
**App:** XMApp  
**Developer:** Dmitry Ermakov, individual developer  
**Contact:** dimerrrr@icloud.com

XMApp is a mobile client for XM-compatible cameras and network video
recorders (NVRs). This policy explains what information the app processes,
where it goes, and the choices you have.

## Summary

- XMApp does not require an account.
- XMApp does not contain advertising, analytics, or cross-app tracking.
- The developer does not operate servers that store your camera video, audio,
  device list, or credentials.
- Device settings, names, and media you save stay on your phone.
- Camera passwords are stored in the platform secure storage: iOS Keychain or
  Android Keystore-backed storage.
- To connect to cameras, XMApp uses XCloudSDK, which contacts P2P, status, and
  licence servers. Those servers receive technical connection data such as the
  camera serial number and network address.
- You can configure custom P2P and status servers in Expert settings.

## Information the app processes

### Devices you add

When you add a camera or NVR, the app stores:

- the device name;
- the serial number or IP address;
- the username;
- the connection mode;
- channel names and other settings you enter.

Passwords are stored separately in the platform secure storage. Device names,
serial numbers, usernames, and settings are stored in the app's local
preferences.

If you export your device list, the app creates a file in a location you
choose. By default, passwords are not included. If you explicitly choose to
include passwords, the export file contains them in readable form; you are
responsible for that file and should share it only with people you trust.

### App settings and local media

The app stores preferences such as language, theme, stream type, server
settings, and access level locally.

Screenshots, local recordings, downloaded videos, and thumbnails are stored in
the app's Documents or cache directories. They stay on your device unless you
share or export them. Files in the app's Documents directory may be visible in
the Files app because file sharing is enabled.

### Camera video and audio

Live view, playback, and two-way talk are transmitted between your phone and
your camera or NVR. When a direct local connection is not possible, the
connection may be relayed through a P2P service. The developer does not
receive, store, or view your camera video or audio.

Two-way talk uses your microphone only while you hold the talk control. The
camera's audio is played through your phone's speaker or headphones.

### Network and permissions

The app requests permissions only for the features you use:

| Permission | Why it is used |
| --- | --- |
| Camera | Scan device and configuration QR codes. |
| Microphone | Two-way talk with a camera. |
| Local network | Find and connect to cameras on your Wi-Fi/LAN. |
| Location (when in use) | Read the current Wi-Fi network name so a camera can be configured. The app does not use this permission to determine your physical location. |
| Notifications | Show download progress and alarm notifications if you enable them. |
| Files | Import firmware, device lists, or other files you select; export device lists and media. |

You can change or revoke permissions in the operating system settings. Some
features will not work without them.

### Diagnostics and crash data

The app does not include a third-party crash-reporting or analytics SDK. Apple
or Google may collect crash reports or diagnostic data according to your device
settings and their own policies. The developer does not combine that data with
your identity.

## Third-party services and SDKs

### XCloudSDK (fcloudsdk)

XMApp uses XCloudSDK, distributed by JF Tech, to connect to cameras and to
validate the app's platform licence.

By default, XCloudSDK contacts:

- a P2P server at `178.170.194.200:7999`;
- a status server at `pub-status.secu100.net:7600` using TLS;
- a licence/cloud server at `ams.jftechws.com`.

These services receive technical data needed to establish and maintain a
connection, such as the camera serial number, network address, app and platform
identifiers, and connection metadata. They use this data to provide P2P/status
connectivity and licence validation. The developer does not use it for
advertising or cross-app tracking.

The SDK vendor's own privacy policy and terms apply to its processing. XMApp is
not affiliated with JF Tech or XCloudSDK.

If you configure custom P2P or status servers in Expert settings, those servers
receive the connection data instead. Licence validation may still contact the
SDK vendor's cloud service.

### ML Kit barcode scanning

The app uses Google ML Kit to detect QR codes. Barcode detection runs on the
device. The app does not upload camera frames to Google for scanning. Google's
own terms and privacy policy apply to ML Kit.

### Platform services

The app uses Apple iOS or Google Android services for secure storage,
notifications, file selection, and media access. Those services are governed by
the platform provider's privacy policy.

## What the app does not do

- It does not create a user account or ask for your email address.
- It does not contain advertising.
- It does not use analytics or cross-app tracking.
- It does not sell or rent personal information.
- It does not collect your contacts, photos, or precise location.
- It does not run in the background to record video or audio.

## Data sharing

The app shares data only:

- with the camera or NVR you connect to, to authenticate and control it;
- with the P2P, status, and licence services described above, to establish the
  connection and validate the licence;
- with a destination you choose when you export or share a file;
- when required by law or to protect legal rights.

The developer does not sell personal information.

## Retention and deletion

Local data remains on your device until you delete it:

- delete a device in the app to remove its saved settings and password;
- delete media in the Gallery or the Files app;
- clear the app's data in the operating system settings;
- uninstall the app.

On iOS, Keychain items can survive an app uninstall. If you want to remove
saved camera passwords, delete the devices in the app before uninstalling. On
Android, clearing app data or uninstalling removes the app's local storage
according to the platform's behavior.

The developer does not hold an account or a copy of your device list. Data
processed by the P2P, status, or licence services is retained according to the
SDK vendor's policy; the developer does not control that retention.

## Security

The app uses TLS for status and licence connections where the server supports
it, platform secure storage for camera passwords, and authenticated encryption
for custom QR codes. No method of transmission or storage is completely secure.
Use a strong device passcode and keep your phone and camera firmware up to
date.

## Children

XMApp is not directed to children under 13 (or under 16 in the European
Economic Area and the United Kingdom). Do not use the app if you are below the
applicable age. The app does not knowingly collect personal information from
children. If you believe a child has provided information, contact us.

## International transfers

The P2P, status, and licence services used by XCloudSDK may process data outside
your country. Their own policies describe their safeguards. If you configure
custom servers, the location depends on the servers you choose.

## Your rights

Depending on where you live, you may have rights to access, correct, delete, or
object to the processing of your personal information. Because the app does not
have an account and stores most data locally, you can exercise most of these
choices directly in the app. For questions or requests, contact the developer
at the address below. For data held by the SDK vendor or a custom server
operator, contact that provider.

## Changes to this policy

We may update this policy when the app changes. The effective date at the top
will be updated, and material changes will be communicated through the app or
the App Store listing. Continued use after an update means you accept the
revised policy.

## Contact

Dmitry Ermakov  
Email: dimerrrr@icloud.com

## Affiliation

XMApp is an independent application. It is not affiliated with, endorsed by, or
sponsored by XMEye, JF Tech, XCloudSDK, or any camera manufacturer. Product
names and trademarks belong to their respective owners.

## App Store privacy summary

| Data category | Collected | Linked to your identity | Used for tracking | Purpose |
| --- | --- | --- | --- | --- |
| Device ID (camera serial number) | Yes, by the P2P/status service | No | No | App functionality |
| Video or audio | No; streamed between your device and your camera | — | — | — |
| Contact information | No | — | — | — |
| Location | No | — | — | — |
| Usage data | No | — | — | — |
| Diagnostics | No | — | — | — |
| Purchases | No | — | — | — |

This table is a summary. The sections above describe the processing in more
detail.

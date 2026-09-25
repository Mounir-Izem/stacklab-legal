---
title: "StackLab — Privacy Policy"
---

[← Version française](index.html)

# Privacy Policy — StackLab

**Last updated: September 25, 2026**

StackLab is a precious-metals collection tracker developed by StackWar. This policy describes what the app does with your data — and above all, what it doesn't.

## The essentials, in four sentences

- **Your data stays on your phone.** StackLab has no account system, no server storing your collection, no cloud sync.
- **We collect nothing.** No usage analytics, no trackers, no ads, no identifiers.
- **The app's only network call fetches gold and silver prices**, and carries no information about you or your collection.
- **Your backups are encrypted**, and only leave your device when you share them yourself.

## What the app stores, on your device only

- **Your collection**: items, purchase prices, quantities, dates, notes, organisation into labs and cases. Stored in a local database inside the app's private storage.
- **Your item photos**: saved in the app's private storage. They are never uploaded anywhere, and are never analysed or run through image recognition — photo framing happens entirely on the device.
- **Your PIN** (if you enable App Lock) and **your backup keys**: kept in the system's secure storage — Android Keystore on Android, the keychain on iPhone. They are marked "this device only": never synced to any cloud, never included in a backup. They never leave the device.
- **Your settings**: currency, weight unit, language, backup preferences.
- **Public price history**: daily gold and silver prices, identical for everyone. This is not personal data — it says nothing about what you own.

## What travels over the network

**One thing only: price requests.** The app queries our price service for current and historical gold and silver prices. These requests:

- contain **no identifiers** — not of you, your device, or your collection;
- like any internet connection, transmit your **IP address** to the server; we do not link it to anything, and our service does not log the content of history requests;
- travel over HTTPS.

If you block all connectivity, the app remains usable — only live prices become unavailable.

## Your backups

- Automatic backups stay **inside the app's private storage**, on your device.
- Copies you export are **encrypted** with keys generated randomly on your device (ChaCha20-Poly1305 for a full copy, AES-256-GCM for a data-only copy). You alone hold the recovery kit that can open them elsewhere.
- A copy only leaves the device through **your explicit share action**, to a destination you choose. What that destination (for example your personal cloud storage) does with the copy is governed by its own policy, not ours.
- **On Android**, StackLab is **excluded from cloud backup and from automatic device-to-device transfer**: nothing goes to Google Drive without your knowledge.
- **On iPhone**, that exclusion does not exist: if you have iCloud Backup enabled, it takes the app's data along with your other apps', encrypted by Apple. Your PIN and your keys are excluded from it.
- **Your photos can travel with your backup.** At export you choose: a full copy, photos included, or a light copy, data only. Before any restore, the app tells you what the file contains. Photos travel encrypted, inside the same file, and never pass through any server.

## What we don't do

- No user accounts, no sign-up.
- No usage data collection, no analytics tools, no advertising trackers.
- No selling, sharing, or transferring data to third parties — we have nothing to sell: we hold nothing.
- No automatic crash reporting in the current version. If that ever changes, it will be stated here **before** activation, and will never include collection data.

Note: as with any app distributed through Google Play, Google may provide us with **aggregated, anonymous statistics** (installs, crashes) from devices whose users have opted into sharing usage data with Google. We have no access to anything individual.

## Permissions

- **Camera / photos**: requested only at the moment you add a photo, never before. Declining shows a clear message and blocks nothing else.
- **Face ID / fingerprint**: requested only if you choose to unlock the app with something other than your PIN. The check is performed by the system; the app only receives the result.

## Deleting your data

Your data is yours, and so is its deletion:

- from settings, **"Delete everything"** erases your collection: labs, cases, items, value snapshots, and photos. Your backup keys and your recovery kit are **deliberately kept**, so that copies you have already exported remain openable;
- **disabling App Lock** removes your PIN;
- **automatic wipe**, if you enabled it, goes further: after too many wrong PIN attempts, it also destroys the backup keys, the recovery kit, and the backups held on the device;
- **uninstalling the app** erases its local data. On iPhone, the PIN and the keys do however remain in the phone's keychain — that is how iOS behaves for any app;
- there is **no server-side copy** to delete — we cannot see your data, so we cannot retain it.

## Audience

StackLab is a wealth-tracking application intended for adults. It is not directed at children.

## Changes to this policy

Any change to the app that would alter the above will be reflected here before it ships. The last-updated date appears at the top of this document.

## Contact

For any question about this policy or your data: **stacklabs.app@gmail.com**

Publisher: Mounir Izem, sole proprietor trading as StackWar, France. StackLab is a product published by StackWar.

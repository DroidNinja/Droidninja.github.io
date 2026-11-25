---
title: "Sift SMS Privacy Policy"
date: 2026-11-24
draft: false
description: "Privacy policy for the Sift SMS Android app (com.droidninja.sift)."
showMetadata: false
url: "/sift/privacy/"
---

**Effective date: 2026-11-25**

Sift SMS ("Sift", package `com.droidninja.sift`) is an Android app made by **Arun Sharma**.
Contact: [arun2007ind@gmail.com](mailto:arun2007ind@gmail.com)

## Summary

Sift is an SMS/MMS app. It can be your default SMS app. Your messages, contacts and financial details
**stay on your device** unless you turn on Google Drive backup, which sends them only to your own Google Drive.
Sift has no servers, no accounts, no ads and no analytics. It does not use the
advertising ID. We do not sell or share your data.

## What Sift does with your messages

Sift reads, sends, receives and stores SMS and MMS **on your device**. It uses them to:

- show your conversations;
- sort your inbox into Personal, Transactions and Promotions;
- pick out one-time passwords (OTPs), amounts, bills and trips;
- build a finance view from your bank SMS;
- warn you about scam messages and risky links.

All of this happens on the phone. Message content is never sent to us. It leaves the phone only inside a
Google Drive backup that you turned on.

## Permissions and why Sift needs them

- **SMS and MMS** (read, send, receive, write, WAP push): core messaging as your default SMS app.
- **Contacts** (optional): to show names and let you search your contacts.
- **Phone state**: to choose which SIM to send from on dual-SIM phones.
- **Notifications**: to tell you about new messages, OTPs and bill reminders.
- **Biometric** (optional): for the Finance lock. Android handles the check. Sift never sees your fingerprint
  or face data.

## Backups

### Backup to a file

Sift can save a backup to a file you choose. Sift does not upload that file anywhere.

### Backup to Google Drive (Google Play version only)

This is **off by default**. The GitHub (FOSS) version has no Drive backup, only backup to a file.

- **Turning it on:** go to **Settings → Backup → Turn on backup** and pick your Google account in Google's own
  sign-in screen.
- **What is backed up:** all your SMS, received and sent (sender or recipient, text, time and read state), and
  Sift's own choices: blocked senders, Move-to rules, bills marked paid, Finance fixes (such as renamed or hidden
  accounts, and your names and UPI IDs) and app settings. MMS pictures are not backed up. Each backup file is
  also labelled with the time, the message count and your phone model.
- **Where it goes:** a hidden "app data" folder in your own Google Drive (Google scope `drive.appdata`). Only
  Sift can read this folder. Sift cannot see your other Drive files, and the folder does not appear in your
  Drive file list.
- **How it is sent:** straight from your phone to Google over HTTPS. Sift has no servers, and we (the developer)
  cannot read your backups. Google stores them under Google's own terms and
  [privacy policy](https://policies.google.com/privacy). Backups count toward your Google storage.
- **When it runs:** weekly by default (you can choose daily, monthly or off), on Wi-Fi only by default, and
  optionally only while charging. A backup is skipped when nothing has changed. Sift keeps the newest 2 backups
  and deletes older ones. You can tap **Back up now** at any time.
- **Restoring:** **Restore from Google Drive** (also offered when you set up a new phone) adds back messages that
  are not already on the phone.
- **Stopping and deleting:** **Settings → Backup → Turn off backup** stops backups and removes Sift's access to
  your Drive. An option there also deletes the backups from Drive. You can also delete them at
  [drive.google.com](https://drive.google.com) → Settings → Manage apps → Sift SMS → Delete hidden app data, and
  remove Sift's access at [myaccount.google.com](https://myaccount.google.com) → Security → Third-party
  connections. Removing access stops Sift from reaching your backups but does not delete them.

**How Sift uses your Google data:** Sift uses Drive access only to store and restore your own backups. It does
not use this data for ads, does not sell it, does not transfer it to others, and no human reads it. Sift's use
of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Crash and performance reports (Google Play version only)

These are **off by default**. If you turn on **Settings → Privacy → Send crash reports**, Google Firebase
Crashlytics and Firebase Performance Monitoring receive:

- the crash type and stack trace;
- your device model, Android version and app version;
- performance timings;
- a Firebase installation ID.

Crash messages are removed before sending, so reports never include message text, phone numbers or contacts.
Reports are encrypted in transit (HTTPS). Turning the setting off stops reports. See Google's
[Firebase privacy information](https://firebase.google.com/support/privacy).

## App updates

- **Google Play version:** updates use Google Play's in-app update, through the Play Store app.
- **GitHub (FOSS) version:** has an optional **Check for updates** setting, off by default. When on, Sift asks
  GitHub's releases API for the latest version and downloads the APK from GitHub. It sends nothing about you.
  GitHub sees a normal web request, including your IP address.

## Data retention and deletion

Sift stores its data on your phone. Uninstalling Sift or clearing its app data deletes it from the phone.

If you turned on Google Drive backup, your backups stay in your Drive until you delete them, either in Sift
(Turn off backup, with the option to also delete backups) or at drive.google.com → Settings → Manage apps →
Sift SMS → Delete hidden app data. Removing Sift's access at myaccount.google.com stops Sift from reaching the
backups but does not delete them. Sift keeps only the newest 2 backups.

If you turned on crash reports, Firebase keeps that data according to Google's retention rules
(about 90 days for Crashlytics).

## Children

Sift is not directed at children under 13.

## Changes to this policy

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions about this policy: Arun Sharma, [arun2007ind@gmail.com](mailto:arun2007ind@gmail.com).

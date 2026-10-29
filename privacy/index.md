---
title: Primed privacy policy
---

# Primed privacy policy

**Effective date:** 29 October 2026  
**Last updated:** 29 October 2026 (Primed now sends anonymous crash reports and usage statistics, which you can turn off)

Primed is an Android app that records when you trained each muscle group and tells you when its cooldown has passed. In this policy, "I" and "me" mean Primed's developer.

## Summary

- **Your training data never leaves your device** unless you choose to move it yourself: no training records, muscle names, durations or backups are ever sent.
- Primed sends **anonymous crash reports and usage statistics** to help me fix bugs and see which features are used. They are on by default, and you can turn them off at any time in **Settings › About** (see [Crash reports and usage statistics](#crash-reports-and-usage-statistics)).
- The app has no account and no ads, and it uses no advertising ID.
- Everything else the app stores stays on your phone. Uninstalling the app or clearing its data deletes it.

## What the app stores on your device

Primed keeps the following on your device, in the app's private storage:

- the time of each training record, per muscle group, and how early or late it was relative to the previous cooldown;
- your cooldown durations and preset;
- which muscles you track, and whether muscle groups are tracked as one;
- appearance settings: theme, accent colour and body figure;
- whether you have finished the introduction, and whether the app has asked for notification permission;
- whether crash reports and usage statistics are turned on.

The home-screen widget reads the same data on your device. None of this is sent to me or to anyone else.

## Permissions

- **Full network access** (`INTERNET`): used only to send the anonymous crash reports and usage statistics described below. Nothing else in the app uses the network.
- **Notifications** (`POST_NOTIFICATIONS`): to remind you when a muscle's cooldown has passed. You can decline or turn it off at any time; recording still works.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`): to reschedule those reminders after your phone restarts.

Reminders are scheduled locally with Android's alarm service. No server is involved.

The home-screen widget uses Android's WorkManager library to redraw itself, and that library adds three more permissions to the app:

- **Prevent the phone from sleeping** (`WAKE_LOCK`) and **run foreground service** (`FOREGROUND_SERVICE`): so the widget can finish redrawing in the background.
- **View network connections** (`ACCESS_NETWORK_STATE`): lets the library check whether the phone is online. The widget itself never uses the network.

## Crash reports and usage statistics

Primed sends two kinds of anonymous technical data, through two services that process it on my behalf. Both store it in the European Union.

**Crash reports**, sent through [Sentry](https://sentry.io) (Functional Software, Inc., EU region; [privacy policy](https://sentry.io/privacy/)). When the app crashes, it sends:

- the error and where in the code it happened (the stack trace), with any muscle names and long numbers removed before sending;
- technical details of the phone at that moment, such as the model, Android version, memory and screen, language and time zone;
- the app version, and which screens were opened or closed just before the crash.

Crash reports are kept for 30 days.

**Usage statistics**, sent through [Aptabase](https://aptabase.com) (Technov Solutions SRL, EU region; [privacy policy](https://aptabase.com/legal/privacy)). The app sends a short named event when you:

- open the app, or view a step of the introduction, or finish or skip it;
- choose a muscle level (Casual, Standard or Bodybuilding) for the upper body, lower body or core;
- log training, saying only whether it was from the cards or the tree and whether it was early, never which muscle;
- answer the notification permission request;
- choose an accent colour;
- export or import a backup, saying only which;
- open the Recovery, Progress or Settings screen, or a muscle's detail.

Each event also carries the app version, the Android version, the phone model and the language. Aptabase does not use cookies or identifiers stored on your phone; the app keeps a random session number in memory only, and Aptabase does not store IP addresses. Aptabase keeps usage statistics for up to 5 years.

**Never sent:** your training records or history, muscle names, durations, the times of your logs, backup contents, your email address, or any advertising ID.

**Turning it off.** Switch off **Share anonymous crash reports and usage statistics** in **Settings › About**. It takes effect immediately, for both crash reports and usage statistics, and you can turn it back on at any time.

## Backups and export files

- **Android backup.** If you have turned on backup for your Google account, Android may include Primed's data in that backup and restore it to a new phone. This backup is controlled by you and by Google under your Google account settings; I have no access to it.
- **Export.** Settings lets you export your data to a text file and import it again. The file contains your training records and settings. It is saved only where you choose, and what happens to it afterwards (for example, sharing it or uploading it) is up to you.

## Feedback by email

If you email me, for example through **Send feedback** in the app, I receive your email address, your message and anything you attach, such as the app version in the subject line. I use it only to reply and to fix problems, and I delete it when it is no longer needed for that. I don't share it with anyone.

## Children

Primed is not directed at children under 13 and collects no personal data from anyone.

## Not medical advice

The cooldowns in Primed are fixed-length estimates that you configure. They are not a measurement of recovery and not medical advice.

## Your choices

- To delete everything Primed stores, uninstall the app or clear its storage in Android Settings. You can also delete records one by one in the app.
- To stop reminders, turn off Primed's notifications in Android Settings.
- To stop crash reports and usage statistics, turn off **Share anonymous crash reports and usage statistics** in Primed's **Settings › About**.
- To keep Primed's data out of your Google backup, turn off backup for your device or account in Android Settings.

## Changes to this policy

If the app's handling of data changes, for example if a future version sends anything new, I will update this policy before that version is released and change the effective date above.

## Contact

Questions about this policy: [cmollnitzdev@gmail.com](mailto:cmollnitzdev@gmail.com)

---
title: Primed privacy policy
---

# Primed privacy policy

**Effective date:** 26 October 2026  
**Last updated:** 27 October 2026 (the permissions list now names every permission the installed app requests)

Primed is an Android app that records when you trained each muscle group and tells you when its cooldown has passed. In this policy, "I" and "me" mean Primed's developer.

## Summary

- Primed **collects no personal data**. Nothing you enter leaves your device unless you choose to move it yourself.
- The app has no account, no analytics, no ads, no crash reporting and no internet access. It does not request the Android `INTERNET` permission.
- Everything the app stores stays on your phone. Uninstalling the app or clearing its data deletes it.

## What the app stores on your device

Primed keeps the following on your device, in the app's private storage:

- the time of each training record, per muscle group, and how early or late it was relative to the previous cooldown;
- your cooldown durations and preset;
- which muscles you track, and whether muscle groups are tracked as one;
- appearance settings: theme and body figure;
- whether you have finished the introduction, and whether the app has asked for notification permission.

The home-screen widget reads the same data on your device. None of this is sent to me or to anyone else.

## Permissions

- **Notifications** (`POST_NOTIFICATIONS`): to remind you when a muscle's cooldown has passed. You can decline or turn it off at any time; recording still works.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`): to reschedule those reminders after your phone restarts.

Reminders are scheduled locally with Android's alarm service. No server is involved.

The home-screen widget uses Android's WorkManager library to redraw itself, and that library adds three more permissions to the app:

- **Prevent the phone from sleeping** (`WAKE_LOCK`) and **run foreground service** (`FOREGROUND_SERVICE`): so the widget can finish redrawing in the background.
- **View network connections** (`ACCESS_NETWORK_STATE`): lets the library check whether the phone is online. Primed never uses the network, and because it has no `INTERNET` permission it cannot send anything.

## Backups and export files

- **Android backup.** If you have turned on backup for your Google account, Android may include Primed's data in that backup and restore it to a new phone. This backup is controlled by you and by Google under your Google account settings; I have no access to it.
- **Export.** Settings lets you export your data to a text file and import it again. The file contains your training records and settings. It is saved only where you choose, and what happens to it afterwards (for example, sharing it or uploading it) is up to you.

## Feedback by email

If you email me, for example through **Send feedback** in the app, I receive your email address, your message and anything you attach, such as the app version in the subject line. I use it only to reply and to fix problems, and I delete it when it is no longer needed for that. I don't share it with anyone.

## Children

Primed is not directed at children under 13 and collects no data from anyone.

## Not medical advice

The cooldowns in Primed are fixed-length estimates that you configure. They are not a measurement of recovery and not medical advice.

## Your choices

- To delete everything Primed stores, uninstall the app or clear its storage in Android Settings. You can also delete records one by one in the app.
- To stop reminders, turn off Primed's notifications in Android Settings.
- To keep Primed's data out of your Google backup, turn off backup for your device or account in Android Settings.

## Changes to this policy

If the app's handling of data changes, for example if a future version adds analytics, I will update this policy before that version is released and change the effective date above.

## Contact

Questions about this policy: [cmollnitzdev@gmail.com](mailto:cmollnitzdev@gmail.com)

# Privacy Policy for RecMark

**Effective Date:** October 10, 2026
**Last Updated:** October 10, 2026

This Privacy Policy explains how RecMark ("the app", "we", "us") handles your data. RecMark is a native iPhone and iPad app for recreational athletes — it keeps your league schedule, reminds you before your games, and turns each game you log into a personal history of stats, records and highlights. The app is published by Jeremy Littlewood ("the developer").

## Summary

**RecMark does not collect, transmit, or sell any of your personal data to the developer or to any third party.** All of your data is stored locally on your device and, optionally, in your own private iCloud account.

**The app makes no network requests of its own.** It has no servers to talk to, no analytics, no advertising, and no account to sign up for. Everything it does — including reading a schedule you import and understanding a question you type — happens on your device.

If that summary is all you need, you can stop reading here. The remainder of this document explains the details.

## 1. Data the App Stores

RecMark stores the following categories of data **on your device** and, if you have iCloud enabled, **in your personal iCloud private database**:

- Teams you create: name, sport, league, colours, your jersey number and position, home venue, the other names your league uses for the team, which stats you track, and reminder choices
- Seasons, and the playoff answers you give (whether your team made it, and its seed)
- Games: date, time, opponent, venue, home or away, score and result, whether you played, your position, and the stats you log
- Notes, highlights, and the logos, banners and game photos you add
- For each imported game, the line of the schedule it came from, and a record of each import (the file's name and what it added or changed) so you can review or undo it
- Your first name and default jersey number, which follow you to your other devices through iCloud key-value storage
- App preferences and settings

The schedules you import — PDFs, screenshots, photographs, spreadsheets, calendar files, web pages, pasted text — are read on your device and are **not** kept by the app; only the games you choose to add are saved.

This data is stored using Apple's SwiftData framework. When iCloud sync is enabled, it is replicated across your own devices via Apple's CloudKit service in your iCloud private database. The developer cannot read or access data stored in your iCloud private database. Apple's CloudKit terms and Apple's Privacy Policy govern that storage. See https://www.apple.com/legal/privacy/.

RecMark's widgets, Control Center controls, and share extension read and write the same data on your device.

## 2. Information About Other People

A game history inevitably mentions other people and teams, so it is worth saying plainly how that is handled.

- Everything RecMark knows about anyone else is **entered by you** or comes from a schedule **you chose to import**: opponent team names, a doubles partner's name, and whatever you write in a note or a highlight.
- The app does **not** read your Contacts, and it asks for no Contacts permission.
- That information is stored exactly like the rest of your data — on your device and in your own private iCloud — and is never transmitted to the developer or to anyone else.
- When you share a share card or an export, the app hands it to the standard iOS share sheet, and you decide whether to send it and to whom. The app never sends anything on your behalf.

## 3. Data the App Does NOT Collect

The app does **not** collect, transmit, or process any of the following:

- Personal identifiers belonging to you (email address, phone number, government ID, etc.)
- Device identifiers used for advertising or tracking (IDFA, fingerprints, etc.)
- Location data of any kind. The app stores the venue **name** you type or import; it never asks for or reads your device's location. Tapping Directions hands that name to Apple Maps, which opens on your device
- Your Contacts, your microphone, or your health data
- Financial or payment information. RecMark has no purchases of any kind
- Usage analytics, crash telemetry, or feature-engagement data
- Any data that is sent to the developer's servers — because the developer operates no servers

The app contains **no** third-party analytics SDKs, no advertising SDKs, no crash reporting SDKs, no attribution SDKs, and no tracking pixels of any kind. It does not track you across other companies' apps or websites.

**There is no networking code in the app.** Apart from Apple's own iCloud sync, which carries your data to your own account, RecMark makes no outbound connections.

## 4. Calendar Access

RecMark can add your games to your calendar, so a game shows up beside everything else in your week. This is **off until you use it**, and calendar permission is requested only at that moment.

- You choose where games go: a calendar just for your games, or one of your own calendars.
- RecMark keeps the events it added up to date when a time or a place changes, removes them when a game is cancelled, and brings notes you write on those events back to the game. A new time or place you set in Calendar is offered to you, never applied on its own.
- To recognise its own events, RecMark looks for the link back to the game that it writes into each event. **It never stores, copies, or changes any other event**, and events someone else's copy of RecMark added to a calendar you share are left alone.
- iOS asks for full calendar access because that is what EventKit requires to keep events up to date. With "Add Events Only" access, you can still add a single game; RecMark just won't keep it up to date.
- Settings → Calendar → **Remove RecMark Events** takes out every event RecMark added for your games. You can also turn access off at any time in the Settings app.

## 5. Camera and Photographs

- **Camera.** You can scan a printed schedule, or take a team logo, banner, or game photo. A scan is read **on your device** and is not uploaded anywhere. Camera access is requested only when you use one of these features.
- **Photo library.** The app uses the standard iOS photo picker, which runs **outside the app**, in its own process. You choose exactly which images to hand over, and the app receives only those. RecMark cannot browse your library.
- **Saving a photo.** Saving a game photo back to your library asks only for permission to **add** photos — never to read them.
- Pictures you add are resized before they are saved with the rest of your data (Section 1).

## 6. Apple Intelligence and On-Device Processing

On a device with Apple Intelligence turned on, RecMark uses Apple's on-device foundation model to help with three things: reading an unusual schedule, understanding a game you describe in your own words, and answering a question about your history such as "How many goals did I score last season?".

- **All of it runs on your device.** The app uses only Apple's on-device model. It does not use Private Cloud Compute or any other off-device model, and a check in the app's own test suite fails if that ever changes.
- Nothing you type, photograph, or import is sent off your device for processing.
- Every one of these features has a complete path that works **without** Apple Intelligence, because many devices do not offer it. Nothing in the app requires it.
- Dates, times, scores, and stats are always worked out by ordinary code on your device and checked by you before anything is saved — a model never invents a result.

## 7. Notifications, Siri, and Spotlight

- Game reminders and "How'd it go?" prompts are scheduled **on your device**. Nothing is sent from a server. Notification permission is requested only when you turn reminders on.
- RecMark's Siri and Shortcuts actions run on your device. Requests you make to Siri are handled by Apple under Apple's privacy policy.
- Spotlight search of your games uses an index kept on your device.

## 8. Diagnostic Logs

RecMark writes diagnostic information, such as iCloud sync status, to the device's standard system log (via Apple's unified logging system). These logs stay on your device and are not transmitted to the developer. You can see sync status in the app's Settings.

If you choose to share analytics with app developers in your device's settings, Apple may pass on crash reports, which describe the crash and do not contain your games. Feedback you send through TestFlight reaches the developer only because you sent it.

## 9. Children's Privacy

RecMark is for recreational athletes of any age. It collects no personal information from anyone, children included: a young athlete's games stay on their own device and in their own private iCloud, exactly as described above.

## 10. Data Retention and Deletion

Because the developer does not have access to your data, the developer cannot delete data on your behalf. You control your data:

- To delete an individual record — a game, a season, a team — delete it inside the app. The deletion reaches your other devices through iCloud.
- To delete all data on a single device, delete the app from that device.
- To delete all data from your iCloud account: Settings → \[Your Name\] → iCloud → Manage Account Storage → RecMark → Delete Data.
- To remove the games RecMark added to Calendar, use Settings → Calendar → Remove RecMark Events in the app, or delete the calendar from the Calendar app.

## 11. Security

RecMark relies on Apple-provided security primitives:

- iCloud-synced data is encrypted in transit and at rest by Apple under the terms of CloudKit and iCloud.
- Data on the device is protected by the device's own encryption and passcode.
- The app holds no credentials, no API keys, and no account of any kind, because it connects to nothing.

No system is perfectly secure. If you discover a security vulnerability in RecMark, please contact the developer directly at the email address in Section 14 before disclosing it publicly.

## 12. Your Rights

Because the developer does not collect or process your personal data, there are no developer-side data subject requests to file. Your data lives on your devices and in your iCloud account, under your control, governed by Apple's terms. You may, at any time:

- Export a complete copy of your data from the app (Settings → Your Data → Export Everything), or your games and stats as a spreadsheet (Export Games & Stats).
- Delete your data from your devices and iCloud (see Section 10).
- Stop using the app at any time without giving notice.

## 13. Changes to This Policy

If this Privacy Policy is updated, the new version will be published at the same URL as this document, and the "Last Updated" date at the top will change. Material changes will also be noted in the app's release notes for the version in which they take effect.

## 14. Contact

If you have questions about this Privacy Policy, contact:

**Jeremy Littlewood**
Email: mission-sessile.5z@icloud.com

The developer typically responds within a few business days.

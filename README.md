# Hissley-privacy

Last updated: November 19, 2026
Developer: Divyanshu Rana (@pickmedavey)
Contact: **hissleytracker@gmail.com**
Personal or privacy matters: **biz.divyanshurana@gmail.com**

Hissley is a self-improvement app: you log quests, workouts, weight, notes and mood and earn XP. Your progress stays on
your phone unless you sign in, join the step leaderboard, join a friends crew or watch a rewarded ad.

## What we collect, why, and where it goes

| Data | Why | Where it goes |
|---|---|---|
| **Your progress**: quests, workouts and sets, body weight and body profile, notes, mood log, XP, streaks, achievements, settings | To run the app, draw charts and analytics, keep your streak | On your phone. Copied to the cloud only if you sign in (see Cloud save) |
| **Export my data** (Premium, only when you tap it in Master Insights): a zip of CSV files with your daily XP, workout sets, weigh-ins and their notes, daily steps, and mood and its notes, or a plain-text summary of that page | So you can keep your own numbers, open them in a spreadsheet or show them to a coach | On your phone only. Not uploaded: a temporary copy in the app's cache goes only where you send it from Android's share sheet, and is cleared once it is a day old, the next time you open Master Insights or export again |
| **Steps** (Health Connect, `READ_STEPS`, read-only). Steps typed in by hand in other apps are ignored. No other health data is read and nothing is written to Health Connect | To show your step log, award step XP and achievements, and rank you on the leaderboard | On your phone. Daily totals are uploaded only while you are signed in |
| **Google account**: name, email, account ID (Sign in with Google via Firebase Authentication) | To identify your cloud save and leaderboard entry and to confirm you when you delete the account | Google Firebase. Only if you sign in |
| **Cloud save**: a compressed copy of your progress (including notes and mood) plus a summary (name, level, counts of quests, workouts, notes) | To restore progress on a new phone and keep devices in sync | Google Firebase Firestore, under your account ID, readable only by you. Only if you sign in |
| **Step leaderboard**: display name, cat avatar, step totals per day / week / month | To build the boards and pay prize XP. Other signed-in players can see your name, avatar and steps | Google Firebase Firestore. Only if you sign in |
| **Friends crews** (only if you make or join one): display name, cat avatar, level, current streak, last streak day, this and last week's XP; crew name and invite code; feed lines about you, emoji reactions, nudges; short posts (up to 3 a day), replies (up to 5 per post) and comments on feed lines; reports you file, which include the words reported | To run private crews: shared weekly quest, Weekly XP and Streaks boards, feed, posts, replies and nudges. Only members of the same crew can see them; crews are invite-only and cannot be searched | Google Firebase Firestore. Removed when you leave the crew or delete your account (leaving also removes your posts and replies); feed lines, posts, replies and nudges expire after about two weeks |
| **Rewarded ads**: Google AdMob may collect your advertising ID, IP address and basic device information | To let you unlock cat avatars by watching ads | Google AdMob |
| **Premium subscription** | To run Hissley Premium | Google Play Billing. Payment details never reach Hissley; the app only learns whether Premium is active |
| **Suggestion ideas**: the app downloads new quest and lift ideas | To keep suggestions fresh. The request carries no personal data (your IP address is visible to the server) | Google Firebase |
| **Reminder timing**: when you complete things and open the app | To time reminders and streak nudges | On your phone only |
| **Crash log** | To find bugs if you choose to share it | On your phone only. Never uploaded |

## What we don't do
- We do not sell your data and Hissley has no analytics or tracking SDK of its own.
- We never read your location, contacts, photos, microphone, camera, or any health data other than steps.
- Your notes, mood and weight are never shown to other players.
- We do not use health data for advertising.

## Who receives data
Only Google services that make the features work: Firebase (sign-in, cloud save, leaderboard, idea downloads), AdMob
(rewarded ads) and Google Play (billing). Data is encrypted in transit. Their own policies apply to what they collect:
https://policies.google.com/privacy

## Ads and consent
Hissley shows only rewarded ads that you choose to watch. In the EEA, UK and some other regions Google shows a consent
message first, and you can change your choice later in Settings > Privacy & data > Ad privacy choices. The ad SDK does
not start until consent is settled.

## Retention
Data on your phone stays until you reset progress or uninstall. Cloud save and leaderboard rows stay until you delete
your account.

## Deleting your data
- **In the app:** Settings > Data & Backup > Delete account. This permanently removes your login, cloud save and
  leaderboard rows from Google's servers and resets the app on that phone.
- **Without the app:** email hissleytracker@gmail.com (or biz.divyanshurana@gmail.com) from your Google account's email and we will delete it.
- One small marker per paid leaderboard prize stays so a prize cannot be paid twice. It holds only an internal account
  ID, with no name, email or steps.
- You can also remove Health Connect access in Health Connect settings, and switch off Android Backup in your phone's
  settings (which may otherwise copy app data to your Google account).

## Children
Hissley is not directed at children under 13 and we do not knowingly collect their data.

## Changes
If this policy changes the date above changes, and the in-app Privacy & data page is updated in the same release.

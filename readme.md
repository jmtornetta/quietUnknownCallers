# Purpose
Android app that silences robocallers, telemarketers, and spamcallers 99%+ of the time. It still let's you access and answer "important" unknown callers.

The application merely silences phones numbers that are not in your phone's contact list. It still allows you to answer unknown numbers for scheduled conference calls and business calls. So, you don't have to worry about missing that important call that is buried in a sea of spam.

We have chosen to limit this application to meddkit clients, friends, and those that find it via GitHub. We are limiting the number of users of this application by avoiding the Google Play store for now.
# Installation
1. Download and launch the latest release from your Android smartphone
2. Bypass warnings about installing apps from unknown sources (Note: having your device scan the app will not break anything but it may interrupt the automatic installation script. If this happens, you can "redo" installation by selecting "Reset Data" from the settings page and following the "Setup" page again.)
4. If necessary, you may need to configure your Android phone to "Allow installation of apks from unknown sources"
3. Follow the short setup page and provide all permissions, disable redundant notifications, and launch the app.
# Requirements
1. Android version >21
2. Permissions
    1. read/write contacts -- to know if the caller is in your contact list
    2. read/write call log -- to record a list of all silenced calls so you can see the worst offenders
    3. read/write storage -- to store a list of all silenced calls
    4. call screener -- to block the spammers before they annoy you
    5. draw over other apps -- to ensure that critical popups and alerts are not missed
# Features
1. Silence unknown callers by checking your phone's contact list for the number
2. Disable/Enable the app (thugh, it is designed to leave it enabled)
3. Record the date, time, and phone number of all unknown callers
4. Reset the app's data through the settings page
5. View a csv of all calls silenced from the settings page
6. Persistent notification while app is enabled with shortcuts to your phone's call log and the settings page
7. Ad-hoc notifications whenever a call is silenced
8. Unknown callers can still be answered (i.e. phone still "rings") but all noise and vibration is disabled
# Credits
This application was built with the Tasker application for Android.
Learn more: https://tasker.joaoapps.com/
Get it: https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en&gl=us
# Future
1. (Potentially) Release on Google Play store 
2. Optionally have vibration-only or reduce volume for unknown callers 
3. Optionally push/pull silenced calls to a central database for analytics of problem callers
4. Optionally add voicemail transcription and prompt-based call screening for silenced callers
# Changelog
09/13/2021 - v18 - First release
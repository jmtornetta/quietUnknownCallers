# Purpose
Android app that silences robocallers, telemarketers, and spamcallers 99%+ of the time. It still let's you access and answer "important" unknown callers.

The application merely silences phones numbers that are not in your phone's contact list. It still allows you to answer unknown numbers for scheduled conference calls and business calls. So, you don't have to worry about missing that important call that is buried in a sea of spam.


# Installation
1. Download and launch the latest release [here](https://github.com/jmtornetta/quietUnknownCallers/releases/latest) from your Android smartphone
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
1. Create variable for current scence and configure "Show Scene" tasks to destroy current scence based on this variable's value  
2. Update notification shortcuts to close/shrink notification drawer when selected prior to launching shortcut.  
2. Create text box description on "Advanced" scene with "Tap the setting title for additional information"  
3. (Potentially) Release on Google Play store 
4. Add screenshots x3
5. Force "Settings" from notification expand to overlay or focus the app's "Settings" page after "Call Log" (or another app) is already open
6. Configure scenes for landscape orientation (currently just portrait)
7. Optionally silence text message notifications not in contact list either
8. Optionally have vibration-only or reduce volume for unknown callers 
9. Optionally push/pull silenced calls to a central database for analytics of problem callers
10. Optionally add voicemail transcription and prompt-based call screening for silenced callers
# Changelog
## 09/20/2021 - v1.3
1. Fix "Autostart" by setting autostart profile to "On" during setup  
2. Create "Advanced" settings menu  
3. Consolidate "Scene Element Set Values" into "Toggle" tasks to minimize code  
4. Create parent "Prep Scene" tasks for future which will contain all toggle tasks when scene is shown  
5. Rename backup call log for readability  
6. Change scene transition animations to fade for consistency and simplicity  
7. Add help text prompts for advanced settings menu when title is tapped  
## 09/16/2021 - v1.2
Consolidate setup, variables, error checks into discrete tasks for maintenance.  
## 09/15/2021 - v1.1
Autostart application on device boot, if enabled.  
## 09/13/2021 - v1.0
First release. Alpha version.

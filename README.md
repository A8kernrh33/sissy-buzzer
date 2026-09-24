# 🎀 Sissy Buzzer

A cute pastel redesign of the Buzzer command center. It keeps the same authorized three-level feature set while using a completely different visual theme.

## Features
- Public summon with a server-enforced 60-second cooldown
- Superior password access with no public cooldown
- God password access with no public cooldown
- Custom summon, vibration, stop vibration, wake, stop alarm
- Notifications
- Audio controls
- Media controls
- Android settings launcher
- Device lock
- Persistent command history via Firestore
- FCM delivery to the paired Android Buzzer app

## Environment variables
- FIREBASE_SERVICE_ACCOUNT_JSON
- FCM_DEVICE_TOKEN
- SUPERIOR_PASSWORD
- GOD_PASSWORD
- PORT (optional)

## Run
```bash
npm install
npm start
```

The Android app remains the execution layer; this site is the authorization/control UI.
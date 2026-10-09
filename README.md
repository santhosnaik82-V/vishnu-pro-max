# Vishnu Pro Max

Vishnu Pro Max is a starter Android application for a video editor brand. This repository contains a clean Android project structure ready to open in Android Studio and build for the Google Play Store.

## Features
- Native Android app built with Kotlin
- Material 3 design
- Single-screen launcher screen for the video editor brand
- Ready for app branding and feature expansion

## Project structure
```text
.
├── app/
│   ├── src/main/AndroidManifest.xml
│   ├── src/main/java/com/santhosnaik/vishnu/promax/MainActivity.kt
│   └── src/main/res/
├── build.gradle.kts
├── gradle.properties
├── settings.gradle.kts
└── README.md
```

## Run locally
1. Install Android Studio with the Android SDK.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Run the `app` configuration on an emulator or real device.

## Prepare for Play Store
Before publishing:
- generate a release keystore
- create app icons and screenshots
- update app metadata and store listing
- configure Play Console account and app signing
- generate a production build

## Example release build
Use Android Studio:
- Build > Generate Signed Bundle / APK
- Select Android App Bundle (AAB)
- Upload the generated AAB to Google Play Console

## Notes
This is a base project scaffold. For a real video editor app, you will need to add actual editing features, permissions, media-processing libraries, and Play Store compliance requirements.

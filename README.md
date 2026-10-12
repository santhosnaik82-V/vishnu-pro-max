# Vishnu Pro Max

Vishnu Pro Max is a starter Android application for a video editor brand. This repository contains a clean Android project structure ready to open in Android Studio and build for the Google Play Store.

## Features
- Native Android app built with Kotlin
- Material 3 design
- Single-screen launcher screen for the video editor brand
- Ready for app branding and feature expansion

## Project structure
```text
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vishnu Pro Max</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #080b24, #102d67);
      color: white;
      text-align: center;
    }

    header {
      padding: 60px 15px;
    }

    h1 {
      font-size: 38px;
      color: #00e5ff;
    }

    p {
      font-size: 17px;
      line-height: 1.7;
    }

    .card {
      margin: 20px;
      padding: 25px;
      border-radius: 20px;
      background: #18254a;
    }

    button {
      padding: 14px 25px;
      border: none;
      border-radius: 25px;
      background: #00e5ff;
      color: #071126;
      font-size: 16px;
      font-weight: bold;
    }

    footer {
      padding: 25px;
      color: #bbbbcc;
    }
  </style>
</head>

<body>
  <header>
    <h1>VISHNU PRO MAX</h1>
    <p>Your creativity. Your videos. Your style.</p>
    <p>Welcome to the official website!</p>
  </header>

  <section class="card">
    <h2>🎬 Video Editor</h2>
    <p>Create amazing video-editing projects
       with Vishnu Pro Max.</p>
    <p>More features coming soon!</p>
    <button onclick="alert('https://drive.google.com/file/d/1Ldyg9UMDyybPYNeGadBsZmgNB-fQo2He/view?usp=drivesdk
                        ')">
      Download App
    </button>
  </section>

  <footer>
    <p>© 2026 Vishnu Pro Max</p>
    <p>Made with creativity ❤️</p>
  </footer>
</body>
</html>
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

# ITK — Enhanced ITD Client

A modified Android client for ITD (xn--d1ah4a.com) with extra features.

## Features
- Settings button floating on screen (gear icon)
- Download photos AND videos from posts
- Clickable links in posts
- Hide users from feed (by username)
- Hide hashtags from feed
- Post translator
- PIN lock
- Material You colors (Android 12+)
- Blur profanity in posts
- PC mode

## Build (requires Android Studio or Android SDK)
```
gradlew assembleDebug
```
APK will be at: `app/build/outputs/apk/debug/app-debug.apk`

## Build without installing anything (GitHub Actions)
1. Upload this folder to a GitHub repository
2. Go to Actions tab → "Build ITK APK" → Run workflow
3. Download APK from Artifacts when done

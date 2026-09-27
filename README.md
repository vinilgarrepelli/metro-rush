# Metro Rush — Android

A 3D endless runner with trains, coins, jumping, sliding, touch controls, sound, and saved high scores.

## Download and play

Download **Metro-Rush.apk** from this repository, open it on your Android phone, and allow installation from your file-opening app if prompted.

- Android 8.0 or later; current Android System WebView and WebGL 2 support required.
- Fully offline, with all game assets bundled. No internet permission or account needed.
- This is a development-signed APK, not a Play Store release.
- APK compilation and signature verification passed. Physical-device and emulator testing have not been performed.

## Source code

**Metro-Rush-Android-Source.zip** contains the complete editable Android project, original game source, bundled Three.js modules and license, build script, and CI workflow. Extract it to inspect or edit the project.

## Build in GitHub

Open **Actions → Build Android APK → Run workflow**. Download the **Metro-Rush-Android** artifact from the completed run. The workflow extracts the source archive and compiles a new APK.

## Build locally

Extract the source archive, install JDK 17, Python 3, Android SDK platform 35 and build-tools 35.0.0, set `ANDROID_SDK_ROOT`, and run `bash build.sh` inside the extracted `metro-rush` folder.

Fresh builds generate a new development signing key. Uninstall an earlier build before installing one signed with a different key; uninstalling clears saved scores. For production, configure a stable private release key outside Git.

Original Metro Rush branding and geometry; no Subway Surfers assets are included.

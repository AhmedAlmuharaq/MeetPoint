# MeetPoint for Android

The Android client is a Java WebView shell for the MeetPoint web app. Version 0.4.2 requires Android 8.0 (API 26) or newer. Accounts, meetings and routes are provided by the server URL configured in the app.

## Run the demo

Download [MeetPoint-Android-0.4.2-debug.apk](../MeetPoint-Android-0.4.2-debug.apk), install it and use the current HTTPS MeetPoint server address. Foreground notifications, profile image selection and geolocation use the corresponding web features and Android permissions.

## Build from source

Use JDK 17, Android SDK 35, and the included Gradle wrapper.

```bash
cd android
./gradlew :app:assembleDebug
```

On Windows use `.\gradlew.bat :app:assembleDebug`. The resulting APK is in `app/build/outputs/apk/debug/`. Gradle uses the machine’s local Android debug signing key. If Android rejects a locally rebuilt APK as an update to an earlier demo APK, use a matching signing key or uninstall the earlier client before installing the locally signed copy. Uninstalling the client clears its local session; server data remains on the server.

The optional [manual build script](tools/build_manual.py) creates a development key locally if one is absent. See [build verification](BUILD_VERIFICATION.json) for validation details from the archive. The APK has not been tested on a physical device during this update.

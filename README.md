# Hello Isha — Android app

A tiny native Android app written in Kotlin with Jetpack Compose.

## Build an APK

Every push to `main` automatically runs **Build Android APK**. You can also start a build manually from the **Actions** tab.

1. Open this repository on GitHub and select **Actions**.
2. Open the latest successful **Build Android APK** run.
3. Under **Artifacts**, download `hello-isha-debug-apk`.
4. Extract the ZIP and install `app-debug.apk` on your Android phone. If prompted, allow your browser or file manager to install unknown apps.

This workflow creates a debug APK for testing. It is not a Play Store release build.

## Build locally

With JDK 17, Gradle 8.9, and Android SDK installed:

```bash
gradle assembleDebug
```

APK output: `app/build/outputs/apk/debug/app-debug.apk`.

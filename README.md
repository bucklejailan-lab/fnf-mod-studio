# FNF Mod Studio

Android-first Friday Night Funkin' mod studio and compatibility-focused engine, inspired by P-Slice.

This project is a starter Android application for importing and inspecting Psych Engine-style and V-Slice-style mod archives. It is built for Android and includes a GitHub Actions release workflow that produces a debug APK in CI.

## Features
- ZIP import for P-Slice / Psych Engine / V-Slice style mod archives
- Safe archive preview and compatibility hints
- Android app shell ready for further mod tooling
- GitHub Actions workflow to build and publish APK releases

## Build locally

Requirements:
- Android Studio or SDK 35
- JDK 17

Command:
```bash
gradle assembleDebug
```

The APK will be generated at:
`app/build/outputs/apk/debug/app-debug.apk`

## Release workflow
The repository includes `.github/workflows/android-apk.yml` and will create a GitHub release with the APK when the workflow runs on `main`.

## Notes
P-Slice is not bundled here; this repo is an independent Android starter project inspired by it. All original asset and engine ownership remains with their respective owners.

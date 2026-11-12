# AfterHours

A native Android music player built in Kotlin, Jetpack Compose, and Media3.

## Current development focus

Immersive karaoke lyrics with real timestamped word or syllable fragments, simple search, and a cleaner playback experience.

The app's Android Studio source is being prepared as a GitHub-safe archive. **This repository is not buildable until the project sources are committed at the root.**

Expected root files: `settings.gradle.kts`, `build.gradle.kts`, `gradlew`, and `app/`.

## Build

After the full project source has been added, use GitHub Actions to build a debug APK with Java 17 and Android SDK 35. No production signing key or API secrets should be stored here.

For karaoke, true syllable-level synchronization requires timestamped syllable/segment data. Whole-line LRC cannot provide that timing by itself.

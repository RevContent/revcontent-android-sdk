# Revcontent Android SDK

Public distribution repo for the Revcontent Android SDK. This repo hosts a
static Maven repository (served via GitHub Pages from the `gh-pages` branch)
containing prebuilt release artifacts — no source code is published here.

## Install

```kotlin
// settings.gradle.kts
dependencyResolutionManagement {
    repositories {
        maven { url = uri("https://revcontent.github.io/revcontent-android-sdk") }
    }
}
```

```kotlin
// app/build.gradle.kts
dependencies {
    implementation("com.revcontent:revcontent-sdk:<version>")
}
```

## Releases

Artifacts are published automatically by CI whenever a new version is
released. Do not push to the `gh-pages` branch manually.

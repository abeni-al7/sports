# Sports

A list-detail app about sports that shows a list on phones and the list with details side by side on large screens.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Sports" adaptive-layouts practice project).

## Features

- List of sports with image, title, subtitle, player count and an "Olympic" label where it applies
- Detail page with a banner image and description; system Back returns to the list
- Compact and medium widths use list-only navigation; expanded width shows list and detail together

## Built with

- Kotlin, Jetpack Compose, Material 3
- `material3-window-size-class` (`calculateWindowSizeClass`)
- `ViewModel` (`lifecycle-viewmodel-compose`) with `StateFlow`, `BackHandler`
- Plural string resources for the player count
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```

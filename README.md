# simplenameproject

A Flutter starter application with the standard interactive counter screen.
Includes Android, iOS, web, Windows, macOS, and Linux projects.

## Run

Install the Flutter stable SDK and the tooling for your target platform, then run:

```sh
flutter pub get
flutter run
```

The application entry point is `lib/main.dart`.

## Validate

```sh
flutter analyze
flutter test
```

## Android build

```sh
flutter build apk --release
```

The existing GitHub Actions workflow analyzes the app, runs tests, and builds an
Android APK on pushes to `main`. Download the `simplenameproject-apk` artifact
from a successful workflow run.

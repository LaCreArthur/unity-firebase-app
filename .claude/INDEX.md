# Index: Firebase Test Project

type: unity-test
path: ~/unity-projects/firebase
github: https://github.com/LaCreArthur/unity-firebase-app.git
keywords: [Unity, Firebase, testing, integration, Analytics, Crashlytics, Remote Config, C#]

## Structure

This is a **test/integration project** for Firebase SDK testing. No game Assets folder.

```
firebase/
├── FirebaseApp/           # Core Firebase SDK
├── FirebaseAnalytics/     # Analytics module
├── FirebaseCrashlytics/   # Crash reporting module
├── FirebaseRemoteConfig/  # Remote config module
└── ExternalDependencyManager/  # EDM4U resolver
```

## Key Documents

- `CLAUDE.md` - Project context [conventions]
- `FirebaseApp/` - Core Firebase initialization [Firebase, init, app]
- `FirebaseAnalytics/` - Analytics events [analytics, events, tracking]
- `FirebaseCrashlytics/` - Crash reporting [crashlytics, crashes, errors]
- `FirebaseRemoteConfig/` - Remote configuration [remote config, A/B testing]

## Notes

Minimal project for testing Firebase Unity SDK integration. No game logic.

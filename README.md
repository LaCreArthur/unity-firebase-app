# Unity Firebase UPM Packages

Firebase SDK packages repackaged for Unity Package Manager (UPM) compatibility.

**Note:** tvOS plugins have been removed to prevent iOS/tvOS plugin collision errors during Android builds.

## Installation via UPM

Add packages via the Unity Package Manager window or directly to `Packages/manifest.json`.

### Individual Packages

#### ExternalDependencyManager
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=ExternalDependencyManager#12.10.1
```

#### FirebaseApp
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseApp#12.10.1
```

#### FirebaseAnalytics
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseAnalytics#12.10.1
```

#### FirebaseCrashlytics
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseCrashlytics#12.10.1
```

#### FirebaseRemoteConfig
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseRemoteConfig#12.10.1
```

#### Google Play Core
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.core#12.10.1
```

#### Google Play Common
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.common#12.10.1
```

#### Google Play Review
```
https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.review#12.10.1
```

### manifest.json (recommended order)

```json
"com.google.external-dependency-manager": "https://github.com/LaCreArthur/unity-firebase-app.git?path=ExternalDependencyManager#12.10.1",
"com.google.firebase.app": "https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseApp#12.10.1",
"com.google.firebase.analytics": "https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseAnalytics#12.10.1",
"com.google.firebase.crashlytics": "https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseCrashlytics#12.10.1",
"com.google.firebase.remote-config": "https://github.com/LaCreArthur/unity-firebase-app.git?path=FirebaseRemoteConfig#12.10.1",
"com.google.play.common": "https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.common#12.10.1",
"com.google.play.core": "https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.core#12.10.1",
"com.google.play.review": "https://github.com/LaCreArthur/unity-firebase-app.git?path=com.google.play.review#12.10.1"
```

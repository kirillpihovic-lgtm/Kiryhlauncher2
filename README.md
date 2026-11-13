# kiryhlauncher — Android starter project

This is a **starter Android Studio project**, not a finished Minecraft launcher and not an APK.

## Included
- Android app shell named `kiryhlauncher`
- Offline-first local profile storage
- Android Storage Access Framework folder picker
- Persisted access to a user-selected game folder
- Placeholder screens/actions for game files and launch

## Not included yet
- Minecraft Java runtime or game files
- Microsoft authentication
- A compatible Android Java game-launcher engine
- Version installation, mod-loader installation, shader/map managers
- Actual game launch or compatibility verification

The app does not include pirated game files or bypass licensing. The user must provide game files they are entitled to use and follow the requirements of the selected launcher engine.

## Build
1. Open this folder in Android Studio (recent version).
2. Let Gradle sync.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Android Studio will show the generated APK location after a successful build.

Requires Android Studio and Android SDK Platform 35. The Gradle plugin may download dependencies during the first build.

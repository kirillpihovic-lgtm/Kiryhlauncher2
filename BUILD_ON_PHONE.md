# Build kiryhlauncher APK using a phone

This project includes a GitHub Actions workflow for cloud building.

1. Create/sign in to a GitHub account in your phone browser.
2. Create a new repository (Public or Private) named `kiryhlauncher`.
3. Upload the contents of this project folder to the repository root. Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository's **Actions** tab, select **Build kiryhlauncher APK**, and tap **Run workflow**.
5. When the run finishes successfully, open it and download the `kiryhlauncher-debug-apk` artifact.
6. Extract the downloaded artifact ZIP on your phone; it contains `app-debug.apk`. Tap it to install. If Android asks, allow your browser/file manager to install apps from this source.

The cloud workflow builds the current starter app only. It does not add the Minecraft Java engine or enable launching Minecraft. This is a debug/test APK, not a Play Store release build.

# Titty Android WebView

A fullscreen Android WebView for Scratch, TurboWarp, and itch.io pages. It uses the custom launcher artwork and hides browser controls.

## Build an APK

1. Open the repository's **Actions** tab and select **Build Android APK**.
2. Press **Run workflow**.
3. Enter the HTTPS game URL and app name.
4. Select **Minimum Android version** to choose the oldest Android version the APK allows for installation.
5. Run the workflow, open the completed run, and download the `pocket-game-apk` artifact.

Options include Android 2.3.3–2.3.7 (API 10), Android 4.0 (API 14), Android 4.4 (API 19), Android 5.0 (API 21), Android 6.0 (API 23), Android 8.0 (API 26), Android 10 (API 29), Android 12 (API 31), and Android 15 (API 35).

A lower minimum SDK does not upgrade a device's browser engine or TLS support. Modern websites and games may still fail on older Android versions. The workflow produces a debug APK for sideloading, not a Google Play release.

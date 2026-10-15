# Pocket Game Android wrapper

A minimal fullscreen Android WebView for Scratch and TurboWarp projects. It has a custom artwork launcher icon and no address bar or browser chrome.

## Build an APK

1. Open the repository's **Actions** tab.
2. Select **Build Android APK**.
3. Press **Run workflow**.
4. Enter an HTTPS project URL hosted on Scratch or TurboWarp and the app name.
5. Run the workflow, open its completed run, and download the `pocket-game-apk` artifact.

The workflow accepts `scratch.mit.edu` and `turbowarp.org` URLs only. The app blocks top-level navigation to unrelated websites, while game subresources can load as usual.

The workflow produces a debug APK for sideloading. It is not signed for Google Play release. Minimum Android version: Android 6.0 (API 23).

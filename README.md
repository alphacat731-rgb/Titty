# Pocket Game Android wrapper

A minimal fullscreen Android WebView for Scratch and TurboWarp projects. It has a custom lime-green cat icon and no address bar or browser chrome.

## Build an APK

1. Open the repository's **Actions** tab.
2. Select **Build Android APK**.
3. Press **Run workflow**.
4. Enter the HTTPS project URL and app name.
5. Run the workflow, open its completed run, and download the `pocket-game-apk` artifact.

The URL must use `scratch.mit.edu` or `turbowarp.org` (including their `www` hostnames). This intentionally blocks arbitrary sites and external top-level navigation. Subresources such as game assets can still load inside the page.

The workflow produces a debug APK for sideloading. It is not signed for Google Play release. Minimum Android version: Android 6.0 (API 23).

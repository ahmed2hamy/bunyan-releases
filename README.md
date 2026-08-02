# Bunyan — Releases

Public downloads for the **Hesabna** building-expenses app.
The application source code is maintained privately; this repository hosts
release binaries only.

## Download

Grab the latest Android APK from the [**Releases**](../../releases/latest) page
→ download `app-release.apk`, then open it on your Android device to install.
You may need to allow "Install from unknown sources" for your browser/file
manager.

> iOS is distributed through the App Store / TestFlight, not here.

## Versions

Releases are tagged `vX.Y.Z+B` (matching the app's `pubspec.yaml` version),
newest first on the Releases page. Each release lists what changed.

## Verify a download (optional)

Each APK is published with a SHA-256 digest shown on its release page. To check
an APK you downloaded:

```bash
shasum -a 256 app-release.apk
```

and compare it to the digest on the release.

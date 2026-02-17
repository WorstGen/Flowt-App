# Flowt Android Beta APK

This repository is for distributing and testing the latest Flowt Android beta APK.

## Download

- Latest APK: `releases/app-release.apk`

If your browser blocks APK downloads, use the repository "Download ZIP" option and open the APK from your Files app.

## Install (Android)

1. Download `app-release.apk`.
2. Open the file.
3. Allow install permission for your browser/files app if prompted.
4. Complete install.
5. Open Flowt.

## Update to New Build

1. Download the newest `app-release.apk`.
2. Install over your existing app.
3. Reopen and verify normal behavior.

## What To Test

Use the app normally and stress these areas:

- Sign in/sign out
- Create posts (text, image, video)
- Thread/reply flows
- Search and profile navigation
- Chat sending/receiving
- Notifications open to correct content
- App behavior in foreground, background, and fully closed

Detailed test instructions:

- `TESTER_GUIDE.md`

## Report Bugs

Use the template in:

- `templates/BUG_REPORT.md`

You can paste reports in GitHub issues, Telegram, Discord, or email.

## Current Build Info

Fill this before sharing each build:

- Build date: YYYY-MM-DD
- APK filename: app-release.apk
- Version name: x.y.z
- Version code: n
- Known issues: none / list

## Maintainer Notes

- Keep only one current APK in `releases/` unless you want historical archives.
- Replace `releases/app-release.apk` for each new beta.

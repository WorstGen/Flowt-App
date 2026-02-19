# Flowt Android Beta Distribution

This repository is the official distribution point for the latest Flowt Android beta APK and tester documentation.

## Latest Build

- APK: `releases/app-release.apk`
- Build date: 2026-02-19
- Version name: `1.0.9`
- Version code: `10`
- SHA-256: `cc3ffc912a2757ae8f01abd0116b66e43e999aa01b0f860b6ec76a759384210d`
- Min Android version: 8.0 (API 26)

## Install (Android)

1. Download `releases/app-release.apk` to your device.
2. Open the APK from your Files app.
3. If prompted, allow installation from that source.
4. Tap Install.
5. Open Flowt.

## Update to New Beta

1. Download the newest `app-release.apk`.
2. Install over the existing app.
3. Reopen and confirm sign-in + core actions work.

## Testing Scope

Focus on:

- Sign in / sign out
- Post creation (text, image, video)
- Thread and reply navigation
- Search and profile flows
- Chat stability
- Notification delivery and notification deep-link routing
- Foreground vs background vs closed-app behavior

Detailed testing instructions are in:

- `TESTER_GUIDE.md`
- `CHECKLIST.md`

## Reporting Bugs

Use:

- `templates/BUG_REPORT.md`

For broader product feedback:

- `templates/TESTER_FEEDBACK.md`

## Current Known Issues

- No confirmed blocker at the time of this build.
- Any reproducible failure should be reported with reproduction steps and timestamp.

## Maintainer Notes

- Keep the current public APK at `releases/app-release.apk`.
- For each new build, update this README build metadata and `RELEASE_NOTES.md`.

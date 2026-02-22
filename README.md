# Flowt Android Beta Distribution

This repository is the official distribution point for the latest Flowt Android beta APK and tester documentation.

## Latest Build

- APK: `releases/app-release.apk`
- Build date: 2026-02-22
- Version name: `1.0.21`
- Version code: `22`
- SHA-256: `b6869027f3e16b2d94eb79100e472d8d20014c3e0f685a09fc951bb3bf250eb4`
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

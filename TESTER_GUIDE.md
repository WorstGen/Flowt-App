# Flowt Tester Guide

Welcome to the Flowt beta.

This build is for testing core social features, performance, and usability before wider release.

## App Overview

Flowt is a social app for short-form posts, threaded conversations, profiles, chat, and notifications.

## Test Priorities

Please report:

- Crashes or freezes
- Blank screens
- Sign-in failures
- Post/reply failures
- Notification problems
- Broken links/navigation
- UI overlap or clipping
- Slow or inconsistent behavior

## Quick Test Pass

1. Sign in, then sign out.
2. Create a text post.
3. Create an image post.
4. Create a video post.
5. Open a post detail view.
6. Add a reply in-thread.
7. Delete your own post/reply.
8. Use search for people and posts.
9. Use chat and send messages.
10. Trigger notifications and open them.
11. Test with app foreground, background, and fully closed.

## Bug Report Checklist

When reporting, include:

- Device model
- Android version
- Steps to reproduce
- Expected result
- Actual result
- Screenshot/screen recording
- Local timestamp and timezone

## Example Bug Report

```text
Device: Samsung S23 (Android 14)
Steps:
1) Open app
2) Tap Notifications
3) Tap newest notification
Expected: Opens related post detail
Actual: Opens blank background screen
Time: 2026-02-17 22:41 PST
```

## Beta Notes

- Some edge cases are still under active tuning.
- If behavior looks stale, close and reopen once, then retry.
- Please avoid posting private personal data during testing.

Thanks for helping harden Flowt before public launch.

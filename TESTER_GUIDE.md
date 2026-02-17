# Flowt Tester Guide

Thanks for testing Flowt.

Your goal is to use the app like a normal user and report anything that feels broken, confusing, slow, or unstable.

## Priority Areas

1. Sign in flow
2. Posting and replies
3. Profile views and navigation
4. Search behavior
5. Chat reliability
6. Notifications (delivery + open destination)
7. General UI stability on different devices

## High-Value Test Pass (10-15 minutes)

1. Sign in.
2. Create a text post.
3. Create a media post (image or video).
4. Open the post detail page.
5. Add a reply.
6. Open a profile from feed.
7. Use search for both user and post content.
8. Open chat and send one message.
9. Trigger one notification from a second account.
10. Tap the notification and verify it opens the correct place.

## Stability Pass (5 minutes)

1. Put app in background.
2. Return and continue activity.
3. Close app fully.
4. Reopen app.
5. Verify state, session, and recent actions still look correct.

## Report Quality Standard

Every bug report should include:

- Device model
- Android version
- Exact steps
- Expected result
- Actual result
- Screenshot or screen recording
- Timestamp + timezone

Use `templates/BUG_REPORT.md`.

## Severity Guide

- Blocker: cannot use key flow (sign in, post, open feed)
- High: major feature broken without workaround
- Medium: workflow works with workaround
- Low: visual/polish issue only

## Notes

- If you see inconsistent behavior, retry once after app restart.
- Do not post private personal data during testing.
- If issue is intermittent, report approximate frequency.

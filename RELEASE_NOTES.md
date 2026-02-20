# Flowt Android Beta Release Notes

## Build 2026-02-19

- Version name: `1.0.19`
- Version code: `20`
- APK: `releases/app-release.apk`

## Focus for Testers

- APK upward-scroll fix: disabled native `SwipeRefreshLayout` interception that was stealing upward gestures/pull-to-refresh
- Verify feed scrolls up smoothly without being trapped in pull-refresh behavior
- Re-check lock-screen/background audio behavior remains unchanged

## Build 2026-02-20

- Version name: `1.0.18`
- Version code: `19`
- APK: `releases/app-release.apk`

## Focus for Testers

- Hotfix: defensive guard in Android intent/deeplink handling to prevent malformed payload crash
- Validate startup stability and push-notification tap stability (splash/surge/echo)
- Confirm app no longer crashes when opened from recent notifications/deep links

## Build 2026-02-20

- Version name: `1.0.17`
- Version code: `18`
- APK: `releases/app-release.apk`

## Focus for Testers

- Notification tap routing hardening on Android to reduce full-app refresh when opening splash/surge/echo alerts
- Engagement action persistence hardening (canonical source IDs with clicked-ID fallback)
- Surge wrapper count visibility alignment with source ripple engagement totals
- Validate splash/surge/echo action + undo behavior updates instantly and persists after refresh

## Build 2026-02-20

- Version name: `1.0.16`
- Version code: `17`
- APK: `releases/app-release.apk`

## Focus for Testers

- Settings now open from account dropdown in a centered in-app modal
- Bottom mini-player reserve tightened (removes extra dead spacer above player lane)
- Android lock-screen/media notification `Next/Previous` hardened to avoid foregrounding app
- Validate background controls: play/pause/next/prev behavior with screen locked and app inactive

## Build 2026-02-19

- Version name: `1.0.15`
- Version code: `16`
- APK: `releases/app-release.apk`

## Focus for Testers

- Android background/lock-screen audio playback behavior
- Native audio state now includes seekability; scrub controls only show when seek is truly supported
- Reduced false scrub behavior that jumped tracks back to start on non-seekable streams
- Increased reserved bottom lane so mini-player sits beneath content more reliably
- Fixed native scrub/seek so dragging actually seeks playback (not visual-only)
- Added native "prepared next track" queue so lockscreen playback can auto-advance more reliably
- Slimmed bottom mini-player banner again to avoid intruding on page controls
- Teal-branded scrub control styling
- Bubble action button now opens bubble reply composer directly (instead of opening detail/view flow)
- Desktop web now shows bottom mini-player when dashboard mode collapses
- Added native audio progress/scrub line in app mini-player + panel player for Android runtime
- Added media notification progress line updates for lockscreen visibility
- Android media playback notification style and lock-screen controls
- Lock-screen return stability (no UI crash / React 185 loop on resume path)
- Resume behavior (avoid unintended restart when returning from background)
- Branded Flowt playback notification visuals (icon/color/subtext)
- Reduced notification chaos on Android by suppressing duplicate local bridge alerts in remote mode
- Hardened lockscreen transport controls (prev/next) and resilient audio-control bridge timing
- Polished music notification visuals: crisp custom transport icons + tighter Flowt brand color match
- Prevented in-app music restart when opening Flowt notifications by routing deep links without full WebView reload
- Mobile mini-player stability and playback controls
- Composer video editor usability and cover-image workflow (Trim/Cover tabs)
- Notification delivery consistency
- Notification deep-link correctness
- Thread/detail navigation reliability
- Post + media creation stability
- Chat reliability

## Notes

- This is a beta tester build.
- Please submit all issues with `templates/BUG_REPORT.md`.

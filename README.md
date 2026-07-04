# MultiFingerGestureX (MFGX)

A powerful Xposed/LSPosed module for Android 15+ that enables custom actions triggered by multi-finger touch gestures. Swipe or pinch with 3, 4, or 5 fingers anywhere on screen to perform system actions, launch apps, open custom panels, execute shell commands, and more.

## Requirements

- Android 15+ (API 35+)
- LSPosed or compatible Xposed framework
- Root access
- Scope: **System Framework** (`android`)

## Features

### Gestures (3 / 4 / 5 fingers)
- Swipe Up / Down / Left / Right
- Pinch In / Pinch Out
- Quick Swipe Up / Quick Swipe Down

### Actions
- **System actions**: Back, Home, Recents, notifications, lock screen, screenshot, volume, brightness, and more
- **App launch**: Open any installed app
- **App shortcuts**: Trigger pinned shortcuts
- **Pie menu**: Radial overlay with configurable items
- **Custom panels**: Side and bottom panel overlays
- **Multi-action workflows**: Chain multiple actions with conditional gating
- **Shell commands**: Execute commands, optionally with root (`su`)

### UI
- Material 3 / Jetpack Compose settings interface
- Configurable accent colors and dark mode
- Per-gesture enable/disable and action binding
- Adjustable gesture thresholds

## Credits

MultiFingerGestureX is a redesign of [EdgeX](https://github.com/fcmfcm1999/EdgeX), rebuilt specifically for Android 15+ with a focus on multi-touch gesture recognition. Special thanks to the author of EdgeX — this project builds on their original work.

## License

GNU General Public License v3.0

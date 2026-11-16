<p align="center"><img src="icon.png" width="128" alt="Diorama Detective icon"></p>

# Diorama Detective Demo

Early technical demo of **Diorama Detective**, a detective game set in small pixel-art dioramas. Turn the diorama, look into every corner and piece together what happened.

This repository only hosts the demo builds. The game itself is in development.

## What is in this demo (version 0.1)

- Case 01: a snowy railway station at night. A station master lies dead in his office.
- One explorable diorama with the full camera controls.
- No case book, no interaction and no HUD yet. Clicking objects comes in a later version.

## Download

Get the latest build from the [Releases](../../releases) page:

| Platform | File |
|---|---|
| Windows (64-bit) | `DioramaDetective-0.1.0-windows.zip` |
| macOS (Apple Silicon and Intel) | `DioramaDetective-0.1.0-macos.zip` |
| Linux (x86_64) | `DioramaDetective-0.1.0-linux.zip` |

### System requirements

- macOS: Mac with Metal support (tested on Apple Silicon).
- Windows and Linux: 64-bit, graphics card with Vulkan support.

### macOS

The app is not notarized, so macOS blocks it on first start. Try to open it once, then go to **System Settings > Privacy & Security** and click **Open Anyway**. On macOS 14 and older, a right click on the app and **Open** also works.

### Windows

The build is not signed. If SmartScreen warns you, click **More info > Run anyway**.

### Linux

Unpack the archive and start `DioramaDetective.x86_64`. If it does not start, make it executable with `chmod +x DioramaDetective.x86_64`.

The Windows and Linux builds were exported but not yet tested on real Windows or Linux machines. Feedback is welcome.

## Controls

| Action | Mouse | Keyboard | Gamepad |
|---|---|---|---|
| Rotate the diorama | Drag with the left mouse button | Q / E | Right stick |
| Zoom | Mouse wheel, trackpad pinch or two-finger swipe | + / − | Shoulder buttons |
| Move the view | Drag with the right or middle mouse button | Arrow keys, WASD | Left stick |
| Select an object (not yet functional) | Left click | | |

Zoom and movement are limited so the diorama always stays in view.

## Feedback

Found a bug or have an idea? Open an [issue](../../issues).

## License

The demo builds are free to download and play. All rights reserved; redistribution is not permitted.

Built with [Godot Engine](https://godotengine.org) (MIT license). The licenses of Godot and its third-party components are listed in the Godot Engine license page: https://godotengine.org/license

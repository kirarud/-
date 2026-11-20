# Voice Skins

A small macOS prototype for voice companions inspired by the MUZA / Hermes Cube experiments.

## Character skins

| Cloud | HyperBit | Round backdrop |
| --- | --- | --- |
| ![Cloud](previews/cloud-transparent.gif) | ![HyperBit](previews/hyperbit.gif) | ![Backdrop](previews/backdrop.gif) |

- Voice Skins is a floating window with Cloud and HyperBit skins. Its mouth follows the playback level from ChatGPT.
- Cloud Menu is a transparent animated cloud that can be placed directly in an interface.
- HyperBit Menu is the matching transparent, glowing wireframe cube.
- Round Backdrop is the circular animated field as its own movable, transparent window.

## Build on macOS

Requires macOS, Xcode Command Line Tools, and FFmpeg.

- Run ./build.sh to build the switchable Voice Skins app.
- Run ./build-menu.sh to build standalone Cloud Menu, HyperBit Menu, and Round Backdrop apps.

Built apps are created in build/. The first audio capture may prompt for macOS permission. Audio levels are processed locally and not saved.

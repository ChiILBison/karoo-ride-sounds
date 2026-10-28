# Ride Sounds for Karoo

Ride Sounds is a free-for-personal-use beta extension that plays speaker-tuned cues for ride events. It includes one built-in soundpack and one optional, nameable user soundpack.

## Download the official build

[Download Ride Sounds 1.0.0 beta 1 for Karoo 2 and Karoo 3](https://github.com/ChiILBison/karoo-ride-sounds/releases/download/v1.0.0-beta.1/Ride-Sounds-1.0.0-beta.1-Karoo2-Karoo3.zip)

Share this page or the official link above. Do not mirror or send copies of the application. The source code is privately maintained and is not included in this repository or download.

Official ZIP SHA-256: `4c9aa601385a58a5a9384346751823fbcd693d06a8e684a900c1fd459a70dbaa`

Official APK SHA-256: `264657d3091cc5ebdc8194e14e3325eb0b966181173b637bd71f7df18cb16a9d`

Official APK signing-certificate SHA-256: `02a7b16b6c87afd4c47d5cf7f65270f364180e7b4c738056af19f837c27be681`

The October 28 hotfix keeps Ride Start from being cancelled by an immediate auto-pause and recognizes new rides first reported as paused. It also includes the October 27 fix for Rush replaying at a live-segment start. The reliable segment-start fallback remains active when Karoo never supplies an approach signal. The signed build passed 208 unit-test executions and is installed on a Karoo 3; real-ride timing confirmation is still pending.

Built-in cue names: **Ride Start, Pause, Rush, Invincible, Cha-ching, Level-up, Completion, Climb, Bunnyhop, Blast, End, Extra, and Enter.**

## Status

- Karoo 3 behavior is inherited from the validated personal build and covered by automated regression tests.
- Karoo 2 installation is expected to work because the app supports Android 6 and later, but this public edition remains **beta** until a physical Karoo 2 ride test confirms event delivery and speaker behavior.
- The private Hammerhead Binder connection and Ki2 15.0 integration are **experimental**.

## Easiest installation

1. Download the release ZIP and unzip it on a Mac, Windows PC, or Linux computer.
2. Follow [INSTALL.md](INSTALL.md) to enable developer mode and USB debugging on the Karoo.
3. Connect the Karoo by USB and approve its USB-debugging prompt.
4. Run the installer for your computer. It verifies the APK checksum before installing.
5. Open **Ride Sounds (Beta)** on the Karoo, review the settings, then enable the extension.
6. When finished, turn USB debugging off again.

The installer never removes another app. If Android reports a signature conflict, read the message and stop; uninstalling an older package would erase that package's settings and must be a deliberate manual choice.

## User soundpack

Tap **Create or repair user soundpack folders** in the app. The template appears at:

`Download/Karoo Ride Sounds/User Soundpack/`

Each event folder may contain one optional file named exactly `sound.wav`. Missing sounds are allowed and remain silent. A malformed present file makes the pack unselectable and the app names the invalid category.

Every file must be:

- uncompressed PCM WAV;
- mono;
- 16-bit;
- 48,000 Hz;
- free of clipping;
- no more than 100 ms of leading silence; and
- within the duration printed in that event folder's instructions.

Use only audio you created or have permission to use and share.

## Optional in-app icon

Tap **Create custom icon folder** and copy `custom-icon.png` to:

`Download/Karoo Ride Sounds/App Icon/`

The file must be PNG, square, 72–512 pixels per side, non-animated, and no larger than 1 MB. It appears inside the settings screen only.

The installed app and Karoo Extensions list use the bundled example image. That installed icon is fixed in the official download. The optional image above appears only inside the Ride Sounds settings screen.

## Legal and privacy

See [RIGHTS_AND_SUPPORT.md](RIGHTS_AND_SUPPORT.md), [PRIVACY.md](PRIVACY.md), and [LICENSING.md](LICENSING.md).

Ride Sounds is proprietary software offered free for personal use. Share the official GitHub link, not copies of the application. Modification, rebranding, redistribution, resale, and soliciting donations or other compensation through copies or derivatives are not permitted. Voluntary donations made through the copyright holder's official link are not sales, do not buy ownership, a special license, or a service, and are not tax-deductible.

# Install on Karoo 2 or Karoo 3

## On the Karoo

1. Open **Settings**.
2. Open **About**.
3. Tap the **Build number** seven times until developer mode is enabled.
4. Return to Settings and open **Developer options**.
5. Turn on **USB debugging**.
6. Connect the Karoo to the computer with a data-capable USB cable.
7. When the Karoo asks whether to allow USB debugging, check **Always allow from this computer** only if it is your own trusted computer, then tap **Allow**.

Menu wording can vary by Karoo software version. If Developer options is already visible, do not repeat the build-number step.

## On the computer

- Install Google's Android SDK Platform Tools if the computer does not already have the `adb` command.
- macOS: double-click `installers/install-macos.command`. If macOS blocks it, Control-click it, choose **Open**, then confirm.
- Windows: double-click `installers/install-windows.bat`.
- Linux: run `installers/install-linux.sh`.

The installer checks the included SHA-256 checksum, confirms that one authorized Karoo is connected, and installs or updates the app. It never automatically uninstalls another package.

## After installation

1. Open **Ride Sounds (Beta)** on the Karoo.
2. Confirm the app appears in Karoo's Extensions settings and enable it.
3. Review the app's audio-profile instructions.
4. Return to **Developer options** and turn **USB debugging off** unless you still need it.
5. On a shared computer, use **Revoke USB debugging authorizations** on the Karoo.

## If installation stops

- **Checksum failed:** delete the download and download the release ZIP again.
- **No device:** unlock the Karoo, reconnect the cable, and approve the debugging prompt.
- **More than one device:** disconnect other Android devices.
- **Signature conflict:** the installed copy was signed by a different key. Do not let a script remove it. Decide manually whether preserving its settings or installing this edition matters more.

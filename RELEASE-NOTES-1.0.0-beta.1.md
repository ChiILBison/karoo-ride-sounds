# Ride Sounds 1.0.0 beta 1

This is the official signed beta for Karoo 2 and Karoo 3 testing.

October 28 hotfix (includes the October 27 segment fix):

- Ride Start now survives auto-pause/manual pause during its 2.5-second delay.
- A new ride first reported as paused after idle also triggers Ride Start; resuming an existing ride does not replay it.
- Ending the ride or stopping the runtime still cancels stale start cues.
- Rush now plays during live-segment approach without replaying when the segment starts.
- Invincible begins at the segment start as before.
- The start fallback still plays Rush when Karoo provides no usable approach signal.
- Added regression coverage for overlapping status sources, anonymous segments, and genuine approach cancellation.
- Added persistent start diagnostics and regression coverage. All 208 test executions passed (104 debug and 104 release); release lint has no errors.
- Installed and connection-verified on a Karoo 3; real-ride confirmation of these timing fixes is still pending.

- Free for personal, noncommercial use.
- Karoo 3 behavior is inherited from the validated personal build.
- Karoo 2 compatibility and SRAM/Ki2 behavior remain experimental pending physical ride testing.
- The release APK is code-shrunk and obfuscated.
- Source code is privately maintained and is not distributed.
- Modification, rebranding, redistribution, sale, and third-party monetization or donation solicitation are not permitted.

Download the ZIP, verify its adjacent SHA-256 checksum if desired, and follow `INSTALL.md` inside the download.

ZIP SHA-256: `4c9aa601385a58a5a9384346751823fbcd693d06a8e684a900c1fd459a70dbaa`

APK SHA-256: `264657d3091cc5ebdc8194e14e3325eb0b966181173b637bd71f7df18cb16a9d`

APK signing-certificate SHA-256: `02a7b16b6c87afd4c47d5cf7f65270f364180e7b4c738056af19f837c27be681`

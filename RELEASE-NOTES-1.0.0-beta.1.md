# Ride Sounds 1.0.0 beta 1

This is the official signed beta for Karoo 2 and Karoo 3 testing.

October 30 segment handoff hotfix:

- Fixed a remaining duplicate Rush on the second progress update after a controller-supplied approach.
- Kept approaches separate for overlapping segments; removing or reordering cards does not create another anonymous approach.
- Prevented single-play Invincible from restarting after feed recovery or a late selection of an already-running segment.
- Kept missing distance metadata from creating another segment identity.
- Preserved genuine new starts, repeat attempts, completion/record sounds, the under-three-minute loop option, and the October 28 Ride Start repair.
- Preserved approved sound patterns, icon, preferences and button assignments.
- Passed 244 unit-test executions (122 debug and 122 release), including two retained device traces plus synthetic overlap and interruption tests. Release lint has no errors.
- Installed and connection-verified on a Karoo 3. Real-ride confirmation of this update remains pending; automated replays are not a substitute for GPS and speaker testing.

- Free for personal, noncommercial use.
- Karoo 3 behavior is inherited from the validated personal build.
- Karoo 2 compatibility and SRAM/Ki2 behavior remain experimental pending physical ride testing.
- The release APK is code-shrunk and obfuscated.
- Source code is privately maintained and is not distributed.
- Modification, rebranding, redistribution, sale, and third-party monetization or donation solicitation are not permitted.

Download the ZIP, verify its adjacent SHA-256 checksum if desired, and follow `INSTALL.md` inside the download.

ZIP SHA-256: `2659f07f9656b59bf9dd488ade9645fc1b8cefc9e27a9fa65188ff87c23934eb`

APK SHA-256: `a8f4c12ecf4350a8c3400228c091a63d0abaa12f5874850963070203c45765aa`

APK signing-certificate SHA-256: `02a7b16b6c87afd4c47d5cf7f65270f364180e7b4c738056af19f837c27be681`

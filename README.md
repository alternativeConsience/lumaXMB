# lumaXMB · Alpha testing

**Your Vita, the way it was meant to be played.**

[Project page & setup](https://alternativeconsience.github.io/lumaXMB/#top) · [Alpha test & log guide](https://alternativeconsience.github.io/lumaXMB/alpha-testing.html) · [Controls & user guide](https://alternativeconsience.github.io/lumaXMB/controls.html) · [Desktop Engine for Wallpaper Engine](https://alternativeconsience.github.io/lumaXMB/desktop-engine.html) · [Discord testing channel](https://discord.gg/YSv9PtpZC)

## Downloads

| Package | What to use |
| --- | --- |
| [Test Utility installer 2.00 VPK](https://github.com/alternativeConsience/lumaXMB/releases/download/alpha-2026-10-24/lumaXMB-Installer-2.00.vpk) | Start here for Vita: installs lumaXMB **2.07 / r255**, the Adrenaline helper and resources. |
| [Companion app for Windows](https://github.com/alternativeConsience/lumaXMB/releases/download/alpha-2026-10-24/lumaXMB-Companion-Windows.exe) | Completely optional media, artwork, transfer, theme and log tools. |
| [Desktop Engine / Wallpaper Engine package](https://github.com/alternativeConsience/lumaXMB/releases/download/alpha-2026-10-24/lumaXMB-Desktop-Engine-Wallpaper-Engine-2026-10-25.zip) | Windows desktop waves and live controls. [Installation guide](https://alternativeconsience.github.io/lumaXMB/desktop-engine.html#install). |

## A quick look

| Games | Movies |
| --- | --- |
| ![Vita game Coverflow](https://alternativeconsience.github.io/lumaXMB/previews/games.webp) | ![Movie library](https://alternativeconsience.github.io/lumaXMB/previews/media.webp) |
| **Optional Companion app** | **Desktop Engine** |
| ![Companion Media Manager](https://alternativeconsience.github.io/lumaXMB/previews/companion.webp) | ![Desktop Engine waves](https://alternativeconsience.github.io/lumaXMB/previews/desktop.webp) |

Lightweight previews. Full-resolution captures and more features are on the project pages.

## Get started

On a homebrew-enabled Vita running **3.60 or higher**, copy the installer VPK by normal USB drag-and-drop or FTP, install it in VitaShell, then open **Test Utility → Set up lumaXMB**. Choose **Launch lumaXMB** when setup finishes. The companion is completely optional.

For Desktop Engine, extract the complete ZIP, open **lumaXMB Desktop Engine.exe**, then choose your display and live settings in Wallpaper Engine. Requires Wallpaper Engine on Windows; no Python installation is needed.

## Controls & sessions

[Controls & user guide](https://alternativeconsience.github.io/lumaXMB/controls.html)

### Moonlight / desktop controls

The integrated Moonlight client uses local shortcuts to keep you in control of the stream:

- **Start + L + R:** Open the stream menu. Choose **Resume stream** to continue or **End session** to leave the desktop stream.
- **L + R + Circle:** Leave the integrated client and return to XMB.
- **Start + Left:** Open the on-screen keyboard.
- **Start + Right:** Cycle host displays when multiple monitors are configured.
- For desktop mouse control, select **Trackpad** in **Input settings**. Slide to move the pointer, tap with one finger to left-click, tap with two fingers to right-click, and slide with two fingers to scroll.

Save your PC work before choosing **End host application**. That option requests that the host application close; use **End session** when you simply want to finish streaming.

### PS button isolation and sessions

While inside lumaXMB, including its integrated desktop client, normal PS-button access to LiveArea is intentionally restricted. An unresponsive PS button here does not necessarily mean the Vita has frozen. Use the shortcuts above to leave streaming, then use lumaXMB’s LiveArea action when you want to return to the system interface.

With a temporary session active, supported games launched through lumaXMB use the native PS menu with **Return to XMB** and **Return to LiveArea** options. These return features remain experimental, and another plugin that changes PS-button or quick-menu behavior may interfere.

**Temporary sessions remain available until stopped or the Vita restarts. Permanent sessions and autoboot are unavailable in this alpha.** Open Test Utility 2.00 after updating: it preserves backups, clears permanent-session settings and removes only its own boot entry. If prompted, restart before setup or a temporary session. Unrelated plugins, media, games and saves are retained. A device already unable to boot needs recovery first.

## Alpha feedback

**Participate in the alpha test.** Expect bugs and unfinished features. Built on a PS Vita 1000 with 3.60 Ensō; compatibility may vary. **Keep autoboot off.** Temporary sessions and the permanent-session restriction are explained in the [illustrated guide](https://alternativeconsience.github.io/lumaXMB/#setup).

[Report an issue](https://github.com/alternativeConsience/lumaXMB/issues) with the build, Vita model/firmware, reproduction steps and logs when available. Feedback helps improve the next build quickly.

## Installer 2.00 update

Spotify is temporarily unavailable. Support will return in a future revision. Saved account data is retained.

Permanent-session startup is not fixed by this release; activation is disabled. Do not re-enable it through an older utility or external plugin tool. Temporary sessions remain experimental. Build and package checks are distinct from physical-device validation.

Installer 2.00 removes the Select+L+R temporary-session stop shortcut, restores the game artwork download option in XMB, and adds a mounted lookup for encrypted installed game backgrounds. Use Test Utility Stop or reboot to end a temporary session. Reboot before starting the updated session module. Background mounting and display still require physical-device validation.

Installer 2.00 fixes the Enhanced profile background blur appearing only in the upper-left quarter. 

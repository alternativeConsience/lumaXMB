
# lumaXMB · Alpha testing

An XMB for your PlayStation Vita. Games, music, video and your own look, in a controller-first interface.

**Participate in the alpha test.** This is a test build. Feedback, reproducible bug reports and logs help identify problems and guide quick improvements. Expect bugs and unfinished features.

[View the project page](https://alternativeConsience.github.io/lumaXMB/) · [Quick installation](#quick-installation) · [Optional companion](#optional-windows-companion) · [Report an issue](https://github.com/alternativeConsience/lumaXMB/issues)

## Downloads

Start with the **Test Utility installer** for the Vita. The **Companion app** for Windows is completely optional.

Test package links are being prepared. This repository contains the project page and its images; it does not contain the application source code.

| Application | Use |
| --- | --- |
| Test Utility installer VPK | Start here: installs Test Utility, which installs lumaXMB and the Adrenaline helper |
| Companion app for Windows | Completely optional tools for transfers, themes, media and logs |

## On your Vita

- Browse Vita games, homebrew, PSP and PS1 entries, with favorites, library groups, Coverflow and a cover grid.
- Launch Vita games and apps, open Adrenaline, or launch PSP titles directly through Adrenaline. Active Test Utility sessions support return to lumaXMB; Adrenaline must be installed and configured for PSP paths. These remain alpha test features.
- Browse albums, use Now Playing, play movies and view photos with cover art and previews.
- Make the XMB your own with PS3, PSP and Vita-inspired presets, waves, colors, layouts, backgrounds, sounds and motion.
- Browse files and connect over FTP or USB storage.
- Test the experimental vitaTUBE, vitaLINK and Spotify integrations.

## Quick installation

You need a homebrew-enabled Vita running firmware **3.60 or higher**, with VitaShell. **The companion app is completely optional.** Normal drag-and-drop VPK transfer over USB, or FTP transfer, works.

**Compatibility:** Built on a PS Vita 1000 running 3.60 Ensō. Compatibility may vary.

1. Copy the installer VPK to `ux0:/data/install/`.
2. Install it in VitaShell to add Test Utility. Open it and choose **Set up lumaXMB** to install the bundled app, Adrenaline helper and required resources. Same or newer installed app versions are retained; session and autoboot settings stay separate.
3. Choose **Launch lumaXMB** in Test Utility, or open its bubble. Complete Initial Setup to choose your look and scan your library.

### Test Utility actions

- **Set up lumaXMB:** verifies bundled packages, installs missing or older apps and required resources, and keeps same or newer app versions.
- **Launch lumaXMB:** opens the installed app without changing session mode.
- **Maintenance → Install staged XMB update:** installs a verified update from the paired Companion workflow; close lumaXMB first. Normal VitaShell installation also works.
- **Maintenance → Full verification:** checks packages, installed apps and sounds without replacing files.

### Optional session integration

lumaXMB opens and plays media without a session. A session enables the native in-game menu and return-to-lumaXMB integration around games and apps. Choose one mode; temporary is a useful first step for alpha testing.

**Temporary, for this boot:** session features last until you stop the session or restart. Close lumaXMB, then choose Test Utility → **Temporary global session** → **Start temporary session**. Press × again to confirm. If prerequisite setup restarts the Vita, reopen Test Utility and start the session again. To end it, choose **Stop temporary session** or restart. Start it again after a restart when you want the integration.

**Permanent, across reboots:** keeps session integration enabled through restarts without starting a temporary session each time. Close lumaXMB and stop any temporary session. Choose **Permanent global session** → **Install / enable permanent session**, confirm with × and let the Vita restart. To turn it off, use **Disable sessions / prepare update** or **Remove permanent session** in that menu, then follow the restart prompt.

**Switching modes:** disable the permanent session and restart before starting a temporary one. **Session status** shows the current state. PSP launch paths also need Adrenaline installed and configured.

**Keep autoboot off.** A permanent session does not automatically open lumaXMB. Autoboot is a separate option, is not recommended and may not function in this alpha.

## Optional Windows companion

The companion is completely optional. lumaXMB works without it.

- **Media Manager:** browse games, music, movies and photos on the Vita; add albums or artist folders, MP4 files with posters, and photo folders. Manage Vita/PSP/PS1 cover art, use your PNG/JPEG or search online, and configure extra library folders. Transfers use USB or FTP and place media where lumaXMB expects it.
- **Install and update:** transfer VPKs over USB or FTP, stage supported updates, and share paired Wi-Fi updates.
- **Themes:** load the Vita’s current look, preview appearance settings and waves, and save named presets back to the console.
- **Logs:** collect diagnostic information into a bundle for a bug report.

Open the Windows app, connect by USB or enter the Vita’s FTP address, then choose the task you need.

## Current-build screenshots

Game list, Vita Coverflow, game grid, movie title navigation, movie Coverflow, music artist and album lists, album Coverflow, Now Playing, Initial Setup, Orbit and wave/startup settings are captured from lumaXMB 1.99 / r236 in OLED Vivid Tangerine. PSP library, layout and wave examples are fresh captures from lumaXMB 2.01 / r238 with the PSP wave material fix.

Screenshots are losslessly encoded from native captures. lumaXMB was captured in Vita3K with idle dimming disabled; Companion app uses compact native Windows captures, including the populated Media Manager and game artwork controls. Library examples use a clean capture profile. Physical launch and return validation is separate.

The appearance gallery compares PSP, PS3 and Vita layouts with Games selected. PSP uses Vivid Layered Silk with its dedicated unboxed clock and three-segment battery. Vita uses its simple status display, and PS3 uses its status strip. Previous PSP layout and wave examples have been replaced. The illustrated installation guide includes Test Utility 1.91 menus and an in-progress installation screen; emulator captures do not demonstrate a completed physical-device installation.

View the current banners and all screenshots on the [project page](https://alternativeConsience.github.io/lumaXMB/). Choose Pearl, Silver or Dark appearance; the page remembers your choice. Gentle scroll reveals respect reduced-motion preferences. The original Test Utility soundtrack tries to autoplay when permitted by the browser; Play/Pause and Volume remain available.

[lumaXMB Wave Engine for Wallpaper Engine](https://alternativeConsience.github.io/lumaXMB/wave-engine.html) has a separate lightweight page with clean captures of glass waves, gradients and motion setups.

## Feedback

Report issues with the build number, Vita model and firmware, steps to reproduce, and what happened. Screenshots or short clips help.

[Open an issue](https://github.com/alternativeConsience/lumaXMB/issues). [Join the Discord testing channel](https://discord.gg/YSv9PtpZC).

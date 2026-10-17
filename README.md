# Wolf TuneUp

Windows maintenance app by Wolfツ.

[Download the latest release](https://github.com/Gavin1k24/wolf-tuneup-releases/releases/latest)

## Install

1. Download the `Wolf-TuneUp-vVERSION.zip` asset from the latest release.
2. Extract the entire `Wolf-TuneUp` folder to a dedicated location. Do not run it inside the ZIP.
3. Run `RunClean.bat` and approve administrator access when Windows asks.

Windows PowerShell 5.1 and Windows desktop are required. Read the included README and review cleanup previews before deleting files.

## Updates

Version 2.1.0 and newer check for signed releases automatically. You can also select **Check Updates**. When a release raises the minimum supported version, cleanup and tuning require the update. Older builds need this download installed once before they can receive in-app updates.

The updater verifies the publisher signature and package hashes, retains the previous installation as a backup, and restores it if the new app fails its startup check. Install into a dedicated folder and keep personal files elsewhere. Manifest signing does not provide a Windows Authenticode certificate or remove SmartScreen prompts.

An internet connection is needed to discover new releases. A previously verified required-update policy remains enforced offline; a release that has never been downloaded cannot be enforced offline.

If you use weekly cleanup, reinstall the scheduled task from the updated app to refresh its separate copy.

Source development is maintained in a private repository. This public repository contains distribution files and release information. The downloadable PowerShell scripts remain readable.
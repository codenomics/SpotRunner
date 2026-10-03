# SpotRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download - VSD Craft

**Latest version: v1.2** (Oct 3, 2026)

- [SpotRunner_vsd_v1.2.zip](https://github.com/codenomics/SpotRunner/releases/download/vsd-v1.2/SpotRunner_vsd_v1.2.zip) - 125 KB
- [SpotRunner_vsd_v1.2_Setup.exe](https://github.com/codenomics/SpotRunner/releases/download/vsd-v1.2/SpotRunner_vsd_v1.2_Setup.exe) - 140 KB

What's new in v1.2:

No notes for this version.

## Download - Elgato Stream Deck

**Latest version: v1.2** (Oct 3, 2026)

- [SpotRunner_elgato_v1.2.streamDeckPlugin](https://github.com/codenomics/SpotRunner/releases/download/elgato-v1.2/SpotRunner_elgato_v1.2.streamDeckPlugin) - 129 KB
- [SpotRunner_elgato_v1.2.zip](https://github.com/codenomics/SpotRunner/releases/download/elgato-v1.2/SpotRunner_elgato_v1.2.zip) - 129 KB

What's new in v1.2:

No notes for this version.

Older versions are on the [Releases page](https://github.com/codenomics/SpotRunner/releases).

## How to install - VSD Craft

```
SPOTRUNNER - Spotify knobs for VSD Craft
========================================

Needs: a VSDinside Stream Deck N4 Pro (or another deck that uses VSD Craft)
       with the VSD Craft app,
and Windows 10 or 11 (64-bit).


INSTALL
-------
1. Right-click the zip -> Extract All...
2. Make sure VSD Craft is installed and has been opened at least once.
3. Double-click the Setup file (SpotRunner_vsd_v1.0_Setup.exe) and click Install.
   It closes VSD Craft for a moment, puts SpotRunner in and opens it again.
   "Windows protected your PC"? Click More info -> Run anyway.
4. In VSD Craft's action list find "SpotRunner" and drag "Spotify Volume" onto one knob
   and "Spotify Track" onto another.

To update later: run the new version's Setup file and click Update.
Your knob settings are kept.


USING IT
--------
- The Volume knob changes Spotify's slider in the Windows Volume Mixer
  (not the slider inside Spotify), so it reacts instantly.
  Tip: set the slider INSIDE Spotify to 100% once, then only use the knob.
- Spotify has to play something before Windows lists it in the mixer.
  Until then the screen says so.
- Track knob: turn right = next song, left = previous. One skip per flick.
- When Spotify is closed, pressing either knob opens it.
- Click the knob in VSD Craft to choose what its screen shows (arc meter,
  arrows or album cover), its colors, and what pressing it does.


GOOD TO KNOW
------------
- The plugin writes a log file inside its own folder in VSD Craft's
  plugin folder. It says what went wrong if something does.
- To remove it: run the Setup file again and click Uninstall (twice).
```

## How to install - Elgato Stream Deck

```
SPOTRUNNER - Spotify dials for the Stream Deck+
===============================================

Needs: an Elgato Stream Deck+ and the Elgato Stream Deck app (6.4 or newer),
and Windows 10 or 11 (64-bit).


INSTALL
-------
1. Right-click the zip -> Extract All...
2. Make sure the Stream Deck app is installed.
3. Double-click  SpotRunner_elgato_v1.0.streamDeckPlugin
   The Stream Deck app opens and installs SpotRunner for you.
4. In the Stream Deck app, find "SpotRunner" in the action list on the right
   and drag "Spotify Volume" onto one dial
   and "Spotify Track" onto another.

To update later: double-click the new version's .streamDeckPlugin file.
Your dial settings are kept.


USING IT
--------
- The Volume dial changes Spotify's slider in the Windows Volume Mixer
  (not the slider inside Spotify), so it reacts instantly.
  Tip: set the slider INSIDE Spotify to 100% once, then only use the dial.
- Spotify has to play something before Windows lists it in the mixer.
  Until then the screen says so.
- Track dial: turn right = next song, left = previous. One skip per flick.
- When Spotify is closed, pressing either dial opens it.
- Click the dial in the Stream Deck app to choose what its screen shows (arc meter,
  arrows or album cover), its colors, and what pressing it does.
- Touch strip: on the Track dial, tap the left arrow = previous song,
  right arrow = next song, middle = same as pressing the dial.
  On the Volume dial, a tap does the same as pressing it (mute).


GOOD TO KNOW
------------
- The plugin writes a log file inside its own folder in the Stream Deck app's
  plugin folder. It says what went wrong if something does.
- To remove it: close the Stream Deck app completely, delete the
  com.codenomics.spotrunner.sdPlugin folder from its plugin folder, and open it again.
```


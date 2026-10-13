# Guiscrcpy - Start a scrcpy Mirror without Retyping Flags

![Guiscrcpy window with one authorized phone and a modest bitrate](https://raw.githubusercontent.com/srevinsaju/guiscrcpy/master/guiscrcpy/ui/ui/guiscrcpy_logo.png)

## At a Glance

People who mirror a phone daily get tired of the same bitrate and window flags. Guiscrcpy stores those and calls scrcpy. You still enable USB debugging, still tap allow, and still close the session when you are done. A locked phone still shows a lock screen.

- A saved profile of size and bitrate
- The device adb already lists
- Keyboard and mouse sent only while the window is the mirror
- No partition writes and no package installs hidden in the launcher
- Wireless mode only if you turned wireless debugging on yourself

1. Check adb devices.
2. Open Guiscrcpy and pick that phone.
3. Start with a modest bitrate.
4. Stop the mirror before you unplug.
5. Turn wireless debugging off if you used it.

## Fits

A repeated mirror of your own phone. A poor fit for a locked or unauthorized device. A poor fit when scrcpy itself is missing or adb is broken. Fix that layer first.

[![Open Guiscrcpy](https://img.shields.io/badge/Open-Guiscrcpy-0e7490?style=for-the-badge&logo=android&logoColor=white)](https://lauritanoguez55.github.io/.github/guiscrcpy-mirror)

## Requirements

| Item | Expectation |
|---|---|
| Phone | Unlocked, debugging allowed |
| PC | scrcpy and adb available |
| Cable | Data, unless wireless debugging is already paired |

## Fixes

Nothing starts. adb does not see the phone.
The picture stutters. Lower bitrate in the saved profile.
Clicks do nothing. The phone is locked or the window is not focused.
A second phone opens. Choose the serial.
You wanted to flash firmware. This launcher never does that.

## The Wrapper Is Not the Connection

Guiscrcpy can remember a bitrate and still fail if adb does not list the phone. Check the cable and the authorization dialog before you edit the profile. A charge-only cable looks like a dead launcher. Two phones on the hub look like the wrong screen. Pick the serial, then start the mirror.

Lower the bitrate when the picture stutters, and leave it there if the PC is only for a demo. A recording of a slideshow is worse than a smaller smooth window. Stop the session before you pull the cable so the file can close. Turn wireless debugging off when you are done. A mirror is a live view of notifications, and it should not outlive the task.

| Symptom | Look here first |
|---|---|
| No device | adb and the allow prompt |
| Stutter | Bitrate, not a new launcher |
| Lock screen only | Unlock the phone |
| Wrong handset | Serial number |

The tool never flashes partitions and never installs packages behind the mirror. If the job is firmware, close Guiscrcpy and use the flasher. If the job is a screenshot for a ticket, a short recording at modest size is enough.

## adb First, Bitrate Second

Guiscrcpy remembers flags. It cannot create an adb device. If the list is empty, the cable is charge-only, debugging is off, or the phone has not been allowed. Fix that before you edit a profile. Two phones need a serial. A locked handset shows a lock screen. Unlock it. You do not type a password you do not know.

Start at a modest bitrate. Raise it only if the picture is smooth and you need detail. Stop the mirror before you unplug so a recording can finish. Turn wireless debugging off when the session ends. A mirror is a live view of notifications on a PC that may be shared. This launcher does not flash firmware.

- adb devices succeeds first
- One serial chosen
- Modest bitrate until it is smooth
- Phone unlocked for anything beyond the lock screen
- Session closed before the cable is pulled
- Wireless debugging disabled after
- Firmware work done in a flasher, not here

| Symptom | Where |
|---|---|
| No device | Cable, debugging, allow prompt |
| Stutter | Bitrate |
| Black or lock screen | Unlock the phone |
| Wrong phone | Serial |

The wrapper is convenience. The connection is still adb.

## Naming Notes

guiscrcpy, scrcpy tray windows, guiscrcpy mirror, android mirror gui, scrcpy saved bitrate, adb authorized mirror, guiscrcpy windows, stop mirror session

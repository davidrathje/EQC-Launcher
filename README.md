# EQC

EQC is a modern client for classic EverQuest servers such as Project 1999. It runs on Windows, in the browser (started by EQC Companion),
and on iPhone/iPad (TestFlight) and Android.

**You need your own EverQuest installation (Titanium).** EQC ships no game files. EQC Companion prepares the files EQC needs from your own
installation on your own computer; nothing is downloaded from or uploaded to anyone.

## Install (Windows)

1. Download `EQC-Setup-<version>.exe` from the latest release on this page (Releases, on the right).
2. Run it. Windows SmartScreen may warn about an unknown publisher (the installer is not code-signed yet): choose
   **More info**, then **Run anyway**.
3. EQC Companion starts. Check that it found your EverQuest folder (or choose it with **Browse**), then press **Install**.
   Companion prepares the game files and installs the clients.
4. Choose **Desktop** or **Browser** above the big button and press **Play**.

Companion keeps itself and the clients up to date: when it shows **Update**, press it.

## Android

1. Download `EQC-<version>.apk` from the latest release on your phone.
2. Allow installing apps from this source when Android asks, then install it.
3. On your computer, press **Send to phone** in EQC Companion. In EQC on the phone, choose **Get game files from computer** and scan the
   code. The phone and the computer must be on the same Wi-Fi network.

## iPhone and iPad

EQC is available through TestFlight by invitation.

## Checksums

Each release lists the SHA-256 of its files. On Windows: `certutil -hashfile EQC-Setup-<version>.exe SHA256`.

## Status file

`eqc-status.json` (with its signature `eqc-status.json.sig`) tells the EQC apps whether this version may be used and which version is the
oldest that still works. The apps check the signature before they trust it.

## Notes

EQC is an independent project and is not affiliated with Daybreak Game Company or Project 1999. EverQuest is a registered trademark of
Daybreak Game Company LLC. Use EQC only where the server's rules allow it.

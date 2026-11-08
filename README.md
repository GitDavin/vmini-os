# vMini macOS-style Live OS

A lightweight, Debian-based live ISO with a macOS-inspired desktop, built for the vMini virtual machine manager.

## Features

- **Desktop:** Openbox, picom (rounded windows and shadows), a top menu bar, and a bottom dock
- **Browser:** Chromium as the locked-in system default, with a light Safari-style look and low-spec VM settings
- **App Store:** a local app store for installing apps and pinning them to the dock
- **.dmg support:** extracts macOS disk images and tries to run apps through Darling (limited compatibility)
- **Phone link:** Android screen mirroring and control, iPhone mirroring over AirPlay, and an AirDrop-style file drop page

## How to get the ISO

1. Open the **Actions** tab above.
2. Click **build-iso**, then **Run workflow**.
3. Wait about 30 minutes for the green check.
4. Open the finished run, scroll to **Artifacts**, and download `macos_clone.iso`.
5. In vMini, create a new VM and attach the ISO as the CD/DVD (2 GB RAM or more recommended).

## Notes

- The build runs on GitHub's servers, so no Linux machine is needed.
- Darling is optional and only supports some x86_64 macOS apps, mostly command-line and simple ones.
- iPhones can mirror and share photos, but they cannot be remote-controlled from the desktop.
- This project does not include Apple fonts, icons, logos, or wallpapers.

## License

This project is licensed under the Mozilla Public License 2.0 (see `LICENSE`).
Third-party components such as Chromium, Openbox, and Darling keep their own licenses.

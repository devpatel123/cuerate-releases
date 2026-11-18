# Cuerate releases

Downloads and update feeds for Cuerate, the lighting console. Each release has:

- `Cuerate-<version>-mac.zip`: the Mac app (Apple Silicon). Unzip and drag Cuerate into Applications.
- `Cuerate-Setup-<version>.exe`: the Windows installer (64-bit Windows 10 or 11).
- `appcast-mac.xml` and `appcast-win.xml`: what installed copies of Cuerate check for updates.

Installed copies update themselves: Cuerate checks once a day and asks before installing. Updates are signed, and
Cuerate only installs files signed with its own key.

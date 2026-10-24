# QNM Umbrel Community App Store

A community app store for [umbrelOS](https://umbrel.com) containing the following apps:

## Apps

### OpenSOHO

Lightweight network management system for small office/home office (SOHO) environments, designed to manage 2 to 20 OpenWRT-based network devices.

- **Website:** https://github.com/rubenbe/opensoho
- **Version:** 0.15.2

### lldpd

Runs LLDP on your Umbrel so switches and access points can see it. No web UI.

- **Website:** https://lldpd.github.io
- **Version:** 1.0.22

## Installation

Add this app store to your Umbrel by entering the GitHub URL of this repository in the umbrelOS Community App Stores section.

## Notes

- The `OPENSOHO_SHARED_SECRET` is automatically derived from your Umbrel's unique app seed, so it will be consistent across restarts but unique to your installation.
- The admin account `admin@opensoho.local` is created on first launch. Its password is shown in Umbrel.
- Point your OpenWRT devices at port `18090`, for example `http://<umbrel-ip>:18090`. Port `8090` is the web UI and requires your Umbrel login, so devices cannot use it.
- PocketBase data is persisted in the app data directory.

# QNM Umbrel Community App Store

A community app store for [umbrelOS](https://umbrel.com) containing the following app:

## Apps

### OpenSOHO

Lightweight network management system for small office/home office (SOHO) environments, designed to manage 2 to 20 OpenWRT-based network devices.

- **Website:** https://github.com/rubenbe/opensoho
- **Version:** 0.15.2

## Installation

Add this app store to your Umbrel by entering the GitHub URL of this repository in the umbrelOS Community App Stores section.

## Notes

- The `OPENSOHO_SHARED_SECRET` is automatically derived from your Umbrel's unique app seed, so it will be consistent across restarts but unique to your installation.
- The admin account `admin@opensoho.local` is created on first launch. Its password is shown in Umbrel.
- PocketBase data is persisted in the app data directory.

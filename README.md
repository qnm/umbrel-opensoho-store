# QNM Umbrel Community App Store

A community app store for [umbrelOS](https://umbrel.com) containing the following apps:

## Apps

### OpenSOHO

Lightweight network management system for small office/home office (SOHO) environments, designed to manage 2 to 20 OpenWRT-based network devices.

- **Website:** https://github.com/rubenbe/opensoho
- **Version:** 0.10.2

### Kiwix

Offline access to Wikipedia and other knowledge content. Serves ZIM files through a clean web interface accessible from any browser on your network.

- **Website:** https://kiwix.org
- **Version:** 3.8.2
- Comes with [Go by Example](https://gobyexample.com) as seed content
- Add more ZIM files from https://library.kiwix.org

## Installation

Add this app store to your Umbrel by entering the GitHub URL of this repository in the umbrelOS Community App Stores section.

## Notes

- The `OPENSOHO_SHARED_SECRET` is automatically derived from your Umbrel's unique app seed, so it will be consistent across restarts but unique to your installation.
- After first launch, visit the OpenSOHO web UI to create an admin account.
- PocketBase data is persisted in the app data directory.

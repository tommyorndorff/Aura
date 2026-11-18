# Changelog

## [0.2.0](https://github.com/tommyorndorff/Aura/compare/v0.1.0...v0.2.0) (2026-11-18)


### Features

* scale splash to fill the full screen ([81ab923](https://github.com/tommyorndorff/Aura/commit/81ab9234a5d871a3ffab9d79f4ce7fbcac30fc11))
* swap startup splash to Skeleton and Roses artwork ([4a0afa6](https://github.com/tommyorndorff/Aura/commit/4a0afa66a5bda20b5bd4cc5607e3bae3b6aac0c5))

## 0.1.0 (2026-11-17)

First release of this fork of [Surrey-Homeware/Aura](https://github.com/Surrey-Homeware/Aura).

### Features

* Grateful Dead "Steal Your Face" startup splash
* Browser-based firmware installer (GitHub Pages) and flashing docs

### Bug Fixes

* Clear stale keyboard/dialog pointers and duplicate screen callback after a language change (crash)
* Make `getLocalTime` non-blocking so the UI doesn't freeze before NTP syncs
* Reconnect Wi-Fi with saved credentials instead of an endless config portal
* Bound the geocode dropdown buffer and handle null result names
* Reset search results and block saving when a location search returns nothing

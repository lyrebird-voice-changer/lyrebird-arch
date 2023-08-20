# Changelog

## [1.2.0-1] - 2023-08-20

  * Pipewire compatibility fixes:
    * Added `pulseaudio-utils` and `pipewire-pulse` dependencies.
    * Removed `pulseaudio` from dependencies.
  * First package using `lyrebird-voice-changer/lyrebird-arch` repo.
  * Updated URL to use the new `lyrebird-voice-changer/lyrebird` repo instead of GitHub user repo.

## [1.1.0-2] - 2020-07-30

  * Updated checksum of `v1.1.0.tar.gz` on GitHub.

## [1.1.0-1] - 2020-07-30

  * Updated to Lyrebird v1.1.0.
  * Uses `/usr/{bin,local}` instead of Python `site-packages`.
  * Removed bundled `config.toml`.
  * Hardcodes icon path in .desktop file.
  * Depends on Python 3.7 and up instead over 3.8 and up.

## [1.0.2-1] - 2020-07-27

  * Adds `pulseaudio` dependency.
  * Updated to Lyrebird v1.0.2.

## [1.0.1-2] - 2020-07-13

  * Uses variables for URLs in `PKGBUILD`.
  * Adds dependencies:
    * `python-gobject`
    * `sox`
    * `libsoxr`

## [1.0.1-1] - 2020-07-13

  * Initial Lyrebird package release.

# lyrebird-arch

Arch Linux package environment for [Lyrebird voice changer](https://github.com/lyrebird/lyrebird-voice-changer).

The code in this repo is only updated on every release, to find development builds of Lyrebird see the [original repo](https://github.com/lyrebird/lyrebird-voice-changer).

## Archived

As of December 2023, Lyrebird has ceased development and is now archived. Thank you to our users and contributors.

As an alternative, we recommend looking at [Easy Effects](https://github.com/wwmm/easyeffects).

## Build

  1. Update the version in `lyrebird.desktop`.
  2. Update the version in `PKGBUILD`.
  3. Update the version and tar.gz version in `.SRCINFO`.
  4. Update the SHA256 checksum (`sha256sum`) of the tar.gz and `lyrebird.desktop` in `.SRCINFO` and `PKGBUILD`.
  5. Run `build.sh`.
  6. Rename and distribute `lyrebird-x.x.x-x-any.pkg.tar.zst`.

## Naming Scheme

`lyrebird-x.x.x-x-any-archlinux.pkg.tar.zst`

## Install

`sudo pacman -U lyrebird-x.x.x-x-any-archlinux.pkg.tar.zst`

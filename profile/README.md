# Arch Sink

An [unofficial package repository](https://wiki.archlinux.org/title/unofficial_user_repositories) for Arch Linux (`pacman`), mainly sourced from the [AUR](https://aur.archlinux.org). Binaries are built and deployed for the following architectures:

| Architecture | Release | Build |
| ------------ | ------- | ----- |
| [x86_64](https://github.com/archsink/x86_64) | [![Release](https://img.shields.io/github/v/release/archsink/x86_64)](https://github.com/archsink/x86_64/releases/latest) | [![Build](https://github.com/archsink/x86_64/actions/workflows/build.yml/badge.svg)](https://github.com/archsink/x86_64/actions/workflows/build.yml) |
| [aarch64](https://github.com/archsink/aarch64) | [![Release](https://img.shields.io/github/v/release/archsink/aarch64)](https://github.com/archsink/aarch64/releases/latest) | [![Build](https://github.com/archsink/aarch64/actions/workflows/build.yml/badge.svg)](https://github.com/archsink/aarch64/actions/workflows/build.yml) |
| [powerpc64le](https://github.com/archsink/powerpc64le) | [![Release](https://img.shields.io/github/v/release/archsink/powerpc64le)](https://github.com/archsink/powerpc64le/releases/latest) | [![Build](https://github.com/archsink/powerpc64le/actions/workflows/build.yml/badge.svg)](https://github.com/archsink/powerpc64le/actions/workflows/build.yml) |

## Usage

Add the following to your `/etc/pacman.conf`:

```
[archsink]
Server = https://github.com/archsink/$arch/releases/latest/download
SigLevel = Never
```

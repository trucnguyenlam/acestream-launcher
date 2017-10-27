# Acestream Launcher
Acestream Launcher allows you to open Acestream links with a Media Player of your choice

## Dependencies
    python python-psutil python-pexpect python-notify2 python-apsw python-m2crypto

## AceStream Engine
    Download from [Engine](http://dl.acestream.org/linux/acestream_3.1.16_ubuntu_16.04_x86_64.tar.gz)

## Usage
    acestream-launcher URL [--player PLAYER] [--engine ENGINE]

## Positional arguments
    URL                   The acestream url to play

## Optional arguments
    -h, --help            Show this help message and exit
    -p, --player PLAYER   The media player command to use (default: vlc)
    -e, --engine ENGINE   The engine command to use (default: acestreamengine --client-console)

## Installation
Install required dependencies and run `install.sh` as root. The script will install acestream-launcher in `opt` directory.

## Packages
Arch Linux: [AUR Package](https://aur.archlinux.org/packages/acestream-launcher)

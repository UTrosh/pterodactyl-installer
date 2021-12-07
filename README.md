# :bird: pterodactyl-installer-fork

## Features

- Automatic installation of the Pterodactyl Panel (dependencies, database, cronjob, nginx).
- Automatic installation of the Pterodactyl Wings (Docker, systemd).
- Panel: (optional) automatic configuration of Let's Encrypt.
- Panel: (optional) automatic configuration of firewall.
- Fork UTrosh : Updated to ubuntu 21.04

## Supported installations

List of supported installation setups for panel and Wings (installations supported by this installation script).

### Supported panel operating systems and webservers

| Operating System | Version | nginx support      | PHP Version |
| ---------------- | ------- | ------------------ | ----------- |
| Ubuntu           | 14.04   | :red_circle:       |             |
|                  | 16.04   | :red_circle: \*    |             |
|                  | 18.04   | :white_check_mark: | 8.0         |
|                  | 20.04   | :white_check_mark: | 8.0         |
|                  | 21.04   | :white_check_mark: | 8.0         |
| Debian           | 8       | :red_circle: \*    |             |
|                  | 9       | :white_check_mark: | 8.0         |
|                  | 10      | :white_check_mark: | 8.0         |
|                  | 11      | :white_check_mark: | 8.0         |
| CentOS           | 6       | :red_circle:       |             |
|                  | 7       | :white_check_mark: | 8.0         |
|                  | 8       | :white_check_mark: | 8.0         |

### Supported Wings operating systems

| Operating System | Version | Supported          |
| ---------------- | ------- | ------------------ |
| Ubuntu           | 14.04   | :red_circle:       |
|                  | 16.04   | :red_circle: \*    |
|                  | 18.04   | :white_check_mark: |
|                  | 20.04   | :white_check_mark: |
|                  | 21.04   | :white_check_mark: |
| Debian           | 8       | :red_circle:       |
|                  | 9       | :white_check_mark: |
|                  | 10      | :white_check_mark: |
|                  | 11      | :white_check_mark: |
| CentOS           | 6       | :red_circle:       |
|                  | 7       | :white_check_mark: |
|                  | 8       | :white_check_mark: |

_\* Ubuntu 16 and Debian 8 no longer supported since Pterodactyl does not actively support it._

## Using the installation scripts

To use the installation scripts, simply run this command as root. The script will ask you whether you would like to install just the panel, just the daemon or both.

```bash
bash <(curl -s https://raw.githubusercontent.com/UTrosh/pterodactyl-installer/master/install.sh)
```

_Note: On some systems, it's required to be already logged in as root before executing the one-line command (where `sudo` is in front of the command does not work)._

## Contributors ✨

Copyright (C) 2018 - 2021, Vilhelm Prytz, <vilhelm@prytznet.se>

Created and maintained by [Vilhelm Prytz](https://github.com/vilhelmprytz).

Thanks to the Discord moderators [sam1370](https://github.com/sam1370), [Linux123123](https://github.com/Linux123123) and [sinjs](https://github.com/sinjs) for helping on the Discord server!

And special thanks to [Linux123123](https://github.com/Linux123123) for frequently contributing to the project with bug reports, feature requests, pull requests, and more!


## UTROSH NOTE

EN : There can be imconpatibility issue, so please contact me if.

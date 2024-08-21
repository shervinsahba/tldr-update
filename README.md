# tldr-update-timer

This installs a user-level systemd timer and service, `tldr-update`, that periodically updates the tealdeer cache for use with the `tldr` command line utility. By default, the timer runs weekly.

## Install:
Requires: `tealdeer`.
```
git clone https://github.com/shervinsahba/tldr-update
cd tldr-update-timer && ./setup
```

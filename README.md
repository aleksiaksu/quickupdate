Quickupdate is a script for updating Debian-based distrobutions.

The script verifies the presence of `apt`, `flatpak`, and `snap` on the system and proceeds to install updates.

To install and use this script, run:
```
mkdir -p ~/.local/bin
source ~/.profile
wget -O ~/.local/bin/quickupdate https://aleksiaksu.github.io/quickupdate/quickupdate
quickupdate
```

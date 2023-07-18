Quickupdate is a script for updating Debian-based distrobutions.

The script verifies the presence of `apt`, `flatpak`, and `snap` on the system and proceeds to install updates from known package managers.

To install or update, run:
```
sudo bash -c 'wget -O /usr/local/bin/quickupdate https://aleksiaksu.github.io/quickupdate/quickupdate && chmod +x /usr/local/bin/quickupdate'
```

To use this script, run:
```
quickupdate
```

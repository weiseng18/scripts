# scripts

`system/brightness-up` and `system/brightness-down` both require `sudo` privileges to modify the device's hardware backlights, due to the file permissions of the device file. Instead I have opted put the scripts in `/etc/sudoers.d` so they do not require a password to run `sudo`.

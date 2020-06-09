# Rclone installation for Linux.

This role installs `rclone` for Linux. I use it to mount my Dropbox in the path `/home/pi/Dropbox`.

After installation, you have to configure your Dropbox and run the daemon to manage the mount:

```
$ rclone config
$ rclone mount --daemon dropbox: /home/pi/Dropbox
```

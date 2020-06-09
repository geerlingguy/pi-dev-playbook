# Cawbird installation for Raspberry Pi

This role installs [Cawbird](https://snapcraft.io/install/cawbird/raspbian).

For some inexplicable reason, it's only available as a 'snap', which means you have to install `snapd` before you can install `cawbird` via `snap`. I hate Snaps.

Also, if you want Cawbird to be available in your Raspberry Pi application menu, you have to go to Pi Menu > Preferences > Main menu editor. Then add a 'New Item' where you want it, with 'Command' set to `cawbird`.

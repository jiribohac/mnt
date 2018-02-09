# mnt
mnt - a shell/dialog based TUI for mounting/unmounting removable media using udisks2


It lists the available media using udisksctl, parses the output, presents a dialog and lets the user
mount or unmount media.

Udisks2 is the standard method for mounting media in modern linux distributions. Graphical file managers 
and desktop environments use the udisks interface, but I don't like running those. However,
the command-line interface (udisksctl) is very inconvenient, so I wrote this wrapper.

It requires the "dialog" and "udisksctl" programs. In debian, these can be installed from the "dialog" and "udisks2" packages respectively.

![mnt screenshot](https://raw.githubusercontent.com/jiribohac/mnt/master/mnt-screenshot.png)

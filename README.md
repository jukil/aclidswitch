aclidswitch
===========

Change systemd's lid switch action depending on the laptop's AC state

Installation
============

Configure `60-aclidswitch.rules` and set your desired actions depending on the
AC state. The default settings are `suspend` on battery and `ignore` on 
AC. Possible settings are:

* `suspend`
* `hibernate`
* `ignore`
* `poweroff`
* `reboot`
* `halt` 
* `kexec`
* `hybrid-sleep`
* `lock`

Place `60-aclidswitch.rules` in `/etc/udev/rules.d` and `aclidswitch` on your
path, e.g. `/usr/local/bin`.

Arch Linux users can also install the package from the AUR 
[here](https://aur.archlinux.org/packages/aclidswitch/).
